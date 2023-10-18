# maven-versioning-demo

## Prepare a release
```mvn release:clean release:prepare```
 This will update the version of a project and push to github repo that is specified
## Perform a release
```mvn release:perform```
This will update the code to the given third party repository example **NEXUS**

## Link
-  https://maven.apache.org/maven-release/maven-release-plugin/index.html

**NOTE:** I am not able to perform mvn release:perform getting this error


[ERROR] Failed to execute goal org.apache.maven.plugins:maven-deploy-plugin:2.7:deploy (default-deploy) on project version-demo: Deployment failed: repository element was no
t specified in the POM inside distributionManagement element or in -DaltDeploymentRepository=id::layout::url parameter -> [Help 1]
 
