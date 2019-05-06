> *The following text is extracted and transformed from the transloadit.com privacy policy that was archived on 2019-05-06. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20190506083818id_/https%3A//transloadit.com/legal/privacy) for the most accurate reproduction.*

# Privacy policy | Transloadit

In order to provide this service, we capture and store information about you and about users uploading material to the service:

As of 25 May 2018, the European General Data Protection Regulation (GDPR) has come into force. We wrote this post to outline what Transloadit - and our customers - can do to make sure the new rules are being followed.

## Who is responsible for data protection?

Since we are operating with a staff of less than ten people, we do not have an external data officer. Responsible for data protection are our founders Tim Koschützki and Kevin van Zonneveld. You can reach them at [founders@transloadit.com](mailto:founders@transloadit.com).

## What data is collected?

Transloadit collects and shares information about its customers. Since Transloadit is a B2B service, this concerns data on businesses. We also receive a limited amount of data on our customers' customers. These are the individuals or 'data subjects' that the GDPR specifically aims to protect, and they come in contact with Transloadit when we handle their uploads or when they request the status of encoding progress of their files.

As far as these cases are concerned, Transloadit receives the following **data** on end-users:

### From the website

  1. IP addresses
  2. Request headers
  3. Data entered on our website
  4. The browser session (identified through a cookie)
  5. Information used to analyze usage of our platform (through cookies from Google Analytics. More on cookies is explained below)



### From the API

  1. IP addresses
  2. Request headers
  3. Your user agent (browser, device, etc.)
  4. Data submitted to our API (media files, uploads)



All data stored by us is only used for internal processing, and never sold or otherwise given away.

Since Transloadit does not store data on data subjects, migration or deletion tools are not applicable.

### What data is stored exactly?

Transloadit only stores links to uploaded media files in the status JSON of an Assembly. We do not store any other data coming from data subjects.

