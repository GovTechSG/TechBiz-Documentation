# Release notes

> **Tip**: Click the triangle to view more details about the change.

## Release 10 May 2023

Frontend version: 1.0.0-20230509.1043 | Backend version: 1.61.9-230508.0922

**Changes** 

<details>
<summary style="font-size:20px;font-weight:bold"> Enhancement to SEED device onboarding Status for public officers.
</summary>

Previously, Public Officers would only see their device status as ‘pending’ until it was fully onboarded. We have now introduced more granular status updates, including 'triggered, waiting for software installation', 'software installed, awaiting backend onboarding', and 'failed'. This offers user greater visibility into the onboarding process. Additionally, we've added a **retry** button to enable users to restart the onboarding process should it fail under certain circumstances.

> **Note**: This change only affects public officers. Vendors currently do not trigger onboarding through the TechPass portal and do not have a **pending** device.

</details>