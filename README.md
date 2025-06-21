#TODO
- instead of using a shell script to create the CodeBuild Project, do it with a CloudFormation Template
This project does not actually use "sam pipeline" commands but showcase how one can build an AWS CodeBuild project yourself and then also build your own buildspec.yml file to
include sam commands to build and test.

- The pipeline.yaml was mostly modified to include the custom CodeBuild project
- 
# Execute in Steps
1 - sam-init.sh
2 - create-sam-codebuild-project.sh
3 - sam-python-app/pipeline.yaml
