> *The following text is extracted and transformed from the rvtraderonline.com privacy policy that was archived on 2002-12-06. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20021206035606id_/http%3A//www.rvtraderonline.com/about.html%3Fview%3Dprivacy) for the most accurate reproduction.*

# About RV Trader Online

|  | 

Trader Online Privacy Policy

**Privacy Policy for TraderOnline.com**

  1. What information is collected?
  2. How is the information collected?
  3. How information will be used?
  4. User choices in receiving and distribution of information
  5. Data Security
  6. Data Quality and Access
  7. Questions



**I. What information is collected?**

  * Personal Information:  
We require personal contact information and vehicle information from our members. The required information is used to effectively and accurately create, maintain, and display TraderOnline.com's classified services. The required vehicle information varies with each site of the TraderOnline.com network depending on the industry and its relevant data.
  * Cookies:  
Some sites in the TraderOnline.com network utilize cookies in order to provide members and merchants with a more personalized experience by remembering who you are when you revisit the site. Cookies also track visitor activity and traffic patterns among the sites so that we can identify users' interests and behavior. With this information, we can improve existing user services and develop new products appropriate for our audience.   
back to the top



**II. How is the information collected?**

  * Members are requested to submit personal and vehicle information using the online Email Notify, Place An Ad, Dealer and My Trader services. Users unwilling to pass personal information online can choose to work with a sales representative or customer service representative to utilize member services.   
back to the top



**III. How information will be used?**

  * Resale and Disclosure of Information  
Trader Publishing Company reserves the right to sell or disclose some personal information collected on our site to third parties. We may provide third parties with non-exclusive, limited use of Trader Publishing Company's collected information in order for the third party to promote and market the third party's service. Any right of the third party to distribute, transfer, transmit, or re-sell Trader Publishing Company's information is prohibited.
  * Privacy of TraderOnline.com Email Lists  
We collect and record personal information in order to maintain email lists. We utilize the emails to keep members informed of the site services, site performance, promotions, and offer information regarding industry related services and products.   
back to the top



**IV. User choices in receiving and distribution of information**

  * TraderOnline.com Email Lists  
Dealer members receive monthly emails informing them of special promotions and advertising tips. Dealers wishing not receive the mailer can send a request via email to be removed from the mailing list. Private party members automatically receive an email to confirm their placement on our site and to give them the necessary information to edit and delete their classified ads. Private parties also receive notification of ad renewal opportunities. Trader Publishing Company reserves the right to include third party advertisements that provide additional services to members in the confirmation emails.
  * Third Party Distribution  
Private party members may receive information directly from third parties that have related services. Private parties that do not wish to receive the third party information can opt-out of the service at the time they place an ad with TraderOnline.com. Third parties receive only the needed personal information in order to effectively target members' needs and interests. Third parties have non-exclusive, limited use of the information provided by Trader Publishing Company. Any right of the third party to distribute, transfer, transmit, or re-sell Trader Publishing Company's information is prohibited.   
back to the top



**V. Data Security**

  * Personal Information  
To protect the member's account information, TraderOnline.com assigns each member with either a unique user name or password or a unique ad ID number. These unique identifiers are disclosed to the user via email immediately upon joining the TraderOnline.com network. Only members have the ability to modify their personal information and delete their ads as needed.
  * Credit Card Transactions  
TraderOnline.com works off an all UNIX house and uses Checkpoint Firewall-1 software to insure the security and reliability of the TraderOnline.com network. We work in compliance with Verisign Certification and transmit all online credit card transaction in an encrypted format.   
back to the top



**VI. Data Quality and Access**

  * Members may access their information 24 hours a day using their designated user name and password or ad ID number. Members may modify or delete their information as needed. Private party users may cancel their service at anytime and dealer members may cancel their service after submitting 30 days written notice to Trader Publishing Company.   
back to the top


