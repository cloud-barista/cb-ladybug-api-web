# GitHub Pages to host CB-MCKS API Documentation

CB-MCKS is a Framework for Cloud-Barista Platform to Manage Multi-Cloud Kubernetes Service.
(https://github.com/cloud-barista/cb-mcks)

This repository is to host CB-MCKS API Documentation in GitHub Pages.

```
[NOTE]
CB-MCKS is currently under development. (the latest version is 0.4 Cafe Mocha)
So, we do not recommend using the current release in production.
Please note that the functionalities of CB-MCKS are not stable and secure yet.
If you have any difficulties in using CB-MCKS, please let us know.
(Open an issue or Join the cloud-barista Slack)
```

The API document in this repo is for CB-MCKS master branch. 
(https://github.com/cloud-barista/cb-mcks/tree/master)

It is not for API release but for development.
(master branch is a dev branch)

## Access the API documentation page

Access to: https://cloud-barista.github.io/cb-mcks-api-web/
(Authorize with `default`/`default`)

## How to update the API documentation page

Replace 

https://github.com/cloud-barista/cb-mcks-api-web/blob/master/swagger.yaml 

with 

https://github.com/cloud-barista/cb-mcks/blob/master/src/docs/swagger.yaml

GitHub pages will update the page automatically.
