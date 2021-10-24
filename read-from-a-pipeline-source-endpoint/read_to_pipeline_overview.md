# Read from a Pipeline overview

You can use this source endpoint to read from the Pipeline created in SnapLogic Intelligent Integration Platform (IIP). Following rules should be adhered to while selecting the created Pipeline from Flows.

To select the Pipelines from IIP:

1. Create the Pipeline in the SnapLogic IIP at the project level.
2. While configuring the account for the Pipeline, select the same shared folder that is selected in Flows. If the pipeline is created in any other folder, they are not displayed for the selection in Flows.
3. In Flows, select **Read from a Pipeline**. The list of Pipelines from the selected folder is displayed with the appropriate title and description. These details are read from the Pipeline **Purpose** and **Notes** fields respectively. If these fields are not populated, then use the **Label** of the Pipeline.

**Note**: When adding Read from a Pipeline to any source endpoint, the respective IIP Pipeline should have open output. Else, the Pipeline is disabled and cannot be selected in Flows.
