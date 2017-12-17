# DevTest Labs

## Service description

One of the main attractions of the cloud is the flexibility and potential cost savings/avoidance that you can have when operating your workloads. This is especially important when you think of environments such as Dev/Test, that may not need to be in operation 365 days a year, 24x7. Today, 50-70% of on premises compute is used for non-production workloads. But the benefits are not solely focused on cost savings. What about the potential for increased agility in your application development? Or developing for those mobile-users, on the move?

The DevTest Labs workstream will provide a foundation including:
* Insight into the options of managing your development environment
    * Using subscriptions
    * Using Resource Groups
    * Using DevTest Labs

Building upon that foundation, you will then look into DevTest Labs.

    Gain insight into Azure DevTest Labs; a service that helps IT manage environments that empower developers and testers to quickly create infrastructure for use within the development lifecycle. While this process happens, allowing IT to define a set of policies that control how the resources can be used in the lab, which creates a sandbox environment that enforces developers and testers smartly use the resources in a predictable way.

## Agenda

* Traditional DevTest Challenges
* DevTest Labs Overview
* DevTest Labs Scenarios
* DevTest Labs POC (From the persona of an environment Owner and User)
    * Resources Created
    * Access Control (DevTest Labs User)
    * Governance - Limiting Resources
    * Governance - Cost Management
    * Virtual Machine Management
    * Repeatable Tasks - Formulas and Environments (ARM Templates)
    * Artifacts
    * Claimable Virtual Machines
    * Private Repositories for Artifacts and Environments (ARM Templates)

## Prerequisites
Please ensure that the customer has the following lined up, so that you can run through the session successfully;

* Access to the Azure Portal
* Ability to join the skype call below, and screen share.
* At least two attendees with access to Azure.
    * One user will need owner access to a  subscription/Resource Group, to provision DevTest labs.
    * The second user should have no permissions higher than reader over the subscription. This will allow us to walkthrough the persona of a DevTest labs user.
* *If possible, a GitHub account* (and ability to generate a Personal Access Token)

## Delivery guide

> **Note:** When doing demos use the [Public version of the Azure Portal](https://portal.azure.com/?feature.customportal=false)

|  | Source format | Estimated time | Deliver from | Readiness Resources |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| DevTest Labs Overview | PowerPoint | 30 - 40 min | [Delivery Ready IP\Dev-Test\DevTest Labs\FTA - DevTest Labs - Overview.pptx](https://microsoft.sharepoint.com/teams/fasttrackforazure/CE/_layouts/15/SkySyncRedir.aspx?Type=2&ResourceId=4f56e6390a64408bb719f8e3a777d2c6) | |
| DevTest Labs POC - Environment Owner | POC Guide | 1.5 hrs | [github.com/azure/fta-devops/articles/devtest-labs-walkthrough-it.md](https://github.com/Azure/fta-devops/blob/master/devtest-labs/articles/devtest-labs-walkthrough-it.md) | | 
| DevTest Labs POC - Environment User | POC Guide | 15 mins | [github.com/azure/fta-devops/articles/devtest-labs-walkthrough-dev.md](https://github.com/Azure/fta-devops/blob/master/devtest-labs/articles/devtest-labs-walkthrough-dev.md) | | 