ADMSandbox
==========
This provides a Sample implementation of ADM.

To push a message you need the following:
Your server needs an auth token from amazon. Your service must provide a client id, client secret, and device registration id.

Your app must be authorized under a security profile by creating an API key. 
The api key is associated with the security profile and generated based on the APK's or keystore's md5 and package name. 

The device will generate a registration id based on the API key that will map back to the original auth. 
