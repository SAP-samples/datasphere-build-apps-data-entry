# Prerequisites

This section contains the prerequisites that you have to fulfill before you get started. Make sure that the prerequisites are fulfilled and all required systems, services, and tools are available.

## SAP BTP Accounts

1. SAP BTP Cloud Foundry Global Account (with one of the below plans)
   - Pay-As-You-Go 
   - CPEA (Cloud Platform Enterprise Agreement) 
   - Subscription-Based Commercial Model

    [Pay-As-You-Go with free tier model](https://www.sap.com/products/technology-platform/trial.html) is open to customers, partners, and individual developers and let you try out SAP BTP for free without time limits. It enables you to test your scenario and generally offer the option to upgrade to paid service plans.

2. SAP BTP Subacount with below entitlements
3. SAP BTP Space
 
## System

[SAP Analytics Cloud (SAC)](https://www.sap.com/products/technology-platform/cloud-analytics.html)

## Entitlements

The mission requires the following [Entitlements and Quotas](https://help.sap.com/docs/btp/sap-business-technology-platform/entitlements-and-quotas) in the SAP BTP cockpit.

| Service | Plan |
| --- | --- |
| SAP Build Apps | free or standard |
| SAP Build Work Zone, standard edition | free or standard |
| SAP Business Application Studio | free or standard |
| SAP Datasphere | free or standard |
| SAP HANA Schemas & HDI Containers | hdi-shared |

## Tools (Optional for manual deployment to SAP BTP)

- [Cloud Foundry command line interface (v7 version or later)](https://github.com/cloudfoundry/cli/wiki/V7-CLI-Installation-Guide)

- [Cloud MTA Build Tool](https://sap.github.io/cloud-mta-build-tool/) - you can install it using Node.js.

```
npm install -g mbt
```


