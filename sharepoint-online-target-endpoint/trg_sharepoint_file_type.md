# Configure SharePoint Online Data Delivery Type

Select your SharePoint endpoint for any one of the following data delivery types to start your Flow and provide the following information:

* **Create Folder**: Select this data delivery type to create a folder both in a SharePoint Online document library and within another item of type folder.
  * **Site**: The name of a site that contains the list of document libraries to be used in the subsequent Snap settings.
  * **Document library**: Select the drive representing the top-level container for the system such as Onedrive or Sharepoint document libraries.
  * **Folder Name**: The folder name to be used to create the folder.
* **Create Item Permission**: Select this data delivery type to create ad share invitations for an item to the configured set of recipients.
  * **Site**: The name of a site that contains the list of document libraries to be used in the subsequent Snap settings.
  * **Document library**: Select the drive representing the top-level container for the system such as Onedrive or Sharepoint document libraries.
  * **Source item relative path**: Enter the item resource path that represents a file, folder, or other item stored in a document library to get the available permissions on the item.
  * **Roles**: Specify the roles that are to be granted to the recipients of the invitation.
  * **Recipients**: Enter the comma-separated recipients who will receive access and the sharing invitation to the selected item.&#x20;
* **Create List: **Select this data delivery type to create a list or list item in SharePoint Online.
  * **Site**: The name of a site that contains the list of document libraries to be used in the subsequent Snap settings.
  * **List name**: Select the name of the list.&#x20;
* **Copy and Update Item**: Select the data delivery type to copy the item resource path that represents a folder or file stored in a document library and update a name or move an item.
  * **Site**: The name of a site that contains the list of document libraries to be used in the subsequent Snap settings.
  * **Document library**: Select the drive representing the top-level container for the system such as Onedrive or Sharepoint document libraries.
  * **Source item relative path:** Enter the item resource path that represents a file, folder, or other item stored in a document library to get the available permissions on the item.
* **Update Item Permission: **Select this data delivery type to update item permission associated with an item/folder of the SharePoint Online document library.
* **Delete Item Permission**: Select this data delivery type to delete item permission of an item from the SharePoint Online document library.
  * **Site**: The name of a site that contains the list of document libraries that are used in the subsequent Snap settings.
  * **Document library**: Select the drive representing the top-level container for the system such as Onedrive or Sharepoint document libraries.
  * **Source item relative path**: Enter the item resource path that represents a file, folder, or other item stored in a document library to get the available permissions on the item.
  * **PermissionId**: Select the permission id from the drop-down list associated with an item selected in the Source file path property.
  * **Roles**: Specify the roles that are to be granted to the recipients of the invitation.
* **Update List Item**:** **Select this data delivery type to update the values of an existing list item in a SharePoint Online site.
* **Delete List Item**: Select this data delivery type to delete items from the SharePoint Online document library.
  * **Site**: The name of a site that contains the list of document libraries to be used in the subsequent Snap settings.
  * **List name**: Select the name of the list.&#x20;
  * **Item Id**: Select or enter the item id from the suggestion drop-down list of a specific list or use the expression to pass from the upstream document to perform the update item.
* **Delete Item**: Select this data delivery type to delete items from the SharePoint Online document library.
  * **Site**: The name of a site that contains the list of document libraries to be used in the subsequent Snap settings.
  * **Document library**: Select the drive representing the top-level container for the system such as Onedrive or Sharepoint document libraries.
  * **Source item relative path**: Enter the item resource path that represents a file, folder, or other item stored in a document library to get the available permissions on the item.
