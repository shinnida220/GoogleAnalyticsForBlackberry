GoogleAnalyticsForBlackberry
============================

This is a very simple, straight to the wrapper for Google Analytics on the BB OS, supports OS 5 to 7.x

# This approach uses Measurement Protocol Reference


Sample Usage:
=================

Import the package..
import me.folorunsho.GoogleAanalytics.*;


Use the getInstance Class to setup your identity..
 GATracker.getInstance("Your Google Analytics Key Here", "Your App Name Here");

Call the addToQueue to notify GA of your presence..
 GATracker.addToQueue(new ScreenViewRequest("Screen Name here"));




# Please read below:
	Measurement Protocol / SDK / User ID Policy
	
	All applications using the Measurement Protocol / SDKs / User ID must adhere to the following policies:
	
	You must make sure you have the full rights to use this service, to upload data, 
		and to use it with your Google Analytics account.
	You will give your end users proper notice about the implementations and features 
		of Google Analytics you use (e.g. notice about what data you will collect via Google Analytics, 
		and whether this data can be connected to other data you have about the end user). 
		You will either get consent from your end users, or provide them with the opportunity 
		to opt-out from the implementations and features you use.
	You will not upload any data that allows Google to personally identify an individual 
		(such as certain names, social security numbers, email addresses, or any similar data), 
		or data that permanently identifies a particular device 
		(such as a mobile phone’s unique device identifier if such an identifier cannot be reset), 
		even in hashed form.
	If you upload any data that allows Google to personally identify an individual, 
	your Google Analytics account can be terminated, and you may lose your Google Analytics data.

https://developers.google.com/analytics/devguides/collection/protocol/policy
