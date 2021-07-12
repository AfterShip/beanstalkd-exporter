#!/usr/bin/env groovy
// Centralize Jenkins Pipelines configuration using Shared Libraries
// https://github.com/AfterShip/deployment-jenkins-pipeline-library-ci-aftership-org
@Library("jenkins-pipeline-library@automation") _
entry {
	isDryRun = false
	flow = "golang"
	ci_only = true
	configInfo = [
	      deploymentGroup          : "postmen",
	      appName                  : "beanstalkd-exporter",
	      gitRepoName              : "beanstalkd-exporter.git",
	      chartName                : "worker",
	      essentialDockerImage     : "golang-essential",
	      essentialTag             : "golang-1.13.5",
	      requireStaticAsset       : false,
	      uploadAssetCredential    : "",
	      unitTest                 : "",
	      integrationTest          : "",
	      useEnvironmentVariable   : true,
	      hasReleaseEnvironment    : false,
	      hasStagingEnvironment    : false,
	      hasProductionEnvironment : true,
	    ]
}
