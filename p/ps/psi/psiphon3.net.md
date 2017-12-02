> *The following text is extracted and transformed from the psiphon3.net privacy policy that was archived on 2017-12-02. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20171202103116id_/http%3A//www.psiphon3.net/en/privacy.html) for the most accurate reproduction.*

# Psiphon | Privacy Policy

Psiphon is committed to protecting the privacy interests of its customers, end users, distributors and suppliers. This privacy policy is intended to provide you with general information on how your personal information may be used. Psiphon is a Canadian corporation with its head office located in Ontario, and our privacy policy has been developed to reflect Canadian and Ontario privacy laws and statutes. 

For further information regarding Canadian and Ontario privacy laws, please visit: 

  * [ Office of the Privacy Commissioner of Canada ](http://www.priv.gc.ca/)
  * [ Office of the Information and Privacy Commissioner of Ontario ](http://www.ipc.on.ca/)



Psiphon is designed to provide you with open access to online content. Psiphon does not increase your online privacy, and should not be considered or used as an online security tool. 

## What user information does Psiphon collect?

From time to time Psiphon may have to record additional information in order to resolve a problem with our service. When this occurs, we will add an entry to the [Privacy Bulletin](https://web.archive.org/web/20171202103116id_/http%3A//www.psiphon3.net/en/privacy-bulletin.html) describing what was recorded, how long it was kept, and why. 

### Psiphon Client Software

#### Advertising Networks

We sometimes use advertisements to support our service, which may use technology such as cookies and web beacons. Our advertising partners' use of cookies enable them and their partners to serve ads based on your usage data. Any information collected through this process is handled under the terms of our advertising partners' privacy policies: 

  * <http://www.mopub.com/legal/privacy/>
  * <http://www.inmobi.com/privacy-policy/>
  * <http://www.millennialmedia.com/privacy-policy>



You can opt out of the use of cookies for interest-based advertising by visiting: 

  * <http://www.mopub.com/optout/>
  * <http://www.inmobi.com/page/opt-out/>
  * <http://www.millennialmedia.com/privacy-policy/opt-out>



### Websites

#### Google Analytics

We use Google Analytics on some of our websites to collect information about usage. The information collected by Google Analytics will only be used for statistical analysis related to your browsing behaviour on this specific site. The information we obtain from Google Analytics is not personally identifying, nor is it combined with information from other sources to create personally identifying information. 

Google Analytics plants a permanent cookie on your web browser to identify you as a unique user the next time you visit the site, but this cookie cannot be used by anyone except Google, and the data collected cannot be altered or retrieved by services from other domains. 

Google’s ability to use and share information collected by Google Analytics about your visits to this site is restricted by the [Google Analytics Terms of Use](http://www.google.ca/analytics/terms/us.html) and the [Google Privacy Policy](http://www.google.com/policies/privacy/). You may choose to opt out by turning off cookies in the preferences settings in your web browser. 

#### Storage Access Logging

We use Amazon S3 to store assets such as website files and Psiphon server discovery lists. We sometimes enable logging of downloads of these files. Analyzing these logs helps us to answer questions like "how many users are starting but not completing the download of the server discovery list?", "how is the downloaded data split between website assets and server discovery?", and "is an attacker making a denial-of-service attempt against our websites?" 

S3 [bucket access logs](https://docs.aws.amazon.com/AmazonS3/latest/dev/LogFormat.html) contain IP addresses, user agents, and timestamps. These logs are stored in S3 itself, so Amazon has access to these logs. (However, Amazon already serves the files, so they can already access this information.) Psiphon developers will download the logs, aggregate and analyze the data, and then delete the logs. Raw data will be kept only long enough to aggregate it and will not be shared with third parties. 

### Psiphon Servers

We collect the following data to find out how well Psiphon is working, what sites are popular, and what propagation strategies are effective. This information is shared with our partners so that they can see, for example, how often their sites are visited through Psiphon and from which countries. 

  * Number of email requests for client download link
  * Number of upgrades
  * How often each protocol is used, and error codes after failure
  * How often new servers are discovered
  * Session count and session duration
  * Total bytes transferred and bytes transferred for some specific domains
  * Client platform (simplified operating system list; e.g, not a detailed browser user agent)



User IP addresses are not collected by Psiphon servers in the normal course of operation. Psiphon does not require user accounts, so, by default, there is no collection of email addresses, usernames, or passwords. 

Event logs include timestamps, region codes (country and city), and non-identifying attributes including sponsor ID (determined by which Psiphon client build is used), client version, and protocol type. Page views are aggregated by time and/or session before being logged. 

All statistics shared with sponsors are further aggregated by date, sponsor, and region. 

### Feedback

When you choose to submit feedback through Psiphon you will have the option of including diagnostic data. We use this data to help us troubleshoot any problems you might be having and to help us keep Psiphon running smoothly. Sending this data is entirely optional. The data is encrypted before you send it, and can only be decrypted by us. The information in the data varies by platform, but it may include: 

Windows: 

  * Operating system version
  * Anti-virus version
  * How you're connected to the internet (for example, if you're using dial-up or connected via a proxy)
  * How much free memory your computer has



Android: 

  * Android version
  * Device model
  * Whether your device is rooted



### Email Responder

When you send an email request to our email auto-responder server, we are able to see your email address. While your email is being processed it is saved to the email server's disk, and it is deleted as soon as it is processed (usually in a few seconds). We do not allow your email address to be written to the system's log file. 

Our email auto-responder server is hosted in the Amazon EC2 cloud. We send two email responses to every request, and for one of those responses we use Amazon SES. This means that Amazon is able to see the email you send and our response to you. 

For each email we receive, we store the following information: 

  * The date and time the email request was received.
  * The date and time the email request was replied to.
  * The size of the email.
  * The mail server the email request came from. (The three least specific parts of the domain name. For example, `ne1.example.com`, but not `web120113.mail.ne1.example.com`.)



If we need to diagnose a problem, we may enable full mail server logging for a short amount of time. If you send an email during that time, your email address will be written to the system log. Those logs are deleted after one week. 

### App Stores

Note that if you get Psiphon from an "app store", such as the Google Play Store or Amazon AppStore, additional statistics may be collected by that store. For example, here is a description of what the Google Play Store collects: <https://support.google.com/googleplay/android-developer/answer/139628?hl=en>
