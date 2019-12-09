> *The following text is extracted and transformed from the psiphon3.com privacy policy that was archived on 2019-12-09. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20191209012237id_/https%3A//www.psiphon3.com/en/privacy.html) for the most accurate reproduction.*

# Psiphon | Privacy Policy

Psiphon is committed to protecting the privacy interests of its customers, end users, distributors and suppliers. This privacy policy is intended to provide you with general information on how your personal information may be used. Psiphon is a Canadian corporation with its head office located in Ontario, and our privacy policy has been developed to reflect Canadian and Ontario privacy laws and statutes. 

For further information regarding Canadian and Ontario privacy laws, please visit: 

  * [ Office of the Privacy Commissioner of Canada ](http://www.priv.gc.ca/)
  * [ Office of the Information and Privacy Commissioner of Ontario ](http://www.ipc.on.ca/)



## What user information does Psiphon collect?

From time to time Psiphon may have to record additional information in order to resolve a problem with our service. When this occurs, we will add an entry to the [Privacy Bulletin](https://web.archive.org/web/20191209012237id_/https%3A//www.psiphon3.com/en/privacy-bulletin.html) describing what was recorded, how long it was kept, and why. 

### User Activity and VPN Data

#### Why should you care?

When using a VPN or proxy you should be concerned about what the VPN provider can see in your data, collect from it, and do to it. 

When you use a VPN, all data to and from your device goes through it. If you visit a website that uses unencrypted HTTP, all of that site's data is visible to the VPN. If you visit a website that uses encrypted HTTPS, the site content is encrypted, but some information about the site might be visible to the VPN. Other apps and services on your device will also transfer data that is encrypted or unencrypted. (Note that this is distinct from the encryption that all VPNs provide. Here we're only concerned with data that is or is not encrypted _inside_ the VPN tunnel.) 

For unencrypted services, it is possible for a VPN provider to see, collect, and modify (e.g., injecting ads into) the contents of your data. For encrypted data, it is still possible for a VPN to collect metadata about sites visited or actions taken. You should also be concerned with your VPN provider sharing your data with third parties. 

#### What does Psiphon **NOT** do with your data?

We DO NOT collect or store any VPN data that is not mentioned here. 

We DO NOT modify the contents of your VPN data. 

We DO NOT share any sensitive or user-specific data with third parties. 

#### What kinds of user data does Psiphon collect?

We will define some categories of data to help us talk about them in the context of Psiphon. 

##### _User Activity Data_

While a user's device is tunneled through Psiphon, we collect some information about how they're using it. We record what protocol Psiphon used to connect, how long the device was connected, how many bytes were transferred during the session, and what city, country, and ISP the connection came from. For some domains (but very few, and only popular ones) or server IP addresses (e.g., known malware servers) that are visited, we also record how many bytes were transferred to it. (But never full URLs or anything more sensitive. And only domains of general interest, not all domains.) 

Geographical location and ISP info are derived from user IP addresses, which are then immediately discarded. 

An example of user activity data might be: At a certain time a user connected from New York City, using Comcast, and transferred 100MB from `youtube.com` and 300MB in total. 

We consider user activity data the most sensitive category of data. We never, ever share this data with third parties. We keep user activity data for at most 60 days, and then we aggregate it and delete it. 

##### _Aggregated Data_

Data is “aggregated” by taking a lot of sensitive user activity data and combining it together to form coarse statistical data that is no longer specific to a user. After aggregation, the user activity data is deleted. 

An example of aggregated data might be: On a particular day, 250 people connected from New York City using Comcast, and transferred 200GB from `youtube.com` and 500GB in total. 

Aggregated data is much less sensitive than activity data, but we still treat it as potentially sensitive and do not share it in this form. 

##### _Shareable Aggregated Data_

When sharing aggregated data with third parties, we make sure that the data could not be combined with other sources to reveal user identities. For example, we do not share data for countries that only have a few Psiphon users in a day. We make sure that the data is anonymized. 

We also never share domain-related information with third parties. 

An example of shareable aggregated data might be: On a particular day, 500 people connected from New York City and transferred 800GB in total. 

An example of data that is _not shareable_ : On a particular day, 2 people connected from Los Angeles. Those people will be included in the stats for the entire US, but that is too few people to anonymously share city data for. 

#### What does Psiphon do with User Activity and Aggregated Data?

Activity and aggregated statistical data are vital for us to make Psiphon work best. It allows us to do things like: 

  * Monitor the health and success of the Psiphon network: We need to know how many people are connecting, from where, how much data they're transferring, and if they're having any problems.
  * Monitor threats to our users' devices: We watch for malware infections that attempt to contact command-and-control servers.
  * Ensure users stay connected while foiling censors: We try to detect that a user is behaving like a real person and then reveal new Psiphon servers to them. (This is our obfuscated server list technology.)
  * Estimate future costs: The huge amount of user data we transfer each month is a major factor in our costs. It is vital for us to see and understand usage fluctuations.
  * Determine the nature of major censorship events: Sites and services often get blocked suddenly and without warning, which can lead to huge variations in regional usage of Psiphon. For example, we had up to 20x surges in usage within a day when [Brazil blocked WhatsApp](https://blog-en.psiphon.ca/2016/07/psiphon-usage-surges-as-brazil-blocks.html) or [Turkey blocked social media](https://blog-en.psiphon.ca/2016/11/social-media-and-internet-ban-in-turkey.html).
  * Understand who we need to help: Some sites and services will never get blocked anywhere, some will always be blocked in certain countries, and some will occasionally be blocked in some countries. To make sure that our users are able to communicate and learn freely, we need to understand these patterns, see who is affected, and work with partners to make sure their services work best with Psiphon.



#### Who does Psiphon share Aggregated Data with?

Shareable aggregated data is shared with sponsors, organizations we collaborate with, and civil society researchers. The data can be used to show such things as: 

  * How well Psiphon is working in a particular region.
  * The blocking patterns in a given country, for example during political events.
  * That the populace of a country is determined to access the open internet.



Again, only anonymized shareable aggregated data is ever shared with third parties. 

### Psiphon Client Advertising Networks

We sometimes use advertisements to support our service, which may use technology such as cookies and web beacons. Our advertising partners' use of cookies enable them and their partners to serve ads based on your usage data. Any information collected through this process is handled under the terms of our advertising partners' privacy policies: 

  * <https://www.mopub.com/legal/privacy/>
  * <https://www.mopub.com/legal/partners/>
  * <https://policies.google.com/technologies/partner-sites>



You can opt out of the use of cookies for interest-based advertising by visiting: 

  * <https://www.mopub.com/optout/>



### Psiphon Websites

#### Google Analytics

We use Google Analytics on some of our websites to collect information about usage. The information collected by Google Analytics will only be used for statistical analysis related to your browsing behaviour on this specific site. The information we obtain from Google Analytics is not personally identifying, nor is it combined with information from other sources to create personally identifying information. 

Google Analytics sets a permanent cookie in your web browser to identify you as a unique user the next time you visit the site, but this cookie cannot be used by anyone except Google, and the data collected cannot be altered or retrieved by services from other domains. 

Google’s ability to use and share information collected by Google Analytics about your visits to this site is restricted by the [Google Analytics Terms of Use](http://www.google.ca/analytics/terms/us.html) and the [Google Privacy Policy](http://www.google.com/policies/privacy/). You may choose to opt out by turning off cookies in the preferences settings in your web browser. 

#### Storage Access Logging

We use Amazon S3 to store assets such as website files and Psiphon server discovery lists. We sometimes enable logging of downloads of these files. Analyzing these logs helps us to answer questions like "how many users are starting but not completing the download of the server discovery list?", "how is the downloaded data split between website assets and server discovery?", and "is an attacker making a denial-of-service attempt against our websites?" 

S3 [bucket access logs](https://docs.aws.amazon.com/AmazonS3/latest/dev/LogFormat.html) contain IP addresses, user agents, and timestamps. These logs are stored in S3 itself, so Amazon has access to these logs. (However, Amazon already serves the files, so they can already access this information.) Psiphon developers will download the logs, aggregate and analyze the data, and then delete the logs. Raw data will be kept only long enough to aggregate it and will not be shared with third parties. 

### PsiCash

The PsiCash system only collects information necessary for the functioning of the system, monitoring the health of the system, and ensuring the security of the system. 

The PsiCash server stores per-user information to allow for operation of the system, including: 

  * generated user access tokens
  * balance
  * last activity timestamp
  * PsiCash earning history, including what actions the rewards were granted for
  * PsiCash spending history, including what purchases were made



In the user's web browser, some data is stored to allow for earning rewards and making purchases. This data includes: 

  * generated user access tokens
  * when a PsiCash reward is allowed to be claimed again



For monitoring system health and security, system activity data is collected and aggregated. This data includes: 

  * user country
  * balance
  * user agent string
  * client version
  * PsiCash earning and spending details



Individual user data is never shared with third parties. Coarse aggregate statistics may be shared, but never in a form that can possibly identify users. 

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
