# CSV Generator overview

The CSV Generator allows you to create CSV documents within Flows. The CSV can be exported to SnapLogic's file system using the export action.

Click **Edit CSV** to launch the CSV Editor. Edit the CSV document and click **Ok** to save.

**Advanced Settings:**

Choose how the Snap will be executed:

* **Validate & Execute:** Performs limited execution of the Snap during Pipeline validation and performs full execution of the Snap during Pipeline execution.
* **Execute only:** Performs full execution of the Snap during Pipeline execution but does not execute the Snap during Pipeline validation.
* **Disabled:** Disables the Snap and downstream Snaps.

Use the **Filter Data** option to filter the incoming data uploaded by the source endpoint. Once a filter is applied, you can view it in the **Data Wrangler** and further edit the filter condition.
