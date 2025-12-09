Braintree CRM24

First Use Training Guidelines

Your CRM24 “Training Handbook”

# Basic Navigation

## Access Environment

### URL

CRM24 is a web-based application, using Microsoft’s cloud-based Dynamics 365 Customer Engagement Platform

Access your environment by opening your web browser and browse to the URL provided to you by Braintree

The URL will look something like this: https://{yourorgname}.crm4.dynamics.com/main.aspx

### Username and Password for Admin User

When accessing the above URL, use the username and password for the admin user access provided by Braintree to access your environment and follow the rest of the steps below

The username will look something like this: name.surname@orgname.onmicrosoft.com unless you are using your own existing O365 instance, in which case the username will differ.

### Access via  O365

A quick overview of some of the areas within here.

What you have access to will depend on your licences and roles.

You've got your Admin area (if you are an admin). This is the admin error for the Office 365 where SharePoint Azure as well as when we get into what's referred to as the Power platform for our environment management.

The Power Apps area here. We'll be going into this if you were going to be doing any configuration or customization to your apps Power Automate some of you might be familiar with this already and the flows – this replaces the classic workflows of Dynamics 365 CE

Then you have other Microsoft apps here, under the Business Apps area where we're going to start.

CRM24 can also be accessed via your O365 login and selecting the Sales Hub BTCRM24Combo Business app

## Navigation

The BTCRM24Combo Business App opens in the following page

Your navigation within the app is located here on the left side, also referred to as the site map.

These are your different areas like your dashboards, activities, other entities or tables as I'll refer to them, like your accounts, contacts, leads, opportunity and so forth.

At the bottom left is where you can change the area within the app so this could be app settings.

### Navigation Pane

To navigate your CE Application: Use the Navigation Pane on the left

To switch between the Sales Hub or the Service Hub, simply click on the existing hub e.g. Sales Hub, found on the top of the page next to the CRM24 icon.

As part of CRM24 the 2 apps that will be available for use are : Customer Service Hub and Sales Hub.

After selecting Service Hub, the navigation pane on the left will have a few different options, now relevant to the Service Hub.

For easy navigation, you can use the “Recent” area to navigate to areas recently visited

To pin items from recently viewed record types to see them under “Pinned” area.

### Dashboards

For both the Sales and Service areas there are a number of default dashboards that can be viewed.

Each of these dashboards is customised to show relevant data

e.g. Tier 2 Dashboard

### List Views

Click on the item in the left navigation bar e.g. Activities, or Accounts etc.

For the specific list you can use the dropdown next to the view name and choose the appropriate option

Use the command bar buttons at the top to create new records.

e.g. New Appointment

e.g. New Account

The details of the new record can then be completed and saved e.g. new appointment.

Note: The red Asterix indicates required fields. If you try to save a record without completing all required fields you will receive an error showing you the fields needing to be completed.

When a list of records is displayed from a view, click on the name of the record to open that record.

The record is then opened for viewing /editing/

### Filtering & Searching

Global Search

The global search is very useful to search across various entities i.e. Clients, Contacts, Leads etc.

The Record search bar can be used to restrict the list of records in a list.

The Advanced Find

The Advanced Fine is where you can build personal views. You could start with a default view and then save it with a new name, and thereafter edit the columns and properties and filters used.

These Personal Views can be used for  Ad hoc reporting, for instance to export some lists to Excel.

The Advanced Filter can be used to restrict the list based on certain applied column filters.

After clicking on the Advanced Filter

Various fields can then be used to apply filters to the list.

Another way of applying a column filter is to click on the column and choose to Filter By

### Timeline

With your timeline, you can create your different activities, your notes with attachments and other posts. You do have a nice filtering capability. So within the timeline you could filter by record type like the different activity types. If you wanted to just look at the emails or just look at the tasks or phone calls, do that right within here within the record.

### Personalisations

Using the Gear in the top right of the window, you can access Personalisation Settings

This is where you can set certain settings that are relative to your login only i.e. No of records to display on a page (useful when needing to export records to Excel), or an email signature e.t.c.

