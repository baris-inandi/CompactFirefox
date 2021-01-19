### **Install CompactFirefox:**



First, you need to enable [userChrome](https://www.userchrome.org/) to use a custom theme in Firefox:

* Type ```about:config``` in Firefox search bar to go to advanced settings and accept the risk to continue 
* Search for ```toolkit.legacyUserProfileCustomizations.stylesheets``` in the search bar above.
* Double-click on ```toolkit.legacyUserProfileCustomizations.stylesheets``` to change the value from ```false``` to ```true```

Install the css file:

* Type ```about:profiles``` in Firefox search bar 
* Click on ```Open Folder``` next to the ```root folder``` section under your default profile. 
* In the opened window, create a new folder called ```chrome```.
* Download userChrome.css from [here](https://raw.githubusercontent.com/baris-inandi/CompactFirefox/main/userChrome.css) and move it into the chrome folder you created. 

Now restart Firefox and you have CompactFirefox installed!