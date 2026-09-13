# Setup guide

## Prerequisites

- A GoHighLevel sub-account
- A property consultation calendar
- A real estate sales pipeline
- At least one CRM user who can own new leads

## 1. Create the trigger

Create a workflow and select **Customer Booked Appointment**.

Apply these filters:

- Contact mode: `Contact`
- Calendar: your property consultation calendar

Keeping the calendar filter prevents unrelated appointments from entering the workflow.

## 2. Create or update the opportunity

Add **Create or Update Opportunity** and select:

- Your real estate pipeline
- The `Appointment Booked` stage

The create-or-update behavior helps prevent unnecessary duplicate opportunities.

## 3. Assign the lead

Add **Assign to User** and select the responsible sales user. Place this action before the notification so the contact has an owner when the alert runs.

## 4. Configure the internal alert

Add **Send Internal Notification** with the following settings:

- Type: `Notification`
- Recipient type: `Assigned owners`
- Assigned owner: `Contact owner`
- Redirect page: `Contact`
- Title: `New Property Consultation Booked`

Suggested message:

> A new lead has booked a property consultation. Open the contact record to review the appointment and follow up.

This is an internal CRM alert and does not message the customer.

## 5. Add the contact tag

Add **Contact Tag** and apply `appointment booked`. The tag can later support filters, reporting, nurture sequences, or manual follow-up queues.

## 6. Test before publishing

Use a clearly identified dummy contact and run the built-in workflow test. Confirm every action in **Execution Logs**.

Do not publish until all actions show `Executed` and the workflow reaches its end state.

## 7. Publish

After successful validation, switch the workflow from Draft to Publish and save the workflow.

