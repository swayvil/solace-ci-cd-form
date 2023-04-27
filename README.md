# solace-ci-cd-workflow
An example to create or update a queue on PubSub+ using Github Actions
## Prerequisites
### Declare a secret and environment variables
How to: [Creating configuration variables for a repository](https://docs.github.com/en/actions/learn-github-actions/variables#creating-configuration-variables-for-a-repository)
#### Declare this secret:
- SEMP_PWD
#### Declare these environment variables:
- MSG_VPN
- SEMP_URL (format should be: https://xxx.messaging.solace.cloud:943)
- SEMP_USER

## Usage
#### Run the workflow manually:
<img src="https://github.com/swayvil/solace-ci-cd-workflow/blob/main/run-workflow.png" width=50% height=50%>

## Limitations
Github Actions input form is limited to 10 fields maximum
