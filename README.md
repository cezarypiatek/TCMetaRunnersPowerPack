# TCMetaRunnersPowerPack
A set of Team City meta runners. Meta runners can be imported by uploading meta runner definition file in "Meta runners" tab in project settings. To get know Team City meta runners please read the [meta runners documentation](https://confluence.jetbrains.com/display/TCD10/Working+with+Meta-Runner)

![Meta runner uploads](https://github.com/cezarypiatek/TCMetaRunnersPowerPack/blob/master/doc/MetaRunnersImport.jpg?raw=true)


## Microsoft Teams Notification
This meta runner send notification to MS Teams chat via webhooks. In order to generate webhook url use right click on given MS Teams channel,
click "Connectors" from the context menu and select "Incomming webhook" on the "Configuration" list. 
More details about webhooks in MS Teams can be found [here](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/connectors
). This meta runner use powershell under the hood. 
![MSTeams meta runner configuration](https://github.com/cezarypiatek/TCMetaRunnersPowerPack/blob/master/doc/MicrosoftTeamsNofirication.jpg?raw=true)

## Changelog Generator
Meta runner responsible for generating file with changelog from build changes. You can generate changelog in TEXT or HTML format. HTML changelog contains hyperlinks to change page in TeamCity and issue tracker as well. Changelog is generated with powershell using [TeamCity REST API](https://confluence.jetbrains.com/display/TCD10/REST+API#RESTAPI-Changes). Inspired by [Nordine Ben Bachir](https://github.com/nordineb) great [blogpost](https://open.bekk.no/generating-a-project-change-log-with-teamcity-and-powershell).

![Changelog genertor configuration](https://github.com/cezarypiatek/TCMetaRunnersPowerPack/blob/master/doc/ChangelogGenerator.jpg?raw=true)
