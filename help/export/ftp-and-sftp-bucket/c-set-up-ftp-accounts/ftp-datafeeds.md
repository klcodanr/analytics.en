---
description: Data Feeds are an export of the clickstream data received by Adobe that offers both standard and custom Data Feeds.
keywords: ftp;sftp
seo-description: Data Feeds are an export of the clickstream data received by Adobe that offers both standard and custom Data Feeds.
seo-title: Data Feeds
solution: Analytics
title: Data Feeds
uuid: 3411900f-c706-44a7-8623-2b20636db371
index: y
internal: n
snippet: y
---

# Data Feeds

Data Feeds are an export of the clickstream data received by Adobe that offers both standard and custom Data Feeds.

If you have purchased Adobe data warehouse, [!UICONTROL Standard Data Feeds] can be set up through your Adobe Account Manager. They can be sent to any FTP account (either one set up by Adobe or an external FTP). Adobe Engineering Services offers custom [!UICONTROL Data Feeds] that can be sent by virtually any means.

[!UICONTROL Data Feed]FTP accounts allow 2 GB or 63 files (by default). All other standard FTP accounts are 50MB by default. In cases where clients are using the FTP account for its proper intended use, some users with high traffic amounts can quickly fill up these accounts. When an FTP account is full, no additional files can be pushed to them. Therefore, any files being delivered to that FTP account ( [!UICONTROL Data Feeds], data warehouse requests, and so forth) are not delivered. This is one reason it is important to manage your Adobe FTP account by removing files that have been received and downloaded.

When an FTP account is full, you should download and remove the current files, and let Adobe know the space has been cleared. Adobe can then resend files that have not been delivered. Some tools, such as data warehouse, lets users resend these files. Resending may not require Adobe involvement. If your FTP account appears to be filling up frequently, contact Adobe Customer Care, which can suggest delivery alternatives that can include increasing the FTP space and file number quota on the account.

For information on FTP limits and data retention, see [FTP Limits and Data Retention](../../ftp-and-sftp-bucket/ftp-limits.md#concept_8CAA1D8F27B3411AB902520AD6C9A70E). 