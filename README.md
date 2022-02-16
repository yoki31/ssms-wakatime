# WakaTime for SQL Server Management Studio

Metrics, insights, and time tracking automatically generated from your programming activity.

## Installation

1. Download the latest release <https://github.com/gandarez/ssms-wakatime/releases/latest>.

2. Unzip the content.

3. Run `AddPackage.bat` to add WakaTime extension into registry white list.

4. Copy the folder `WakaTime.v18` to the desired installation folder:
    * `C:\Program Files (x86)\Microsoft SQL Server Management Studio 18\Common7\IDE\Extensions\`
    * Or, for SSMS versions before `v18` copy the folder `WakaTime` to the desired installation folder(s):
        * v2012 - `C:\Program Files (x86)\Microsoft SQL Server\110\Tools\Binn\ManagementStudio\Extensions`
        * v2014 - `C:\Program Files (x86)\Microsoft SQL Server\120\Tools\Binn\ManagementStudio\Extensions`
        * v2016 - `C:\Program Files (x86)\Microsoft SQL Server\130\Tools\Binn\ManagementStudio\Extensions`
        * v17 - `C:\Program Files (x86)\Microsoft SQL Server\140\Tools\Binn\ManagementStudio\Extensions`

5. Enter your [api key](https://wakatime.com/settings#apikey), then press `enter`.

6. Use SSMS and your coding activity will be displayed on your [WakaTime dashboard](https://wakatime.com).

## Usage

Visit <https://wakatime.com> to see your coding activity.

![Project Overview](https://wakatime.com/static/img/ScreenShots/Screen-Shot-2016-03-21.png)

## Supported SQL Server Management Studio Editions

* SQL Server Management Studio 2012 (build number 11.0.x.x)
* SQL Server Management Studio 2014 (build number 12.0.x.x)
* SQL Server Management Studio 2016 (build number 13.0.x.x)
* SQL Server Management Studio 17 (build number 14.0.x.x)
* SQL Server Management Studio 18 (build number 15.0.x.x)

## Troubleshooting

If the extension was blocked, try running as administrator.

```xml
<description>Appid denied the loading of package</description>
<guid>{52D9C3FF-C893-408E-95E4-D7484EC7FA47}</guid>
```
