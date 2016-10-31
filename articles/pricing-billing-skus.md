<properties
    pageTitle="Licensing overview | Microsoft PowerApps"
    description="Microsoft PowerApps licensing overview."
    services=""
    suite="powerapps"
    documentationCenter="na"
    authors="jamesol-msft"
    manager="anneta"
    editor=""
    tags=""
 />
<tags
    ms.service="powerapps"
    ms.devlang="na"
    ms.topic="article"
    ms.tgt_pltfrm="na"
    ms.workload="na"
    ms.date="10/30/2016"
    ms.author="jamesol"/>

# Licensing overview #
PowerApps is licensed on a per-user basis. Each user who accesses the service to create and run apps needs a license. Office 365 and Dynamics 365 customers can immediately benefit from the PowerApps and Microsoft Flow capabilities that these offerings include. Customers who want to build apps and flows that access data sources outside Office 365 and Dynamics 365, or need additional functionality, can purchase standalone  subscriptions to PowerApps and Microsoft Flow. There are important differences in functionality between these groups of licenses.

## Pricing ##
Please see the [PowerApps pricing page][2] for the latest pricing information for each PowerApps license.
Please see [Microsoft Flow pricing page][1] for the latest pricing information for each Microsoft Flow license.

## Licenses ##

### PowerApps for Office 365 and Dynamics 365 ###
PowerApps capabilities for Office 365 and Dynamics 365 enable users to create and run apps within the context of these services. These apps can also be extended to leverage data in common cloud services including Box.com, Facebook, and many more. Users with access to PowerApps through Office 365 and Dynamics 365 can't create or run apps against Microsoft Common Data Service databases. See the [PowerApps pricing page][2] for the list of Office 365 and Dynamics 365 plans that include PowerApps capabilities.

### PowerApps standalone Plan 1 and Plan 2 ###
Full-featured standalone PowerApps plans provide users the ability to create and run apps across data sources that extend beyond Office 365 and Dynamics 365, such as Salesforce and on-premises data sources, as well as Microsoft’s Common Data Service. These subscriptions also include features not available in Office 365 and Dynamics 365 plans.

- Microsoft PowerApps Plan 2 subscriptions are for users and administrators who need full create and run capabilities. These users have access to important management capabilities like viewing usage and setting policy. PowerApps Plan 2 users can model data in the Common Data Service.
- Microsoft PowerApps Plan 1 subscriptions are for users who primarily run apps. These users can still create apps and flows, but they can't model data in the Common Data Service or perform management tasks.

## PowerApps includes Flow ##
PowerApps licenses always include Microsoft Flow capabilities.  In addition to being included in PowerApps licenses, Microsoft Flow is also available as a standalone service. See [PowerApps pricing page][2] for more information on the specific Microsoft Flow capabilities that each PowerApps license includes.

## Resource capacity is included with each license ##
The per-user licenses above come with included capacity for resources used when an app or flow is executed. These resources include data storage, file storage, and flow runs. The capacities included in the per-user licenses are pooled at the tenant level and, when the tenant’s capacity is exhausted, customers may purchase additional capacity through add-on licenses. See the [PowerApps pricing page][2] for the capacity quantities that each PowerApps license includes.

## PowerApps licensing examples ##
Let’s take a look at an example. ABC Inc. has 1,000 employees, of which 700 employees are licensed with Office 365 Enterprise 3. Early on, a power user creates a line-of-business application that simplifies how customer orders are tracked. Later, the HR department works with IT to roll out an app for reporting time off and absences, and the app is built on the Common Data Service.

### Order-tracking app ###
ABC Inc. starts by developing an app for its Office 365 licensed users. The app brings together customer and product configuration data stored in Office 365 SharePoint lists with customer-order documents, which they store in Box.com. Because this app only accesses data stored in Office 365 and a common cloud service covered with a standard connector, the Office 365 licenses they already have cover both creation and usage of this app.

**Licenses required**:  The 700 Office 365 Enterprise 3 licenses they already have are sufficient.

### Time and absence app ###
Based on how quickly and easily the order-tracking app was launched, ABC’s Human Resources group enlists the help of IT to create a time and absence reporting app that will be rolled out across the entire company.  All employees will be required to use this app to report their hours, vacations, and sick days.

For this app, IT selects the Common Data Service as the system in which to store time and absence data. The Common Data Service provides the security and data-policy capabilities that IT requires for information related to employees. They assign two IT employees to the project to create the database and model the time and absence app data in the Common Data Service. These employees are also responsible for tracking app usage and establishing the policy applied to this data.

**Licenses required**:
* PowerApps Plan 2 – 10 licenses:  The 10 IT administrators who will set up the environments for the company to test and deploy their application, model data in the Common Data Service, and establish data-security policies will each require PowerApps Plan 2 to perform these functions.
* PowerApps Plan 1 – 990 licenses:  The 700 Office 365 users will need to be licensed with PowerApps Plan 1 because this app relies on data stored outside Office 365 (that is, in the Common Data Service). The other 290 users who don’t have Office 365 or the PowerApps Plan 2 license will need this license to have rights to run the app.

<!--Reference links in article-->
[1]: https://flow.microsoft.com/pricing/
[2]: https://powerapps.microsoft.com/pricing