## Theme Colours and Logo

The system theme colours of CRM24 can be changed to match your organisations theme colours. You can also add a logo.

This is done from within Settings  Customisation

And then choosing Themes

New themes can be creating by Clicking on New.

Existing Themes can be cloned by clicking on Clone.

Once a theme has been created\edited – to make it the active theme, click on Publish Theme.

Note: The logo 1st needs to be added as a web resource before it can be used

Navigate to Settings - >> Customise the system

Navigate to Components - >> Web Resources

Choose to Add a New web resource.

# Service Cases & Activities

## Overview

Customer service is a module that relates around servicing a customer

A case is the central record that identifies the incident that a customer has been facing for some products.

Activities are the means by which we can communicate with a customer either Incoming or Outgoing i.e.  we can make a phone call to a customer i.e.  it is an Outgoing phone call.

If a customer direct calls to a customer representative for some breakdown purpose, then through a phone call, we can also create an activity called “Phone call” with direction Incoming, because the phone call came from the customer itself towards our business.

These type of activities are normally the origin for a the generation of a case.

In the service module different routing rules can be setup, by which we can route a specific incident or a case to a queue or a team or a user to handle that case in proper time.

A queue can be seen as a bucket where we assign some of the cases or incidents to that queue so, that the users who belongs to that queue will take action on that case record or incident record

Holiday schedules are the timelines by which we can define which days of the year represent a holiday for our business. These can then be used in cases to ensure SLA’s defined are based on the business operating times and days only.

An SLA is nothing but the service level agreement by which we can provide a facility to the customer to solve any type of issue within a specified time limit right. If there is high priority incident rate, then we can able to solve that issue or case within two hours so do our says that a select time period or ritual being used case.

Entitlements are nothing but the level of services that the business will provide to the customer e.g. granting the customer a 24/7 service for a product that we have sold

Scheduling is nothing but extending or deciding a timeline at a customer's place for servicing or installment or installation or maintenance activities.

## Cases & Activities & Queues

### New Case

Click on Cases in the left Navigation Pane, then on the top command bar, click “+ New”.

Then complete all fields.

### Business Process

Use the Guided Process flow at the top to ensure the correct process is followed in resolving the case.

Once the info for a stage is completed you can click on “Next stage” to move to the next stage.

### Add Activities

Add activities to show the work done in resolving the case.

e.g. add a task

All activities need to be marked as Complete before the case can be marked as resolved.

If the action is taken to Resolve Case and there is an open activity then the case is preventing from being resolved, unless you are willing for those activities to be auto cancelled.

The activities can be actioned from the Timeline

They can either be:

Assigned

Closed

Added to a Queue

Record Opened

Deleted

Once opened the activity can be marked as Complete

A note with an attachment can also be added to the Case – this could perhaps be a screenshot sent be a user of the error.

Part of the case resolve process is to determine if any escalation is required

Other tabs on the case are:

Case Relationships

Articles & Contracts

Associated Knowledge Records

Related

### Assignment

A case can be assigned to a user or a team

### Adding to Queue

A case can also be assigned to a queue and then from there a user can access the queue and

If a queue does not exist it can be created

Once the case is assigned to a queue, a user that belongs to that queue can select the case and choose Pick – this thereby assigns the case to the user to work on.

### Resolve Case

When all case activity is complete, click on “Resolve” in the top command bar. The case is read only when resolved / finalised.

If a case needs to be reactivated after it was resolved i.e. perhaps an additional note needed to be added, then the case can be reactivated, then the additional activity added, and then the case resolved again.

Once the case is resolved the case can be seen from the List: My Resolved Cases

# Sales Leads, Opportunities and Activities

## Overview

A Lead is nothing but a potential business. Let's say you are running a campaign of one of your products somewhere and you have you have distributed your company information and product related information to some users or prospects. A lead is the first stage of sales process.

Now, when you have a lead, there is a requirement of follow ups to the lead to gauge whether the customer is still interested or perhaps forgot the communication between your business. This consistent follow up with the lead is necessary to gain the confirmed interest from the lead and consequently we can create opportunities in the system.

