---
description: Testing any modifications to the .JS file or HTML code is the responsibility of the customer. It should be completed prior to publishing the modifications to production websites.
keywords: Analytics Implementation
seo-description: Testing any modifications to the .JS file or HTML code is the responsibility of the customer. It should be completed prior to publishing the modifications to production websites.
seo-title: Code modifications
solution: Analytics
title: Code modifications
topic: Developer and implementation
uuid: 2ccf0046-13bc-4036-b903-97bebdeaa40e
index: y
internal: n
snippet: y
---

# Code modifications

Testing any modifications to the .JS file or HTML code is the responsibility of the customer. It should be completed prior to publishing the modifications to production websites.

Ensure that the linefeeds/return characters are not stripped or altered from the code that is placed within the HTML, or from within the [!DNL .JS] file. Ensure that the JavaScript executes without an error on all pages and page templates (in Internet Explorer Internet Options, select the Advanced Tab, and click Display a Notification about Every Script Error.

When testing for errors, paste the code into a default HTML page to determine if the error is occurring because of other page elements/objects.

```js
<html><head></head><body>
...paste code here to debug...
</body></html>

```
