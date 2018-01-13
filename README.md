# TCMetaRunnersPowerPack
A set of Team City meta runners. Meta runners can be imported by uploading meta runner definition file in "Meta runners" tab in project settings. To get know Team City meta runners please read the [meta runners documentation](https://confluence.jetbrains.com/display/TCD10/Working+with+Meta-Runner)

![Meta runner uploads](https://github.com/cezarypiatek/TCMetaRunnersPowerPack/blob/master/doc/MetaRunnersImport.jpg?raw=true)


# Microsoft Teams Notification
This meta runner send notification to MS Teams chat via webhooks. In order to generate webhook url use right click on given MS Teams channel,
click "Connectors" from the context menu and select "Incomming webhook" on the "Configuration" list. 
More details about webhooks in MS Teams can be found [here](https://docs.microsoft.com/en-us/microsoftteams/platform/concepts/connectors
). This meta runner use powershell under the hood. 
![MSTeams meta runner](https://github.com/cezarypiatek/TCMetaRunnersPowerPack/blob/master/doc/MicrosoftTeamsNofirication.jpg?raw=true)