Transloadit only stores temporary files, and we do [so for **24 hours**](https://web.archive.org/docs/faq/temporary-purge-sooner/). Files are hashed and anonymized.

Transloadit employees only look at your files to troubleshoot problems. This rarely happens, and when it does, we do so with the understanding that anything we see is to be kept strictly confidential.

Any Transloadit employee or subcontractor with access to these systems will have signed an NDA, which among other things, includes enforcing two-factor authentication for critical services, encrypted drives, and password managers.

If it is important to you that the media files of your end-users, kept during the 24-hour window, temporarily resides in a particular region, Transloadit currently operates in two regions: `us-east-1` (Virginia, USA) and `eu-west-1` (Ireland). By default, Transloadit will serve your users from the region closest to them, but you can also opt to exclusively address one region, by using an endpoint like `https://api2-eu-west-1.transloadit.com/`.

## Storing Assemblies

Assemblies contain links to the media files that have been uploaded by data subjects. If the links point to files temporarily hosted by us, then these links will expire after 24 hours (at the point when the associated files are discarded). Links to files that were exported to your own storage system (Amazon S3, FTP server, Rackspace container, etc.) will expire based on the expiry policy you set forth on these containers.

Assemblies will be archived after three months following their creation. Any Assembly Status JSON will cease to be available through https://api2.transloadit.com/assemblies/[[assembly_id]] after three months, along with all links to media files uploaded for this Assembly. Assembly IDs are secure: only the data subject, you as our customer and Transloadit staff know these Assembly IDs.

## Third-party services

We use the following third-party services which also store data about you:

supplier | subject | data | encryption | anonymized | discarded | archived  
---|---|---|---|---|---|---  
Transloadit | end user (data subject) | browser identifiers |   |   | instantly |    
AWS S3 | end user (data subject) | media files |   | ✅ | >24h |    
AWS RDS | customer (business) | address, email |   | ✅ |   | >30d  
AWS RDS | customer (business) | assembly meta data |   | ✅ |   | >30d  
AWS RDS | customer (business) | credentials for writing to cloud storage | aes256 | ✅ |   |    
AWS RDS | customer (business) | transloadit password | bcrypt | ✅ |   |    
Discourse | customer (business) | public support tickets |   | n/a |   |    
Google Analytics | customer (business) | browser identifiers |   | ✅ |   |    
Intercom | customer (business) | browser identifiers |   |   |   |    
Intercom | customer (business) | support tickets |   |   |   |    
Librato | customer (business) | ops heuristics |   | ✅ |   |    
Papertrail | customer (business) | logs |   |   |   | >7d  
RBS Worldpay/Ipayment | customer (business) | credit card data | PCI compliant |   |   |    
  
  * **encryption** : At rest. All connections in transit are [protected by tls](https://web.archive.org/blog/2016/07/ssl-upgraded/)
  * **anonymized** : Any data that can be used to identify the 'data subject' is scrubbed
  * **discarded** : Data is destroyed
  * **archived** : Data is accessible only by founders



## Breach notifications

In the event that your private data or API-uploaded temporary files are disclosed to unauthorized people (such as hackers), Transloadit will send out email notifications to all possibly affected parties. We will also update our blog at http://transloadit.com/blog, our Twitter account at https://twitter.com/transloadit and our status page at https://status.transloadit.com.

## Your information and your rights

If you are based within the EEA (European Economic Area) or within another jurisdiction that has similar data protection laws, under certain circumstances, you have the following rights:

  1. the right to be told how we use your information and obtain access to your information;
  2. the right to have your information rectified or erased, or to place restrictions on processing your information;
  3. the right to object to the processing of your information e.g. for direct marketing purposes or where the processing is based on our legitimate interests;
  4. the right to have any information you provided to us on an automated basis returned to you in a structured, commonly-used and machine-readable format, or sent directly to another company, where technically feasible (“data portability”);
  5. where the processing of your information is based on your consent, the right to withdraw that consent subject to legal or contractual restrictions;
  6. the right to object to any decisions based on the automated processing of your personal data, including profiling; and
  7. the right to lodge a complaint with the supervisory authority responsible for data protection matters (e.g. in the UK, the Information Commissioner’s Office).



If you request a copy of your information, you may be required to pay a statutory fee.

If we hold any information about you which is incorrect or if there are any changes to your details, please let us know so that we can keep our records accurate and up to date.

If you withdraw your consent to the use of your personal information for purposes set out in our Privacy Policy, we may not be able to provide you with access to (parts of) our website, applications, and services.

We will retain your personal information for the duration of our business relationship and afterwards for as long as is necessary and relevant for our legitimate business purposes, or as otherwise permitted by applicable laws and regulations. When we no longer need your personal information, we will dispose of it in a secure manner (without further notice to you).

## Changes to our privacy policy

We may change this privacy policy from time to time. Nevertheless, we will not reduce your rights under this privacy policy. We will always update the privacy policy on our website, so please try to read it when you visit the website (the ‘last updated’ reference tells you when we last updated this privacy policy).

## Cookies, analytics and traffic data

Cookies are small text files that are transferred from our website and stored on your device. We use cookies to help us provide you with a personalized service, and to help make our website and service better for you.

Our cookies may be session cookies (temporary cookies that identify and track users within our websites) which are deleted when you close your browser or persistent cookies (cookies that enable our website to “remember” who you are and to remember your preferences within our website) which will stay on your computer or device after you close your browser).

We use the following different types of cookies:

### Strictly necessary cookies

These are cookies which are needed for our website to function properly. For example, these cookies allow you to access the secure area of our website after login.

### Performance cookies and analytics technologies

These cookies collect information about how visitors and users use our website. For example, they register which functionality our visitors use most often, or if they receive error messages from certain areas of our website. These cookies don't collect information that can be used to identify a visitor or user. All information collected by these cookies is aggregated and therefore anonymous. We only use these cookies to improve how our website works.

### Functionality cookies

These cookies allow our website to remember the choices you make (such as your user name, language or the region you are in) and provide enhanced and more personal features. These cookies can also be used to remember changes you have made to text size, fonts and other parts of web pages that you can customize. They may also be used to provide services you have asked for. The information collected by these cookies may be anonymised. They cannot track your browsing activity on other websites.

### IP Address and traffic data

We keep a record of traffic data which is logged automatically by our servers, such as your Internet Protocol (IP) address, device information, the website that you visited before ours and the website you visit after leaving our site. We also collect some site, application and service statistics, such as access rates, page hits and page views. We are not able to identify any individual from traffic data or site statistics.

#### Google Analytics

Our platform uses Google Analytics, which uses cookies. The information created through these cookies about your usage of transloadit.com will be transmitted to a Google server in the United States of America and stored there. When you are located in one of the states of the European Union, your IP address will be anonymized on our platform prior to transmitting it. We use the code "ga('set', 'anonymizeIp', true);" to ensure an anonymous way of saving of IP addresses (so-called IP-masking).

Google will use this information to analyze your usage of our platform and to create reports about the activities on our platform. The IP address that will be sent to Google as a result of Google Analytics will not be connected to any other data on Google.

You can avoid any cookies being saved by changing the settings in your browser accordingly. Please be aware that if you choose to do so, you might not be able to make full use of our website and all of its features. You can also prevent the analysis of your browsing behavior on our platform through Google Analytics by installing the following browser plugin: http://tools.google.com/dlpage/gaoptout

Google, Inc. (“Google”) head quarters are located at "1600 Amphitheatre Parkway Mountain View, California 94043, USA". Their privacy policy is located here: https://policies.google.com/privacy.

## How to disable cookies

You may be able to configure your browser or our website to restrict cookies or block all cookies if you wish. If you disable cookies, you may find that this affects your ability to use certain parts of our website. For more information about cookies and instructions on how to adjust your browser settings to accept, delete or reject cookies, see the [www.allaboutcookies.org](https://www.allaboutcookies.org/) website.

## Data Processing Addendum (DPA)

If you require a countersigned copy of our DPA, please [reach out to support](mailto:hello@transloadit.com?subject=I+request+a+countersigned+copy+of+your+DPA).

## Last Updated

This privacy policy was last updated on June 14, 2018.
