﻿Customer Manager with AngularJS
===============

```
If you’re new to AngularJS check out my [AngularJS in 60-ish Minutes](http://weblogs.asp.net/dwahlin/archive/2013/04/12/video-tutorial-angularjs-fundamentals-in-60-ish-minutes.aspx) video tutorial or download the [free eBook](http://weblogs.asp.net/dwahlin/archive/2013/07/30/angularjs-in-60-ish-minutes-the-ebook.aspx). Also check out [The AngularJS Magazine](http://flip.it/bdyUX) for up-to-date information on using AngularJS to build Single Page Applications (SPAs).
```

![Customer Management App](https://raw.github.com/DanWahlin/CustomerManager/master/CustomerManager/Content/images/customerApp.png)

This application demonstrates:

* A complete application with read-only and editable data
* Using AngularJS with $http in a factory to access a backend Web API service
* Using BreezeJS in a factory to access a backend Web API Service
* Techniques for showing multiple views of data (card view and list view)
* A custom filter for filtering customer data
* A custom routing mechanism that allows a controller & template to be downloaded dynamically "on the fly" and provides a standard convention for controller and view names (see [this post](http://weblogs.asp.net/dwahlin/archive/2013/05/22/dynamically-loading-controllers-and-views-with-angularjs-and-requirejs.aspx)
 for more details)
* A custom directive to ensure unique values in a form for email 
* A custom directive that intercepts $http and jQuery XHR requests (in case either are used) and displays a loading dialog

The factories can be switched by changing the app/services/config useBreeze setting to true.

The AngularJS portion of the app is structured using the following folders:

![Customer Management App Structure](https://raw.github.com/DanWahlin/CustomerManager/master/CustomerManager/Content/images/appFolders.png)

#### Requirements:

The following is required to support the backend services:

* Visual Studio 2012 Web Express (free version) or higher - http://www.microsoft.com/visualstudio/eng/products/visual-studio-express-products#product-express-summary

* ASP.NET MVC and Web API are used for the back-end services along with Entity Framework for database access (included if you have VS 2012 express installed)

To get started, double-click the CustomerManager.sln file located at the root of the CustomerManager repository. 


**I'm interested in porting the backend to NodeJS/MongoDB as well so if anyone has any interest there let me know!**

