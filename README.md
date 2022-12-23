# Enhanced-URL-Tracking-Filter
Enhanced tracking parameters remover for AdGuard. Removes tracking parameters for Google and Amazon that are not removed if you use only the official list. Link for the official list: https://raw.githubusercontent.com/AdguardTeam/FiltersRegistry/master/filters/filter_17_TrackParam/filter.txt 
* [Installation](#installation)


<a id="installation"></a>
## Installation
### 1. Install the AdGuard extension 
```
https://github.com/AdguardTeam/AdguardBrowserExtension#installation
```
### 2. Click on 
```settings``` > ```Filters``` > ```add custom filter``` > ```enter the url below``` > ```subscribe``` > ```Stealth Mode``` > ```enable "Remove tracking parameters"```
```
https://raw.githubusercontent.com/MartinLoerchdelaRosa/Enhanced-URL-Tracking-Filter/main/Enhanced-URL-Tracking-Filter.txt
```
### 3. Install Don't track me Google
```
https://github.com/Rob--W/dont-track-me-google
```
You need to install this, otherwise the visit button on the images tab would give you a 404 error meassage when clicking on it. This is caused due to the remvoed tracking parameters of Google´s redirect tracking url when you are using this list. Without tracking parameters Google prevents you from using the visit button. Fortunately you can do a workaround with this extension. It goes directly to the requested url and completly get´s rid of google´s redirect links. 

The 404 eroor meassage: ```404. That’s an error. The requested URL /url was not found on this server. That’s all we know.```
