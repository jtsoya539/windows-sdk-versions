---
layout: default
---
{::options parse_block_html="true" /}

This is an overview of all Windows 10 and Windows 11 versions and their corresponding identifiers for Windows developers. Anyone is welcome to open [an issue or pull request](https://github.com/jtsoya539/windows-sdk-versions). Happy developing!
{: #intro}

<div id="compact-toc">
* TOC
{:toc}
</div>

<div id="main-table" class="table-responsive">
<table class="full-width">
  <tr>
    <th style="min-width: 6.5em">Version</th>
    <th>Desktop OS Build</th>
    <th>Mobile OS Build</th>
    <th>Release version / name</th>
    <th>SDK version</th>
    <th>Mobile Emulator version</th>
    <th>Release date (GA)</th>
  </tr>
  <tr>
    <td rowspan="6">
      <b><a href="#">Windows 11</a></b>
    </td>
    <td>28000.*</td>
    <td rowspan="6">n/a</td>
    <td><code>26H1</code></td>
    <td>10.0.28000.*</td>
    <td rowspan="6">n/a</td>
    <td>2025</td>
  </tr>
  <tr>
    <td>26200.*</td>
    <td><code>25H2</code></td>
    <td>-</td>
    <td>2025</td>
  </tr>
  <tr>
    <td>26100.*</td>
    <td><code>24H2</code></td>
    <td>10.0.26100.*</td>
    <td>2024</td>
  </tr>
  <tr>
    <td>22631.*</td>
    <td><code>23H2</code></td>
    <td>-</td>
    <td>2023</td>
  </tr>
  <tr>
    <td>22621.*</td>
    <td><code>22H2</code></td>
    <td>10.0.22621.*</td>
    <td>2022</td>
  </tr>
  <tr>
    <td>22000.*</td>
    <td><code>21H2</code> RTM</td>
    <td>10.0.22000.*</td>
    <td>2022</td>
  </tr>
  <tr>
    <td rowspan="16">
      <b><a href="#">Windows 10</a></b>
    </td>
    <td>19045.*
      <sup id="fnref:1"><a href="#fn:1" class="footnote">1</a></sup>
    </td>
    <td>-</td>
    <td><code>22H2</code> 2022 Update</td>
    <td>-</td>
    <td>-</td>
    <td>Sept/Oct 2022 (GA Oct 18, 2022)</td>
  </tr>
  <tr>
    <td>19044.*</td>
    <td>-</td>
    <td><code>21H2</code> November 2021 Update</td>
    <td>-</td>
    <td>-</td>
    <td>Nov 16, 2021</td>
  </tr>
  <tr>
    <td>19043.*</td>
    <td>-</td>
    <td><code>21H1</code> May 2021 Update</td>
    <td>-</td>
    <td>-</td>
    <td>May 18, 2021</td>
  </tr>
  <tr>
    <td>19042.*</td>
    <td>-</td>
    <td><code>20H2</code> October 2020 Update</td>
    <td>-</td>
    <td>-</td>
    <td>Oct 20, 2020</td>
  </tr>
  <tr>
    <td>19041.*</td>
    <td>-</td>
    <td><code>2004</code> May 2020 Update</td>
    <td>10.0.19041.0</td>
    <td>-</td>
    <td>May 27, 2020</td>
  </tr>
  <tr>
    <td>18363.*</td>
    <td>-</td>
    <td><code>1909</code> November 2019 Update</td>
    <td>-</td>
    <td>-</td>
    <td>Nov 2019</td>
  </tr>
  <tr>
    <td>18362.*</td>
    <td>-</td>
    <td><code>1903</code> May 2019 Update</td>
    <td>10.0.18362.1</td>
    <td>-</td>
    <td>May 2019</td>
  </tr>
  <tr>
    <td>17763.*</td>
    <td>-</td>
    <td><code>1809</code> October 2018 Update (Redstone 5)</td>
    <td>10.0.17763.0</td>
    <td>-</td>
    <td>Oct 2, 2018</td>
  </tr>
  <tr>
    <td>17134.*</td>
    <td>-</td>
    <td><code>1803</code> April 2018 Update (Redstone 4)</td>
    <td>10.0.17134.12</td>
    <td>-</td>
    <td>Apr 30, 2018</td>
  </tr>
  <tr>
    <td>16299.*</td>
    <td>15254.*
      <sup id="fnref:2"><a href="#fn:2" class="footnote">2</a></sup>
    </td>
    <td><code>1709</code> Fall Creators Update (Redstone 3)</td>
    <td>10.0.16299.91</td>
    <td>10.0.15254.1</td>
    <td>Oct 17, 2017</td>
  </tr>
  <tr class="table-notes">
    <td colspan="6">
      <ul>
        <li><b>Key milestone</b> UWP can use <code>.NET Standard 2.0</code> when MinVersion ≥ Build <code>16299</code>.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>15063.*</td>
    <td>15063.*</td>
    <td><code>1703</code> Creators Update (Redstone 2)</td>
    <td>10.0.15063.468</td>
    <td>10.0.15254.1</td>
    <td>Apr 2017</td>
  </tr>
  <tr>
    <td>14393.*</td>
    <td>14393.*</td>
    <td><code>1607</code> Anniversary Update (Redstone 1)</td>
    <td>10.0.14393.795</td>
    <td>10.0.14393.0</td>
    <td>Aug 2, 2016</td>
  </tr>
  <tr>
    <td>10586.*</td>
    <td>10586.*
      <sup id="fnref:3"><a href="#fn:3" class="footnote">3</a></sup>
    </td>
    <td><code>1511</code> November Update (Threshold 2)</td>
    <td>10.0.10586.212</td>
    <td>10.0.10586.11</td>
    <td>Nov 2015</td>
  </tr>
  <tr>
    <td>10240.*
      <sup id="fnref:4"><a href="#fn:4" class="footnote">4</a></sup>
    </td>
    <td>10240.*</td>
    <td><code>1507</code> RTM (Threshold 1)</td>
    <td>10.0.10240</td>
    <td>10.0.10240</td>
    <td>July 29, 2015</td>
  </tr>
  <tr class="table-notes">
    <td colspan="6">
      <ul>
        <li><code>.NET Standard</code> <b>not</b> fully supported (UWP era: early <code>.NET Standard 1.x</code> support limited).</li>
      </ul>
    </td>
  </tr>
</table>
</div>

## Definitions

#### Target settings

<div class="table-responsive">
<table class="full-width">
  <tr>
    <th>Setting</th>
    <th class="nowrap">Project file setting</th>
    <th>Definition</th>
  </tr>
  <tr>
    <td>Target Version</td>
    <td class="nowrap"><code>TargetPlatformVersion</code></td>
    <td>The version of Windows 10 or Windows 11 that your app is intended to run on. This sets the <code>TargetPlatformVersion</code> setting in your project file. It also determines the value of the <code>TargetDeviceFamily@MaxVersionTested</code> attribute in your app package manifest.</td>
  </tr>
  <tr>
    <td>Minimum Version</td>
    <td class="nowrap"><code>TargetPlatformMinVersion</code></td>
    <td>The earliest version of Windows 10 or Windows 11 needed to support the basic functions of your app. This sets the <code>TargetPlatformMinVersion</code> setting in your project file. It also determines the value of the <code>TargetDeviceFamily@MinVersion</code> attribute in your app package manifest.</td>
  </tr>
</table>
</div>

## Footnotes

<div class="footnotes">
  <ol>
    <li id="fn:1">
      <p>Final Windows 10 feature update. <a href="#fnref:1" class="reversefootnote">↩</a></p>
    </li>
    <li id="fn:2">
      <p>Final Windows 10 Mobile feature update. <a href="#fnref:2" class="reversefootnote">↩</a></p>
    </li>
    <li id="fn:3">
      <p>Initial Windows 10 Mobile release. <a href="#fnref:3" class="reversefootnote">↩</a></p>
    </li>
    <li id="fn:4">
      <p>Initial Windows 10 release. <a href="#fnref:4" class="reversefootnote">↩</a></p>
    </li>
  </ol>
</div>

## See also

* [https://learn.microsoft.com/en-us/windows/uwp/whats-new/windows-10-build-19041]()
* [https://developer.microsoft.com/en-us/windows/downloads/sdk-archive/]()
* [https://developer.microsoft.com/en-us/windows/downloads/sdk-archive/index-legacy]()
* [https://learn.microsoft.com/en-us/windows/release-health/windows11-release-information#windows-11-release-history]()
* [https://learn.microsoft.com/en-us/windows/release-health/release-information#windows-10-release-history]()
* [https://devblogs.microsoft.com/dotnet/announcing-uwp-support-for-net-standard-2-0/]()
* [https://gal.vin/posts/old/a-quick-word-on-windows-10-names-builds-and-versions/]()
* [https://learn.microsoft.com/en-us/windows/uwp/updates-and-versions/choose-a-uwp-version]()
* [https://portablelibraryprofiles.stephencleary.com/]()