At the lead stage, we have a Qualify stage by which we can convert the lead to a opportunity in the system.

We can also disqualify the lead if the lead no longer wants to purchase the product that they were previously interested in, or if they have changed their mind If the lead is disqualified then the lead is stopped there and then there will be no opportunity created in the system.

If the lead is qualified a contact record and an account record gets created automatically in the system as per the out of the box feature of dynamics 365 Customer Engagement.

In the typical sales process lifecycle there are two types of entities involved in the sales process:

A contact and an account.

An account is a company or an organization from which we get business.

A contact is an individual from which we get business.

There are two ways two ways that we can create customers in CRM24. One is from the lead qualification process, which you will automatically create contact and account and another is manually creating the contact and if we very sure that there is no requirement of leads, we can directly create customers.

The lead can be an individual or an organization or sometimes it happens the individual might be a part of the organisation.

So, there is a relationship between a contact and account – this is setup as a connection. Other connections can also be created in the system i.e. between 2 different customers.

A lead is always generated from a marketing campaigns. We distribute all our promotional offers to customers and based from this we get leads. Once the leads are captured in the system, we qualify and disqualify the lead

We are also able to associate an account with a parent account so that there will be a hierarchy organization hierarchy that we can set up and we can associate corresponding records like opportunities, orders and invoices

At the stage of opportunity, we have flexibilities to identify who the stakeholders of this opportunity are, who the competition may be, and who are the sales team.

We then add the products that the customer is interested in and the associated price list.

Once the opportunity section is done, we provide a quotation to the customer of the products and services they require. This quote can be emailed to the customer.

Once the quotation is accepted and approved by the customer, we move to the order stage.

Once the order is fulfilled, an invoice is created showing the actual price and an invoice document will be sent to the customer for payment.

## Sales: Leads, Opportunities & Activities

In order to get leads some sort of marketing activity or campaign needs to be run.

The marketing campaign will be targeted at either : accounts, contacts or  leads. This is achieved by creating a marketing list and focussing the campaign to all members of the marketing list.

To create a Sales process Flow, start by creating a Lead.

Complete all Lead details, then qualify the Lead into an Opportunity.

Complete the business process guided flow, and all the fields of the Opportunity.

Add activities (e.g. Tasks \ Appointments) to indicate work done in closing the deal.

At the end of the sales process, close the Opportunity as Won or Lost.

### Create a marketing List

Create a new Marketing List.

The list type can either be : Static (manually entered and does not auto update) or Dynamic (can change automatically based on criteria)

The Targeted at can either be: Accounts, Contacts or Leads.

Once the list is saved members can be added

When you choose to Add, depending on who the marketing list is targeted at, that entity i.e. Lead, or Account or Contact will be created

Note: Once the Targeted At, and List Type are entered and the list saved, these cannot be changed. If a mistake was made the marketing list would need to be deactivated and a new marketing list created.

Deactivating a list can be reactivated later if required.

When a dynamic list is created, use Manage Members and then add in the criteria for the automatic membership.

Click on Find to see the contacts or accounts that meet the criteria.

If satisfied choose Use Query

This will add these contacts to the marketing list.

Note: In the future is a new contact is added and meets the criteria they will then automatically be added to the dynamics marketing list.

### Create a Campaign

Click on New to create a campaign

Once the campaign has been saved there are 2 ways to associate the marketing list to the campaign.

The 1st is to return to the marketing list and then choose to add an Existing Campaign

The 2nd is to from the campaign in the Marketing List section click on the 3 elipses and choose “Add Existing Marketing List”

### Campaign targeted products

A target product can be added to a campaign if applicable

Choose to Add Existing Product

### Adding Sales Literature to a Campaign

From the Campaign Choose related - > Sales Literature, and then select to Add Existing Sales Literature

Note: The Product and Sales Literature would likely be added in advance

e.g.

### Campaign Planning Activities

All the activities required to plan the campaign need to be added to the campaign. This is achieved by navigating to Related - > Planning Activities

