# Gym Management Power Automate
These Power Automate workflows are designed to automate routine gym management tasks, such as equipment maintenance notifications, membership renewals, and more.

## Getting Started:
Access Power Automate and sign in with your Microsoft account.
Import the provided .zip files containing each workflow.
Customize workflow triggers, actions, and schedules to fit your gym's requirements.
Enable and test each workflow to ensure proper functionality.
Monitor workflow performance and adjust as needed.
For detailed instructions on customization and deployment, refer to the documentation provided within the Power Automate project.

## Technical Documentation:
Check the Documentation folder for technical documentation generated using PowerDocu. The documentation provides insights into the workflows' configurations, triggers, and actions.

## Features:
Approve inscripitons

The flow is triggered when a new inscription is added to the database

![1 1_FlowChart](https://github.com/zepedromvramiao/Portfolio/assets/60276332/395d118e-97f3-41db-9579-1ddd4f039e39)

The inscription needs to be approved by the person responsible for the respective gym activity

![1 2_FlowChart](https://github.com/zepedromvramiao/Portfolio/assets/60276332/b66c289b-7822-4f1a-bb82-0cb7b341217f)

![2 1_Aprovacao](https://github.com/zepedromvramiao/Portfolio/assets/60276332/07b166ef-9164-419d-8c00-3f2c2a9b2eda)

Once the approval is initiated, the inscription in the database changes to "pending"

After de approval decision, the inscription in the database is updated to approved or rejected, and the person who made the inscription is notified by email