**VIII. Questions**

  * If you have further questions that were not addressed in the above privacy policy, please contact Trader Publishing Company Legal Department at 757-640-4000 or email [webmaster@traderonline.com](mailto:webmaster@traderonline.com).   
back to the top



|  |   
---|---|---|---|---  
  
* * *

**Queries**
    
    
     **cSpecial** (Records=1, Time=Cached Query)
    SQL = 
    select http_host, special_text_4 
       from site_information 
       where http_host = 'www.rvtraderonline.com'
    
    **site** (Records=1, Time=311ms)
    SQL = 
    SELECT        A.HTTP_HOST,
    				A.REALM_ID,
    				A.COLOR_1,
    				A.COLOR_2,
    				A.COLOR_3,
    				A.COLOR_4,
    				A.COLOR_5,
    				A.COLOR_6,
    				A.COLOR_7,
    				A.COLOR_8,
    				A.COLOR_9,
    				A.COLOR_10,
    				A.STYLE_SHEET,
    				A.NAME_PREFIX,
    				A.OFFICIAL_NAME,
    				A.FONT_1,
    				A.FONT_2,
    				A.SPECIAL_TEXT_1 AS SITE_SPECIAL_TEXT_1,
    				A.SPECIAL_TEXT_2 AS SITE_SPECIAL_TEXT_2,
    				A.SPECIAL_TEXT_3 AS SITE_SPECIAL_TEXT_3,
    				A.SPECIAL_TEXT_4 AS SITE_SPECIAL_TEXT_4,
    				B.PAGE_TITLE,
    				B.PAGE_TEMPLATE,
    				B.CAT_ID,
    				B.SPECIAL_TEXT_1 AS PAGE_SPECIAL_TEXT_1,
    				B.SPECIAL_TEXT_2 AS PAGE_SPECIAL_TEXT_2,
    				B.SPECIAL_TEXT_3 AS PAGE_SPECIAL_TEXT_3,
    				B.SPECIAL_TEXT_4 AS PAGE_SPECIAL_TEXT_4,
    				B.WEB_PAGE,
    				B.META_DESCRIPTION,
    				B.META_KEYWORDS,
    				B.META_URL,
    				B.META_CLASSIFICATION,
    				B.META_SUBJECT,
    				B.CAT_ID as AREA
    FROM 			SITE_INFORMATION A, PAGE_INFORMATION B
    WHERE 			A.HTTP_HOST = B.HTTP_HOST
    AND 			A.HTTP_HOST = 'www.rvtraderonline.com'
    AND				B.WEB_PAGE  = 'aboutpage'
    
    **realmcounts** (Records=1, Time=Cached Query)
    SQL = 
    SELECT		REALM_ID,
    	            AD_ROWS,
    				DEALER_ROWS,
    				PART_ROWS
    	FROM		REALM
    	WHERE		REALM_ID = 3
    
    **qGetMags** (Records=2, Time=Cached Query)
    SQL = 
    SELECT		a.MAGAZINE_ID,
    	            b.MAGAZINE_ID,
    	            a.TITLE, 
    				a.HTTP_HOST,
    				a.REALM_ID,
    				b.REALM_ID
    	FROM		SITE_MAGAZINE a, SITE_MAGAZINE_PRICE b
    	WHERE 		a.MAGAZINE_ID = b.MAGAZINE_ID
       	
    	 AND		a.REALM_ID = 3
    	 AND 		b.REALM_ID = 3
    
    **qGetService** (Records=2, Time=Cached Query)
    SQL = 
    SELECT		 *
    		FROM		SITE_ADVERTISER2
    		WHERE		HTTP_HOST = 'www.rvtraderonline.com'
    		AND ADVERTISER_ID <> 21
    		ORDER BY	ORDER_BY
    
    ****(Records=1, Time=12ms)
    SQL = 
    REFCURSORS.GET_SITE **qGetMags** (Records=2, Time=Cached Query)
    SQL = 
    SELECT		a.TITLE, 
    				a.DESCRIPTION,
    				b.DURATION, 
    				b.PRICE, 
    				b.PRICE_ID,
    				a.REALM_ID,
    				a.HTTP_HOST,
    				a.MAGAZINE_ID 
    	FROM		SITE_MAGAZINE a, SITE_MAGAZINE_PRICE b
    	WHERE 		a.MAGAZINE_ID = b.MAGAZINE_ID	
    	
    	AND			a.REALM_ID = 3
    	AND 		b.REALM_ID = 3
    

