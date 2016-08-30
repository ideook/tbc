<head>
<title>The Building Coder</title>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
<link rel="stylesheet" type="text/css" href="3dwc.css"/>
<script src="https://cdn.rawgit.com/google/code-prettify/master/loader/run_prettify.js?autoload=true" defer="defer"></script>
</head>

<!---

12104801 [Revit 2016 SDK Macro Samples Obsolete]
http://forums.autodesk.com/t5/revit-api/revit-2016-sdk-macro-samples-obsolete/m-p/6518413

https://github.com/jeremytammik/Revit_Macro_Samples
http://thebuildingcoder.typepad.com/blog/2016/04/whats-new-in-the-revit-2017-api.html#comment-2862033662

2013:
    C:\Users\tammikj\AppData\Local\Temp\{6C6A5DA5-CCB4-41B8-9D36-5D69BB2D798A}\Revit\DocHookups6200\32510532416\MacroCSharpSamples\Source
  /v/C/Users/tammikj/AppData/Local/Temp/{6C6A5DA5-CCB4-41B8-9D36-5D69BB2D798A}/Revit/DocHookups6200/32510532416

2017:
    C:\Users\tammikj\AppData\Local\Temp\{6C6A5DA5-CCB4-41B8-9D36-5D69BB2D798A}\Revit\DocHookups6200\32867228480\MacroCSharpSamples\Source\MacroCSharpSamples\CapitalizeText\CapitalizeText.cs
  /v/C/Users/tammikj/AppData/Local/Temp/{6C6A5DA5-CCB4-41B8-9D36-5D69BB2D798A}/Revit/DocHookups6200/32867228480

https://github.com/jeremytammik/Revit_Macro_Samples/compare/2013.0.0.1...2017.0.0.0

Revit Macro Samples Migrated to Revit 2017 #revitapi #3dwebcoder @AutodeskRevit @AutodeskForge #aec #bim

I recently received requests for a migration of the macro samples provided in the <code>Revit_Macro_Samples.rvt</code> project. The version included in the Revit 2017 SDK miraculously is still based on Revit 2013 pre-release version, according to the update message displayed when opening it, and the macros cannot be executed successfully due to a number small Revit API enhancements made in the intervening years
&ndash; Problem
&ndash; Solution &ndash; Sam comes to the rescue
&ndash; See the Diffs on GitHub...

-->

### Revit Macro Samples Migrated to Revit 2017

I recently received several requests for a migration of the macro samples provided in the `Revit_Macro_Samples.rvt` project.

The project included in the Revit 2017 SDK miraculously is still based on Revit 2013 pre-release version, according to the update message displayed when opening it:

<center>
<img src="img/Revit_Macro_Samples_upgrade.png" alt="Revit_Macro_Samples.rvt upgrade message" width="476">
</center>

Unfortunately, after the update process, the macro samples included in the project still cannot be executed successfully due to a number small enhancements made in the intervening years to some of the Revit API function calls and signatures.

