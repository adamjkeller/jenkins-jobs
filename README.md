# THIS REPO'S ORIGIN IS IN GITHUB
#### If you're reading this from devgit, please submit a PR to the github url instead. 

https://github.com/brentley/jenkins-jobs


If you want a job to be built in jenkins, this is where you start. Add the job name, repo url, and branch to be built. It will be read from here and the job will be created.

NOTE: The actual Jenkinsfile, which defines the pipeline to build the code will live IN the code repo itself, not here. This is just going to generate a basic shell job that will point to your repo and look for the Jenkinsfile in that repo.
