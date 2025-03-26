# Manage user access

Subscription and technical admins can control user access to the SGTS Products they have subscribed to. Subscription admins can manage both account and system user access, while technical admins can only manage system user access for the systems they are designated as admins.

> **Note:** Refer to the description text located underneath the tool label to understand the functionalities that the tool controls access to.

- [Add or remove users](#add-or-remove-users)
- [Open Access](#open-access)

## Audience

- Primary and secondary subscription admins.
- Technical admins.

## Prerequisites

- You need a [non-SE GSIB](https://docs.developer.tech.gov.sg/docs/techbiz-documentation/glossary) or [GMD](https://docs.developer.tech.gov.sg/docs/security-suite-for-engineering-endpoint-devices/additional-resources/glossary?id=gmd) device.
- You need to be logged in to [TechBiz](https://portal.techbiz.suite.gov.sg/) portal.
- An approved **TechBiz account**.
- A provisioned **TechBiz system**.

## Add or remove users

Subscription and technical admins can control user access to the SGTS Products they have subscribed to. Subscription admins can manage both account and system user access, while technical admins can only manage system user access for the systems they are designated as admins.

> **Note:** Refer to the description text located underneath the tool label to understand the functionalities that the tool controls access to.

**To add users**

1. From the sidebar, click **Accounts**.
2. Select **APPROVED** from the **Status** dropdown list to view all the approved accounts.
3. Select the required account.
4. Click **USER MANAGEMENT** tab.

   ![User Management](images/user-man.png)

5. Select the required Product from the **Products** dropdown list to select the SGTS Product tools to manage.
6. Select the required tool to add users. For example, GitLab.

   ![Manage Users](images/manage-users.png)

7. Click **Manage** \> **Add users**.

   ![User Manage Add](images/user-manage-add.png)

> **Note:**
> - The usage count is linked to the corresponding subscription plan.
> - **Usage count** displays the quantity of assigned users and the maximum number of concurrent users authorised. For example, a count of 2/33 indicates that 2 out of the total 33 subscribed users have been assigned.

8. Enter the name or email address of the user.

   ![Add Users Management](images/add-users-mgmt.png)

> **Note:** 
> - User needs to have a TechPass account for their names to appear in the dropdown list.
> - Each user can only be added to one subscription account. Attempting to add a user to multiple subscription accounts will result in an error. 
> - To add a user to a specific Product, such as GitLab, Atlassian, SonarQube, or others, the user needs to access the Product itself and configure their user account accordingly. Each Product may have its own dedicated user management interface or settings panel where users can add, modify, or remove user accounts.

9. Click **Submit**.

   ![Submit User](images/submit-user.png)

**To add multiple users**

1. Click **Batch add**.

   ![Batch Upload Management](images/batch-upload-man.png)

2. Download the **excel template**. Enter the required details on the excel sheet and save the file.

   ![Excel Batch](images/excel-batch.png)

3. Click **Choose a file**. Select the required file.

   ![Choose File Batch](images/choose-file-batch.png)

4. Click **Submit**.

   ![Submit Batch](images/submit-batch.png)

> **Note**: Admins may encounter common errors such as users already associated with another subscription account, users without a TechPass account, and incorrect email addresses.

**To remove a user**

1. From the sidebar, click **Accounts**.
2. Select **APPROVED** from the **Status** dropdown list to view all the approved accounts.
3. Select the required account.
4. Click **USER MANAGEMENT** tab.
5. Select the required Product from the **Products** dropdown list to select the SGTS Product tools to manage.
6. Select the required tool to remove users. For example, GitLab.

   ![Manage Users](images/manage-users.png)

7. Click **Manage**.
8. Click the **delete icon** corresponding to the user's name.

   ![Delete Users](images/delete-users.png)

9. Click **Confirm** to delete the user.

   ![Confirm Delete User](images/confirm-delete-user.png)

The user record is removed from the **Users** list.

**To remove multiple users**

1. Select the users.

   ![Remove Selected](images/remove-selected.png)

2. Click **Remove selected**.

   ![Remove Selected Confirm](images/remove-selected-confirm.png)

3. Click **Confirm**.

A confirmation message is displayed. 

## Open Access

There is now a third user type called *DashboardViewer*. By default, it is open to Public officers to view as a dashboard.
  
The different roles appear under the row/column below: 
  
   ![Role Access Configuration](images/dashboardviewer.png)

To toggle switch (as shown in the image below) to manage access:
  
   ![Toggle Switch](images/um-toggle.png)

If switched off, all users cannot access. However, specific users, including vendors, can be added.

