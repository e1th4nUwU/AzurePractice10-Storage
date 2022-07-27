# Storing files in an Azure Storage Account
![StorageLogos](img/storage-icons.png)


---------------------------------------------------------


## Requirements
- Microsoft Azure Account ( with funds or credits    )
- Microsoft Azure Suscription
- A web browser
- Access to internet

---------------------------------------------------------

## Create Storage Account
#### 1. Login to the [Azure Portal](https://portal.azure.com/).
#### 2. Once you're on the portal's home page, you will see something like this:
![PortalImage](img/portal-main.png)
#### 3. Inside the search bar (located at the top), look for *storage accounts* and click on it.
![Searchbar](img/searchbar.png)
#### 4. Click on *Create*.
![CreateButton](img/create-storage-account.png)
#### 5. First, configure the *Basics* for your storage account: subscripton, resource group and name. If you want, you can change the redundancy option, but I suggest that you leave it as it is.
![StorageBasicas](img/storage-basics.png)
#### 6. Click on *Networking* and make sure *Enable public access from all networks* is selected.
![EnablePublicAccess](img/networking.png)
#### 7. Click on *Review + create*.
![ReviewAndCreate](img/review-and-create.png)
#### 8. If validation passed, click *Create*.
![Create](img/create.png)
#### 9. Deployment will begin, please wait a couple of seconds.
![DeploymentInProgress](img/deployment-in-progress.png)
#### 10. Once deployment has been completed, click on *Go to resource*.
![GoToResource](img/go-to-resource.png)
#### 11. You will now be inside a dashboard .
![Dashboard](img/storage-account-dashboard.png)

---------------------------------------------------------

## Blob Storage
#### 1. Go to your storage account's dashboard and click on *Containers*.
![Containers](img/containers-dashboard-select.png)
#### 2. Click on the *+ Container* button.
![+Container](img/new-container.png)
#### 3. Give your container a name and set the public access level to *Container* (this will make your blob available to anyone worldwide). When you're done, click *Create*.
![ConfigContainer](img/config-container.png)
#### 4. Click on your newly created container.
#### 5. Click *Upload*.
![Upload](img/upload.png)
#### 6. Select some files to upload and, when you're done, click *Upload*.
![UploadBlob](img/upload-blob.png)
#### 7. You have now uploaded your files to the blob. You are able to preview, download, share and edit them. For example, if you uploaded an image and you want to share it, you can go to the *Overview* tab, copy the URL and use it elsewhere.
![ImageURL](img/image-url.png)
#### 8. If you upload a web page (such as the one in this repository), you could also host a static web page in here (of course, you would also need to import CSS and JS files in order to improve the overall experience of your page).
![WebPageURL](img/page-url.png)
![WebPageView](img/page-view.png)
#### 9. Now, let's say you remove a file from your blob. You can see which files have been deleted by clicking on the *Show deleted blobs* switch; you can also undelete them by right clicking the deleted file and clicking *Undelete*.
![DeleteFile](img/delete-file.png)
![DeletedFiles](img/show-deleted-blobs.png)
![Undelete](img/undelete.png)
#### 10. By right-clicking a file and clicking *View snapshots*, you are able to manage snapshots of your file; snapshots are a read-only version of a blob that's taken at a point in time.
![Snapshots](img/snapshots.png)

---------------------------------------------------------

## File Storage
#### 1. Go to your storage account's dashboard and click on *File shares*.
![FileShares](img/file-shares-dashboard-select.png)
#### 2. Click on the *+ File Share* button.
![+FileShare](img/new-file-share.png)
#### 3. Give your new file share a name. I suggest you leave the tier as *Transaction optimized* in order to access your files instantly (if you want a cheaper but slower alternarive, you can change it). When you're done, click *Create*.
![FileShareConfig](img/file-share-config.png)
#### 4. Click on your newly created file share, you will now be inside its dashboard.
![FileShareDashboard](img/file-share-dashboard.png)
#### 5. To upload files in here, just click on *Upload*, choose your files and then click *Upload*.
![UploadFileShare](img/upload-file-share.png)
#### 6. If you click on the *Connect* button, you can connect to your file share from your local system. You just need to copy the corresponding command to your OS terminal and you'll be able to connect to it.
![ConnectButton](img/connect-button.png)
![ConnectProcess](img/connect-file-share.png)

---------------------------------------------------------

## Queue Storage
#### 1. Go to your storage account's dashboard and click on *Queues*.
![Queues](img/queue-dashboard-select.png)
#### 2. Click on the *+ Queue* button.
![+Queue](img/new-queue.png)
#### 3. Give you queue a name and click *Ok*.
![QueueName](img/queue-name.png)
#### 4. Click on your new queue to enter to its dashboard
![QueueDashboard](img/queue-dashboard.png)
#### 5. You can add messages to your queue by clicking *Add message*, writing it and then clicking *Ok*.
![AddMessageToQueue](img/add-message-to-queue.png)
#### 6. You can delete messages from the queue and clear the whole queue as well.
![DeleteFromQueue](img/delete-from-queue.png)

---------------------------------------------------------

## Table Storage
#### 1. Go to your storage account's dashboard and click on *Tables*.
![Tables](img/tables-dashboard-select.png)
#### 2. Click on the *+ Table* button.
![+Table](img/new-table.png)
#### 4. Give your table a name and click *Ok*.
![TableName](img/table-name.png)
#### 5. In order to edit your table, you must use the *Storage browser*. Once you're in there, click on tables and then on the table you created.
![StorageBrowser](img/storage-browser.png)
#### 6. Click on *Add entity*.
![AddEntity](img/add-entity.png)
#### 7. Insert properties and values to add. Once you're done, click *Insert*.
![InsertPropertiesAndValues](img/identity-values.png)
#### 8. You have now inserted a new item into your table.
![TableItem](img/table-item.png)


---------------------------------------------------------

## Congratulations ! You've just worked with all of the available options in an Azure Storage Acoount !