# Demo: API Protection with Barracuda CloudGen WAF

## Introduction

This lab can be used to demo the API protection features on the Barracuda Cloud Gen WAF. The backend server used is DVWS. To know more about DVWS visit: https://github.com/snoopysecurity/dvws-node


## How-to

Deploy the arm template to get started with demo.

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Faravindan-acct%2FDVWS_with_WAF_demo%2Fmain%2Fazuredeploy.json" target="_blank"><img src="http://azuredeploy.net/deploybutton.png"/></a>

## About DVWS

The attacks that can be executed on DVWS are provided here: https://github.com/snoopysecurity/dvws-node/wiki


## WAF Configuration Instructions

1. Create a HTTP or HTTPS service on the waf
2. Import the swagger file into the JSON Security page on the waf under the service created in step1.
   Use the file "swagger2_0.json" for this step.
