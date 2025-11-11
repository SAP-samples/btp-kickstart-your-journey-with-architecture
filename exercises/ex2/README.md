# Exercise 2: Explore SAP BTP Services and Content

[**< Return to the main page**](../../)

<br/>

> [!NOTE]
>
> **Learning Objectives**:
>
> - Learn about the BTP Services Catalog in the SAP Discovery Center.
>
>   [SAP BTP Services Catalog ](https://discovery-center.cloud.sap/viewServices)
>
> - Get to know the SAP Business Accelerator Hub, SAP's central repository for business content that simplifies starting and implementing projects on SAP Business Technology Platform.
>
>   [SAP Business Accelerator Hub ](https://api.sap.com/)
>
> - Learn how to use the SAP BTP Estimator tool in the SAP Discovery Center to estimate platform costs for your scenarios.
>
> **Duration**: ~15 minutes

<br/>

## Step 1: Evaluating Details for SAP BTP Services <br/>

Now that you understand the BTP services required for the chosen architecture, you'll gather more details about them. We'll use "SAP Build Process Automation" as an example.<br>

1. On the "Extend Joule with Joule Studio" page in the SAP Architecture Center, scroll down to the list of services and components for the architecture.<br>

   ![Architecture Explorer2](./images/12.png)<br>

2. Choose "SAP Build Process Automation" to view details for that BTP service.

   This opens a new tab/window, taking you to the service's page in the SAP Discovery Center Service Catalog.<br>

   ![Architecture Explorer3](./images/13.png)<br>

3. Quickly review the features to understand the service's purpose. You can also look at "Customer Stories" or "Related AI Offerings" for usage examples.<br>

   SAP BTP provides technical services and business content. Next, you'll check if there is any pre-existing content available for this service.<br>

4. Navigate to "SAP Build Process Automation" in the "Integration Content" section. <br>

   This opens a new tab/window with the product page for SAP Build Process Automation on the "SAP Business Accelerator Hub," the central repository for business content for services on SAP BTP.

## Step 2: Browsing Business Content on SAP Business Accelerator Hub

The page outlines the availability, definition, and documentation of an OData and a REST-based API, as well as a link to the general service documentation.<br>

5. Click on "REST API" to discover details of the available operations.

   ![Business Accelerator Hub](./images/14.png)<br>

Looking at the general navigation of the Business Accelerator Hub, you will also find a link to pre-packaged integrations for SAP Integration Suite, available Data Products for the SAP Datasphere offering, and a section for SAP Build - SAP BTP's portfolio for Application Development and Automation.

Since "SAP Build Process Automation" is part of the SAP Build portfolio, you decide to drill down into the "SAP Build" section.<br>

6. Navigate to the general content space for "SAP Build" in the top navigation. <br>

   ![SAP Build Content](./images/15.png)<br>

7. Browse the available SAP Build Content to understand the different types available. Use the filter to see the different content types offered for SAP Build. <br>

   Unfortunately, no SAP Build content is currently available for your scenario, so you decide to go back to the Discovery Center. <br>

🧠 **Knowledge check:**

<details>
    <summary>
        What are the four different kinds of project-related content packages currently available for SAP Build?
    </summary>
     The four different types of project content that can be downloaded for SAP Build are:<br>
     - Task Automations<br>
     - Business Processes<br>
     - Live Processes<br>
     - Full-Stack Applications<br>

</details>
<br>

8. Close the SAP Business Accelerator Hub tab/window and return to the SAP Build Process Automation page in the SAP Discovery Center's Service Catalog. <br/>
   <br/>

## Step 3: Estimating Costs for a Scenario

To get a cost estimation for a scenario, you need to understand the commercial model and metrics of the required services.

9. Navigate to the "Pricing" tab of the "SAP Build Process Automation" page.

![Pricing Tab](./images/16.png)<br>

10. Find the commercial model dropdown to see the different models available for this service. Choose "BTPEA". <br>

11. Review the different sections for the available service plans. Note that there is a "free tier" service plan available for consumption-based contracts, which allows free service usage with certain restrictions (described in the service plan section).

12. Navigate to the "Standard User" service plan and read the description to understand that this is the required license/service plan for the end-users of the scenario.

13. Add this service plan to the estimator by clicking the "Add to Estimator" button. A short message will appear confirming it has been added.

14. Also, add the "Advanced User" service plan to the estimator. The description shows that this is the required plan for users who will create or administer scenarios in SAP Build Process Automation.

Now that you have added the required service plans for SAP Build Process Automation to your scenario, open the estimator.

15. Click the small calculator symbol at the top right of the page to open the estimator and choose "Local Estimate".

![Estimator Icon](./images/17.png)<br>

The estimator page will appear:<br>

![SAP BTP Estimator](./images/18.png)<br>
The SAP BTP Estimator helps you get an understanding of the cost of a specific scenario.

16. You can name your estimation and check the calculation period, commercial model, and other general settings by clicking the pencil symbol.

17. Make sure to select the preferred region for deployment and the needed number of users for both service plans added to the estimator. Select "30" standard users and "5" advanced users.<br>

Be aware that BTP uses active users as its user metric and that you are calculating for a consumption-based model (BTPEA). This means these values reflect the actual number of users of the service over one month for the overall period of a full year. Less consumption/usage in some months will save credits for months of higher usage.

Have a look at the screen. You have now estimated the cost for end-users and creators of the Process Automation service as part of the scenario. Be aware that these users are not restricted to a certain scenario. If the users of your applications use SAP Process Automation in other scenarios, these costs can also be split by usage (see the split circle symbol next to the trashcan). <br>
If you want to create an estimation for a full scenario, you can add all BTP services with their respective plan(s) here to do your estimations (either by clicking the "Add Services" button or by browsing the catalog and adding them from the respective service pages). <br>
To collaborate, share, and discuss your estimations with colleagues and partners, you can manage, configure, personalize, and share several different estimations if you register and log in to the Discovery Center.<br>

🧠 **Knowledge check:**

<details>
    <summary>
        What is the BTP "Free Tier" option? Are all BTP Customers entitled to use the free-tier service plans?
    </summary>
    <p>
        The free-tier offering lets you try out SAP BTP for a service-defined time span for free. These account types enable you to test your scenarios and generally offer the option to upgrade to paid service plans. These accounts also allow you to store data long-term and move projects to production.
        <br/>
        Only the consumption-based contracting models of SAP BTP (CPEA, BTPEA, Pay-as-you-go) include the entitlements to use the free-tier service plans.
    </p>
</details>

<br/>

[**< Return to the main page**](../../)
