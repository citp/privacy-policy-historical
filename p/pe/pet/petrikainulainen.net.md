> *The following text is extracted and transformed from the petrikainulainen.net privacy policy that was archived on 2019-06-24. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20190624001559id_/https%3A//www.petrikainulainen.net/privacy-policy) for the most accurate reproduction.*

# Privacy Policy

Last updated: August 7, 2018

This is a private policy that is required by the [EU General Data Protection Regulation (GDPR)](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32016R0679&from=EN). Note that [our cookie policy](https://web.archive.org/cookie-policy/) is also a part of this privacy privacy.

 **Table of Contents**

  * The Holder of the Collected Data
  * The Person in Charge of the Collected Data
  * The Data Sources of the Collected Data
  * The Data Collected by the petrikainulainen.net Website
  * Regular Transfer of Data
  * Transfer of Data Outside the EU or EEA
  * The Data Stored in Backups
  * The Principles of Protecting the Collected Data
  * Individual Rights



## The Holder of the Collected Data

Petri Kainulainen  
Arkkitehdinkatu 34 C 27  
33720 Tampere  
Finland

Petri Kainulainen  
Arkkitehdinkatu 34 C 27  
33720 Tampere  
Finland  
Email Address: petri.kainulainen@gmail.com

## The Data Sources of the Collected Data

The collected data is either received directly from the user or determined from the data given by the user. The exact data sources of the collected data are described in the following sections.

## The Data Collected by the petrikainulainen.net Website

This section describes the data that is collected by the petrikainulainen.net website. If you want take a look at a specific subsection of this section, you can use the following links:

  * Access Log
  * Blocked IP Addresses
  * Comments
  * Live Traffic
  * Login Attempts
  * Opt-In Forms



### Access Log

We use the [Apache HTTP server](https://httpd.apache.org/) that logs all requests processed by the server. These requests are written to a so called [access log](https://httpd.apache.org/docs/1.3/logs.html#accesslog). The access log contains the following data:

  * The timestamp of the HTTP request
  * The IP address of the client
  * The value of the User-Agent HTTP request header
  * The value of the Referer HTTP request header
  * The requested resource
  * The request method
  * The used HTTP protocol
  * The returned HTTP status code
  * The size of the returned HTTP response



The collected data is extracted mainly from the incoming HTTP request. Also, before the Apache HTTP server returns the response to the client, it will extract the returned HTTP status code and the size of the returned response, and write this information to the access log.

We collect this data because we have a legitimate interest to prevent abuse.

We store old access logs for one month.

### Blocked IP Addresses

The [Wordfence](https://www.wordfence.com/) WordPress plugin provides additional protection for the petrikainulainen.net website. This plugin identifies malicious traffic and blocks IP addresses that send this traffic to this website. We can also block IP addresses manually by creating so called block rules.

A block rule contains the following information:

  * The IP address
  * The country of the IP address
  * A reason that explains why the IP address is blocked
  * The creation time of the rule
  * The expiration time of the rule
  * The timestamp of the last request send to this website



This data is extracted from the malicious HTTP request or given manually by an administrator. The country of the IP address is determined by using an IP location finder.

We collect this data because have a legitimate interest to prevent abuse.

If the block rule is created automatically by Wordfence, it is stored for five days (120 hours). If the block rule is created manually, it will be stored indefinitely.

Because this website is basically a blog, readers can leave comments to blog posts published on this site.

A comment contains the following information:

  * The IP address of the reader
  * The name or alias of the reader.
  * The comment text.



This data is given by the reader when he/she submits the comment form, and we use this data for helping our readers to solve their problems. In other words, we collect this data because we have a legitimate interest to make our website as useful as possible.

All comments are stored indefinitely.

### Live Traffic

The [Wordfence](https://www.wordfence.com/) WordPress plugin provides additional protection for the petrikainulainen.net website. This plugin has a firewall that keeps track of the HTTP requests send to this website and blocks malicious HTTP requests.

Wordfence collects the following information:

  * The timestamp of the HTTP address
  * The IP address of the client
  * The host name of the IP address
  * The geolocation of the IP address (city and country)
  * The value of the User-Agent HTTP request header
  * The type of the HTTP request (human, bot, warning, blocked)
  * The requested resource
  * The returned HTTP status code



This data is extracted mainly from the incoming HTTP request. The city and country of the IP address are determined by using an IP location finder. Also, the returned HTTP status code is extracted from the returned HTTP response.

We collect this data because we have a legitimate interest to identify and block malicious traffic.

This data is stored for one week.

### Login Attempts

The [Wordfence](https://www.wordfence.com/) WordPress plugin provides additional protection for the petrikainulainen.net website. This plugin keeps track of login attempts and blocks login attempts if it suspects that someone is trying log in by using a brute force attack.

Wordfence collects the following data:

  * Timestamp
  * The IP address of the client
  * Username
  * A boolean which is true if the user is an existing user and false otherwise.
  * The outcome of the login attempt (success, failed).



This data is extracted mainly from the HTTP request which is send to the petrikainulainen.net website when a user submits the login form. The outcome of the login attempt and the boolean flag (existing user) is determined from the result of the login attempt.

We collect this data because we have a legitimate interest to prevent abuse.

We store this data for three months.

### Opt-In Forms

We have implemented our opt-in forms by using the [Thrive Leads](https://thrivethemes.com/leads/) WordPress plugin. This plugin gathers statistics about the conversation rates of our opt-in forms and stores the email address of every person who subscribes our email newsletter.

Thrive Leads collects the following data when the user submits an opt-in form.

  * Timestamp
  * Email address
  * The lead group / short code which displayed the opt-in form
  * The type of the opt-in form
  * The referrer URL



The email address is given by the reader of our website when he/she subscribes our email newsletter. The lead group / short code and the type of the opt-in form is determined by Thrive Leads. The referrer URL is extracted from the incoming HTTP request.

We collect this data because we have a legal obligation ([Article 7 of EU GDPR](https://www.privacy-regulation.eu/en/article-7-conditions-for-consent-GDPR.htm)) to prove that a person has given us his/her consent to send email to him/her.

This data is stored as long as the subscriber has confirmed his/her subscription by clicking the opt-in link found from the confirmation email. However, because it would take too much time to delete this information one row at the time, we clear the content of this database table once a week.

## Regular Transfer of Data

This section identifies the information that is transferred to third parties. If you want take a look at a specific subsection of this section, you can use the following links:

  * Attack Data
  * Tracking and Analytics
  * Email List



### Attack Data

The [Wordfence](https://www.wordfence.com/) WordPress plugin provides additional protection for the petrikainulainen.net website. This plugin has a firewall that keeps track of the HTTP requests send to this website and blocks malicious HTTP requests. When the HTTP request contains malicious activity or suspicious behavior (such as a failed login), Wordfence sends the following data to Defiant (the company behind Wordfence):

  * The IP address of client
  * The request time of the HTTP request
  * The referrer (when available)
  * The browser user-agent string
  * The metadata stored on the device (such as other HTTP headers that might indicate preferred language)



Defiant extracts the following information from the collected data:

  * The IP address of the client
  * The location of the client
  * The search queries done by the client
  * The date and time of the HTTP request
  * The referral URL
  * The device make
  * The device model
  * The device OS
  * The mobile network info
  * The ISP used by the client
  * The browser type
  * The preferred language



We transfer this data to Defiant because we have a legitimate interest to identify and block malicious traffic, and Wordfence helps us to do it.

Typically the collected data is deleted after 90 days because it is no longer needed. However, if the IP address continues to be involved in malicious activity, it might be added to the Defiant’s blacklist. If this happens, the data will kept as long as the IP address will be kept on the blacklist.

### Tracking and Analytics

This section identifies the information that is collected by third parties which we use to gather information from the users of this website. Before we describe the data that is collected by our analytics partner, we will identify three things which we don’t do:

  * We don’t use Facebook advertising and we don’t load the Facebook tracking pixel.
  * We don’t use the advertising features of Google Analytics. In other words, we don’t see the demographics and interest reports.
  * We don’t use Google AdWords.



#### Google Analytics

This website uses [Google Analytics](https://analytics.google.com/analytics/web/) for gathering information from the anonymous users of this website. The tracking script of Google Analytics is run on every page load. Google Analytics identifies the user by using cookies and the gathered information is send to Google’s servers which can be located in the United States. Google will use this information for providing us different reports from our visitors. These reports are used to compile visitor statistics and improve our service.

By the way, **we honor the Do Not Track (DNT) header**. If a visitor of this website signals that he/she doesn’t want to be tracked, this website doesn’t load the Google Analytics tracking script.

Google Analytics tracks the incoming traffic and collects information from the website usage. It also gathers data about the user’s computer / mobile device. The collected information information include:

  * The anonymized IP address (not shown on the UI)
  * The cookie(s) which identifies the user
  * The requested page
  * The used browser
  * The used operating system
  * The used mobile device
  * The used internet service provider
  * The screen resolution of the computer / mobile device
  * The requested page
  * The referrer of the request
  * The Google Analytics campaign parameters
  * Events. We use events for measuring the conversion rate of our landing pages.
  * The landing page / exit page
  * The demographics and interest information of the user. Google can gather this information if the user has visited other websites which belong to the Google Display Network. The gathered data is anonymized and Google doesn’t gather data about actual website visits or individual visitors.



This information is either extracted from the incoming HTTP request or determined from it.

We use this data for two purposes:

  * It helps us to measure the effectiveness of our content marketing efforts.
  * It helps us to identify topics which are useful to our readers. This means that Google Analytics helps us to provide useful content to our readers.



In other words, we collect this data because we have a legitimate interest to measure the effectiveness of our content marketing efforts and provide useful content to our readers.

This information is stored indefinitely.

 **Additional Information:**

  * [Wikipedia – Do Not Track](https://en.wikipedia.org/wiki/Do_Not_Track)
  * [The Data privacy and Security of Google Analytics](https://support.google.com/analytics/answer/6004245)
  * [IP Anonymization in Analytics](https://support.google.com/analytics/answer/2763052?hl=en)
  * [Google Analytics Custom Campaigns](https://support.google.com/analytics/answer/1033863?hl=en)
  * [How Google uses data when you use our partners’ sites or apps](https://policies.google.com/privacy/partners)
  * [Tracking Code Overview](https://developers.google.com/analytics/resources/concepts/gaConceptsTrackingOverview)
  * [Google’s Privacy Policy – Information We Collect](https://policies.google.com/privacy#infocollect)



### Email List

We have an email list that allows us to keep in touch with the regular readers of this blog. We use an email marketing tool called [Drip](https://www.drip.com/) for this purpose.

Drip collects the following data:

  * The email address of the subscriber.
  * The time zone of the subscriber.
  * The method that was used to subscribe the newsletter.
  * The tags which are used to segment subscribers to different groups. For example, when a user subscribes our email newsletter he/she can specify what kind of emails he/she want to get it. These email preferences are saved by using tags. Also, if the person has purchased my Test With Spring course, he/she will have tags which identify him/her as a person who has purchased this course.
  * A list of emails send to the subscriber.
  * A list of emails which were opened by the subscriber.
  * A list of emails which contained a link that was clicked by the subscriber.
  * A list of trigger links clicked by the subscriber.
  * A list of subscribed email campaigns.
  * Notes about the customer.



Drip collects its data by using these data sources:

  * The subscriber. The email address and email preferences (tags) are provided by the subscriber. Also, when a subscriber opens our email or clicks a link found from our email, Drip updates the open and click statistics of the email in question.
  * Drip. A list of emails send to the student is updated by Drip when we send a new email to the subscribers of our newsletter.
  * An administrator. When a person subscribes our newsletter and he/she has purchased my Test With Spring course, an administrator will add to the correct tags to the subscriber.



We use the collected data for four different purposes:

 **First** , we send useful content to our subscribers. This means that every time when we publish a new blog post, we send an email to our subscribers.

 **Second** , we send relevant marketing emails to our subscribers. These emails market either our own products or the products of our business partners.

 **Third** , we segment our subscribers to different groups because this allows us to send relevant information to our subscribers. For example, if the subscriber has told us that he/she wants to get only testing related information, we won’t send him/her an email when we release a blog post that doesn’t talk about testing.

 **Fourth** , we use the open and click rates for improving our communication. We want to provide useful information to our readers and these two statistics help us to achieve this goal.

We collect this data because the subscriber has given us his/her consent to do so. When a person subscribes our email newsletter, he/she has to confirm his/her subscription by clicking the confirm link found from the confirmation email.

This data is stored as long as the subscriber is subscribed to the newsletter. When a subscriber cancels his/her subscription, we store this data for 30 days before it is deleted permanently.

 **More Information:**

  * [Drip’s Privacy Policy](https://www.drip.com/privacy)



## Transfer of Data Outside the EU or EEA

The following data is transferred outside the EU or EEA:

  * The data collected by Google Analytics. Note that the Google complies with the [EU-US and Swiss-US Privacy Shield Frameworks](https://policies.google.com/privacy/frameworks).
  * The data collected by Drip. Note that Drip is a U.S. company and the data that is collected by it is processed in the United States or any other country in which Drip or its subsidiaries, affiliates or service providers maintain facilities.
  * The attack data collected by Wordfence. Note that Defiant (the company behind Wordfence) is a U.S. company and the data is processed in United States or any other country in which Defiant or its subsidiaries, affiliates or service providers maintain facilities. Note that Defiant has applied for the Privacy Shield certification program for both EU-US and Swiss-US, and they are waiting to be certified.



## The Data Stored in Backups

We take periodical backups from the database of the petrikainulainen.net website. These backups contains all data that is collected by the petrikainulainen.net website.

We have to take these backups because have a legitimate interest to be able to recover from accidents that lead into loss of data.

Each database backup is stored for one month. When this period is over, the backup will be deleted.

## The Principles of Protecting the Collected Data

This section describes the principles which we use to protect the data that is collected by us.

### The petrikainulainen.net Website

The data that is collected by the petrikainulainen.net website is protected by following these rules:

  * All communication between a web browser and the petrikainulainen.net website uses HTTPS.
  * The petrikainulainen.net website has a firewall that protects it from malicious traffic and blocks brute force attacks.
  * The petrikainulainen.net website uses a malware scanner that performs regular malware scans.
  * The petrikainulainen.net website sends automatic email alerts to the administrator when a WordPress plugin update is available.
  * Only the administrator of the petrikainulainen.net website has the required permissions to access the information stored to the database of the website.
  * The information is saved in a database that is protected with username and password. Only the administrator of the petrikainulainen.net website has access to this database.
  * The database server and web server are located in Finland at locked and guarded premises. Only authorized personnel are allowed to access these premises and the information stored on these servers.



### Manual Processing

When we process the collected data manually, we follow these principles:

  * We minimize the number of persons who can access the collected data. At the moment only one person (Petri Kainulainen) can access it.
  * We use two factor authentication every time when it’s supported by the service that collects the data described in this privacy notice.
  * All communication between the administrator and a remote system happens by using HTTPS.
  * All backups are stored in an encrypted hard drive.
  * If a file is transferred to a cloud storage, it is encrypted before it is transferred.



## Individual Rights

You have the right of access your personal data that has been collected by us. You can obtain a copy of your personal data by sending a signed letter to the person who is in charge of the collected data. This letter must contain the information that allows us to identify you. You can obtain your personal data free of charge once per year. Your request is processed within 30 days of receiving your letter.

You have the the right to rectify incorrect data or complete incomplete data. If you want to exercise this right, you have to contact the person who is in charge of the collected data. Your request is processed within 30 days.

You have the right to have your personal data erased. You can have your personal data erased by sending a signed letter to the person who is in charge of the collected data. This letter must contain the information that allows us to identify you. Your request is processed within 30 days of receiving your letter. Note that if you want to erase the data collected by Drip, you don’t have to send us a signed letter. You can simply unsubscribe our newsletter and you data will be erased.

You have the right to restrict the processing of your personal data. If you want restrict us from processing your personal data, you have to send a signed letter to the person who is in charge of the collected data. This letter must contain the information that allows us to identify you. Your request is processed within 30 days of receiving your letter.

You have the right to data portability. This means that you can obtain the collected data in a machine readable format. You can obtain a copy of your personal data in a machine readable format by sending a signed letter to the person who is in charge of the collected data. This letter must contain the information that allows us to identify you. Your request is processed within 30 days of receiving your letter.

You have the right to object the data processing based on legitimate interest, direct marketing, and data processing for purposes of scientific/historical research and statistics. If you want to exercise this right, you have to contact the person who is in charge of the collected data. Your request is processed within 30 days.

Also, if you think that we are processing your personal data in a way that breaks the law, you have the right to file a complaint to [the office of the data protection ombudsman](http://www.tietosuoja.fi/en/index.html).
