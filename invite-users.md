# Invite users

Public officers and vendors need to have a TechPass account to access [Singapore Government Tech Stack(SGTS)](https://www.developer.tech.gov.sg/singapore-government-tech-stack/overview/index.html) products and [SEED provisioning](https://docs.developer.tech.gov.sg/docs/security-suite-for-engineering-endpoint-devices/) is needed to access SGTS products from the Internet device. TechBiz allows public officers to send SEED and TechPass invites to other public officers or create a TechPass account on behalf of other public officers and vendors. 

Public officers with \<your_name>@\<acronym for your agency>.gov.sg can also use the TechPass OTP service to create accounts. A TechPass account will automatically be created upon approval. 

>**Notes:**
> - Public officers using a [non-SE GSIB](glossary) device can also use [TechPass Portal](http://portal.techpass.gov.sg/) to do a self-service sign-up for a TechPass account. For more information, refer to [TechPass documentation.](https://docs.developer.tech.gov.sg/docs/techpass-user-guide/) 
 Existing TechPass users can also request for [SEED provisioning](https://docs.developer.tech.gov.sg/docs/security-suite-for-engineering-endpoint-devices/).
> - SEED provisioning is needed to access SGTS products from the Internet device. If you are a public officer, click [Onboard to SEED](https://docs.developer.tech.gov.sg/docs/techpass-user-guide/#/onboard-to-seed) and follow the on-screen instructions. If you are a vendor, raise a [service request](https://go.gov.sg/techpass-sr) in the TechPass service desk.

## Prerequisites

- Public officers using a [non-SE GSIB](glossary) device can invite other public officers or vendors.

- Have the following information ready before proceeding:
  - Public officers and vendors who require a TechPass account
    - Organisation email address
    - **First name** and **Last name**
    - **Contact number**
    - **Organisation**
    - **Department** (optional)
    - **TechPass username** (for vendors)


## Invite users to TechPass

1.  [Log in to TechBiz portal.](log-in-to-TechBiz-portal.md)

2.  In **Overview**, click **Invite users**.

3.  Select the invitation type.

There are 3 different invitation types:

| <div style="width:270px">Invitation type</div>  | When to use |
| :------------------------------------------ |:-------------|
| Email invitation| Select this to create a TechPass account for the following users:<br> - Public officers using a non-SE GSIB device and whose email address is in the format of \<your_name>@\<acronym for your agency>.gov.sg.<br> |
| Create account | Select this to create a TechPass account for a vendor. |
| Batch upload | Select this to create TechPass accounts for more than one public officer and vendor. |

4.  Select the required **invitation type**, enter the required details and click **Submit**.

For more information on each invitation type, refer to the following:

* [Email invitation](#email-invitation)
* [Create account](#create-account)
* [Batch upload](#batch-upload)


### Email invitation

1. From **Invitation type**, select **Email invitation**.

 <kbd>![email_invite1](/images/invitation-email.png ':size=100%')</kbd>

2. Enter the required details and click **Submit**.

 <kbd>![email_invite](/images/email_invite2.png ':size=100%')</kbd>

Refer to the following for more information on the required details.

| <div style="width:270px">Field Name</div>  | Description |
| :------------------------------------------ |:-------------|
| **Email address**| Enter the email address of the public officer who requires a TechPass account. Email address must be in the format of \<your_name>@\<acronym for your agency>.gov.sg. for public officers.<br> | **Is onboarding to [SEED](https://docs.developer.tech.gov.sg/docs/security-suite-for-engineering-endpoint-devices/#/) required?** | Indicate **Yes** if the public officer needs SEED provisioning.<br />Note: SEED provisioning is needed to access SGTS products from the Internet device.
| **Reason** | Enter the **Reason** why the public officer needs a TechPass account.

### Create account

1. From **Invitation type**, select **Create account**.

 <kbd>![create_acct](/images/create-account.png ':size=100%')</kbd>

2. Enter the required details and click **Submit**.

 <kbd>![create_account](/images/create_acct2.png ':size=100%')</kbd>

Refer to the following for more information on the required details.

| <div style="width:270px">Field Name</div>  | Description |
| :------------------------------------------ |:-------------|
| **Email address**| Enter the organisational email address of the vendor who requires a TechPass account. </br></br> **Note:** The email address must be the email address provided by the vendor.
| **TechPass username** | This field is required if you are requesting TechPass account for a vendor. Enter the required username for the TechPass account.
| **First name,** **Last name,** **Contact number,** **Organisation, and Department**| Enter the required details.<br />Note: **Department** is optional.
| **Is onboarding to [SEED](https://docs.developer.tech.gov.sg/docs/security-suite-for-engineering-endpoint-devices/#/) required?** | Indicate **Yes** if the vendor needs SEED provisioning.<br />Note: SEED provisioning is needed to access SGTS products from the Internet device.
| **Reason** | Enter the **Reason** why the vendor needs a TechPass account.

### Batch upload

1. From **Invitation type**, select **Batch upload**.

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

### To view the status of invited users

From **Invitation type**, select **Invite User Status**.

The page will indicate "No record found" when no users have been invited. If you have invited users using TechBiz, their TechPass and SEED onboarding status will be displayed.

<kbd><img src="images/invite-stats.png" alt="drawing" width="100%"/></kbd>


>**Notes:**
> - Only users invited via TechBiz portal will be displayed on this list. 
> - First name and last name are displayed if the user signed up for TechPass via the TechPass portal or if the TechPass account was created through [create account](#create-account)  or [batch upload](#batch-upload). 
> - Click **Resend invite** to re-invite users through email. Invitations can be sent once a day. The button is available after invites have been sent.

