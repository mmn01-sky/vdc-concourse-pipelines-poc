# vdc-concourse-pipelines-poc

https://concourse.at.sky/
https://github.com/mmn01-sky/vdc-concourse-pipelines-poc 

Unpause all pipelines

# notes
set primary pipeline:
fly -t concourse-prod set-pipeline -p vdc-pipelines -c pipelines/set-pipelines.yaml
unpause pipeline
fly -t concourse-prod unpause-pipeline -p vdc-pipelines