Next add the various activities i.e. tasks, phone calls etc.

The list of these activities are then visible

Once the activities are complete they can be marked as Complete

### Add Campaign activities

Once the campaign is created and a marketing list has been associated the various campaign activities can be created.

The status of the campaign can then be changed to “Ready to Launch”

Once the status is changed the Campaign Activity can be distributed to the people in the marketing list.

If the Channel is one that can be distributed i.e. Email then the New Email box is provided where you can choose to use a template or simply add the detail, and once done click Distribute to send the email to all people in the Marketing List.

### Campaign responses

All email responses from the people that received the distributed email, will lie in the Responses section of the Marketing Campaign.

Campaign Responses can also be captured manually in the Details tab on the Responses section

If the response is favourable it can be converted to a lead (new or existing), or created as an opportunity.

If you choose a Lead it uses the information from the response as the basis for the Lead

In the new lead the Source Campaign is populated

Once a campaign is complete it can be deactivated.

### Create a Quick Campaign

A quick campaign is a single campaign activity geared toward a targeted audience. Track the success of your quick campaign through campaign responses, and convert the positive responses into new leads, quotes, orders, or opportunities.

The difference between a campaign and a quick campaign

To create a quick campaign , from the marketing list, choose to “Create Quick Campaign”

This opens the Quick Campaign wizard

Specify a name for the quick campaign

Specify the type of activity

Specify the topic and description

Once you have created the quick campaign it is visible under Quick Campaigns.

You will see that the activity has been created for all members that were part of the marketing list

Once the activity has been completed, mark is as completed

### Create a Lead

A lead can be created directly as well as from a campaign response (as we have already seen)

Once the basic info is completed the Sales Process guide you through additional info needed to be entered to progress through the Stages

If a contact or account do not yet exist, they can be created here on the fly.

When trying to move to the next stage since no opportunity exists, one is prevented.

Before proceeding the Lead needs to be qualified

Note: if for some reason the prospect was no longer interested, you could choose to Disqualify the Lead

Once the Lead is qualified, the lead is transferred into an opportunity, and also the contact and account is created.

### Opportunity

An opportunity can be created directly, or is created once a lead is qualified.

Once the basic information of an opportunity is completed, additional info around the decision process can then be completed

The product(s) related to the opportunity can be added

