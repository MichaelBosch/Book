# Reports

The reports which come out of the box provide a wide variety of information regarding your Sitecore installation.

We've built quite a few reports, many similar to the [Advanced System Report][1] (ASR) module.

### Running a Report

The custom reports can be found by navigating to *Sitecore -> Reporting Tools -> PowerShell Reports*.

![Reports](images/screenshots/reports/reports.png)

As an example, let's run the Unused media items report.

![Unused Media Items](images/screenshots/reports/reports-unusedmedia.png)

Once the report completes, the results appear in a report window.

![Unused Media Items Output](images/screenshots/reports/reports-output.png)

### Reports in SPE like ASR

While SPE contains many reports, they don't match identical to ASR reports. We've done our best to build those that seem most relevant or likely to be used. If you find a report in ASR that you would like to exist in SPE please submit a request.

| **SPE Report** | **ASR Report** |
| -- | -- |
| | Active Aliases |
| | Aliases |
| | Audit |
| Broken Links<sup>2</sup> | Broken Links |
| | Broken Links in publishable items |
| | Item History |
| | Items with Invalid Names |
| Items with security for an account<sup>2</sup> | Items with Security for an account |
| | Items with Tokens in Fields |
| | Links |
| Locked Items<sup>2</sup> | Locked Items |
| | Logged errors |
| Logged in Session Manager<sup>5</sup> | Logged in Users |
| Limit number of versions<sup>4</sup> | Multiple versions |
| | My Owned Items |
| Media items last updated before date<sup>3</sup> | Not recently modified |
| Media items not used by content items<sup>3</sup> | Orphaned media assets report |
| | Owned items |
| | Recent Workflow History |
| Media items last updated after date<sup>3</sup> | Recently Modified |
| | Regex Item Searcher |
| | Renderings |
| Index Viewer<sup>5</sup> | - |
| Rules based report<sup>5</sup> | - |
| Task Manager report<sup>5</sup> | - |

Check the reports in SPE under these sections to see the full list.

* <sup>1</sup> Configuration Audit report
* <sup>2</sup> Content Audit report
* <sup>3</sup> Media Audit report
* <sup>4</sup> Solution Audit report
* <sup>5</sup> Toolbox

**Note:** Examples included are in the following modules
* Content Reports

[1]: https://marketplace.sitecore.net/en/Modules/A/Advanced_System_Reporter.aspx