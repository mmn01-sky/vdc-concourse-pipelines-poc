# vdc-concourse-pipelines-poc

# concourse notes
set primary pipeline:
fly -t concourse-prod set-pipeline -p vdc-pipelines -c pipelines/set-pipelines.yaml
unpause pipeline
fly -t concourse-prod unpause-pipeline -p vdc-pipelines