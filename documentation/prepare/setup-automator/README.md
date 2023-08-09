# Configure Your Global Account in SAP BTP Using the Setup Automator Tool

The Setup Automator is an open source tool you can find on GitHub in the [https://github.com/SAP-samples/btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) repository. It helps you to configure automatically your global account in SAP BTP.

With the Setup Automator tool, you can configure:
* Global account in SAP BTP
* Service entitlements
* Subscriptions to applications and service instances with service keys
* Administrator users to global account and subaccounts
* Roles and role collections, assignment of roles collections to users
* Application deployment
* Cleaning up all the configurations you have done using the tool

The Setup Automator is a script running on a [Docker](https://www.docker.com/) container and is under an open source license. You configure the tool with two files both in JSON format:
* parameters.json: in this file you specify where the global account in SAP BTP is
* usecase.json: in this file you specify the services you want to explore

In the [usecase](https://github.com/SAP-samples/btp-setup-automator/tree/main/usecases/released) folder of the Setup Automator repository, there are the released use cases. In each use case, you can find the serivces used, their service plans, and other parameters.

To install and run the Setup Automator tool, see the [https://github.com/SAP-samples/btp-setup-automator](https://github.com/SAP-samples/btp-setup-automator) repository on GitHub.

For an overview and a demo of the Setup Automator tool, see the following video:

[![Ask-the-expert video recording](https://img.youtube.com/vi/3pLNXsn-cLM/0.jpg)](https://www.youtube.com/watch?v=3pLNXsn-cLM)
