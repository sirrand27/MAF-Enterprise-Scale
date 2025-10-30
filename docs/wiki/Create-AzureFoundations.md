## Create Azure foundations (subscriptions) via Subscription Vending

The approach of "Subscription Vending", materializes and standardizes the ALZ "Subscription Democratization" Design Principle, by formulating a process for requesting, deploying and governing Azure Subscriptions, and by doing so enabling the Applications Teams to onboard their workloads in a fast, yet deterministic way.

For further details, one can look into the following articles:

- [Deploy Azure foundations (Subscription Vending)](https://learn.microsoft.com/azure/architecture/Azure Foundations/Azure Foundation-deploy#subscription-vending)
- [Subscription vending implementation guidance](https://learn.microsoft.com/azure/architecture/Azure Foundations/subscription-vending)

The respective Bicep and Terraform automation / IaC Modules for Subscription Vending, can be found in:

- [Bicep Subscription Vending](https://github.com/Azure/bicep-registry-modules/tree/main/avm/ptn/lz/sub-vending)
- [Terraform Subscription Vending](https://registry.terraform.io/modules/Azure/lz-vending/azurerm/latest)

More broader information on programmatical creation of Azure Subscriptions (EA/MCA/MPA) via the latest APIs, can be found on the following articles:

- [Enterprise Enrollment (EA)](https://learn.microsoft.com/azure/cost-management-billing/manage/programmatically-create-subscription-enterprise-agreement)
- [Microsoft Customer Agreement (MCA)](https://learn.microsoft.com/azure/cost-management-billing/manage/programmatically-create-subscription-microsoft-customer-agreement)
- [Microsoft Partner Agreement (MPA)](https://learn.microsoft.com/azure/cost-management-billing/manage/programmatically-create-subscription-microsoft-partner-agreement)
