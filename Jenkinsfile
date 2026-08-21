// https://github.com/Rudd-O/shared-jenkins-libraries
@Library('shared-jenkins-libraries@master') _


genericFedoraRPMPipeline(
	{
        downloadCrateSourceFromSpecfile sha256sum: "0dc5b2b13cb6a9a5fcf7c668ebf2aef67e0d83d4451c1db95feb9fb0775874f0"
	},
	{
		SRPMStrategyRpmbuildBs()()
	},
)
