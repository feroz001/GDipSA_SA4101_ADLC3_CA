# ADLC3_CICD_CA

DipSA CICD Workshop
Due: 0900 Monday May 08 2023 Total marks: 16% of SA4101
This is an individual workshop.

What it does?
- Repo contains a simple golang application and a workflow.
- A pipeline is triggered when a branch with the following format release/v<digit>.<digit> is pushed.
For example, if a branch is pushed with the following names release/v1.0, release/v15.3 or release/v7.09, it should trigger the workflow but not release/v0.1-, release/beta, v0.1.1 or feature-01.

- Once triggered, workflow will deploy the application to a provisioned Railway service and send a notification to Slack using webhook.

- Slack notification is built with https://app.slack.com/block-kit-builder
