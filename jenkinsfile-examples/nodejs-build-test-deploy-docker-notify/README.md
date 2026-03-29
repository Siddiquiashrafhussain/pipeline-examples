# Synopsis
Demonstrate an example of a Jenkinsfile to build/test/deploy and notify based on results

# Background

This sample uses Declarative Pipeline stages and `post` conditions to perform result-based actions. This example Jenkinsfile shows.
- Pull from Git
- Install nodejs
- Build
- Test
- Build and push a docker container to private dockerhub
- SSH to a server to tell it to use the new image
- Notification by email of positive or negative results through `post { success/failure }`

# A more detailed groovy example
The inspiration and help on how to do this came from (https://github.com/freebsd/freebsd-ci/blob/master/scripts/build/build-test.groovy)



 

