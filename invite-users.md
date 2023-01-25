# Invite users

This feature allows Public officers to invite other Public officers and vendors to get onboarding invitation to [TechPass](http://portal.techpass.gov.sg/) and [SEED](https://docs.developer.tech.gov.sg/docs/techpass-user-guide/#/onboard-to-seed).

There are 3 ways a Public officer can invite users:

* [Email invitation](#email-invitation). Use this option to invite Public officers.
* [Create account](#create-account). Use this option to invite vendors.
* [Batch upload](#batch-upload). Use this option to invite multiple Public officers and vendors.

## Prerequisites

- Public officers using a [non-SE GSIB](glossary) device can invite other public officers or vendors.

Have the following information ready before proceeding:
- Organisational email address.
  - For public officers, it is the Whole of Government email address of the public officer.
  - For vendors, it should be the email address provided by the vendor.
- **First name** and **Last name**
- **Contact number**
- **Organisation** (only for vendors)
- **TechPass username** (only for vendors)

> **Note:** You can use the vendor's full name as the TechPass username.


## Email invitation

**To invite Public officers**

1. From the sidebar, click **Invite users** > select **Email invitation**.

<kbd>![email_invite1](/images/invitation-email.png ':size=100%')</kbd>

2. Enter the required details and click **Submit**.

<kbd>![email_invite](/images/email_invite2.png ':size=100%')</kbd>

Refer to the following for more information on the required details.

| <div style="width:270px">Field Name</div>  | Description |
| :------------------------------------------ |:-------------|
| **Email address** | Enter the email address of the public officer who requires a TechPass account. Email address must be in the format of \<your_name>@\<acronym for your agency>.gov.sg. for public officers.<br> | **Is onboarding to [SEED](https://docs.developer.tech.gov.sg/docs/security-suite-for-engineering-endpoint-devices/#/) required?** | Indicate **Yes** if the public officer needs SEED provisioning.<br /><br /> **Note**: SEED provisioning is needed to access SGTS products from the Internet device. |
| **Reason** | Enter the **Reason** why the public officer needs a TechPass account. |

## Create account

**To invite vendors**

1. From the sidebar, click **Invite users** > select **Create account**.

<kbd>![create_acct](/images/create-account.png ':size=100%')</kbd>

2. Enter the required details and click **Submit**.

<kbd>![create_account](/images/create_acct2.png ':size=100%')</kbd>

Refer to the following for more information on the required details.

| <div style="width:270px">Field Name</div>  | Description |
| :------------------------------------------ |:-------------|
| **Email address**| Enter the organisational email address of the vendor who requires a TechPass account. </br></br> **Note:** The email address must be the email address provided by the vendor. |
| **TechPass username** | This field is required if you are requesting TechPass account for a vendor. Enter the required username for the TechPass account. |
| **First name,** **Last name,** **Contact number,** **Organisation, and Department**| Enter the required details.<br />Note: **Department** is optional. |
| **Is onboarding to [SEED](https://docs.developer.tech.gov.sg/docs/security-suite-for-engineering-endpoint-devices/#/) required?** | Indicate **Yes** if the vendor needs SEED provisioning.<br /><br />**Note**: SEED provisioning is needed to access SGTS products from the Internet device. |
| **Reason** | Enter the **Reason** why the vendor needs a TechPass account. |

## Batch upload

**To invite multiple Public officers or vendors**

1. From the sidebar, click **Invite users** > select **Batch upload**.
2. Click **Download excel template link**.

  <kbd>![downloadtemplate](/images/download-template.png ':size=100%')</kbd>
  
> **Notes:**
>
> Usernames should contain the following:
> - Start and end with alphanumeric characters.
> - Username can contain alphanumeric characters, '_', ’ ‘, '-', or '.'. 
> - Two consecutive '.' is not allowed.

3. Open the downloaded .xlsx file extension, specify the required details and save the file.
4. In **Upload user list** section, select **Choose a file**.

  <kbd>![downloadtemplate](/images/choose-file.png ':size=100%')</kbd>

5. Select the saved file and upload it.
6. Click **Submit**.

 <kbd>![submit](/images/batch-upload-submit.png ':size=100%')</kbd>

  - To view or edit user details, click the ellipsis on the row and click **View details**.

 <kbd>![view-details](/images/view-details.png ':size=100%')</kbd>

  - To delete a single user, click **Remove**.

  <kbd>![delete](/images/remove-user.png ':size=100%')</kbd>

  - To delete all users, click **Reset**. To confirm reset, click **Confirm**.
  <kbd>![remove](/images/reset.png ':size=100%')</kbd>


>**Notes:**
>
> When an invitation is unsuccessful, you will receive an error notification during submission. You need to do the following:
>
> To troubleshoot [email invitation](#email-invitation) or [create account](#create-account) issues:
> - Raise a service request by clicking on the support email link provided in the error notification and attach the Trace ID shown on the error notification.
> - To troubleshoot [batch upload](#batch-upload) issues:
>    1. In the user list of the uploaded file, click the ellipsis on the row with errors.
>    2. Click **View details**.
>    3. Amend the required details and click **Save**.
>    4. Click **Submit**.


## View status of invited users

Public officers can view the status of the users they have invited using TechBiz portal. **Invite User Status** displays the TechPass and SEED onboarding status of the invited users.

**To view the status of invited users**

1. From the sidebar, click **Invite users** > select **Invite User Status**.

The page will indicate "No record found" when no users have been invited. If you have invited users using TechBiz, their TechPass and SEED onboarding status will be displayed.

<kbd><img src="images/invite-stats.png" alt="drawing" width="100%"/></kbd>

Refer to the following for more information.

| <div style="width:270px">Field Name</div>  | Description |
| :------------------------------------------ |:-------------|
| **First Name** | First name of the invited user. | 
| **Last Name** | Last name of the invited user. |
| **Email adress** | Organisational email address of the invited user. |
| **Organisation** | Name of the vendor organisation. |
| **Department** | Name of the vendor's department. |
| **Date of Invite** | Date of user invitation to TechPass. |
| **TechPass Status** | TechPass status of the user. |
| **SEED Status** | SEED status of the user.|
| **Resend invite** | The button is displayed when user has not onboarded to TechPass. |

>**Notes:**
> - Only users invited via TechBiz portal will be displayed on this list. 
> - First name and last name are displayed if the user signed up for TechPass via the TechPass portal or if the TechPass account was created through [create account](#create-account) or [batch upload](#batch-upload). 
> - Click **Resend invite** to re-invite users through email. Invitations can be sent once a day. The button is available after invites have been sent.

