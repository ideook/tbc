<head>
<title>The Building Coder</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link rel="stylesheet" type="text/css" href="3dwc.css"/>
<script src="https://cdn.rawgit.com/google/code-prettify/master/loader/run_prettify.js?autoload=true" defer="defer"></script>
</head>

<!---

12174739 [Revit 2017 API bug report: wrong texture export]
http://forums.autodesk.com/t5/revit-api-forum/revit-2017-api-bug-report-wrong-texture-export/m-p/6566378
  
Material Asset Textures, @AutodeskForge Webinar Recordings #revitapi #3dwebcoder @AutodeskRevit #aec #bim @RTCEvents

Today is the last day before my one-week vacation, directly followed non-stop by the ISEPBIM Forge and BIM workshops at Porto University, the RTC Revit Technology Conference Europe, and the Forge Accelerator in Munich. Before leaving, here is a note about another recording of the Forge webinar series and a happy resolution of a recent material asset texture related Revit API issue:
&ndash; Forge webinar series and BIM360 recordings
&ndash; Listing material asset textures and sub-textures...

-->

### Material Asset Textures, Forge Webinar Recordings

Today is the last day before my one-week vacation, directly followed non-stop by
the [ISEPBIM](https://www.facebook.com/ISEPBIM) Forge and BIM workshops at [ISEP](http://www.isep.ipp.pt), Porto University,
the [RTC Revit Technology Conference Europe](http://www.rtcevents.com/rtc2016eur) in Porto, and
the [Forge Accelerator](http://autodeskcloudaccelerator.com) in Munich.

So come the end of the month I will probably be in dire need of another vacation &nbsp; :-)

Anyway, before leaving, here is a note about another recording of the Forge webinar series published for your convenience and pleasure, and a happy resolution of a recent material asset texture related Revit API issue:

- [Forge webinar series and BIM360 recordings](#2)
- [Listing material asset textures and sub-textures](#3)


#### <a name="2"></a>Forge Webinar Series and BIM360 Recordings

The [Forge webinar series](http://autodeskforge.devpost.com/details/webinars) continues.

Yesterday, Mikako Harada presented 
an [Introduction to BIM360](http://adndevblog.typepad.com/cloud_and_mobile/2016/10/introduction-to-bim-360.html).
 
As always, API keys to try it out yourself can be obtained
from [developer.autodesk.com](https://developer.autodesk.com), which also hosts
the [BIM360 documentation](https://developer.autodesk.com/en/docs/bim360/v1).
 
In this context, you might also be interested in
the [Forge DevCon recording on BIM 360](https://www.youtube.com/watch?v=cOQEyI-EMAQ).

Here are the recordings and documentation pointers for all the topics covered so far:

- September 20
&ndash; [Introduction to Autodesk Forge and the Autodesk App Store](http://adndevblog.typepad.com/cloud_and_mobile/2016/09/introduction-to-autodesk-forge-and-the-autodesk-app-store.html)
- September 22
&ndash; [Introduction to OAuth and Data Management API](http://adndevblog.typepad.com/cloud_and_mobile/2016/09/introduction-to-oauth-and-data-management-api.html)
&ndash; on [OAuth](https://developer.autodesk.com/en/docs/oauth/v2/overview)
and [Data Management API](https://developer.autodesk.com/en/docs/data/v2/overview), providing token-based authentication, authorization and a unified and consistent way to access data across A360, Fusion 360, and the Object Storage Service.
- September 27
&ndash; [Introduction to Model Derivative API](http://adndevblog.typepad.com/cloud_and_mobile/2016/09/introduction-to-model-derivative-api.html)
&ndash; on the [Model Derivative API](https://developer.autodesk.com/en/docs/model-derivative/v2/overview) that enables users to represent and share their designs in different formats and extract metadata.
- September 29
&ndash; [Introduction  to Viewer](http://adndevblog.typepad.com/cloud_and_mobile/2016/09/introduction-to-viewer-api.html)
&ndash; the [Viewer](https://developer.autodesk.com/en/docs/viewer/v2/overview), formerly part of the 'View and Data API', is a WebGL-based JavaScript library for 3D and 2D model rendering of CAD models from seed files, e.g., [AutoCAD](http://www.autodesk.com/products/autocad/overview), [Fusion 360](http://www.autodesk.com/products/fusion-360/overview), [Revit](http://www.autodesk.com/products/revit-family/overview) and many other formats.
- October 4
&ndash; [Introduction to Design Automation](http://adndevblog.typepad.com/cloud_and_mobile/2016/10/introduction-to-design-automation.html)
&ndash; the [Design Automation API](https://developer.autodesk.com/en/docs/design-automation/v2/overview), formerly known as 'AutoCAD I/O', enables running scripts on native CAD design files such as `DWG`,
cf. [Albert's tutorials](https://github.com/szilvaa/acadio-tutorials).
- October 6
&ndash; [Introduction to BIM360](http://adndevblog.typepad.com/cloud_and_mobile/2016/10/introduction-to-bim-360.html) and
the [Forge DevCon recording on BIM 360](https://www.youtube.com/watch?v=cOQEyI-EMAQ)
&ndash; [BIM360](https://developer.autodesk.com/en/docs/bim360/v1/overview) enables apps to integrate with BIM360 to extend its capabilities in the construction ecosystem.

For code samples on any of these, please refer to the Forge Platform samples on GitHub
at [Developer-Autodesk](https://github.com/Developer-Autodesk),
optionally adding a filter, e.g., like this for `Design.automation`: [...Developer-Autodesk?query=Design.automation](https://github.com/Developer-Autodesk?query=Design.automation).

The Forge Webinar series continues during the remainder of
the [Autodesk App Store Forge and Fusion 360 Hackathon](http://autodeskforge.devpost.com) until the end of October.

Next is session 7, an Introduction to Fusion 360 Client API:

- October 11 &ndash; [Fusion 360 Client API](http://help.autodesk.com/view/NINVFUS/ENU/?guid=GUID-A92A4B10-3781-4925-94C6-47DA85A4F65A) &ndash; an integrated CAD, CAM, and CAE tool for product development, built for the new ways products are designed and made.
- October 13 &ndash; Q&A on all APIs.
- October 20 &ndash; Q&A on all APIs.
- October 27 &ndash; Submitting a web service app to Autodesk App store.

Quick access links:

- For API keys, go to [developer.autodesk.com](https://developer.autodesk.com)
- For code samples, go to [github.com/Developer-Autodesk](https://github.com/Developer-Autodesk)
 
Feel free to contact us at [forgehackathon@autodesk.com](mailto:forgehackathon@autodesk.com) at any time with any questions.

<!----
<center>
<img src="img/forge_accelerator.png" alt="Forge &ndash; build the future of making things together" width="400">
</center>
---->

#### <a name="3"></a>Listing Material Asset Textures and Sub-Textures

An issue concerning access to material asset sub-textures was raised in 
the [Revit API discussion forum](http://forums.autodesk.com/t5/revit-api/bd-p/160) thread
on [Revit 2017 API bug report: wrong texture export ](http://forums.autodesk.com/t5/revit-api-forum/revit-2017-api-bug-report-wrong-texture-export/m-p/6566378) and
resolved by the development team:

**Question:** I work with Revit API and, seemingly, encountered a bug with asset content. 

While exporting from `.rvt` project a material with the following texture characteristics:

<center>
<img src="img/material_texture.png" alt="Material texture" width="705">
</center>

In other words, textured material with a checker basic procedural texture and both 2 checkers as its sub-textures.

Exploring this through Python, I saw the following situation:

<center>
<img src="img/material_texture_asset_code.png" alt="Material texture asset code" width="705">
</center>

This can be described as follows: the first slot `(asset["checker_color1"])` was exported correctly, since the method:

<pre>
  asset["checker_color1"].GetAllConnectedProperties()
</pre>

returned an attached asset, but the second slot was exported incorrectly, because the corresponding method threw an exception and the `checker_color2` position is empty, although, as you can see above, there also must be an asset there. 
 

**Answer:** I logged the issue *REVIT-99286 [API: sub-texture missing in material asset -- 12174739]* with our development team for further exploration.

They reply:

I cannot reproduce this issue in Revit 2016. I added layers of checker to a material's texture and with the API extraction I can see each layer being found and readable. I do not have the customer model, nor did I experiment with the debugger syntax indicated.

I suspect it's more likely the developer has a typo in his code rather than anything else.

I created a sample model with an embedded `ShowMaterialInfo` macro set to read from the checker material which is saved within it.

You can scroll through the output and see the multiple layers of connected assets and their nested properties.

I hope this helps.

I extracted the development team code from their macro and added it
to [The Building Coder samples](https://github.com/jeremytammik/the_building_coder_samples)
module [CmdGetMaterials.cs](https://github.com/jeremytammik/the_building_coder_samples/blob/master/BuildingCoder/BuildingCoder/CmdGetMaterials.cs#L64-L652)
in [release 2017.0.130.4](https://github.com/jeremytammik/the_building_coder_samples/releases/tag/2017.0.130.4), cf.
the [diff](https://github.com/jeremytammik/the_building_coder_samples/compare/2017.0.130.3...2017.0.130.4).

By the way, this code pulls in two new namespaces that were not previously used:

<pre class="code">
<span style="color:blue;">using</span>&nbsp;System.ComponentModel;
<span style="color:blue;">using</span>&nbsp;Autodesk.Revit.Utility;
</pre>

Here is the complete material asset texture listing code including a couple of helper class definitions:

<pre class="code">
<span style="color:blue;">#region</span>&nbsp;List&nbsp;Material&nbsp;Asset&nbsp;Sub-Texture
<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
<span style="color:gray;">///</span><span style="color:green;">&nbsp;A&nbsp;description&nbsp;of&nbsp;a&nbsp;property&nbsp;consists&nbsp;of&nbsp;a&nbsp;name,&nbsp;its&nbsp;attributes&nbsp;and&nbsp;value</span>
<span style="color:gray;">///</span><span style="color:green;">&nbsp;here&nbsp;AssetPropertyPropertyDescriptor&nbsp;is&nbsp;used&nbsp;to&nbsp;wrap&nbsp;AssetProperty&nbsp;</span>
<span style="color:gray;">///</span><span style="color:green;">&nbsp;to&nbsp;display&nbsp;its&nbsp;name&nbsp;and&nbsp;value&nbsp;in&nbsp;PropertyGrid</span>
<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
<span style="color:blue;">internal</span>&nbsp;<span style="color:blue;">class</span>&nbsp;<span style="color:#2b91af;">AssetPropertyPropertyDescriptor</span>&nbsp;:&nbsp;<span style="color:#2b91af;">PropertyDescriptor</span>
{
&nbsp;&nbsp;<span style="color:blue;">#region</span>&nbsp;Fields
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;A&nbsp;reference&nbsp;to&nbsp;an&nbsp;AssetProperty</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">private</span>&nbsp;<span style="color:#2b91af;">AssetProperty</span>&nbsp;m_assetProperty;
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;The&nbsp;type&nbsp;of&nbsp;AssetProperty&#39;s&nbsp;property&nbsp;&quot;Value&quot;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span><span style="color:green;">m</span>
&nbsp;&nbsp;<span style="color:blue;">private</span>&nbsp;<span style="color:#2b91af;">Type</span>&nbsp;m_valueType;
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;The&nbsp;value&nbsp;of&nbsp;AssetProperty&#39;s&nbsp;property&nbsp;&quot;Value&quot;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">private</span>&nbsp;<span style="color:#2b91af;">Object</span>&nbsp;m_value;
&nbsp;&nbsp;<span style="color:blue;">#endregion</span>
 
&nbsp;&nbsp;<span style="color:blue;">#region</span>&nbsp;Properties
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Property&nbsp;to&nbsp;get&nbsp;internal&nbsp;AssetProperty</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:#2b91af;">AssetProperty</span>&nbsp;AssetProperty
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">get</span>&nbsp;{&nbsp;<span style="color:blue;">return</span>&nbsp;m_assetProperty;&nbsp;}
&nbsp;&nbsp;}
&nbsp;&nbsp;<span style="color:blue;">#endregion</span>
 
&nbsp;&nbsp;<span style="color:blue;">#region</span>&nbsp;override&nbsp;Properties
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Gets&nbsp;a&nbsp;value&nbsp;indicating&nbsp;whether&nbsp;this&nbsp;property&nbsp;is&nbsp;read-only</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">override</span>&nbsp;<span style="color:blue;">bool</span>&nbsp;IsReadOnly
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">get</span>
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:blue;">true</span>;
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Gets&nbsp;the&nbsp;type&nbsp;of&nbsp;the&nbsp;component&nbsp;this&nbsp;property&nbsp;is&nbsp;bound&nbsp;to.&nbsp;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">override</span>&nbsp;<span style="color:#2b91af;">Type</span>&nbsp;ComponentType
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">get</span>
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;m_assetProperty.GetType();
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Gets&nbsp;the&nbsp;type&nbsp;of&nbsp;the&nbsp;property.&nbsp;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">override</span>&nbsp;<span style="color:#2b91af;">Type</span>&nbsp;PropertyType
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">get</span>
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;m_valueType;
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;}
&nbsp;&nbsp;<span style="color:blue;">#endregion</span>
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Public&nbsp;class&nbsp;constructor</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>assetProperty<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">the&nbsp;AssetProperty&nbsp;which&nbsp;a&nbsp;AssetPropertyPropertyDescriptor&nbsp;instance&nbsp;describes</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;AssetPropertyPropertyDescriptor(&nbsp;<span style="color:#2b91af;">AssetProperty</span>&nbsp;assetProperty&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;:&nbsp;<span style="color:blue;">base</span>(&nbsp;assetProperty.Name,&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:#2b91af;">Attribute</span>[0]&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;m_assetProperty&nbsp;=&nbsp;assetProperty;
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:blue;">#region</span>&nbsp;override&nbsp;methods
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Compares&nbsp;this&nbsp;to&nbsp;another&nbsp;object&nbsp;to&nbsp;see&nbsp;if&nbsp;they&nbsp;are&nbsp;equivalent</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>obj<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;object&nbsp;to&nbsp;compare&nbsp;to&nbsp;this&nbsp;AssetPropertyPropertyDescriptor.&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">override</span>&nbsp;<span style="color:blue;">bool</span>&nbsp;Equals(&nbsp;<span style="color:blue;">object</span>&nbsp;obj&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyPropertyDescriptor</span>&nbsp;other&nbsp;=&nbsp;obj&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyPropertyDescriptor</span>;
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;other&nbsp;!=&nbsp;<span style="color:blue;">null</span>&nbsp;&amp;&amp;&nbsp;other.AssetProperty.Equals(&nbsp;m_assetProperty&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;the&nbsp;hash&nbsp;code&nbsp;for&nbsp;this&nbsp;object.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Here&nbsp;override&nbsp;the&nbsp;method&nbsp;&quot;Equals&quot;,&nbsp;so&nbsp;it&nbsp;is&nbsp;necessary&nbsp;to&nbsp;override&nbsp;GetHashCode&nbsp;too.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">override</span>&nbsp;<span style="color:blue;">int</span>&nbsp;GetHashCode()
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;m_assetProperty.GetHashCode();
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Resets&nbsp;the&nbsp;value&nbsp;for&nbsp;this&nbsp;property&nbsp;of&nbsp;the&nbsp;component&nbsp;to&nbsp;the&nbsp;default&nbsp;value.&nbsp;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>component<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;component&nbsp;with&nbsp;the&nbsp;property&nbsp;value&nbsp;that&nbsp;is&nbsp;to&nbsp;be&nbsp;reset&nbsp;to&nbsp;the&nbsp;default&nbsp;value.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">override</span>&nbsp;<span style="color:blue;">void</span>&nbsp;ResetValue(&nbsp;<span style="color:blue;">object</span>&nbsp;component&nbsp;)
&nbsp;&nbsp;{
 
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;whether&nbsp;resetting&nbsp;an&nbsp;object&nbsp;changes&nbsp;its&nbsp;value.&nbsp;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>component<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;component&nbsp;to&nbsp;test&nbsp;for&nbsp;reset&nbsp;capability.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">true&nbsp;if&nbsp;resetting&nbsp;the&nbsp;component&nbsp;changes&nbsp;its&nbsp;value;&nbsp;otherwise,&nbsp;false.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">override</span>&nbsp;<span style="color:blue;">bool</span>&nbsp;CanResetValue(&nbsp;<span style="color:blue;">object</span>&nbsp;component&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:blue;">false</span>;
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span><span style="color:green;">G</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Determines&nbsp;a&nbsp;value&nbsp;indicating&nbsp;whether&nbsp;the&nbsp;value&nbsp;of&nbsp;this&nbsp;property&nbsp;needs&nbsp;to&nbsp;be&nbsp;persisted.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>component<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;component&nbsp;with&nbsp;the&nbsp;property&nbsp;to&nbsp;be&nbsp;examined&nbsp;for&nbsp;persistence.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">true&nbsp;if&nbsp;the&nbsp;property&nbsp;should&nbsp;be&nbsp;persisted;&nbsp;otherwise,&nbsp;false.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">override</span>&nbsp;<span style="color:blue;">bool</span>&nbsp;ShouldSerializeValue(&nbsp;<span style="color:blue;">object</span>&nbsp;component&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:blue;">false</span>;
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Gets&nbsp;the&nbsp;current&nbsp;value&nbsp;of&nbsp;the&nbsp;property&nbsp;on&nbsp;a&nbsp;component.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>component<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;component&nbsp;with&nbsp;the&nbsp;property&nbsp;for&nbsp;which&nbsp;to&nbsp;retrieve&nbsp;the&nbsp;value.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;value&nbsp;of&nbsp;a&nbsp;property&nbsp;for&nbsp;a&nbsp;given&nbsp;component.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">override</span>&nbsp;<span style="color:blue;">object</span>&nbsp;GetValue(&nbsp;<span style="color:blue;">object</span>&nbsp;component&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">Tuple</span>&lt;<span style="color:#2b91af;">Type</span>,&nbsp;<span style="color:#2b91af;">Object</span>&gt;&nbsp;typeAndValue&nbsp;=&nbsp;GetTypeAndValue(&nbsp;m_assetProperty,&nbsp;0&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;m_value&nbsp;=&nbsp;typeAndValue.Item2;
&nbsp;&nbsp;&nbsp;&nbsp;m_valueType&nbsp;=&nbsp;typeAndValue.Item1;
 
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;m_value;
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:blue;">private</span>&nbsp;<span style="color:blue;">static</span>&nbsp;<span style="color:#2b91af;">Tuple</span>&lt;<span style="color:#2b91af;">Type</span>,&nbsp;<span style="color:#2b91af;">Object</span>&gt;&nbsp;GetTypeAndValue(&nbsp;<span style="color:#2b91af;">AssetProperty</span>&nbsp;assetProperty,&nbsp;<span style="color:blue;">int</span>&nbsp;level&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">Object</span>&nbsp;theValue;
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">Type</span>&nbsp;valueType;
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:green;">//For&nbsp;each&nbsp;AssetProperty,&nbsp;it&nbsp;has&nbsp;different&nbsp;type&nbsp;and&nbsp;value</span>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:green;">//must&nbsp;deal&nbsp;with&nbsp;it&nbsp;separately</span>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">try</span>
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyBoolean</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyBoolean</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyBoolean</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyBoolean</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;property.Value;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDistance</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyDistance</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDistance</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyDistance</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;property.Value;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDouble</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyDouble</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDouble</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyDouble</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;property.Value;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray2d</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:green;">//Default,&nbsp;it&nbsp;is&nbsp;supported&nbsp;by&nbsp;PropertyGrid&nbsp;to&nbsp;display&nbsp;Double&nbsp;[]</span>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:green;">//Try&nbsp;to&nbsp;convert&nbsp;DoubleArray&nbsp;to&nbsp;Double&nbsp;[]</span>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray2d</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray2d</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray2d</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;GetSystemArrayAsString(&nbsp;property.Value&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray3d</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray3d</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray3d</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray3d</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;GetSystemArrayAsString(&nbsp;property.Value&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray4d</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray4d</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray4d</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleArray4d</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;GetSystemArrayAsString(&nbsp;property.Value&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleMatrix44</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleMatrix44</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleMatrix44</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyDoubleMatrix44</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;GetSystemArrayAsString(&nbsp;property.Value&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyEnum</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyEnum</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyEnum</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyEnum</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;property.Value;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyFloat</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyFloat</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyFloat</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyFloat</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;property.Value;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyInteger</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyInteger</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyInteger</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyInteger</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;property.Value;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyReference</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyReference</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyReference</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyReference</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;<span style="color:#a31515;">&quot;REFERENCE&quot;</span>;&nbsp;<span style="color:green;">//property.Type;</span>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyString</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyString</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyString</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyString</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;property.Value;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">AssetPropertyTime</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyTime</span>&nbsp;property&nbsp;=&nbsp;assetProperty&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyTime</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyTime</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;property.Value;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;valueType&nbsp;=&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">String</span>&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;<span style="color:#a31515;">&quot;Unprocessed&nbsp;asset&nbsp;type:&nbsp;&quot;</span>&nbsp;+&nbsp;assetProperty.GetType().Name;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">if</span>(&nbsp;assetProperty.NumberOfConnectedProperties&nbsp;&gt;&nbsp;0&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">String</span>&nbsp;result&nbsp;=&nbsp;<span style="color:#a31515;">&quot;&quot;</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;result&nbsp;=&nbsp;theValue.ToString();
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">TaskDialog</span>.Show(&nbsp;<span style="color:#a31515;">&quot;Connected&nbsp;properties&nbsp;found&quot;</span>,&nbsp;assetProperty.Name&nbsp;+&nbsp;<span style="color:#a31515;">&quot;:&nbsp;&quot;</span>&nbsp;+&nbsp;assetProperty.NumberOfConnectedProperties&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">IList</span>&lt;<span style="color:#2b91af;">AssetProperty</span>&gt;&nbsp;properties&nbsp;=&nbsp;assetProperty.GetAllConnectedProperties();
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">foreach</span>(&nbsp;<span style="color:#2b91af;">AssetProperty</span>&nbsp;property&nbsp;<span style="color:blue;">in</span>&nbsp;properties&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">if</span>(&nbsp;property&nbsp;<span style="color:blue;">is</span>&nbsp;<span style="color:#2b91af;">Asset</span>&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:green;">//&nbsp;Nested?</span>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">Asset</span>&nbsp;asset&nbsp;=&nbsp;property&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">Asset</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">int</span>&nbsp;size&nbsp;=&nbsp;asset.Size;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">for</span>(&nbsp;<span style="color:blue;">int</span>&nbsp;i&nbsp;=&nbsp;0;&nbsp;i&nbsp;&lt;&nbsp;size;&nbsp;i++&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetProperty</span>&nbsp;subproperty&nbsp;=&nbsp;asset[i];
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">Tuple</span>&lt;<span style="color:#2b91af;">Type</span>,&nbsp;<span style="color:#2b91af;">Object</span>&gt;&nbsp;valueAndType&nbsp;=&nbsp;GetTypeAndValue(&nbsp;subproperty,&nbsp;level&nbsp;+&nbsp;1&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">String</span>&nbsp;indent&nbsp;=&nbsp;<span style="color:#a31515;">&quot;&quot;</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">if</span>(&nbsp;level&nbsp;&gt;&nbsp;0&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">for</span>(&nbsp;<span style="color:blue;">int</span>&nbsp;iLevel&nbsp;=&nbsp;1;&nbsp;iLevel&nbsp;&lt;=&nbsp;level;&nbsp;iLevel++&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;indent&nbsp;+=&nbsp;<span style="color:#a31515;">&quot;&nbsp;&nbsp;&nbsp;&quot;</span>;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;result&nbsp;+=&nbsp;<span style="color:#a31515;">&quot;\n&nbsp;&quot;</span>&nbsp;+&nbsp;indent&nbsp;+&nbsp;<span style="color:#a31515;">&quot;-&nbsp;connected:&nbsp;name:&nbsp;&quot;</span>&nbsp;+&nbsp;subproperty.Name&nbsp;+&nbsp;<span style="color:#a31515;">&quot;&nbsp;|&nbsp;type:&nbsp;&quot;</span>&nbsp;+&nbsp;valueAndType.Item1.Name&nbsp;+
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#a31515;">&quot;&nbsp;|&nbsp;value:&nbsp;&quot;</span>&nbsp;+&nbsp;valueAndType.Item2.ToString();
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
 
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;theValue&nbsp;=&nbsp;result;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">catch</span>
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:blue;">null</span>;
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:#2b91af;">Tuple</span>&lt;<span style="color:#2b91af;">Type</span>,&nbsp;<span style="color:#2b91af;">Object</span>&gt;(&nbsp;valueType,&nbsp;theValue&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Sets&nbsp;the&nbsp;value&nbsp;of&nbsp;the&nbsp;component&nbsp;to&nbsp;a&nbsp;different&nbsp;value.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;For&nbsp;AssetProperty,&nbsp;it&nbsp;is&nbsp;not&nbsp;allowed&nbsp;to&nbsp;set&nbsp;its&nbsp;value,&nbsp;so&nbsp;here&nbsp;just&nbsp;return.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>component<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;component&nbsp;with&nbsp;the&nbsp;property&nbsp;value&nbsp;that&nbsp;is&nbsp;to&nbsp;be&nbsp;set.&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>value<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;new&nbsp;value.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">override</span>&nbsp;<span style="color:blue;">void</span>&nbsp;SetValue(&nbsp;<span style="color:blue;">object</span>&nbsp;component,&nbsp;<span style="color:blue;">object</span>&nbsp;value&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>;
&nbsp;&nbsp;}
&nbsp;&nbsp;<span style="color:blue;">#endregion</span>
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Convert&nbsp;Autodesk.Revit.DB.DoubleArray&nbsp;to&nbsp;Double&nbsp;[].</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;For&nbsp;Double&nbsp;[]&nbsp;is&nbsp;supported&nbsp;by&nbsp;PropertyGrid.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>doubleArray<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">the&nbsp;original&nbsp;Autodesk.Revit.DB.DoubleArray&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;converted&nbsp;Double&nbsp;[]</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">private</span>&nbsp;<span style="color:blue;">static</span>&nbsp;<span style="color:#2b91af;">Double</span>[]&nbsp;GetSystemArray(&nbsp;<span style="color:#2b91af;">DoubleArray</span>&nbsp;doubleArray&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">double</span>[]&nbsp;values&nbsp;=&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:blue;">double</span>[doubleArray.Size];
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">int</span>&nbsp;index&nbsp;=&nbsp;0;
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">foreach</span>(&nbsp;<span style="color:#2b91af;">Double</span>&nbsp;value&nbsp;<span style="color:blue;">in</span>&nbsp;doubleArray&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;values[index++]&nbsp;=&nbsp;value;
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;values;
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:blue;">private</span>&nbsp;<span style="color:blue;">static</span>&nbsp;<span style="color:#2b91af;">String</span>&nbsp;GetSystemArrayAsString(&nbsp;<span style="color:#2b91af;">DoubleArray</span>&nbsp;doubleArray&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">double</span>[]&nbsp;values&nbsp;=&nbsp;GetSystemArray(&nbsp;doubleArray&nbsp;);
 
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">String</span>&nbsp;result&nbsp;=&nbsp;<span style="color:#a31515;">&quot;&quot;</span>;
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">foreach</span>(&nbsp;<span style="color:blue;">double</span>&nbsp;d&nbsp;<span style="color:blue;">in</span>&nbsp;values&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;result&nbsp;+=&nbsp;d;
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;result&nbsp;+=&nbsp;<span style="color:#a31515;">&quot;,&quot;</span>;
&nbsp;&nbsp;&nbsp;&nbsp;}
 
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;result;
&nbsp;&nbsp;}
}
 
<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
<span style="color:gray;">///</span><span style="color:green;">&nbsp;supplies&nbsp;dynamic&nbsp;custom&nbsp;type&nbsp;information&nbsp;for&nbsp;an&nbsp;Asset&nbsp;while&nbsp;it&nbsp;is&nbsp;displayed&nbsp;in&nbsp;PropertyGrid.</span>
<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">class</span>&nbsp;<span style="color:#2b91af;">RenderAppearanceDescriptor</span>&nbsp;:&nbsp;<span style="color:#2b91af;">ICustomTypeDescriptor</span>
{
&nbsp;&nbsp;<span style="color:blue;">#region</span>&nbsp;Fields
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Reference&nbsp;to&nbsp;Asset</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:#2b91af;">Asset</span>&nbsp;m_asset;
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Asset&#39;s&nbsp;property&nbsp;descriptors</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:#2b91af;">PropertyDescriptorCollection</span>&nbsp;m_propertyDescriptors;
&nbsp;&nbsp;<span style="color:blue;">#endregion</span>
 
&nbsp;&nbsp;<span style="color:blue;">#region</span>&nbsp;Constructors
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Initializes&nbsp;Asset&nbsp;object</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>asset<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">an&nbsp;Asset&nbsp;object</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;RenderAppearanceDescriptor(&nbsp;<span style="color:#2b91af;">Asset</span>&nbsp;asset&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;m_asset&nbsp;=&nbsp;asset;
&nbsp;&nbsp;&nbsp;&nbsp;GetAssetProperties();
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:blue;">#endregion</span>
 
&nbsp;&nbsp;<span style="color:blue;">#region</span>&nbsp;Methods
&nbsp;&nbsp;<span style="color:blue;">#region</span>&nbsp;ICustomTypeDescriptor&nbsp;Members
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;a&nbsp;collection&nbsp;of&nbsp;custom&nbsp;attributes&nbsp;for&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">Asset&#39;s&nbsp;attributes</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:#2b91af;">AttributeCollection</span>&nbsp;GetAttributes()
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:#2b91af;">TypeDescriptor</span>.GetAttributes(&nbsp;m_asset,&nbsp;<span style="color:blue;">false</span>&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;the&nbsp;class&nbsp;name&nbsp;of&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">Asset&#39;s&nbsp;class&nbsp;name</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">string</span>&nbsp;GetClassName()
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:#2b91af;">TypeDescriptor</span>.GetClassName(&nbsp;m_asset,&nbsp;<span style="color:blue;">false</span>&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;the&nbsp;name&nbsp;of&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;name&nbsp;of&nbsp;Asset</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">string</span>&nbsp;GetComponentName()
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:#2b91af;">TypeDescriptor</span>.GetComponentName(&nbsp;m_asset,&nbsp;<span style="color:blue;">false</span>&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;a&nbsp;type&nbsp;converter&nbsp;for&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">The&nbsp;converter&nbsp;of&nbsp;the&nbsp;Asset</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:#2b91af;">TypeConverter</span>&nbsp;GetConverter()
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:#2b91af;">TypeDescriptor</span>.GetConverter(&nbsp;m_asset,&nbsp;<span style="color:blue;">false</span>&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;the&nbsp;default&nbsp;event&nbsp;for&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">An&nbsp;EventDescriptor&nbsp;that&nbsp;represents&nbsp;the&nbsp;default&nbsp;event&nbsp;for&nbsp;this&nbsp;object,&nbsp;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;or&nbsp;null&nbsp;if&nbsp;this&nbsp;object&nbsp;does&nbsp;not&nbsp;have&nbsp;events.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:#2b91af;">EventDescriptor</span>&nbsp;GetDefaultEvent()
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:#2b91af;">TypeDescriptor</span>.GetDefaultEvent(&nbsp;m_asset,&nbsp;<span style="color:blue;">false</span>&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;the&nbsp;default&nbsp;property&nbsp;for&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">A&nbsp;PropertyDescriptor&nbsp;that&nbsp;represents&nbsp;the&nbsp;default&nbsp;property&nbsp;for&nbsp;this&nbsp;object,&nbsp;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;or&nbsp;null&nbsp;if&nbsp;this&nbsp;object&nbsp;does&nbsp;not&nbsp;have&nbsp;properties.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:#2b91af;">PropertyDescriptor</span>&nbsp;GetDefaultProperty()
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:#2b91af;">TypeDescriptor</span>.GetDefaultProperty(&nbsp;m_asset,&nbsp;<span style="color:blue;">false</span>&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;an&nbsp;editor&nbsp;of&nbsp;the&nbsp;specified&nbsp;type&nbsp;for&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>editorBaseType<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">A&nbsp;Type&nbsp;that&nbsp;represents&nbsp;the&nbsp;editor&nbsp;for&nbsp;this&nbsp;object.&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">An&nbsp;Object&nbsp;of&nbsp;the&nbsp;specified&nbsp;type&nbsp;that&nbsp;is&nbsp;the&nbsp;editor&nbsp;for&nbsp;this&nbsp;object,&nbsp;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;or&nbsp;null&nbsp;if&nbsp;the&nbsp;editor&nbsp;cannot&nbsp;be&nbsp;found.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">object</span>&nbsp;GetEditor(&nbsp;<span style="color:#2b91af;">Type</span>&nbsp;editorBaseType&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:#2b91af;">TypeDescriptor</span>.GetEditor(&nbsp;m_asset,&nbsp;editorBaseType,&nbsp;<span style="color:blue;">false</span>&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;the&nbsp;events&nbsp;for&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset&nbsp;using&nbsp;the&nbsp;specified&nbsp;attribute&nbsp;array&nbsp;as&nbsp;a&nbsp;filter.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>attributes<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">An&nbsp;array&nbsp;of&nbsp;type&nbsp;Attribute&nbsp;that&nbsp;is&nbsp;used&nbsp;as&nbsp;a&nbsp;filter.&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">An&nbsp;EventDescriptorCollection&nbsp;that&nbsp;represents&nbsp;the&nbsp;filtered&nbsp;events&nbsp;for&nbsp;this&nbsp;Asset&nbsp;instance.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:#2b91af;">EventDescriptorCollection</span>&nbsp;GetEvents(&nbsp;<span style="color:#2b91af;">Attribute</span>[]&nbsp;attributes&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:#2b91af;">TypeDescriptor</span>.GetEvents(&nbsp;m_asset,&nbsp;attributes,&nbsp;<span style="color:blue;">false</span>&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;the&nbsp;events&nbsp;for&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">An&nbsp;EventDescriptorCollection&nbsp;that&nbsp;represents&nbsp;the&nbsp;events&nbsp;for&nbsp;this&nbsp;Asset&nbsp;instance.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:#2b91af;">EventDescriptorCollection</span>&nbsp;GetEvents()
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;<span style="color:#2b91af;">TypeDescriptor</span>.GetEvents(&nbsp;m_asset,&nbsp;<span style="color:blue;">false</span>&nbsp;);
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;the&nbsp;properties&nbsp;for&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset&nbsp;using&nbsp;the&nbsp;attribute&nbsp;array&nbsp;as&nbsp;a&nbsp;filter.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>attributes<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">An&nbsp;array&nbsp;of&nbsp;type&nbsp;Attribute&nbsp;that&nbsp;is&nbsp;used&nbsp;as&nbsp;a&nbsp;filter.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">A&nbsp;PropertyDescriptorCollection&nbsp;that&nbsp;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;represents&nbsp;the&nbsp;filtered&nbsp;properties&nbsp;for&nbsp;this&nbsp;Asset&nbsp;instance.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:#2b91af;">PropertyDescriptorCollection</span>&nbsp;GetProperties(&nbsp;<span style="color:#2b91af;">Attribute</span>[]&nbsp;attributes&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;m_propertyDescriptors;
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;the&nbsp;properties&nbsp;for&nbsp;this&nbsp;instance&nbsp;of&nbsp;Asset.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">A&nbsp;PropertyDescriptorCollection&nbsp;that&nbsp;represents&nbsp;the&nbsp;properties&nbsp;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;for&nbsp;this&nbsp;Asset&nbsp;instance.</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:#2b91af;">PropertyDescriptorCollection</span>&nbsp;GetProperties()
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;m_propertyDescriptors;
&nbsp;&nbsp;}
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Returns&nbsp;an&nbsp;object&nbsp;that&nbsp;contains&nbsp;the&nbsp;property&nbsp;described&nbsp;by&nbsp;the&nbsp;specified&nbsp;property&nbsp;descriptor.</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">param</span><span style="color:gray;">&nbsp;name</span><span style="color:gray;">=</span><span style="color:gray;">&quot;</span>pd<span style="color:gray;">&quot;</span><span style="color:gray;">&gt;</span><span style="color:green;">A&nbsp;PropertyDescriptor&nbsp;that&nbsp;represents&nbsp;the&nbsp;property&nbsp;whose&nbsp;owner&nbsp;is&nbsp;to&nbsp;be&nbsp;found.&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">param</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span><span style="color:green;">Asset&nbsp;object</span><span style="color:gray;">&lt;/</span><span style="color:gray;">returns</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">object</span>&nbsp;GetPropertyOwner(&nbsp;<span style="color:#2b91af;">PropertyDescriptor</span>&nbsp;pd&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>&nbsp;m_asset;
&nbsp;&nbsp;}
&nbsp;&nbsp;<span style="color:blue;">#endregion</span>
 
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;Get&nbsp;Asset&#39;s&nbsp;property&nbsp;descriptors</span>
&nbsp;&nbsp;<span style="color:gray;">///</span><span style="color:green;">&nbsp;</span><span style="color:gray;">&lt;/</span><span style="color:gray;">summary</span><span style="color:gray;">&gt;</span>
&nbsp;&nbsp;<span style="color:blue;">private</span>&nbsp;<span style="color:blue;">void</span>&nbsp;GetAssetProperties()
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">if</span>(&nbsp;<span style="color:blue;">null</span>&nbsp;==&nbsp;m_propertyDescriptors&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m_propertyDescriptors&nbsp;=&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:#2b91af;">PropertyDescriptorCollection</span>(&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:#2b91af;">AssetPropertyPropertyDescriptor</span>[0]&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">else</span>
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">return</span>;
&nbsp;&nbsp;&nbsp;&nbsp;}
 
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:green;">//For&nbsp;each&nbsp;AssetProperty&nbsp;in&nbsp;Asset,&nbsp;create&nbsp;an&nbsp;AssetPropertyPropertyDescriptor.</span>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:green;">//It&nbsp;means&nbsp;that&nbsp;each&nbsp;AssetProperty&nbsp;will&nbsp;be&nbsp;a&nbsp;property&nbsp;of&nbsp;Asset</span>
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">for</span>(&nbsp;<span style="color:blue;">int</span>&nbsp;index&nbsp;=&nbsp;0;&nbsp;index&nbsp;&lt;&nbsp;m_asset.Size;&nbsp;index++&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetProperty</span>&nbsp;assetProperty&nbsp;=&nbsp;m_asset[index];
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">if</span>(&nbsp;<span style="color:blue;">null</span>&nbsp;!=&nbsp;assetProperty&nbsp;)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyPropertyDescriptor</span>&nbsp;assetPropertyPropertyDescriptor&nbsp;=&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:#2b91af;">AssetPropertyPropertyDescriptor</span>(&nbsp;assetProperty&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;m_propertyDescriptors.Add(&nbsp;assetPropertyPropertyDescriptor&nbsp;);
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;&nbsp;&nbsp;}
&nbsp;&nbsp;}
&nbsp;&nbsp;<span style="color:blue;">#endregion</span>
}
 
<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">void</span>&nbsp;ShowMaterialInfo(&nbsp;<span style="color:#2b91af;">Document</span>&nbsp;doc&nbsp;)
{
&nbsp;&nbsp;<span style="color:green;">//&nbsp;Find&nbsp;material</span>
&nbsp;&nbsp;<span style="color:#2b91af;">FilteredElementCollector</span>&nbsp;fec&nbsp;=&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:#2b91af;">FilteredElementCollector</span>(&nbsp;doc&nbsp;);
&nbsp;&nbsp;fec.OfClass(&nbsp;<span style="color:blue;">typeof</span>(&nbsp;<span style="color:#2b91af;">Material</span>&nbsp;)&nbsp;);
 
&nbsp;&nbsp;<span style="color:#2b91af;">String</span>&nbsp;materialName&nbsp;=&nbsp;<span style="color:#a31515;">&quot;Checker&quot;</span>;&nbsp;<span style="color:green;">//&nbsp;&quot;Copper&quot;;//&quot;Prism&nbsp;-&nbsp;Glass&nbsp;-&nbsp;Textured&quot;;&nbsp;//&nbsp;&quot;Parking&nbsp;Stripe&quot;;&nbsp;//&nbsp;&quot;Copper&quot;;</span>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:green;">//&nbsp;&quot;Carpet&nbsp;(1)&quot;;//&nbsp;&quot;Prism&nbsp;-&nbsp;Glass&nbsp;-&nbsp;Textured&quot;;//&nbsp;&quot;Parking&nbsp;Stripe&quot;;&nbsp;//&nbsp;&quot;Prism&nbsp;1&quot;;//&nbsp;&quot;Brick,&nbsp;Common&quot;&nbsp;;//&nbsp;&quot;Acoustic&nbsp;Ceiling&nbsp;Tile&nbsp;24&nbsp;x&nbsp;48&quot;;&nbsp;&nbsp;//&nbsp;&quot;Aluminum&quot;</span>
&nbsp;&nbsp;<span style="color:#2b91af;">Material</span>&nbsp;mat&nbsp;=&nbsp;fec.Cast&lt;<span style="color:#2b91af;">Material</span>&gt;().First&lt;<span style="color:#2b91af;">Material</span>&gt;(&nbsp;m&nbsp;=&gt;&nbsp;m.Name&nbsp;==&nbsp;materialName&nbsp;);
 
 
 
&nbsp;&nbsp;<span style="color:#2b91af;">ElementId</span>&nbsp;appearanceAssetId&nbsp;=&nbsp;mat.AppearanceAssetId;
 
&nbsp;&nbsp;<span style="color:#2b91af;">AppearanceAssetElement</span>&nbsp;appearanceAsset&nbsp;=&nbsp;doc.GetElement(&nbsp;appearanceAssetId&nbsp;)&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AppearanceAssetElement</span>;
 
&nbsp;&nbsp;<span style="color:#2b91af;">Asset</span>&nbsp;renderingAsset&nbsp;=&nbsp;appearanceAsset.GetRenderingAsset();
 
 
 
&nbsp;&nbsp;<span style="color:#2b91af;">RenderAppearanceDescriptor</span>&nbsp;rad
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;=&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:#2b91af;">RenderAppearanceDescriptor</span>(&nbsp;renderingAsset&nbsp;);
 
 
&nbsp;&nbsp;<span style="color:#2b91af;">PropertyDescriptorCollection</span>&nbsp;collection&nbsp;=&nbsp;rad.GetProperties();
 
&nbsp;&nbsp;<span style="color:#2b91af;">TaskDialog</span>.Show(&nbsp;<span style="color:#a31515;">&quot;Total&nbsp;properties&quot;</span>,&nbsp;<span style="color:#a31515;">&quot;Properties&nbsp;found:&nbsp;&quot;</span>&nbsp;+&nbsp;collection.Count&nbsp;);
&nbsp;&nbsp;<span style="color:green;">//</span>
 
&nbsp;&nbsp;<span style="color:blue;">string</span>&nbsp;s&nbsp;=&nbsp;<span style="color:#a31515;">&quot;:&nbsp;Material&nbsp;Asset&nbsp;Properties&quot;</span>;
 
&nbsp;&nbsp;<span style="color:#2b91af;">TaskDialog</span>&nbsp;dlg&nbsp;=&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:#2b91af;">TaskDialog</span>(&nbsp;s&nbsp;);
 
&nbsp;&nbsp;dlg.MainInstruction&nbsp;=&nbsp;mat.Name&nbsp;+&nbsp;s;
 
&nbsp;&nbsp;s&nbsp;=&nbsp;<span style="color:blue;">string</span>.Empty;
 
&nbsp;&nbsp;<span style="color:#2b91af;">List</span>&lt;<span style="color:#2b91af;">PropertyDescriptor</span>&gt;&nbsp;orderableCollection&nbsp;=&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:#2b91af;">List</span>&lt;<span style="color:#2b91af;">PropertyDescriptor</span>&gt;(&nbsp;collection.Count&nbsp;);
 
&nbsp;&nbsp;<span style="color:blue;">foreach</span>(&nbsp;<span style="color:#2b91af;">PropertyDescriptor</span>&nbsp;descr&nbsp;<span style="color:blue;">in</span>&nbsp;collection&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;orderableCollection.Add(&nbsp;descr&nbsp;);
&nbsp;&nbsp;}
 
 
 
&nbsp;&nbsp;<span style="color:blue;">foreach</span>(&nbsp;<span style="color:#2b91af;">AssetPropertyPropertyDescriptor</span>&nbsp;descr&nbsp;<span style="color:blue;">in</span>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;orderableCollection.OrderBy&lt;<span style="color:#2b91af;">PropertyDescriptor</span>,&nbsp;<span style="color:#2b91af;">String</span>&gt;(&nbsp;pd&nbsp;=&gt;&nbsp;pd.Name&nbsp;).Cast&lt;<span style="color:#2b91af;">AssetPropertyPropertyDescriptor</span>&gt;()&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:blue;">object</span>&nbsp;value&nbsp;=&nbsp;descr.GetValue(&nbsp;rad&nbsp;);
 
&nbsp;&nbsp;&nbsp;&nbsp;s&nbsp;+=&nbsp;<span style="color:#a31515;">&quot;\nname:&nbsp;&quot;</span>&nbsp;+&nbsp;descr.Name
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+&nbsp;<span style="color:#a31515;">&quot;&nbsp;|&nbsp;type:&nbsp;&quot;</span>&nbsp;+&nbsp;descr.PropertyType.Name
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;+&nbsp;<span style="color:#a31515;">&quot;&nbsp;|&nbsp;value:&nbsp;&quot;</span>&nbsp;+&nbsp;value;
&nbsp;&nbsp;}
&nbsp;&nbsp;dlg.MainContent&nbsp;=&nbsp;s;
&nbsp;&nbsp;dlg.Show();
 
 
}
 
<span style="color:blue;">public</span>&nbsp;<span style="color:blue;">void</span>&nbsp;ListAllAssets(<span style="color:#2b91af;">UIApplication</span>&nbsp;uiapp)
{
&nbsp;&nbsp;<span style="color:#2b91af;">AssetSet</span>&nbsp;assets&nbsp;=&nbsp;uiapp.Application.get_Assets(&nbsp;<span style="color:#2b91af;">AssetType</span>.Appearance&nbsp;);
 
&nbsp;&nbsp;<span style="color:#2b91af;">TaskDialog</span>&nbsp;dlg&nbsp;=&nbsp;<span style="color:blue;">new</span>&nbsp;<span style="color:#2b91af;">TaskDialog</span>(&nbsp;<span style="color:#a31515;">&quot;Assets&quot;</span>&nbsp;);
 
&nbsp;&nbsp;<span style="color:#2b91af;">String</span>&nbsp;assetLabel&nbsp;=&nbsp;<span style="color:#a31515;">&quot;&quot;</span>;
 
&nbsp;&nbsp;<span style="color:blue;">foreach</span>(&nbsp;<span style="color:#2b91af;">Asset</span>&nbsp;asset&nbsp;<span style="color:blue;">in</span>&nbsp;assets&nbsp;)
&nbsp;&nbsp;{
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">String</span>&nbsp;libraryName&nbsp;=&nbsp;asset.LibraryName;
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyString</span>&nbsp;uiname&nbsp;=&nbsp;asset[<span style="color:#a31515;">&quot;UIName&quot;</span>]&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyString</span>;
&nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#2b91af;">AssetPropertyString</span>&nbsp;baseSchema&nbsp;=&nbsp;asset[<span style="color:#a31515;">&quot;BaseSchema&quot;</span>]&nbsp;<span style="color:blue;">as</span>&nbsp;<span style="color:#2b91af;">AssetPropertyString</span>;
 
&nbsp;&nbsp;&nbsp;&nbsp;assetLabel&nbsp;+=&nbsp;libraryName&nbsp;+&nbsp;<span style="color:#a31515;">&quot;&nbsp;|&nbsp;&quot;</span>&nbsp;+&nbsp;uiname.Value&nbsp;+&nbsp;<span style="color:#a31515;">&quot;&nbsp;|&nbsp;&quot;</span>&nbsp;+&nbsp;baseSchema.Value;
&nbsp;&nbsp;&nbsp;&nbsp;assetLabel&nbsp;+=&nbsp;<span style="color:#a31515;">&quot;\n&quot;</span>;
&nbsp;&nbsp;}
 
&nbsp;&nbsp;dlg.MainInstruction&nbsp;=&nbsp;assetLabel;
 
&nbsp;&nbsp;dlg.Show();
}
<span style="color:blue;">#endregion</span>&nbsp;<span style="color:green;">//&nbsp;List&nbsp;Material&nbsp;Asset&nbsp;Sub-Texture</span>
</pre>

I hope you are glad to hear that no issues were detected and that you can make good use of this handy sample code for further explorations.

Many thanks to Scott Conover for putting it together!

I wish you a happy and fruitful week!