- [Problem](#2)
- [Solution &ndash; Sam comes to the rescue](#3)
- [See the Diffs on GitHub](#4)


#### <a name="2"></a>Problem

It started off with the following question in
the [Revit API discussion forum](http://forums.autodesk.com/t5/revit-api/bd-p/160) thread
on [Revit 2016 SDK macro samples obsolete](http://forums.autodesk.com/t5/revit-api/revit-2016-sdk-macro-samples-obsolete/m-p/6518413):

**Question:** In reviewing the SDK documentation and various web-based Autodesk help resources, I have yet to find a resolution to this issue. The sample Revit project located in the Revit 2016 SDK 'Macro Samples\Revit_Macro_Samples.rvt' project appears to be a Revit 2013 project. After opening and upgrading the document for use in Revit 2016, I attempted to run a macro. The macro manager shows that there are problems with the macros:

<center>
<img src="img/macro-manager.png" alt="Macro manager problems" width="476">
</center>

Upon editing and attempting to build, [debug output indicates many critical errors, cf. build.txt](zip/macro_build.txt), which appear to result from various class methods that have been deprecated somewhere between Revit 2013 and Revit 2016.
 
Is there a functional macro sample Revit project available somewhere? Am I approaching this incorrectly, somehow? The Autodesk help makes multiple mentions of the necessity to upgrade, and sometimes manually edit the macros so that they will function. However, implementing the deprecated methods according to the 2016 API would require significant changes, time, and effort.
 
Is it better to ignore this sample document and use some other web resources for learning the foundations of Revit macro creation? Are there good resources for Python-based macro development? It appears that newly created Python macros are automagically populated with sample macros that can be successfully built. However, creation of new C# and VB.Net do NOT offer similar buildable samples.
 
I'm incredibly confused by the SDK and various documentation inconsistencies, and various web searches do not offer any solutions. Thanks in advance for any insights.

**Answer:** Thank you for your report and very sorry about your confusion.
 
I hope that the material for [getting started with the Revit API](http://thebuildingcoder.typepad.com/blog/about-the-author.html#2) in its non-macro incarnation is a bit clearer.
 
The macro environment should be simpler to use. I am sorry to hear that the samples are broken, though.
 
I checked, and we do indeed have an existing change request number **REVIT-93253** *SDK macro samples cause build errors due to obsolete API* for this issue.
 
I hope this trouble getting started with the Revit macros does not put you off and that you find a good, fruitful, productive and fun way forward with no further frustrations.

#### <a name="3"></a>Solution &ndash; Sam Comes to the Rescue

Happily, the issue has now been resolved by the valiant Samer Najjar
in [his comment](http://thebuildingcoder.typepad.com/blog/2016/04/whats-new-in-the-revit-2017-api.html#comment-2862033662)
on [What's New in the Revit 2017 API](http://thebuildingcoder.typepad.com/blog/2016/04/whats-new-in-the-revit-2017-api.html):

> I don't know if this is the right place to share this but since it's the most responsive blog about the subject (thanks to you) I thought I'd give it a go here.

> I've noticed that the macro demonstration document `Revit_Macro_Samples.rvt` located in Revit SDK macro samples folder is way out dated (its actually still in 2013 format), and I don't know if anyone have already did an upgrade on it so I took the liberty of doing that by eliminating all the errors that prevented the code form compiling, this might be useful for new comers (like me) as a start point for learning the magic of Revit API!

> Now just to be clear, I did not optimise the code to make the best use of the new API features, all I did is going through the errors, fixing them one by one and trying to add/change the least amount of code, so there might be some sluggish bits of code that could obviously be made better, but hey, let the never lazy cast the first stone!
I'm not confident of doing the same for the other macro sample documents (MEP and Family macro samples) as I haven't tinkered with these environments much during my API play time.

> You can find the [upgraded project file on Google drive](https://drive.google.com/file/d/0B5aGWWYfFSEzMWpUUXgtUnFHXzg).

> All macros tested and seem to work fine.

Ever so many thanks to Sam for his migration work, repairing all the issues, and sharing the updated version!


#### <a name="4"></a>See the Diffs on GitHub

In order to easily display the migration modification applied by Sam, I created
the [Revit_Macro_Samples GitHub repository](https://github.com/jeremytammik/Revit_Macro_Samples).

I initially populated it with the C# source code of the original Revit 2013 pre-release version of the macros provided in the Revit 2017 SDK.

I did so by copying all the files from the temporary folder created when editing them in SharpDevelop into the local clone of the repo:

> C:\Users\tammikj\AppData\Local\Temp\{6C6A5DA5-CCB4-41B8-9D36-5D69BB2D798A}\Revit\DocHookups6200\32510532416\MacroCSharpSamples

I created the [release 2013.0.0.1](https://github.com/jeremytammik/Revit_Macro_Samples/releases/tag/2013.0.0.1) to tag that version as the starting point.

Next, I opened the macros in Sam's updated project in a similar fashion, and copied them over the original version; they were located in another temporary SharpDevelop folder:

> C:\Users\tammikj\AppData\Local\Temp\{6C6A5DA5-CCB4-41B8-9D36-5D69BB2D798A}\Revit\DocHookups6200\32867228480\MacroCSharpSamples

That version is tagged as [release 2017.0.0.0](https://github.com/jeremytammik/Revit_Macro_Samples/releases/tag/2017.0.0.0).

You can view the differences by using the GitHub functionality 
to [compare changes 2013.0.0.1...2017.0.0.0](https://github.com/jeremytammik/Revit_Macro_Samples/compare/2013.0.0.1...2017.0.0.0).

I stored a copy of
Sam's [upgraded project file Revit_Macro_Samples_2017.rvt](https://github.com/jeremytammik/Revit_Macro_Samples/blob/master/rvt/Revit_Macro_Samples_2017.rvt) in the GitHub repo as well, to enable you to open it in Revit right away.

I hope this helps, and many thanks once again to Sam for his helpful work!