A price list is chosen (and if one does not exist it needs to be added – products cannot be added before a price list has been selected.

The price list has a start and end date and Price List Items can be added to it.

On the option for Revenue either User Provided or System Generated options are available.

System generated is used when the price is determined by the products added.

When User Provided is chosen you need to enter the estimated revenue manually

When adding in the product either an existing product can be chosen, or a new one created on the fly. Alternatively the option of using a Write-In product exists (used on the opportunity but not saved as a product in CRM24)

The Estimated Revenue is updated with the sum of the prices of the products

There is additional information to be completed for the opportunity and to gather this information an activity like a Phone Call needs to be created

This will help clarify the current situation and customer need.

e.g.

The Phone Call can be closed.

Once the need is confirmed this detail can be added to the opportunity

And in addition the Develop stage fields can be completed

The Sales process prompts that stakeholders, a sales team and competitors be added. If there are no competitors in the system yet these can be created.

If an existing competitor does not exist it can be created

Once these have been added one can move to the Next Stage: Propose.

The Propose stage requires a quote being created

### Create a Sales Quote

A sales quote can be created from within the Quote tab of the Opportunity, or directly from the Site Map

Or

A Quote ID is populated, and if the quote was created from within the opportunity then the same info from the opportunity is used on the quote.

Note: If you want to get the products from a  different opportunity you can click on “Get Products”

And then choose the relevant opportunity.

Once the quote is ready you can generate the quote using a Word Template

An alternative would be to use the option

When the quote has been accepted you can activate the quote

Activating the Quote moves the quote out of Draft stage and allows you to create an order from the quote.

The opportunity can now also move to the next stage

### Create an Order

An order can be created from a Quote, or direct from the site page

or

### Create an invoice

An invoice can be created from an order or directly from scratch.

Once the Invoice has been settled the invoiced can be marked in CRM24 as Paid

### Finalising the Opportunity

The opportunity can then be closed as Won or Closed as Lost

At this stage the Actual Revenue can be edited (in case other revenue not accounted for was applicable)

Note: Before the opportunity can be closed any active or draft quotes needs to be closed

# Customer Accounts and Contacts

Customers are found in Accounts and Contacts.

## Accounts

Use the side navigation Pane to see the List Views on Accounts

Click on a record to Open / view / edit. In an opened record, use the top command bar buttons to perform actions on that record.

Summary

Details

Various other related records can be added to an Account

Activiites i.e. Tasks can be created on the Account

## Contacts

Use the side navigation Pane to see the List Views on Accounts

Summary

Details

Various other related records can be added to an Account

Activities can be created against Contacts

# Configuration and Setup

## Admin websites

With CRM24 there are 3 main websites to be aware of and bookmark

Power Apps

The URL is: http://make.powerapps.com/

The 2 main things to be aware of here are:

The environment you are in – if customisations are made, they should not be made in the default environment, but instead in a new environment.

The Solutions are is where you can make all your customisations.

Within a solution you can see the various tables, views, forms and also processes etc.

### Microsoft 365 Admin Center

URL: https://admin.microsoft.com/Adminportal

From within the Admin portal your CRM24 users can be managed.

### Power Platform Admin Center

URL: https://admin.powerplatform.microsoft.com/environments

This can also be accessed from the Microsoft 355 Admin Center

Opening the environment will take you into CRM24

If you choose Settings, from here you can perform most of the settings found in CRM124.

From within CRM24 there is another way to access these settings, but in time these will likely be deprecated.

For now though we will access these same settings from within CRM24 by going to the cog and then choosing Advanced Settings

The Advanced Settings are is where all customisations and settings can be made and accessed

## Security\Environment Setup

### Setup Business Unit Structure

Navigate to Advanced Settings  Security  Business Units

Business units in CRM24 are a businesses’ departments or divisions.

Business Units in CRM24 control data access.  Users can securely access data in their own business unit, but they can’t access data in other business units.

Note the following in terms of business units:

The organization (also known as the root business unit) is the top level of a CRM24 business unit hierarchy.

Each business unit can have just one parent business unit.

Each business unit can have multiple child business units.

Business Units can have parent child hierarchy settings.

CRM24 security roles and users are associated with a business unit. You must assign every user to one (and only one) business unit.

Security and access privileges can be restricted to Business Unit or Parent Business Unit level (thus also allowing accessibility in all records owned in any child business units under the parent)

You can assign a team to just one business unit, but a team can consist of users from one or many business units. Consider using a team if you have a situation where users from different business units need to work together on a shared set of records.

,

Create all Business Units as “child” units under the main Parent (your Organisation name)

Click on the “New” button in “Business Units”

Complete all details, select the appropriate parent for hierarchy, and click on “Save and Close”

Your business unit structure should follow the advised below process

### Users Setup

To have new users added, contact Braintree for license provisioning through the Microsoft CSP portal.

The initial user setup will be completed, and you will be advised of the Access Details for the initial users requested.

Should you wish to change the security roles, managers, business units or any other demographic information regarding any user, you can follow the process outlined below:

Navigate to:  Advanced Settings → Settings → Security → Users

Click on the username you wish to edit

NB! Note:

When you change the business unit of a user all security roles are removed from the user profile!

Access is only possible if a user is enabled and has a Security Role.

If you do change a user’s business unit, make sure to click on “Manage Roles” and give the user the required security roles again.

### Teams

In CRM24 we setup a Sales team and a Service team only by default.

If you want to expand this later you are most welcome. As part of CRM24 we however will just be assigning users to either the sales team or service team or to both.

To Configure Teams click on the team you wish to edit or add a new Team and members usi9ng the lookup

### Roles

Security roles enable administrators to control users' access to data through a system of access levels and privileges. The combination of access levels and privileges that are included in a specific security role sets limits on each user's view of data and on what actions the user can perform with that data.

You can assign more than one security role to a user. The effect of multiple security roles is cumulative, which means that the user has the permissions associated with all security roles assigned to the user.

Note: Administrators can also create teams, apply security roles to those teams, and add users to each team. All users that belong to a team inherit the security roles applied to that team for as long as they remain a member, and lose those roles as soon as they leave the team (other than roles also granted to them personally or by other teams they are on).

To the Sales team we will by default assign the “Sales Manager” role, and to the Service Team we will be default assign the “CSR manager” role. These roles then filter down to the user when they are assigned to the teams.

In CRM 24 we setup a Sales team and a Service team only by default.

If you want to expand this later you are most welcome. As part of CRM24 we however will just be assigning users to either the sales team or service team or to both.

Navigate to “Manage Role” to change the role(s) for a user.

## Business Management Setup

### Fiscal Year Settings

Navigate to Settings  Business Management  Fiscal year Settings.

Here you can enter the 1st day of the fiscal year.

### Business Closures

Navigate to Settings  Business Management  Business Closures

During this closure, service activities cannot be scheduled. However, resources with the “Do not observe” option selected for business closures can be scheduled for services.

### Currencies

Navigate to Settings  Business Management  Currencies.

The currencies created here can be used when quotes, orders  or invoices are created.

### Sales Territories

Sales Territories can be setup and managed from here i.e. add and remove members, modify territory information and delete territories.

### Sites

Sites (or office locations) are defined here and represent the locations where service activities take place.

### Outlook integration

In terms of Outlook integration – there is also a role called “Dynamics 365 App for Outlook user”.

Adding a user to a team with a assigned role of “Dynamics 365 App for Outlook user” means that the user will be able to from their Outlook have interaction to CRM24.

Note: If users use the online version via the browser, and want outlook integration there is an addon that they’d need to download and install.

Note: An admin will be required to approve email for each users who needs to be able to use their email in CRM24.

In the Email Configuration this can be seen

### Configure Queues:

Queues are instrumental in organizing, prioritizing, and monitoring the progress of your work while you are using CRM24.

As a central location for work management, queues assist you in processing cases, responding to service calls, or sending out product information to prospective customers.

Programmatically, a queue is a collection of queue items. A queue item serves as a container for an entity record, such as a task, an email, or a case that needs processing.

With service management, cases can be assigned to a queue and then any user who belongs to a queue can access the detail in the queue.

Note: Queues can be setup with a mailbox so that if anyone sends an email to that mailbox it automatically is added to the queue and the users in the queue can then access and respond.

To setup a queue  Navigate to: Advanced Settings → Settings → Business Management → Queues

Click on the Queue you wish to edit or add a new Queue and members

Note: Queues can be Public or Private

Public: Everyone has access

Private: Only added members have access

### Subjects

Here you define a subject organizational structure that lets you mark and categorize service cases, knowledge base articles, products, and sales literature. By using the subject hierarchy, you can classify service cases to quickly provide service to your customer.

## Product Catalog

The products, and product families as well as the Price Lists and Discount Lists and Unit Group can all be set here.

They need to be setup prior to being able to add a product to a Sales Quote, order or invoice.

### Products, Families & Bundles

Products are the backbone of your business. They can be physical products or services—whatever your organization sells. Your sales reps use the products you create in Sales to generate sales quotes, marketing campaigns, orders, and invoices. Your customer service reps might also use them when they create customer service cases.

When completing the product some fields :

Valid From/Valid To: Define the period the product is valid for by selecting a Valid From and Valid To date.

Unit Group: Select a unit group. A unit group is a collection of various units a product is sold in and defines how individual items are grouped into larger quantities. For example, if you're adding seeds as a product, you may have created a unit group called "Seeds" and defined its primary unit as "packet."

Default Unit: Select the most common unit in which the product will be sold. Units are the quantities or measurements that you sell your products in. For example, if you're adding seeds as a product, you can sell it in packets, boxes, or pallets. Each of these becomes a unit of the product. If seeds are mostly sold in packets, select that as the unit.

Default Price List: If this is a new product, this field is read-only. Before you can select a default price list, you must complete all the required fields and then save the record. Although the default price list is not required, after you save the product record, it is a good idea to set a default price list for each product. If a customer record does not contain a price list, Sales can use the default price list for generating quotes, orders, and invoices.

Decimals Supported: Enter a whole number between 0 and 5. If the product can't be divided into fractional quantities, enter 0. The precision of the Quantity field in the quote, order, or invoice product record is validated against the value in this field if the product does not have an associated price list.

Subject: Associate this product with a subject. You can use subjects to categorize your products and to filter reports.

### Price Lists

Price levels can be created and different products associated with those price levels.

### Unit Groups

Unit Groups are defined as per how a product is sold i.e. in what unit it is being sold.

### Discount Lists

Discounts can be setup and can be made dependant on the quantity of the product being sold.

## Administration

### System Settings

Navigate to Settings  Administration  System Settings.

System settings should not be changed from the initial setup by anyone without the appropriate Dynamics 365 Experience, as it can affect the performance of the entire environment adversely.

Many different system settings are set here. Some of the key ones to note are mentioned below.

#### Country code

#### Regional number, currency, time and date settings

#### Auditing

Auditing allows you to see changes made by users in the system to records.

Auditing can be enabled at each entity or even at a field level, however with CRM24 by default we provide the option to turn on or off auditing for the Sales module and or Service Module only.

#### Email Server profile

The Server profile is set by default to: Microsoft Exchange Online.

#### Reporting

Where custom Power BI reports are created in the Power BI Service and you wish for these to be embedded in CRM24, then the highlighted option needs to be marked as “Yes”

## Processes

### Business Process Flows

Navigate to: Settings  Processes

Add a filter to the Category to only show Business Process Flows.

A number of business process flows have been created by default for use.

With the “Phone to Case Process” in services (cases/incidents) we have 4 stages in a process: Identify -> Research -> Escalate -> Resolve

With the sales “Lead to Opportunity” and “Opportunity Sales process” business process flows we see 4 stages

A stage is what we see defined when we are working through the capture of information for a particular area i.e. the lead to opportunity process

In Power Apps the fields needed to be completed within each stage are defined.

In the business process flow conditions could also be added, as well as Workflows and Action Steps

### Workflows

Workflows are used to automate certain actions and become very useful. They can be used to notify users of changes and send emails. They can be used to change the status of records etc.

By default we provide a number of default workflows for Sales and Service, however as a start these are mostly not activated.

Sales

Service

On each workflow  various steps are set

e.g. On the Lead, there is a workflow for “Open Passed reminder”

One step involves sending a reminder email – by clicking on Properties the email can be defined according to your need.

## Data Imports

Using the Data Import Templates Provided, populated with the data you wish to import.

Do not remove or expand columns A, B or C

Copy data in columns

Take note of data types

Where Option sets – use available options only

Where Lookup – value must already exist in the system existing data

Where numerical – take note of limitations on number ranges

#### Navigate to Data Management

In the Settings Dropdown, click on the dropdown arrow, then scroll to Data Management Click in the Data Management Tile to open

#### Open the Imports Area

In Data Management, click on Imports

Click on Import Data

#### Select Import Template

Open the “Import Data” wizard, select (browse to) the Import Template File

Click on “Choose File” – select the template to be imported

Click Next to Proceed

#### Select the prepopulated template

#### Review Settings

Allow Duplicates: Decide if you want to allow duplicate values or unique values only

Select Owner: Which system user will be the owner of the records imported - 	Click on “Submit”

#### Finish Import

#### Monitor Success

Still under Settings >> Data Management, check under the Status columns

Success: Successful Records Imported and Created

Errors: Records that failed and were not successfully imported

Compare successes against Total Processed

When status is “Completed”

When Complete, the import process is complete.

If Errors, open the Import File, read error message, fix data in template accordingly, rerun import.

 | 

--- | ---