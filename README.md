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
You need to install this, otherwise the "Visit" button on the "Images" tab will give you a 404 error message when you click on it. This is due to Google's redirect tracking parameters being removed when you use this list. Without tracking parameters, Google prevents you from using the visit button. Fortunately, you can create a workaround with this extension. It goes directly to the requested URL and completely eliminates Google's redirect links.

Translated with www.DeepL.com/Translator (free version)

The 404 error meassage: ```404. That’s an error. The requested URL /url was not found on this server. That’s all we know.```
