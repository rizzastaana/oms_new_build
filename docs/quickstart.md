# System Overview

The Operational Management System (OMS) is amedia management platform that controls, monitors, and surfaces media fulfillment data. The OMS enables users to monitor the health of their business, analyze processes, and provide actionable insight via interactive and customizable visualizations.

Integrated with third party apps such as  SDVI Rally, Rightsline, and BeBanjo, the OMS combines both an order management system with extensible task management queues so that users have a unified view of supply chain data that leverages each core component/integration.

This tutorial teaches you OMS essentials as a new user. This QuickStart guide will show you:

-   how to log into OMS
-   how to set up roles and permissions for specific customers
-   how to create studios, brands and titles in Rightsline
-   OMS supply chain fundamentals
-   how to create OMS customer profiles
-   how to create a customer profile in the OMS
-   how to place and manage orders, jobs, and tasks in the OMS
-   how to navigate and manage your titles in File Manager
    
This QuickStart guide will also show you the OMS interface and the terminologies, naming and file conventions used in the platform, and additional workflows and use cases.

## Getting Started - Logging In

To complete this tutorial using this QuickStart guide, you need to have an Okta account.

Access to the OMS is enabled via Okta. All LADB users that have single sign-on authorization enabled and access requested should be able to view the OMS app in their LADB Okta apps list.

1.  Open a browser and log into your LADB Okta platform using your user credentials.
> **Note:** The following browsers are compatible with OMS:
>- **Fully supported:**
>--   Chrome: version 93.0.4577+
>--   Safari: version 15+
>--   Edge: version 93+
>- **Limited support:**
>-- Firefox

2.  Click OMS from the LADB Okta apps list.
3.  The OMS dashboard is displayed once single sign-on access is authorized.

## The OMS Browser and user interfaces

The OMS platform is comprised of five (5) main user interfaces:  

1.  The OMS Dashboard provides a high-level visualization of content orders, filterable by date month, in order for a user to identify actionable items and see business trends. Users can view order and delivery performance and navigate directly into orders in specific states.

2.  The Orders interface shows a list of content orders at a high level (with optional filters and saved searches). Along with an order’s status and progress, you can click into the Jobs that comprise the Order or edit the Order’s details.
    
> **Note:** An Order is a grouping of line-item jobs.

3.  The Jobs interface shows a list of actionable Jobs that users can navigate into.  
      
    > **Note:** The jobs are line items within an Order.

4. The Task Management module allows you to view specific types of Tasks comprised within a job.
    
**Pending Assets** – Tasks that require assets to be ingested against a SDVI-created shell record, or future use asset, so that the job can continue to the next processing state.

**Review Task** – Tasks that require video QC screening before it can be edited or delivered.

**Edit Tasks** – Tasks that require editing of a master source asset in Adobe Premiere. 
    
**Processing Exceptions** – Tasks that have incurred an error in the workflow and requires action by a user. 

5. File Manager is a user-friendly interface for users to manage content files without needing to gain access to direct storage (e.g. Amazon Web Services (AWS) S3 bucket). 

## Dashboard basics

The OMS Dashboard provides users an at-a-glance view of all orders and deliveries by Month. Users can view order and delivery performance, click into actionable items for orders in specific states, and download daily and weekly reports. 

Upon initial login to the OMS, the Month filter dropdown will default on “All Months”. To change this to a specific month, click on the dropdown arrow and select the month you would like to view Dashboard data for. 

In this example, the “March 2022” filter is selected. Note that counts will then shift and update in real-time. User is now viewing order statuses and deliveries for the March 2022 month: 

**Order Status Cards** 

The status card indicators at the top of the Dashboard allow users to view orders by the following statuses: 

* Awaiting Assets: Orders requests that are awaiting assets 
* Ready: Orders ready for processing 
* Processing: Orders processing in progress 
* Delivering: Orders in a ready for delivery or delivering state 
* Delivered: Completed jobs 

To view all orders for a specific state, click on the associated status card. Note that all orders are derived and aggregated from BeBanjo statuses. Refer to the BeBanjo developer documentation for more information about third-party app integrations. 

**Open Jobs Status** 

The Open Jobs Status provides users with a visualization of orders in the various states. Hovering over a state in the pie chart will display the percentage of orders in that state.  

In this example, we hover over the Awaiting Assets state to view that 46.9% of jobs are missing asset components to be worked on. 

**On-Time Delivery** 

The On-Time Delivery graph displays a comparison of deliveries over the past 6 months. In the image below, the comparison of on-time delivery is between the months of March and April 2022. 

**Media Delivery** 

The Media Delivery module is available when a Month is selected. It displays the percentage of the total media that has been delivered for the selected Month. It also displays the percentage delivered. 

In the example below, 13% of the media has been delivered so far, with 13% of the deliveries delivered on time.
