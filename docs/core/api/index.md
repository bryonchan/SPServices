### Function

$().SPServices

### Certification

![Certified for SharePoint 2007](/docs/img/sp2007-cert.jpg)](/docs/glossary/index.md#Certification) [![Works with Caveats with SharePoint 2010](/docs/img/sp2010-works.jpg)](/docs/glossary/index.md##Certification)
See individual Web Services pages for certification specifics.

### Notes

As of version 2013.01, all calls return a [jQuery deferred object](http://api.jquery.com/category/deferred-object/) aka a promise.

As of v0.7.2, the core `$().SPServices()` function allows for simple caching of the XML results using jQuery promises in a similar manner to that outlined in Scot Hillier's excellent post [Utilizing Promises in SharePoint 2013 Apps](http://www.shillier.com/archive/2012/11/29/utilizing-promises-in-sharepoint-2013-apps.aspx). See the [Caching](/wikipage?title=Caching) page for more details.

### Supported Web Services

The table below shows the Web Services for which we have implemented at least one operation (or have operations coming in planned releases) with a link to more detailed documentation, indicators for whether the Web Service is available in WSS 3.0 and/or MOSS, and links to the MSDN documentation pages. Note that there are some [general syntax instructions](/wikipage?title=%24%28%29.SPServices&ANCHOR#GeneralSyntax) below the table.

| SharePoint 2007 | SharePoint 2010 |
| --------------- | --------------- |

| Web Service | WSS 3.0 | MOSS | MSDN Documentation | Foundation | SP2010 |
| ----------- | ------- | ---- | ------------------ | ---------- | ------ |
| [Alerts](/docs/core/api/Alerts.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Alerts Web Service](http://msdn.microsoft.com/en-us/library/alerts.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Authentication](/docs/core/api/Authentication.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Authentication Web Service](http://msdn.microsoft.com/en-us/library/authentication.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Copy](/docs/core/api/Copy.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Copy Web Service](http://msdn.microsoft.com/en-us/library/copy.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Forms](/docs/core/api/Forms.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Forms Web Service](http://msdn.microsoft.com/en-us/library/forms.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Lists](/docs/core/api/Lists.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Lists Web Service](http://msdn.microsoft.com/en-us/library/lists.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Meetings](/docs/core/api/Meetings.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Meetings Web Service](http://msdn.microsoft.com/en-us/library/ms774629.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [People](/docs/core/api/People.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [People Web Service](http://msdn.microsoft.com/en-us/library/people.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Permissions](/docs/core/api/Permissions.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Permissions Web Service](http://msdn.microsoft.com/en-us/library/permissions.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [SiteData](/docs/core/api/SiteData.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [SiteData Web Service](http://msdn.microsoft.com/en-us/library/ms774821(v=office.12).aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Sites](/docs/core/api/Sites.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | Sites Web Service [2007](http://msdn.microsoft.com/en-us/library/ms774847(v=office.12).aspx) [2010](http://msdn.microsoft.com/en-us/library/bb250173.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Users and Groups](/docs/core/api/Users%20and%20Groups.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Users and Groups Web Service](http://msdn.microsoft.com/en-us/library/ms772647.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Versions](/docs/core/api/Versions.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Versions Web Service](http://msdn.microsoft.com/en-us/library/ms772545.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Views](/docs/core/api/Views.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Views Web Service](http://msdn.microsoft.com/en-us/library/views.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [WebPartPages](/docs/core/api/WebPartPages.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Web Part Pages Web Service](http://msdn.microsoft.com/en-us/library/ms774569.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [Webs](/docs/core/api/Webs.md) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) | [Webs Web Service](http://msdn.microsoft.com/en-us/library/webs.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [PublishedLinksService](/docs/core/api/PublishedLinksService.md) | | ![](/docs/img/checkmark.gif) | [PublishedLinksService Web Service](http://msdn.microsoft.com/en-us/library/aa981003.aspx) | ![](/docs/img/checkmark.gif) |
| [Official File (Records Repository)](/docs/core/api/OfficialFile.md) | | ![](/docs/img/checkmark.gif) | [Official File Web Service](http://msdn.microsoft.com/en-us/library/aa981147(v=office.12).aspx) | ![](/docs/img/checkmark.gif) |
| [Search](/docs/core/api/Search.md) | | ![](/docs/img/checkmark.gif) | [Search Web Service](http://msdn.microsoft.com/en-us/library/search.aspx) | ![](/docs/img/checkmark.gif) |
| [SpellChecker](/docs/core/api/SpellChecker.md) | | ![](/docs/img/checkmark.gif) | [SpellChecker Web Service](http://msdn.microsoft.com/en-us/library/microsoft.sharepoint.publishing.spellchecker.spellcheck.aspx) | ![](/docs/img/checkmark.gif) |
| [UserProfileService](/docs/core/api/UserProfileService.md) | | ![](/docs/img/checkmark.gif) | [User Profile Web Service](http://msdn.microsoft.com/en-us/library/aa981571.aspx) | ![](/docs/img/checkmark.gif) |
| [Workflow](/docs/core/api/Workflow.md) | | ![](/docs/img/checkmark.gif) | [Workflow Web Service](http://msdn.microsoft.com/en-us/library/aa981383.aspx) | ![](/docs/img/checkmark.gif) |
| [Diagnostics](/docs/core/api/Diagnostics.md) | | | [Diagnostics Web Service](http://msdn.microsoft.com/en-us/library/ee551419.aspx) | ![](/docs/img/checkmark.gif) | ![](/docs/img/checkmark.gif) |
| [SocialDataService](/docs/core/api/SocialDataService) | | | [SocialDataService Web Service](http://msdn.microsoft.com/en-us/library/ee590294.aspx) | ![](/docs/img/checkmark.gif) |
| [TaxonomyClientService](/docs/core/api/TaxonomyClientService) | | | [TaxonomyClientService Web Service](http://msdn.microsoft.com/en-us/library/ee586638.aspx) | ![](/docs/img/checkmark.gif) |

### General Syntax

```javascript
$().SPServices({
	operation: "operationname",
	[webURL: "/sitepath",]
	[option1: value1,]
	[option2: value2,]
	[async: false,]
	completefunc: function (xData, Status) {
		//...do stuff...
	}
});
```

_operation_
The name of the Web Service operation (see the SDK documentation links above). Because the Web Services operations are named uniquely, you only need to specify the operation.

_webURL_
For Web Service operations where it makes sense, you can pass in a webURL to change the context for the AJAX call. By default, the current site (as determined by [$().SPServices.SPGetCurrentSite](/docs/utilities/SPGetCurrentSite.md)) is used.

_options_
The options vary based on which Web Service and operation you are calling. In all instances, the options will take the same names as those described in the SDK.

_async_
By default, all of the Web Service operations are called asynchronously with AJAX. Generally, this will be the desired approach, but to force synchronicity, add the async: false option.

_cacheXML_
If set to true, the result's raw XML will be cached using jQuery promises in a similar manner to that outlined in Scot Hillier's excellent post [Utilizing Promises in SharePoint 2013 Apps](http://www.shillier.com/archive/2012/11/29/utilizing-promises-in-sharepoint-2013-apps.aspx). See more about how this works on the [Caching](/wikipage?title=Caching) page.

_completefunc_
A function to call on completion of the AJAX call to the Web Service:

```javascript
completefunc: function(xData, Status) {
  //...do something...
},
```

### Example

Example call for GetListItems. This example is taken directly from SPCascadeDropdowns:

```javascript
$().SPServices({
	operation: "GetListItems",
	// Force sync so that we have the right values for the child column onchange trigger
	async: false,
	webURL: opt.relationshipWebURL,
	listName: opt.relationshipList,
	// Filter based on the currently selected parent column's value
	CAMLQuery: camlQuery,
	// Only get the parent and child columns
	CAMLViewFields: "<ViewFields><FieldRef Name='" + opt.relationshipListParentColumn + "' /><FieldRef Name='" + opt.relationshipListChildColumn + "' /></ViewFields>",
	// Override the default view rowlimit and get all appropriate rows
	CAMLRowLimit: 0,
	completefunc: function(xData, Status) {
		// ...
	}
});
```

Example call for GetUserInfo:
```javascript
waitMessage = "<table width='100%' align='center'><tr><td align='center'><img src='/_layouts/images/gears_an.gif'/></td></tr></table>";

$("#WSOutput").html(waitMessage).SPServices({
	operation: "GetUserInfo",
	userLoginName: "SHARE1\\demouser",
	completefunc: function (xData, Status) {
		$("#WSOutput").html("").append("<b>This is the output from the GetUserInfo operation:</b>");
		$(xData.responseXML).find("User").each(function() {
			$("#WSOutput").append("<li>ID: " + $(this).attr("ID") + "</li>");
			$("#WSOutput").append("<li>Sid: " + $(this).attr("Sid") + "</li>");
			$("#WSOutput").append("<li>Name: " + $(this).attr("Name") + "</li>");
			$("#WSOutput").append("<li>LoginName: " + $(this).attr("LoginName") + "</li>");
			$("#WSOutput").append("<li>Email: " + $(this).attr("Email") + "</li>");
			$("#WSOutput").append("<li>Notes: " + $(this).attr("Notes") + "</li>");
			$("#WSOutput").append("<li>IsSiteAdmin: " + $(this).attr("IsSiteAdmin") + "</li>");
			$("#WSOutput").append("<li>IsDomainGroup: " + $(this).attr("IsDomainGroup") + "</li>");
			$("#WSOutput").append("<hr/>");
		});
	}
});
```
