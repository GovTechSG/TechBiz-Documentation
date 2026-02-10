# Release notes

## December 2025

**19 December 2025**

| Type | Feature | Description |
|---|---|---|
| **Fix** | **Invoice and to-do emails sent to removed contacts** | Fixed an issue where invoice and to-do emails were still sent to account contacts after they had been removed. |
| **Fix** | **Email attachments blocked by SGMail** | Fixed an issue that caused SGMail to block emails sent from TechBiz by changing attachment extensions from `.json` to `.txt`. |
| **Enhancement** | **Improved promo code application flow** | Implemented a **sticky stepper** in the promotional code flow to make the final **Submit** action more visible. |
| **Enhancement** | **Trial to paid account conversion** | Trial users can now convert their trial account to a paid account **before the trial period ends**. |

---

## November 2025

**21 November 2025**

| Type | Feature | Description |
|---|---|---|
| **Enhancement** | **Update subscription admin during APEX migration** | APEX consumers migrating to TechBiz can now update their **primary subscription admin** while their account is still in draft. |
| **Enhancement** | **Billing policy links in documentation** | Links to billing policies from different products are now available in the [TechBiz documentation](https://docs.developer.tech.gov.sg/docs/techbiz-documentation/billing-policies). |
| **Update** | **DGP system tagging restriction** | Newly created systems can now tag **only one DGP system** to one TechBiz system. |
| **Feature** | **Cerberus for Servers billing** | Billing support for **Cerberus for Servers** has been implemented. |

**7 November 2025**

| Type | Feature | Description |
|---|---|---|
| **Fix** | **OTP login failure** | Fixed an issue that caused OTP login attempts to fail. |
| **Enhancement** | **Billing contacts for deleted accounts** | Billing contacts for deleted accounts are now included in product reports and invoices. |
| **Enhancement** | **Project ID dropdown** | [The **Project ID** field in billing details](https://docs.developer.tech.gov.sg/docs/techbiz-documentation/create-subscription-acc/request-for-techbiz-account?id=step-2-enter-subscription-account-details) and during account creation is now a dropdown instead of free text. |
| **Enhancement** | **Conditional approval form display** | The approval form is now shown only if the selected product requires approval. |

---

## October 2025

**24 October 2025**

| Type | Feature | Description |
|---|---|---|
| **Enhancement** | **Expanded CFT resource configuration details** | Additional details have been added to the CFT resource configuration page for better clarity. |
| **Enhancement** | **Direct links to product portals** | After completing actions, users now see **direct links to relevant product pages and portals**, allowing quicker access to subscribed or updated services. |
| **Enhancement** | **Product portal links in user management** | URL links to relevant product portals are now displayed on the **user management** page for easier access. |
| **Feature** | **User management via APIs** | Agencies can now manage user assignment and removal in their accounts using APIs. |


## August 2025

**29 Aug 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **Plan descriptions in billing invoices for SHIP-HATS** | Billing invoices for SHIP-HATS now include plan descriptions. If a plan has extra information that becomes available after resource provisioning, this description will appear in the invoice for clearer billing details. |

**15 Aug 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **Correct pricing calculator for APEX** | The pricing calculator for APEX now allows you to input both G2G and G2B transactions and automatically tabulates the cost, similar to SHIP-HATS. This includes free transaction blocks as part of your subscription. |
| **Feature** | **Migration flag for CFT resources** | When creating a CFT resource, you are now asked if it is an existing CFT project undergoing migration. This prevents users from missing the migration field and ensures smoother resource setup. |

**1 Aug 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **GASSP ID uploads** | TechBiz now automatically collects unique GASSP IDs used in provisioned resources for Cerberus. A scheduled job uploads these IDs to S3 for audit and compliance purposes. |
| **Feature** | **Custom descriptions in plan details** | Plan cards now show a custom description instead of item details, which is especially useful for usage-based products. You can now add and manage plan descriptions during plan creation. The pricing calculator and onboarding screens have been updated to remove item counts. |
| **Feature** | **Multiple email recipients in product catalogue** | Product catalogues now support up to 10 email recipients (previously only one). This allows more stakeholders to be included for updates and notifications. |

## July 2025

**18 Jul 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **Resource-updated webhook with `updatedBy`** | The resource-updated webhook now includes the `updatedBy` field, so you can see who made changes to a resource. |
| **Change** | **StackOps deployment config details hidden** | Deployment configuration details for StackOps are no longer visible to end users, improving security and reducing unnecessary exposure. |
| **Change** | **Updated DevConsole URLs for StackOps resources** | All provisioned StackOps resources now point to the updated DevConsole URL:<br>`https://console.developer.tech.gov.sg/stackops/deployments/{accountId}/{resourceId}` |


## June 2025

**20 Jun 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **StackOps pricing now links to official documentation** | Users can now click the external link on the StackOps product card to access the official sizing and pricing guide on the StackOps documentation site. |

**6 Jun 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **Visual pricing display for products without plan cards** | Some products now show a pricing image instead of selectable plan cards to better explain complex pricing structures. This image also appears on the summary page. |
| **Change** | **Updated approval step description** | The label in the approval step now reads "CIO and delegates" instead of "Deputy Director and above" for clarity. |

## May 2025

**23 May 2025**

| Type | Fix | Description |
| --- | --- | --- |
| **Fix** | **Service month and billing period now shown correctly** | The monthly billing report now accurately shows the billing and service periods in the correct format, reducing manual updates. |

**17 May 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Preliminary invoice email now includes dispute window** | Email notifications now remind Subscription and Billing Admins to raise billing disputes within 14 days of receiving their preliminary invoice. |

**14 May 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Clearer guidance for cancelling APEX Cloud subscriptions** | Users now see a note explaining how to cancel APEX Cloud subscriptions by submitting a support request at go.gov.sg/techbiz-sr. |

**10 May 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Simplified plan selection during onboarding** | Sections with no available plans are now hidden during onboarding, making the experience cleaner and more intuitive. |

**9 May 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **Add and manage tags for systems and resources** | Agencies and products can now tag their resources to organise and track them more easily. Tags can be edited, removed, or kept hidden depending on access. |

## April 2025

**25 Apr 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **APEX billing format now supported** | The new APEX invoice format is now reflected in the preliminary invoice for improved clarity and consistency with APEX billing needs. |

| Type | Fix | Description |
| --- | --- | --- |
| **Fix** | **Role switching no longer exposes restricted actions** | Users who switch roles during a session can no longer access actions tied to higher privileges in other accounts. |

**11 Apr 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **Improved onboarding for non-SGTS products** | Products that do not follow SGTS now show customised product agreements and remove SGTS-specific steps, providing a clearer onboarding flow. |
| **Change** | **'Audit logs' renamed to 'Activity logs' across the portal** | We have renamed audit log references to “activity logs” to better reflect the content and improve consistency across screens and emails. |

## March 2025

**28 Mar 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Activity log now includes historical account approvals** | The activity log now shows past approvals and rejections that were previously only listed in the old activity feed, giving users a more complete view of their account history. |
| **Fix** | **Blank screen issue resolved for users accessing via GMD** | TechBiz now loads correctly when accessed on SEED-enabled (GMD) devices. Users will no longer encounter a blank screen. |
| **Fix** | **History log now shows correct subscription quantities** | The quantity displayed in the history log now reflects the highest value used within the billing period, ensuring consistency with invoices. |
| **Fix** | **Cost estimate now updates after trial ends** | After a trial ends, the cost estimate in the subscription screen now shows actual charges instead of $0, helping users avoid billing surprises. |

**21 Mar 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **More details now included in resource activity logs** | The resource activity log now includes requestor and approver information, providing clearer traceability for changes made. |

**17 Mar 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Banner added to guide offshore TechPass account creation** | A banner now appears when creating users to guide you to the TechPass Portal for offshore vendor accounts. Includes links to step-by-step instructions. |

**14 Mar 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **New activity log to track account changes** | A new activity log section is now available under “History Logs,” showing a record of actions performed on your account. It includes filters and CSV download options. |

**7 Mar 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **User mailing list download now available** | Admins can now download mailing lists for all users, not just other admins. This makes it easier to communicate with the full team involved in each account. |

## January 2025

**24 Jan 2025**

| Type | Fix | Description |
| --- | --- | --- |
| **Fix** | **PDF export button display issue resolved** | Fixed a display issue where the “Export to PDF” button on the Edit Subscription page appeared incorrectly. |

**10 Jan 2025**

| Type | Fix | Description |
| --- | --- | --- |
| **Fix** | **Fixed error when searching for group name** | Searching for group names under account user management now works as expected, even with unusual inputs. |
| **Fix** | **Notification error resolved for “Mark all as read”** | Users can now mark all notifications as read without encountering errors. |
| **Fix** | **Fix for promotional code not appearing after creation** | Newly created promotional codes now appear immediately in the table, without needing a page refresh. |
| **Fix** | **Incorrect amount shown after applying promo code** | The Summary page now shows the correct discounted total after a promotion is applied. |
| **Fix** | **Subscription admin update now works without billing info** | Users can now update subscription admins even if the billing section is empty for older accounts. |
| **Fix** | **Summary PDF resource section now displays correctly** | Fixed layout issues where the resource section was missing or displayed incorrectly in the summary PDF. |
| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Clearer message and weekly reminders for missing admins** | Users now see a warning if a subscription or technical admin was deleted in TechPass, along with weekly email reminders to update admin info. |

## June 2025

**20 Jun 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **StackOps pricing now links to official documentation** | Users can now click the external link on the StackOps product card to access the official sizing and pricing guide on the StackOps documentation site. |

**6 Jun 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **Visual pricing display for products without plan cards** | Some products now show a pricing image instead of selectable plan cards to better explain complex pricing structures. This image also appears on the summary page. |
| **Change** | **Updated approval step description** | The label in the approval step now reads "CIO and delegates" instead of "Deputy Director and above" for clarity. |

## May 2025

**23 May 2025**

| Type | Fix | Description |
| --- | --- | --- |
| **Fix** | **Service month and billing period now shown correctly** | The monthly billing report now accurately shows the billing and service periods in the correct format, reducing manual updates. |

**17 May 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Preliminary invoice email now includes dispute window** | Email notifications now remind Subscription and Billing Admins to raise billing disputes within 14 days of receiving their preliminary invoice. |

**14 May 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Clearer guidance for cancelling APEX Cloud subscriptions** | Users now see a note explaining how to cancel APEX Cloud subscriptions by submitting a support request at go.gov.sg/techbiz-sr. |

**10 May 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Simplified plan selection during onboarding** | Sections with no available plans are now hidden during onboarding, making the experience cleaner and more intuitive. |

**9 May 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **Add and manage tags for systems and resources** | Agencies and products can now tag their resources to organise and track them more easily. Tags can be edited, removed, or kept hidden depending on access. |

## April 2025

**25 Apr 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **APEX billing format now supported** | The new APEX invoice format is now reflected in the preliminary invoice for improved clarity and consistency with APEX billing needs. |

| Type | Fix | Description |
| --- | --- | --- |
| **Fix** | **Role switching no longer exposes restricted actions** | Users who switch roles during a session can no longer access actions tied to higher privileges in other accounts. |

**11 Apr 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **Improved onboarding for non-SGTS products** | Products that do not follow SGTS now show customised product agreements and remove SGTS-specific steps, providing a clearer onboarding flow. |
| **Change** | **'Audit logs' renamed to 'Activity logs' across the portal** | We have renamed audit log references to “activity logs” to better reflect the content and improve consistency across screens and emails. |

## March 2025

**28 Mar 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Activity log now includes historical account approvals** | The activity log now shows past approvals and rejections that were previously only listed in the old activity feed, giving users a more complete view of their account history. |
| **Fix** | **Blank screen issue resolved for users accessing via GMD** | TechBiz now loads correctly when accessed on SEED-enabled (GMD) devices. Users will no longer encounter a blank screen. |
| **Fix** | **History log now shows correct subscription quantities** | The quantity displayed in the history log now reflects the highest value used within the billing period, ensuring consistency with invoices. |
| **Fix** | **Cost estimate now updates after trial ends** | After a trial ends, the cost estimate in the subscription screen now shows actual charges instead of $0, helping users avoid billing surprises. |

**21 Mar 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **More details now included in resource activity logs** | The resource activity log now includes requestor and approver information, providing clearer traceability for changes made. |

**17 Mar 2025**

| Type | Change | Description |
| --- | --- | --- |
| **Change** | **Banner added to guide offshore TechPass account creation** | A banner now appears when creating users to guide you to the TechPass Portal for offshore vendor accounts. Includes links to step-by-step instructions. |

**14 Mar 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **New activity log to track account changes** | A new activity log section is now available under “History Logs,” showing a record of actions performed on your account. It includes filters and CSV download options. |

**7 Mar 2025**

| Type | Feature | Description |
| --- | --- | --- |
| **Feature** | **User mailing list download now available** | Admins can now download mailing lists for all users, not just other admins. This makes it easier to communicate with the full team involved in each account. |

## January 2025

**24 Jan 2025**

| Type | Fix | Description |
| --- | --- | --- |
| **Fix** | **PDF export button display issue resolved** | Fixed a display issue where the “Export to PDF” button on the Edit Subscription page appeared incorrectly. |

**10 Jan 2025**

| Type | Fix | Description |
| --- | --- | --- |
| **Fix** | **Fixed error when searching for group name** | Searching for group names under account user management now works as expected, even with unusual inputs. |
| **Fix** | **Notification error resolved for “Mark all as read”** | Users can now mark all notifications as read without encountering errors. |
| **Fix** | **Fix for promotional code not appearing after creation** | Newly created promotional codes now appear immediately in the table, without needing a page refresh. |
| **Fix** | **Incorrect amount shown after applying promo code** | The Summary page now shows the correct discounted total after a promotion is applied. |
| **Fix** | **Subscription admin update now works without billing info** | Users can now update subscription admins even if the billing section is empty for older accounts. |
| **Fix** | **Summary PDF resource section now displays correctly** | Fixed layout issues where the resource section was missing or displayed incorrectly in the summary PDF. |
| 
## November 2024

**30 Nov 2024**

| Type | Change | Description |
|---|---|---|
| **Feature** | **Free access to centrally funded product development tools** | Centrally Funded Product Development Tools is a FY24 initiative to enable the provisioning of essential product development tools across GovTech Product Teams. This initiative enhances productivity and efficiency, reducing delays in tool availability for developers after onboarding. |


**29 Nov 2024**

| Type | Change | Description |
|---|---|---|
| **Bug fix** | **Resolved database error for dashboard access** | Fixed an issue where certain user types encountered an error when accessing the dashboard tab in the TechBiz portal. |


**15 Nov 2024**

| Type     | Change   | Description |
|---|---|---|
| **Feature** | **TechBiz Portal now accessible on GMD!** | If you are using an internet-enabled device that has SEED (GMD) installed, you can now easily access TechBiz Portal directly from it. No more being restricted to accessing TechBiz only through non-SE GSIB - enjoy greater flexibility and convenience!|

## July 2024

**23 July 2024**

| Type     | Change   | Description |
|---|---|---|
| **Change** | Domain update | The domain has been changed from `mci.gov.sg` to `mddi.gov.sg` effective from 8th July 2024. |
| **Feature** | Agency selection improvement | Users can now select their agency from a dropdown if their approver's agency cannot be determined. |

**2 July 2024**

| Type     | Change   | Description |
|---|---|---|
| **Fix** | Plan quantity adjustment issue | Resolved an issue where users were unable to decrease the plan quantity to 0 when subscribed to the default plan. |
| **Fix** | Extended support plan quantity error | Fixed an error that occurred when users tried to reduce the quantity of Extended Support plans. |


## June 2024

**18 June 2024**

| Type     | Change   | Description |
|---|---|---|
| **Feature** | Updated pricing plan for SHIP-HATS     | We have revised the SHIP-HATS pricing plan on the TechBiz portal.|
| **Feature** | Optional project code for subscription account creation | When creating a subscription account for GovTech Agency, the *Project Code* field is now optiona. |
| **Feature** | Customisable plan descriptions         | We have added fields within the plan page allowing you to add any necessary descriptions. |


**4 June 2024**

| Type     | Change   | Description |
|---|---|---|
| **Feature** | View account/resource short name in user management page | Users can now view the account or resource short name directly on the user management page for easier reference. |
| **Fix** | Incorrect hint text displayed for Resource Short name | Corrected the hint text for the Resource Short name field, ensuring accurate guidance for users. |
| **Feature** | New landing page for TechBiz | TechBiz users now have access to a new, improved landing page, enhancing the user experience and navigation. |



## May 2024

**29 May 2024**

| Type  | Change| Description |
|-------|-------|-------------|
| **Enhancement** | Billing report for TechBiz Billing Admin | TechBiz Billing admins (excluding agencies) can now access a billing report to understand the composition of each billing. This report facilitates mapping back to the EIB (journal & invoice finance template), providing clarity on billing details. |
| **Enhancement** | Improved indication of pending subscription approval | Users can now clearly see which Subscribed products are pending approval by an Agency approver. A tooltip on *Pending* now explains that it refers to pending Agency approver's action to approve or reject Subscribed Products. Additionally, the *status* on Subscribed Product now includes *Pending* to indicate the same tooltip description. |
| **Enhancement** | Indication of system type in StackOps configuration form | Subscription admins and Technical admins can now indicate whether their system is a "non-production system" or "production system" via a dropdown list in the StackOps configuration form. This enhancement ensures that users specify the system type accurately, preventing oversight and promoting better resource management. |
| **Enhancement** | Removal of name restrictions for accounts/systems/resources | Users are no longer restricted when creating account, system, or resource names. This change provides users with more flexibility in naming, allowing them to create names without constraints. |
| **Enhancement** | Documentation reference for creating Product resources | Users can now refer to the TechBiz documentation guide for guidance on creating Product resources. A text directive has been added to guide users to gather more information from the user guide when creating resources. |

**13 May 2024**

| Type     | Change   | Description |
|---|---|---|
| **Fix** | Unable to open account details when creating account that subscribed to 2 products for the first time | Fixed the issue where users were unable to open account details when creating an account that subscribes to two products for the first time. |


## April 2024

**29 April 2024**

| Type     | Change   | Description |
|---|---|---|
| **Feature** | Add sorting to user management group list | Users can now sort the user management group list, making it easier to find and manage specific users within groups. |
| **Feature** | Subscribe to a new Product while waiting for current Subscribed Product to be approved | Users can now subscribe to a new product even while their current subscription is pending approval, improving flexibility and efficiency in managing multiple product subscriptions.|
| **Feature** | Pre-defined SBU list for agencies | TechBiz now provides a pre-defined SBU (Strategic Business Unit) list for agencies to select, eliminating the need for manual text entry and reducing errors. |


**15 April 2024**

| Type  | Change| Description |
|-------|-------|-------------|
| **Change** | Improved system management for technical admins | Technical admins can now only perform CRUD actions on systems for which they have administrative privileges |
| **Change** | Enhanced shortname creation visibility | Users now have visibility into the automatic creation of shortnames for their accounts. This feature enables users to easily adjust their shortnames if necessary, providing greater flexibility and customisation options. |


## March 2024

**20 March 2024**


| Type  | Change| Description |
|-------|-------|-------------|
| **Enhancement** | Enhanced user management metrics | As an  Subscription admin, you can now track the ratio of vendors to public officers within each account/system. This allows for better oversight and management of user roles within the system. Additionally, the user management interface now includes the count of vendors and public officers alongside the total user count, providing clearer insights into the user composition. |
| **Change** | Automatic user email update | User email addresses will now automatically update on TechBiz's side when changed on TechPass. This ensures that any changes made to user emails in TechPass are reflected accurately within TechBiz, enhancing system synchronisation and security. |


## February 2024

**19 February 2024**

| Type  | Change| Description |
|-------|-------|-------------|
| **Enhancement** | Enhanced user management search | As a Subscription admin, you can now search for users in the user management search bar to view which group(s) they belong to. The search functionality has been improved to allow searching for users by email addresses as well. |

