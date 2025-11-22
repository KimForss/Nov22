**SAP System Deployment**

The SAP Application (**X00**) has been deployed to resource group **TST22-SECE-SAP03-X00** in subscription **d6c8e3b6-467e-452e-97c9-49d9de9e37da**.

You can access the resource group directly in the Azure Portal using the following link: [TST22-SECE-SAP03-X00](https://portal.azure.com/#@c01abe72-ffef-4ecc-bda0-937975b49e6b/resource/subscriptions/d6c8e3b6-467e-452e-97c9-49d9de9e37da/resourceGroups/TST22-SECE-SAP03-X00/overview)

**SAP Application Information**


| Setting                    | Value                           |
| :------------------------- | :------------------------------ |
| SID                        | X00                          |
| Database                   | hana                     |
| DB SID                     | HDB                       |
| SCS Server Loadbalancer IP | 10.110.32.7   |
| SCS High Availability      | Yes        |
| DB High Availability       | No   |


**Server Roles and Names**


| Role                           | Names                           |
| :----------------------------- | :------------------------------ |
| Database                       | x00dhdb00l075                   |
| Central Services               | x00scs00l757,x00scs01l757                  |
| Primary Application Server     | x00app00l757                   |
| Additional Application Servers | x00app00l757          |
| Web Dispatchers         | x00web00l757              |


**Access credentials**


| Setting                  | Value                           |
| :----------------------- | :------------------------------ |
| Key Vault Name           | TST22SECESAP03user434                |
| Secret name for username | TST22-SECE-SAP03-X00-sid-username         |
| Secret name for password | TST22-SECE-SAP03-X00-sid-password         |
| Secret name for SSH key  | TST22-SECE-SAP03-X00-sid-sshkey              |