* * *

**Execution Time**
    
    
    525 milliseconds

18 ms| /OPT/COLDFUSION/CUSTOMTAGS/ADDELIVERY.CFM  
---|---  
44 ms| /OPT/COLDFUSION/CUSTOMTAGS/SIMPLESITEINFO.CFM  
34 ms| /OPT/COLDFUSION/CUSTOMTAGS/SITEINFO.CFM  
4 ms| /WWW/FILES/COLDFUSION/ABOUT.HTML  
8 ms| /WWW/FILES/COLDFUSION/HTML/MASTER/MASTER_ABOUTPAGE.HTML  
11 ms| /WWW/FILES/COLDFUSION/HTML/MASTER/MASTER_TOPNAV.HTML  
3 ms| /WWW/FILES/COLDFUSION/HTML/RVTOL/RVTOL_NAVCODE.HTML  
15 ms| /WWW/FILES/COLDFUSION/HTML/RVTOL/RVTOL_NAVPAGE.HTML  
42 ms| /WWW/FILES/COLDFUSION/IMG/TOGGLES/TOGGLES.HTML  
21 ms| /WWW/FILES/COLDFUSION/INCLUDE/MYTRADER_DEFAULTS.HTML  
0 ms| /WWW/FILES/COLDFUSION/INCLUDE/OPENWIN.CFM  
1 ms| /WWW/FILES/COLDFUSION/INCLUDE/PRIVACY.HTML  
322 ms| /WWW/FILES/COLDFUSION/INCLUDE/SITEINFO/CALLER_SITE.QUERY  
1 ms| /WWW/FILES/COLDFUSION/INCLUDE/TOGGLES.HTML  
2 ms| STARTUP, PARSING, & SHUTDOWN  
  
* * *

**Parameters**
    
    
     **Form Fields:**
    
    MYTRADERFLAG=down
    MYTRADERHOST=www.rvtraderonline.com
    TARGET_STRING=None
    
    **URL Parameters:**
    
    CID=0
    IS_LACONIA=no
    RC=n
    SIGNIN=NO
    VIEW=privacy
    
    **CGI Variables:**
    
    AUTH_GROUP=
    AUTH_TYPE=
    AUTH_USER=
    CF_TEMPLATE_PATH=/www/files/coldfusion/about.html
    CLIENT_CERT=
    CLIENT_CERT_ISSUER_DN=
    CLIENT_CERT_SSL_ID=
    CLIENT_CERT_USER_DN=
    CONTENT_LENGTH=
    CONTENT_TYPE=
    HTTP_CONNECTION=Keep-Alive
    HTTP_FROM=crawler@alexa.com
    HTTP_HOST=www.rvtraderonline.com
    HTTP_REMIP=209.237.238.163
    HTTP_USER_AGENT=ia_archiver
    HTTP_VIA=1.0 redline (Redline Networks Accelerator 2.1.15 TX_RELEASE_2_1_15)
    PATH_INFO=
    PATH_TRANSLATED=/www/files/coldfusion/about.html
    QUERY_STRING=view=privacy
    REMOTE_ADDR=10.222.132.190
    REMOTE_HOST=
    REMOTE_USER=
    REQUEST_METHOD=GET
    SCRIPT_NAME=/about.html
    SERVER_NAME=www.rvtraderonline.com
    SERVER_PORT=80
    SERVER_PROTOCOL=HTTP/1.1
    SERVER_SOFTWARE=Netscape-Enterprise/3.6 SP3
    
    
