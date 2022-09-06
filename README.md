# Getting started with the Operational Decision Manager for container 

## Audience

This tutorial is for technical and business users who want an introduction to business rules authoring and management, with IBM Operational Decision Manager (ODM) running in a container environment. Here are the different ODM offerings where you can use this getting started:
   * [IBM Operational Decision Manager for Developers](https://hub.docker.com/r/ibmcom/odm/) - to deploy ODM in Docker environments, for evaluation and development purposes
   * [IBM Operational Decision Manager for Developers on Certified Kubernetes](https://artifacthub.io/packages/helm/ibm-charts/ibm-odm-dev/22.1.0) - to deploy ODM on Certified Kubernetes environments, for evaluation and development purposes 
   * [IBM Operational Decision Manager for production on Certified Kubernetes](https://www.ibm.com/docs/en/odm/8.11.0?topic=kubernetes-installing-odm-production) - to deploy ODM on Certified Kubernetes environments, for production use
   * [IBM Operational Decision Manager in IBM Cloud Pak for Business Automation](https://www.ibm.com/docs/en/cloud-paks/cp-biz-automation/22.0.1?topic=capabilities-operational-decision-manager) - to deploy ODM on Red Hat OpenShift in the context of IBM Cloud Pak for Business Automation


## Time required

1 hour

## Learning objectives

Through a tour of Decision Center and the Rule Execution Server console, you learn how to collaborate with other users to create and modify rules in decision services, manage changes, run tests, deploy rule applications, and test and execute deployed rules as rulesets.

This tutorial does not cover decision service development in Rule Designer, collaborative development in the decision governance framework, or simulations in Decision Center.

## Additional project

This tutorial uses the Miniloan Service decision service. To further explore the development components, you can use the following sample project, which come preloaded in the Decision Center Business console:

|Project|Description|
|------|-----------|
|Loan Validation Service|This decision service validates loans based on borrower data and loan parameters. It also computes loan insurance rates.|

## Table of contents

-   [Tutorial scenario and prerequisites](doc/topics/tut_icp_gs_int.md)
-   [Task 1: Evaluating the decisions](doc/topics/tut_icp_gs_evaluate_changes_lsn.md)
-   [Task 2: Creating and editing rules](doc/topics/tut_icp_gs_create_rules_lsn.md)
-   [Task 3: Verifying updates and deploying](doc/topics/tut_icp_gs_test_deploy_lsn.md)
-   [Task 4: Exploring and testing the ruleset](doc/topics/tut_icp_gs_test_ruleset_lsn.md)
-   [Task 5: Cleaning out databases](doc/topics/tut_icp_gs_clean_db_lsn.md)

## Licensing information

Copyright IBM Corp. 1987, 2022. Licensed to the Apache Software Foundation \(ASF\) under one or more contributor license agreements. See the NOTICE file distributed with this work for additional information regarding copyright ownership. The ASF licenses this file to you under the Apache License, Version 2.0 \(the "License"\); you may not use this file except in compliance with the License. You may obtain a copy of the License at [http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0). Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

[**Next** ![Next icon](doc/images/next.jpg)](doc/topics/tut_icp_gs_int.md)
