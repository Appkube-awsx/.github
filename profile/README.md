## Introduction
   Synectiks Appkube is a SRE platform that primariliy focuses on following :
   -  Manage distributed microservices cost & Quality (container & servless) in multicloud hybrid environment
   -  Deliver reusable common App Blocks to write enterprise products with reduced codeing effort
   -  Deliver DevSecOps tooling to write enterprise products
 
 To know more about Appkube platform , please visit -  https://github.com/AppkubeCloud
 
 
 Appkube-awsx organization hold the source code of all AWS cloud related extensions that we write.
 
 Please refer to the below diagram to know details on how Appkube main platform use awsx tools and utilities.
 
 ![alt text](https://raw.githubusercontent.com/AppkubeCloud/appkube-architectures/main/LayeredArchitecture.svg)
 
 ## Repository Structure 
 awsx -- Its the main aws extension CLI , that has modular structure to cater any subcommand as plugin.
 awsx-cloudelements --- These repos are plugins for main cli
 awsx-api -- AWS extension API Server  
 awsx-metric -- It provides metric/stats for AWS cloud
 awsx-log -- AWS extension API to cater log related challenges
 awsx-trace -- AWS extension API to cater trace related challenges
 awsx-compliance --AWS extension API for Cloud compliance
 awsx-cost --AWS extension API for Cloud Cost API
