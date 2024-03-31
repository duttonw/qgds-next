### For Binary Distribution and CDN repo connections via GitHub Action

## Variables
#This is required to point to the correct repo and allows forks to setup their own version

https://github.com/${org}/qgds-qol-mvp/settings/variables/actions

TARGET_REPO variable must be set
e.g.  ${org}/qgds-next-binary

TARGET_REPO_CDN variable must be set

e.g. ${org}/qgds-next-cdn


## Secrets 
This is required for deployment

https://github.com/${org}/qgds-qol-mvp/settings/secrets/actions

GH_TOKEN secret must be set

structure of the GH_TOKEN is

${username}:${token} 

e.g. username:mypersonalaccesstoken

if this fails, generate a new token via 
https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/creating-a-personal-access-token
and update the secret


