Shodan Adaptive Response Action

This app provides an adaptive response action that performs a lookup on an IP Address against the Shodan API.  The results are parsed and stored in an index of your choice allowing you to create an ongoing repository of Open Source Intelligence data.

The API Reference is located at https://developer.shodan.io/api

The API you can query is: IP

Steps to install
Install Splunk CIM Add On - https://splunkbase.splunk.com/app/1621/
Download from Splunkbase 
Create a new index if need be. In my examples I created a new index called osint_data
Install the App
After installation go to https://your.splunk.address/en-GB/app/TA-sans_isc/configuration
If you have a proxy configure it under the proxy settings
If you want to change logging settings click logging
Click Add-On Settings - Specify the index name that you created before