> *The following text is extracted and transformed from the industrysearch.com.au privacy policy that was archived on 2008-06-19. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20080619181102id_/http%3A//www.industrysearch.com.au/privacypolicy.aspx) for the most accurate reproduction.*

# IndustrySearch.com.au® Australia - Privacy Policy

The following page provides information and guidelines about INDUSTRACOM for the following:

**-News & Information Policy

\- Privacy Policy

**  
  
** \- System Specifications  
**   
**Definitions  
**Website: Refers to the website owner/operator INDUSTRACOM Pty Ltd ([www.industracom.com](http://www.industracom.com/), Australia ABN 20 079 858 236)   
operators of [IndustrySearch.com.au](http://www.industrysearch.com.au/) and [MedicalSearch.com.au](http://www.medicalsearch.com.au/).

* * *

  
**News& Information Policy  
**   
This section outlines the policies and definitions for information published by the website. Editorial integrity is a high priority and as an Australian media & information company we acknowledge a responsibility to publish relevant and accurate news and information. 

_Information Sources_  
Information published on our websites originates from such sources as AAP, Reuters, government and industry bodies. Editorial policy mandates INDUSTRACOM is not geared towards the research or development of original content. 

_Indemnification_  
We do not assume responsibility for damages or inaccuracies as a result of information provided or published by advertisers or other independent sources.  _Advertiser Content_  
Storefront advertisers distribute their own media releases and are provided access to add them directly into our system using an online submission area. Advertiser media releases go through our [editorial process](http://www.industrysearch.com.au/sf_tips.htm#content_exposure) to determine what level of published exposure they will receive. Advertiser content is marked as such by the presence of their company name a link to their advertiser profile.

BACK TO TOP ^

* * *

**Privacy Policy**

The website is firmly committed to privacy in accordance with the Privacy Amendment Act 2000 and is bound by the National Privacy Principles ('NPPs'), which were introduced into the Privacy Act 1988 (Cth) ('Privacy Act') by the Privacy Amendment (Private Sector) Act 2000.

The website will update this privacy policy as required. If changed, the changes will be posted on the website's websites so that users are made aware of what information is collected, how it is used and when it may be disclosed. If at any time the website is required by law to release information, we are obliged to co-operate fully under our legal duty.

This Privacy Policy does not apply to acts or practices of the website that are directly related to employee records of current or former employees. 

 _Sponsor Messages  
_All subscribers to the website's free e-mail newsletters automatically receive sponsor messages. This is a condition of subscription. Sponsor messages subsidise our newsletters and allow the website to provide high quality news and information free of charge. We make every effort maintain a good relationship with our readers/subscribers and therefore limit the number of sponsor messages sent and attempt to ensure they are relevant and valuable offers.

_Collection of Information  
_The website will not sell, rent, trade or otherwise supply to third parties any information obtained unless consented to in each instance. **  
 **  
_News Personalisation  
_Upon subscription we collect information such as company details and job description. This information is collected in order to profile and better understand our audience. News categories are requested in order to provide relevant and personalised content and information. Subscriber details are protected and not supplied to outside organisations. _Sponsored Advertising Campaigns  
_We run sponsored advertising campaigns on behalf of other businesses. Advertisers and sponsors are at no time provided the details of our audience or subscribers. In instances when advertising campaigns require registration or request information, subscribers are made clearly aware that the response mechanism of the advertising campaign will send information to the sponsor, if readers/subscribers/visitors participate.

_Advertiser Requests_  
When website visitors send an email request (through an online form) to an advertiser, the website stores information such as (but not limited to): name, phone number and address, email and message details. Only the advertiser to whom the request was sent is provided with the full details and contact information of the individual or company from which the enquiry was sent. Requests are sent automatically to advertisers by email and the same information is stored and viewable in the advertisers' online management area. _Search Terms  
_When a search is performed, our system gathers basic information such as the search word, search term, date and the time the search was performed. We store and track this information for internal trend analysis. Information such as who performed the search is not gathered or tracked. _Directory Categories  
_When a category in our directory is clicked, our system gathers basic information such as the number of times each category is viewed. We store and track this information for internal trend analysis. Information such as who clicked the category is not gathered or tracked. _Content Statistics  
_When content (contact details, products, news, feature articles, events) is viewed or clicked upon our system gathers basic information such as the number of times content is viewed. We store and track this information for internal trend analysis as well as providing Activity Tracking reports to Storefront advertisers, so they can track and monitor the success of their advertising. Information such as who viewed or clicked content is not gathered or tracked. If visitors place a request to advertisers using one of our online forms then this information is stored and provided to advertisers.

_Secure Storage of Information_  
The website takes reasonable steps and has security measures designed to protect against the loss, misuse and/or alteration of information. We employ a number of means to protect information including:  
 (a) external and internal physical premises security;  
 (b) restricted access to customer information;  
 (c) maintaining technology products to prevent unauthorised computer access via networks (i.e. logical security), for example firewalls, password protection and data encryption;   
 (d) regular reviewing and testing of our technology in order to improve the level of security.  
Additionally, we take reasonable steps when we no longer require this information and it is our practice to securely destroy/delete it from our systems or alternatively, store it securely. 

_Updating or Removing Subscriber Details  
_The website provides options for accessing, modifying and removing subscriber details. Subscribers can choose an unsubscribe option or they may update or remove information online through the the website login facility at any time.

BACK TO TOP ^  
  

* * *

**  
System Specifications  
**  
_Search_  
The Storefront search is driven by the standard free text search algorithm provided by Microsoft SQL Server. The search is implemented uses using Microsoft SQL Sever 2005 fulltext search features known as "CONTAINSTABLE" and "FREETEXTTABLE". The "CONTAINSTABLE" feature make use of "search phrase" and the number of occurrence to derive the ranking for a Storefront whereas the "FREETEXTTABLE" search make use of a well known ranking formula called OKAPI BM25 to determine the ranking. The detail of each feature is provided in the following link [ http://msdn2.microsoft.com/en-us/library/ms142524.aspx](http://msdn2.microsoft.com/en-us/library/ms142524.aspx). The key highlights of the search using these feature is described below: 

  * A search looks within two databases: "Company" and "Products". The fields being searched in the "Company" database are "Business Name", "Description", "Keywords", "Comments", "City" and "State. For "Products" the fields being searched are "Name", "Introduction" and "Full Content".
  * A search calculates a ranking for each Storefront based on the search string provided by the user. The ranking is based on predefined search algorithms bundled with SQL Server 2005.
  * The search term and each individual term with-in the search string is ranked, and the values are summed to arrive at a final ranking score.
  * There are a large number of words which occurred very frequently and which are not helpful in resolving searches. Such words are referred to as noise words. For example words which linguists class as articles, such as the, a, and at are for the most part irrelevant in a search. This words are not included as part of search.
  * The rank for the terms is decided based on frequency of the term and the density or frequency of the search term occurring relative to the other terms. 
  * The search will also add words to the query via inflectional generation (stemmed forms of the original query terms); For example if the user query contains 'label' word, the search will also look for words like 'labeling', 'labeled' etc. These words are treated as separate terms with no special weighting or relationship with the words from which they were generated. 
  * Synonyms generated from the Thesaurus feature are treated as separate, equally weighted terms to determine ranking.



BACK TO TOP ^  

* * *

**  
CONTACTING INDUSTRACOM  
 **  
If you have any questions about privacy-related issues please contact the INDUSTRACOM Privacy Officer:

  WEBSITE: [www.industracom.com](http://www.industracom.com/)   
PHONE: +61 (02) 9925 4000  
FAX: +61 (02) 9925 4099  
Address: Level 8, 97 Pacific Highway, North Sydney  
Postal: PO Box 1597, North Sydney, NSW 2059 Australia  
Last updated: December 10, 2007

BACK TO TOP ^
