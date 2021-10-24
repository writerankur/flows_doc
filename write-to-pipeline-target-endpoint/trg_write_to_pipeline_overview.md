# Write to Pipeline overview

You can use this target endpoint to execute a flow with the Pipeline created in SnapLogic Intelligent Integration Platform (IIP). Following rules should be adhered to while selecting the created Pipeline from Flows.

To select the Pipelines from IIP:

1. Create the Pipeline in the SnapLogic IIP at the project level.** **
2. While configuring the account for the Pipeline, select the same shared folder that is selected in Flows. If the pipeline is created in any other folder, they are not be displayed for the selection in Flows.&#x20;
3. The list of Pipelines is displayed with the appropriate title and description. These details are read from the Pipeline _**Purpose**_ and _**Notes**_ fields respectively. If these fields are not populated then use the pipeline label

Note: When adding Write to Pipeline to any target endpoint, the respective IIP pipeline should have an open input view. Else, the Pipeline is greyed out and cannot be selected in Flows.\
