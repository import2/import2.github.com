---
layout: page
title: false
date: 2012-11-13 18:31
comments: true
sharing: true
footer: false
---

Using the API
=============
Using Import2 API, you can provide customers of your application with a dead-simple migration process from the
app they are substituting with yours. With this guide we will explain and provide code snippets for all
common integration scenarios.

<a id="app-registration"></a>Registering Your Application
---------------------------------------------------------
Currently to register your app you have to contact us at <hassle.free.migration@import2.com>. We will send you
secret API token, which is required to perform API requests.

<a id="authentication"></a>Authentication
-----------------------------------------
Import2 API uses HTTP Basic Authentication. We expect to receive your API token as value of username parameter.
Here is an example of using API token through curl:

```
$ curl -u aafbdfde226327dafc73:X https://www.import2.com/api/v1/imports/3514012b6860e8
```

<a id="sandbox"></a>Sanbox
-----------------------------------------
....


