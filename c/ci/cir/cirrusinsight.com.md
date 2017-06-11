> *The following text is extracted and transformed from the cirrusinsight.com privacy policy that was archived on 2017-06-11. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20170611230613id_/https%3A//www.cirrusinsight.com/trust) for the most accurate reproduction.*

# Trust, Privacy & Security - Cirrus Insight

We built Cirrus Insight to respect and protect your data.  We utilize OAuth 2.0 authentication with Salesforce, Microsoft Office 365, and Google for Work.  We use SSL for secure transmission of data between platforms.  And we do regular third-party security audits by Bishop Fox.  

### Authentication

  * Our product uses OAuth for user authentication.  We never have access to Salesforce, Google, Microsoft, Apple, or Android passwords.

  * Cirrus Insight for iPhone and iPad encrypts the mail login credentials in the keychain just like the native Apple Mail app.

  * Cirrus Insight supports Single Sign On (SSO) and SAML (Security Assertion Markup Language).

  * Support for Salesforce Sandbox

  * OAuth support for Community, Partner Portal, and Chatter licenses

  * HTTP Strict Transport Security which declares that complying web browsers are to interact with Cirrus Insight using only secure HTTPS connections.



### Granting Permission

  * If you're installing Cirrus Insight for Gmail in a Chrome web browser, you'll see a notice about granting Cirrus Insight permission to run on two specific domains: [mail.google.com](http://mail.google.com/) and [secure3.cirrusinsight.com](http://secure3.cirrusinsight.com/) which enables Cirrus Insight to run securely inside Gmail.

  * Without your explicit authorization, Cirrus Insight cannot access your Salesforce data.  After installing Cirrus Insight you’ll be asked to sign in via Salesforce and to approve our request for access. This is called the “OAuth handshake.”  We tell Salesforce what level of access we need to provide the Service which is called the “scope.” 




The levels of access that we request are:

  * “id” so we can identify you.
  * “api” so we can search Salesforce and create leads and contacts and other records when you want. 
  * “refresh_token” so we can get a new session with Salesforce on your behalf and run background jobs for you like email sync and calendar sync. 
  * “web” so we can take you to a specific record in Salesforce without forcing you to sign in every time.



Please note:

  * We _can’t_ do anything you can’t do. For example, if you don’t have access to edit Contacts in Salesforce, you won’t be able to edit a Contract record in Cirrus Insight.

  * We can do _almost_ everything you can do. If you can see every Account in Salesforce, our API access gives us the ability to search every Account on your behalf.

  * You can revoke our access _at any time_ from your Salesforce user record. [More information.](http://support.cirrusinsight.com/customer/portal/articles/616808-how-do-i-uninstall-cirrus-insight-)




### Encryption

  * Data in transit is encrypted via SSL (Secure Socket Layer).

  * Sensitive data stored is encrypted using an AES 256 cipher.



### Data We Collect

  * User profile information (name, email address, etc.)

  * OAuth refresh tokens (encrypted)

  * Salesforce configuration information including time zone, language preference, and profile and permission set.
  * As you use Cirrus Insight, we collect data about the features in use.  We use this data to populate your Cirrus Insight Dashboard, assist with customer support, and plan for future features.
  * We use the payment processor [Stripe](http://www.stripe.com/) for credit card payments. When you enter your credit card information on our site, the information is sent directly to Stripe. Your credit card number is never sent to Cirrus Insight servers.



### Access to Systems

  * All interaction between Cirrus Insight and third-party platforms (e.g. Salesforce, Google, Microsoft) occurs over a secure HTTPS connection.

  * We host our systems on industry-leading cloud infrastructure services including Amazon Web Services.



### Incident Response and Remediation

  * We monitor our systems 24/7/365 with several performance measurement and error-checking tools such as New Relic.

  * If an incident causes downtime, we post the update to the [Cirrus Insight status page](https://www.cirrusinsight.com/status).  We also monitor the health dashboards for Salesforce and Google and Amazon from the status page.

  * Should a security incident occur, we will notify affected users of the nature and extent of the breach, and take steps to minimize any damage.  There have been no security incidents to date.



### Data Confidentiality

  * Cirrus Insight does not rent, sell, trade or disclose your Personal Information to third parties without your consent.

  * Access to customer data by Cirrus Insight employees is limited based on the need to access such data (e.g. to resolve a customer support ticket).

  * When requested, we will destroy a user’s account, removing all customer data associated with that account.

  * Cirrus Insight adheres to the permissions assigned to user profiles in the customer Salesforce org.



### Third-Party Security and Privacy Reviews

  * We passed the [Salesforce Security Review](https://developer.salesforce.com/page/Security_Review) starting in December 2011, and we are [listed on the Salesforce AppExchange](https://appexchange.salesforce.com/listingDetail?listingId=a0N30000004fnkUEAQ).  We have 1,300+ reviews on the AppExchange, making Cirrus Insight the third most reviewed application of all time behind Docusign and Echosign.

  * We are Google for Work Premier Partner and we are listed on the Chrome Web Store.

  * We are a member of the Microsoft Partner Network and we are listed on the Office Store.

  * We are an Apple Partner and we are listed on the iTunes App Store.

  * We are a Google Partner and we are listed on the Google Play Store.

  * We participate in the [EU-U.S. Privacy Shield Framework](https://www.cirrusinsight.com/privacy-shield).  (We can also incorporate the former EU-U.S. Model Clauses into a contract upon request.)

  * We will sign your Business Associate Agreement (BAA) if you transact in Protected Health Information (PHI).

  * We commission third-party application and network security audits by a leading security firm.



### Mobile

  * Salesforce OAuth 2.0 authentication

  * Supports Salesforce 2-factor authentication

  * Supports SSO

  * Email sign in token is stored encrypted in the device keychain (same as native email applications)

  * Supports offline access. Salesforce actions will be transmitted when connectivity is re-established.



### Email Tracking and Link Tracking

  * Cirrus Insight optionally includes Email Tracking and Link Tracking features. Cirrus Insight customers may enable or disable email tracking and link tracking in the Cirrus Insight administrator dashboard.  

  * The usage of tracking functionality is consistent with industry standards. If a Cirrus Insight customer enables Email Tracking, Cirrus Insight embeds a small transparent image pixel in the outgoing email. If the email is opened, Cirrus Insight may be able to inform the user about who opened the email, when it was opened, and where it was opened. If Link Tracking is enabled, Cirrus Insight re-writes the link URL so that it is trackable. If the link is clicked by the recipient, Cirrus Insight may be able to inform the user about who clicked on the link, when it was clicked, and the general location of the visitor when they clicked the link.   

  * Email recipients may block email open tracking via the settings on their email client or by using a pixel-blocking extension.



### Email Search

  * When you open or compose an email message, we search for the sender’s or recipient’s email address in Salesforce and return information about the Lead or Contact. All communication between your browser and our servers is protected by the same level of SSL encryption that banks use for online banking services.

  * When we search Salesforce for information about a specific email address, we return information about related Activities, Account, Opportunities, Cases, and other relevant records. Each new query typically takes 2-3 API calls so we cache the data in RAM (data is not written to disk) for a period of 5-10 minutes. As a result, any searches for an email address in the cache will be returned from the cache making for a much faster response for the user and many fewer API calls for the organization. When the cache expires, the data is permanently deleted.



### Email Attachments

  * If you enable our attachments feature, you can save attachments from Gmail, Outlook, and/or mobile to Salesforce. We never save file attachments to our server.

  * Additionally, we also support saving [Google Drive attachments](https://www.cirrusinsight.com/how-to/add-attachments-to-salesforce-from-gmail/) with an email to Salesforce. Saving Google Drive attachments does not require any additional permission. A link to the file in Google Drive can be saved into the email Activity or into Chatter in Salesforce.




### 3rd Party Services

  * To provide the best experience and level of service, we utilize a number of third party services to monitor systems and track application usage such as New Relic and Zuora. 

  * We may also partner with other cloud software providers to bring additional features to users of Cirrus Insight. Currently, we partner with RingLead to provide a service that allows Cirrus Insight to extract contact information from the email signature when a user wants to create a new Lead or Contact. RingLead does not store any transmitted data. Additionally, the feature may be enabled or disabled by the organization administrator and/or on an individual user basis.



### Our Continuing Commitment

We are continuously improving Cirrus Insight to take advantage of new technologies as well as new capabilities of the Salesforce, Google, and Microsoft platforms.   Material changes to this trust and privacy page will be highlighted.  Customers can check this page any time for the latest version.  This page was last updated with a link to the EU-U.S. Privacy Shield Framework on November 14, 2016.

### Privacy Shield Policy

Cirrus Insight is committed and subject to the Principles of the Privacy Shield Framework, which are principles governing the transfer of personal data between the European Union and the United States.  We are listed as a participating company on the Privacy Shield website at: <https://www.privacyshield.gov/participant?id=a2zt0000000GnN9AAK>, we provide commercially reasonable and appropriate measures to protect your data from loss, misuse, unauthorized access, disclosure, alteration and destruction. 

Through the acts of signing up, cancelling our service, or disabling features within our application, customers can control their data thereby limiting the use and disclosure of the basic personal information we collect. Additionally, users can revoke OAuth in Salesforce and/or Google for Work and/or Microsoft Office 365 which will remove Cirrus Insight’s access to those systems.

In compliance with the Privacy Shield Principles, Cirrus Insight commits to resolve complaints about our collection or use of your personal information.  Individuals in the European Union with inquiries or complaints regarding our Privacy Shield policy should first contact Cirrus Insight at: [https://support.cirrusinsight.comhttps://www.cirrusinsight.com/contact](https://support.cirrusinsight.com/).

Cirrus Insight has further committed to refer unresolved Privacy Shield complaints to JAMS, an alternative dispute resolution provider located in the United States. If you do not receive timely acknowledgment of your complaint, or if we have not addressed your complaint to your satisfaction, please contact or visit  <https://www.jamsadr.com/> for more information or to file a complaint.  The services of JAMS are provided at no cost to you.

As participants in the Privacy Shield Framework, we are subject to the investigatory and enforcement powers of the FTC, the Department of Transportation or any other U.S. authorized statutory body. In the event of a dispute, there is the possibility, under certain conditions, for the individual to invoke binding arbitration. 

Regarding onward transfer, Cirrus Insight is responsible for the processing of personal information we receive under the Privacy Shield and subsequent transfers to a third party acting as an agent on our behalf. Cirrus Insight shall remain liable under the Principles if an agent processes personal information in a manner inconsistent with the Principles, unless Cirrus Insight proves we are not responsible for the event giving rise to the damage.

You can contact us with any inquiries or complaints at [https://support.cirrusinsight.comhttps://www.cirrusinsight.com/contact](https://support.cirrusinsight.com/)

The United States Department of Commerce Privacy Shield website is at [www.privacyshield.gov](http://www.privacyshield.gov/)
