> *The following text is extracted and transformed from the hasin.wordpress.com privacy policy that was archived on 2011-10-04. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20111004221128id_/http%3A//en.wikipedia.org/wiki/P3P) for the most accurate reproduction.*

# P3P - Wikipedia, the free encyclopedia

From Wikipedia, the free encyclopedia

The **Platform for Privacy Preferences Project** , or **P3P** , is a [protocol](https://web.archive.org/wiki/Protocol_\(computing\) "Protocol \(computing\)") allowing [websites](https://web.archive.org/wiki/Website "Website") to declare their intended use of information they collect about browsing users. Designed to give users more control of their personal information when browsing, P3P was developed by the [World Wide Web Consortium](https://web.archive.org/wiki/World_Wide_Web_Consortium "World Wide Web Consortium") (W3C) and officially recommended on April 16, 2002.

## [[edit](https://web.archive.org/w/index.php?title=P3P&action=edit&section=1 "Edit section: Purpose")] Purpose

As the [World Wide Web](https://web.archive.org/wiki/World_Wide_Web "World Wide Web") became a genuine medium in which to sell products and services, [electronic commerce](https://web.archive.org/wiki/Electronic_commerce "Electronic commerce") websites tried to collect more information about the people who purchased their merchandise. Some companies used controversial practices such as tracker [cookies](https://web.archive.org/wiki/HTTP_cookie "HTTP cookie") to ascertain the users' [demographic](https://web.archive.org/wiki/Demographic_profile "Demographic profile") information and buying habits, using this information to provide specifically targeted advertisements. Users who saw this as an invasion of [privacy](https://web.archive.org/wiki/Privacy "Privacy") would sometimes turn off HTTP cookies or use [proxy servers](https://web.archive.org/wiki/Anonymous_proxy_server "Anonymous proxy server") to keep their personal information secure. P3P is designed to give users a more precise control of the kind of information that they allow to release. According to the W3C the main goal of P3P “is to increase user trust and confidence in the Web through technical empowerment.”[1]

P3P is a machine-readable language that helps to express a website’s data management practices. P3P manages information through privacy policies. When a website uses P3P, they set up a set of policies that allows them to state their intended uses of personal information that may be gathered from their site visitors. When a user decides to use P3P, they set their own set of policies and state what personal information they will allow to be seen by the sites that they visit. Then when a user visits a site, P3P will compare what personal information the user is willing to release, and what information the server wants to get – if the two do not match, P3P will inform the user and ask if he/she is willing to proceed to the site, and risk giving up more personal information.[1] As an example, a user may store in the browser preferences that information about their browsing habits should not be collected. If the policy of a Website states that a cookie is used for this purpose, the browser automatically rejects the cookie. The main content of a privacy policy is the following:

  * which information the server stores: 
    * which kind of information is collected (identifying or not);
    * which particular information is collected (IP address, email address, name, etc.);
  * use of the collected information: 
    * how this information is used (for regular navigation, tracking, personalization, telemarketing, etc.);
    * who will receive this information (only the current company, third party, etc.);
  * permanence and visibility: 
    * how long information is stored;
    * whether and how the user can access the stored information (read-only, optin, optout).



The privacy policy can be retrieved as an [XML](https://web.archive.org/wiki/XML "XML") file or can be included, in compact form, in the [HTTP](https://web.archive.org/wiki/HTTP "HTTP") header. The location of the XML policy file that applies to a given document can be:

  1. specified in the [HTTP](https://web.archive.org/wiki/HTTP "HTTP") header of the document
  2. specified in the [HTML](https://web.archive.org/wiki/HTML "HTML") head of the document
  3. if none of the above is specified, the _well-known location_ `/w3c/p3p.xml` is used (for a similar location compare `[/favicon.ico](https://web.archive.org/wiki/Favicon "Favicon")`)



P3P allows to specify a `max-age` for caching. A dummy `/w3c/p3p.xml` file could use this feature:
    
    
    <META xmlns="http://www.w3.org/2002/01/P3Pv1">
      <POLICY-REFERENCES>
        <EXPIRY max-age="10000000"/><!-- about four months -->
      </POLICY-REFERENCES>
    </META>
    

## [[edit](https://web.archive.org/w/index.php?title=P3P&action=edit&section=2 "Edit section: P3P user agents")] P3P user agents

[](https://web.archive.org/wiki/File:IE_P3P_Policy.png)

[Microsoft](https://web.archive.org/wiki/Microsoft "Microsoft") [Internet Explorer](https://web.archive.org/wiki/Internet_Explorer "Internet Explorer") provides the ability to display P3P privacy policies, and compare the P3P policy with your own settings to decide whether or not to allow cookies from a particular site. However, the P3P functionality in Internet Explorer extends only to cookie blocking, and will not alert you to an entire web site that violates your privacy preferences. Users who wish to use a full P3P user agent should use the [AT&T](https://web.archive.org/wiki/AT%26T "AT&T") Privacy Bird,[2] which is now maintained by [Carnegie Mellon's](https://web.archive.org/wiki/Carnegie_Mellon_University "Carnegie Mellon University") [Usable Privacy and Security Laboratory](https://web.archive.org/wiki/CUPS_\(CMU\) "CUPS \(CMU\)").

The Privacy Finder[3] service was also created by [Carnegie Mellon's](https://web.archive.org/wiki/Carnegie_Mellon_University "Carnegie Mellon University") [Usable Privacy and Security Laboratory](https://web.archive.org/wiki/CUPS_\(CMU\) "CUPS \(CMU\)"). It is a publicly available "P3P-enabled search engine." A user can enter a search term along with their stated privacy preferences, and is then presented with a list of search results which are ordered based on whether the sites comply with their preferences. This works by crawling the web and maintaining a P3P cache for every site that ever appears in a search query. The cache is updated every 24 hours so that every policy is guaranteed to be relatively up to date. The service also allows users to quickly determine why a site does not comply with their preferences, as well as allowing them to view a dynamically generated natural language privacy policy based on the P3P data. This is advantageous over simply reading the original natural language privacy policy on a web site because many privacy policies are written in legalese and are extremely convoluted. Additionally, in this case the user does not have to visit the web site to read its privacy policy.

## [[edit](https://web.archive.org/w/index.php?title=P3P&action=edit&section=3 "Edit section: Benefits")] Benefits

P3P allows browsers to understand their privacy policies in a simplified and organized manner rather than searching throughout the entire website. By setting your own privacy settings on a certain level, P3P will automatically block any cookies that you might not want on your computer. Additionally, the W3C explains that P3P will allow browsers to transfer user data to services, ultimately promoting an online sharing community.

Additionally, the P3P Toolbox[4] developed by the Internet Education Foundation recommends, that anyone who is concerned about increasing their users’ trust and privacy should consider implementing P3P. The P3P toolbox site explains how companies have taken individuals data in order to promote new products or services. Furthermore, in recent years companies have taken individuals information and created profiles, which they then market without the individuals consent. Moreover, all this data is misused and we as consumers pay the price and become worrisome of issues such as: junk mail, identity theft and forms of discrimination; therefore implementing P3P's protocol is good and beneficial for internet browsers.

Moreover, since there has been an increase of browsers there are more users at risk running into privacy problems. But the Internet Education Foundation points out that, “P3P has been developed to help steer the force of technology a step further toward automatic communication of data management practices and individual privacy preferences.”[4]

## [[edit](https://web.archive.org/w/index.php?title=P3P&action=edit&section=4 "Edit section: Criticisms")] Criticisms

The [Electronic Privacy Information Center](https://web.archive.org/wiki/Electronic_Privacy_Information_Center "Electronic Privacy Information Center") (EPIC) has been critical of P3P and believes P3P makes it too difficult for users to protect their privacy.[5] In 2002 it assessed P3P, and referred to the technology as a “Pretty Poor Policy”.[5] According to the EPIC, some P3P software is too complex and difficult for the average person to understand, and many Internet users are unfamiliar with how to use the default P3P software on their computers or how to install additional P3P software. Another concern is that websites are not obligated to use P3P, and neither are Internet users. P3P has been known to undermine public confidence by collecting enormous amounts of information that can be used against its user. Moreover, the EPIC website claims that P3Ps protocol would become burdensome for the browser and not as beneficial or efficient as it was intended to be.

The basic idea of privacy protection can be misleading to the visitors on the site. For example, people think that their privacy is actually being protected, but it is not. P3P facilitates data collection from websites. If the actual intention of P3P was to protect visitors to web sites then the information gathering would not be so easy to pass along personal information. Also, people who visit websites where P3P is present are uninformed and misunderstand the level of privacy that P3P provides. There needs to be more effective ways of educating people on the level of privacy and what P3P actually does to protect people.

Another main concern is that the data that is collected does not have an expiration date. People who buy something on the internet will have that information saved for an infinite amount of time, whether it will be recorded for a year or ten. This problem has led people to question where their information is being distributed to and for how long third parties will have access to their information. The idea that people’s personal information can be distributed to other people for an indeterminate amount of time makes people very uncomfortable.

A key problem that occurs with the use of P3P is that there is a lack of enforcement. Thus, promises made to users of P3P can go unfulfilled. Though by using P3P a company/website makes a promise of privacy and of the use of gathered data to the site’s users, there are no real legal ramifications if the company decides to use the information for other functions. Currently, there are no actual laws that have been passed by the [United States](https://web.archive.org/wiki/United_States "United States") about data protection. Though it would be nice to be able to trust every company that states its use for our information, there is no binding reason that the company must actually adhere to the rules it says it will comply by. Though using P3P technically qualifies as a contract, the lack of federal regulation downplays the need for companies to abide.[6]

The agreement to use P3P not only puts in place unenforceable promises, but it also prolongs the adoption of federal laws that would actually inhibit the access and ability to use private information. If the government were to step in and attempt to protect Internet users with federal laws on what information can be accessed, and specific regulations on how user information can be used, companies wouldn’t maintain the leeway they do now to use information as they please, despite what they may actually tell users. In 2002, then EPIC employee Chris Hoofnagle argued that P3P was displacing chances for government regulation of privacy.[7]

Critics of P3P also argue that non-compliant sites are excluded. According to a study done by CyLab Privacy Interest Group at [Carnegie Mellon University](https://web.archive.org/wiki/Carnegie_Mellon_University "Carnegie Mellon University") [8] only 15% of the top 5,000 websites incorporate P3P. Therefore many sites that don’t include the code but do practice high privacy standards will not be accessible to users who use P3P as their only online privacy guide.

EPIC, the technology's obviously largest critic, also talks about how the development and implementation of P3P can cause a monopoly of private information. Since it tends to be only major companies who implement P3P on their websites, only these major companies are tending to then gather this information seeing as only their privacy policies can compare to privacy preferences of users. The EPIC website says, "The incredible complexity of P3P, combined with the way that popular browsers are likely to implement the protocol would seem to preclude it as a privacy-protective technology," EPIC continues on to state, "Rather, P3P may actually strengthen the monopoly position over personal information that U.S. data marketers now enjoy."[5]

The failure for its immediate adoption can be related to the idea of it being a notice and choice approach that doesn’t comply with the Fair Information Practices. According to the Chairman of the FTC,[9] privacy laws are key in today’s society in order to protect the consumer from providing too much personal information for other’s benefit. Some believe that there should be a limit to the collection and use of the consumer’s personal data online. Currently sites are not required under any United States laws to comply with the privacy policies they publish, therefore P3P causes some controversy with consumers who are concerned about the release of their personal information and are only able to rely on P3P’S protocol to protect their privacy.

As people become comfortable with P3P, the technology may be limiting the perceived need of related privacy legislation.

Michael Kaply from IBM is reported saying the following when the [Mozilla Foundation](https://web.archive.org/wiki/Mozilla_Foundation "Mozilla Foundation") was considering the removal of P3P support from their browser-line:[10]

> _Ah the memories._ _We (IBM) wrote the original P3P implementation and then Netscape proceeded to write their own. So both our companies wasted immense amounts of time that everyone thought was a crappy proposal to begin with._ _Remove it._

Live Leer, a PR manager for [Opera Software](https://web.archive.org/wiki/Opera_Software "Opera Software"), explains the deliberate lack of P3P support in their browser:[11]

> _At the moment, we aren't sure whether P3P is the best solution._ _P3P is among the specifications we are considering for support in the future. There have been some issues with how well P3P will protect privacy, and for that reason we have decided to wait until these are resolved._

## [[edit](https://web.archive.org/w/index.php?title=P3P&action=edit&section=5 "Edit section: Alternatives")] Alternatives

P3P user agents are not the only option available for Internet users that want to ensure their [privacy](https://web.archive.org/wiki/Internet_privacy "Internet privacy"). Two of the main alternatives to P3P include [anonymous e-mailers](https://web.archive.org/wiki/Anonymous_remailer "Anonymous remailer") and [anonymous proxy servers](https://web.archive.org/wiki/Anonymizer "Anonymizer").

The main alternative to P3P may not be these technologies, but instead stronger laws to regulate what kind of information from Internet users can be collected and retained by websites. For example, in Europe the [Data Protection Directive](https://web.archive.org/wiki/Data_Protection_Directive "Data Protection Directive") provides individuals with a certain set of principles about how personal information is collected and the person's rights to protecting their personal data.[12] The act allows individuals to control the type of information that is being collected from them. Various principles are included within the act, such the rule that individual has the right to retrieve the data collected about them at any time under certain conditions. Moreover, the individual's personal information cannot be kept longer than necessary, and personal information cannot be released to others unless the individual gives their consent.

Currently, the United States has no federal law protecting the privacy of personal information shared online. However, there are some sectoral laws at the federal and state level that offer some protection for certain types of information collected about individuals.[13] For example, the [Fair Credit Reporting Act](https://web.archive.org/wiki/Fair_Credit_Reporting_Act "Fair Credit Reporting Act") (FCRA) of 1970 makes it legal for consumer reporting agencies to disclose personal information only under three specified circumstances: credit, employment or insurance evaluation; government grant or license; or a “legitimate business need” that involves the consumer. A list of other sectoral privacy laws in the United States can be viewed at the Consumer Privacy Guide's website.[13]

## [[edit](https://web.archive.org/w/index.php?title=P3P&action=edit&section=6 "Edit section: The future of P3P")] The future of P3P

There are many groups who are working to further the future of P3P to make it easier for people to use. Some of these groups are:

[Transparent Accountable Datamining Initiative](https://web.archive.org/w/index.php?title=Transparent_Accountable_Datamining_Initiative&action=edit&redlink=1 "Transparent Accountable Datamining Initiative \(page does not exist\)") (TAMI) is a group out of [MIT](https://web.archive.org/wiki/Massachusetts_Institute_of_Technology "Massachusetts Institute of Technology")’s Computer Science and Artificial Intelligence Laboratory. The goal of TAMI is to create technical, legal, and policy foundations for transparency and accountability in large-scale aggregation. TAMI hopes to help people manage privacy risks in a world where technology is constantly changing.

[Policy Aware Web](https://web.archive.org/w/index.php?title=Policy_Aware_Web&action=edit&redlink=1 "Policy Aware Web \(page does not exist\)") (PAW) is a scalable mechanism for the exchange of rules and proofs for unlimited access control to the Web. “It creates a system of Policy Aware infrastructure using systematic Web rules language with a theorem prover”.[14]

## [[edit](https://web.archive.org/w/index.php?title=P3P&action=edit&section=7 "Edit section: See also")] See also

  * [Internet privacy](https://web.archive.org/wiki/Internet_privacy "Internet privacy")
  * [Identity management](https://web.archive.org/wiki/Identity_management "Identity management")
  * [Privacy policy](https://web.archive.org/wiki/Privacy_policy "Privacy policy")



## [[edit](https://web.archive.org/w/index.php?title=P3P&action=edit&section=8 "Edit section: References")] References

## [[edit](https://web.archive.org/w/index.php?title=P3P&action=edit&section=9 "Edit section: External links")] External links

  * [W3C P3P site](http://www.w3.org/P3P/)
  * [W3C P3P Specifications](http://www.w3.org/TR/P3P/)
  * [P3P in Internet Explorer 6](http://msdn2.microsoft.com/en-us/library/ms537343.aspx)
  * [Center for Democracy and Technology: P3P Privacy](http://www.cdt.org/privacy/pet/p3pprivacy.shtml)



[v](https://web.archive.org/wiki/Template:W3C_standards "Template:W3C standards") **·** [d](https://web.archive.org/wiki/Template_talk:W3C_standards "Template talk:W3C standards") **·** [e](https://en.wikipedia.org/w/index.php?title=Template:W3C_standards&action=edit)[World Wide Web Consortium](https://web.archive.org/wiki/World_Wide_Web_Consortium "World Wide Web Consortium")  
---  
Products and  
standards |  | 

[Recommendations](https://web.archive.org/wiki/W3C_recommendation "W3C recommendation")

| 

[Canonical XML](https://web.archive.org/wiki/Canonical_XML "Canonical XML")  **·** [CDF](https://web.archive.org/wiki/Compound_Document_Format "Compound Document Format")  **·** [CSS](https://web.archive.org/wiki/Cascading_Style_Sheets "Cascading Style Sheets")  **·** [DOM](https://web.archive.org/wiki/Document_Object_Model "Document Object Model")  **·** [Geolocation API](https://web.archive.org/wiki/W3C_Geolocation_API "W3C Geolocation API")  **·** [HTML](https://web.archive.org/wiki/HTML "HTML")  **·** [ITS](https://web.archive.org/wiki/Internationalization_Tag_Set "Internationalization Tag Set")  **·** [MathML](https://web.archive.org/wiki/MathML "MathML")  **·** [OWL](https://web.archive.org/wiki/Web_Ontology_Language "Web Ontology Language")  **·** **P3P**   **·** [PLS](https://web.archive.org/wiki/Pronunciation_Lexicon_Specification "Pronunciation Lexicon Specification")  **·** [RDF](https://web.archive.org/wiki/Resource_Description_Framework "Resource Description Framework")  **·** [RDF Schema](https://web.archive.org/wiki/RDF_Schema "RDF Schema")  **·** [SISR](https://web.archive.org/wiki/Semantic_Interpretation_for_Speech_Recognition "Semantic Interpretation for Speech Recognition")  **·** [SKOS](https://web.archive.org/wiki/Simple_Knowledge_Organization_System "Simple Knowledge Organization System")  **·** [SMIL](https://web.archive.org/wiki/Synchronized_Multimedia_Integration_Language "Synchronized Multimedia Integration Language")  **·** [SOAP](https://web.archive.org/wiki/SOAP "SOAP")  **·** [SRGS](https://web.archive.org/wiki/Speech_Recognition_Grammar_Specification "Speech Recognition Grammar Specification")  **·** [SSML](https://web.archive.org/wiki/Speech_Synthesis_Markup_Language "Speech Synthesis Markup Language")  **·** [SVG](https://web.archive.org/wiki/Scalable_Vector_Graphics "Scalable Vector Graphics")  **·** [SPARQL](https://web.archive.org/wiki/SPARQL "SPARQL")  **·** [Timed Text](https://web.archive.org/wiki/Timed_Text "Timed Text")  **·** [VoiceXML](https://web.archive.org/wiki/VoiceXML "VoiceXML")  **·** [WSDL](https://web.archive.org/wiki/Web_Services_Description_Language "Web Services Description Language")  **·** [XForms](https://web.archive.org/wiki/XForms "XForms")  **·** [XHTML](https://web.archive.org/wiki/XHTML "XHTML")  **·** [XHTML+RDFa](https://web.archive.org/wiki/XHTML%2BRDFa "XHTML+RDFa")  **·** [XInclude](https://web.archive.org/wiki/XInclude "XInclude")  **·** [XLink](https://web.archive.org/wiki/XLink "XLink")  **·** [XML](https://web.archive.org/wiki/XML "XML")  **·** [XML Base](https://web.archive.org/wiki/XML_Base "XML Base")  **·** [XML Encryption](https://web.archive.org/wiki/XML_Encryption "XML Encryption")  **·** [XML Events](https://web.archive.org/wiki/XML_Events "XML Events")  **·** [XML Information Set](https://web.archive.org/wiki/XML_Information_Set "XML Information Set")  **·** [XML namespace](https://web.archive.org/wiki/XML_namespace "XML namespace")  **·** [XML Schema](https://web.archive.org/wiki/XML_Schema_\(W3C\) "XML Schema \(W3C\)")  **·** [XML Signature](https://web.archive.org/wiki/XML_Signature "XML Signature")  **·** [XPath](https://web.archive.org/wiki/XPath "XPath") [1.0](https://web.archive.org/wiki/XPath_1.0 "XPath 1.0"), [2.0](https://web.archive.org/wiki/XPath_2.0 "XPath 2.0")  **·** [XPointer](https://web.archive.org/wiki/XPointer "XPointer")  **·** [XProc](https://web.archive.org/wiki/XProc "XProc")  **·** [XQuery](https://web.archive.org/wiki/XQuery "XQuery")  **·** [XSL](https://web.archive.org/wiki/Extensible_Stylesheet_Language "Extensible Stylesheet Language")  **·** [XSL-FO](https://web.archive.org/wiki/XSL_Formatting_Objects "XSL Formatting Objects")  **·** [XSLT](https://web.archive.org/wiki/XSLT "XSLT") ([elements](https://web.archive.org/wiki/XSLT_elements "XSLT elements"))  
  
---|---  
  
Notes

| 

[XAdES](https://web.archive.org/wiki/XAdES "XAdES")  **·** [XHTML+SMIL](https://web.archive.org/wiki/XHTML%2BSMIL "XHTML+SMIL")  **·** [XUP](https://web.archive.org/wiki/Extensible_User_Interface_Protocol "Extensible User Interface Protocol")  
  
Working Drafts

| 

[CCXML](https://web.archive.org/wiki/Call_Control_eXtensible_Markup_Language "Call Control eXtensible Markup Language")  **·** [CURIE](https://web.archive.org/wiki/CURIE "CURIE")  **·** [HTML5](https://web.archive.org/wiki/HTML5 "HTML5")  **·** [InkML](https://web.archive.org/wiki/InkML "InkML")  **·** [RIF](https://web.archive.org/wiki/Rule_Interchange_Format "Rule Interchange Format")  **·** [SCXML](https://web.archive.org/wiki/SCXML "SCXML")  **·** [SMIL Timesheets](https://web.archive.org/wiki/SMIL_Timesheets "SMIL Timesheets")  **·** [sXBL](https://web.archive.org/wiki/SXBL "SXBL")  **·** [WICD](https://web.archive.org/wiki/Web_Integration_Compound_Document "Web Integration Compound Document")  **·** [XFDL](https://web.archive.org/wiki/Extensible_Forms_Description_Language "Extensible Forms Description Language")  **·** [XFrames](https://web.archive.org/wiki/XFrames "XFrames")  **·** [XBL](https://web.archive.org/wiki/XBL "XBL")  **·** [XHTML+MathML+SVG](https://web.archive.org/wiki/XHTML%2BMathML%2BSVG "XHTML+MathML+SVG")  **·** [XMLHttpRequest](https://web.archive.org/wiki/XMLHttpRequest "XMLHttpRequest")  
  
Guidelines

| 

[Web Content Accessibility Guidelines](https://web.archive.org/wiki/Web_Content_Accessibility_Guidelines "Web Content Accessibility Guidelines")  
  
Initiative

| 

[Multimodal Interaction Activity](https://web.archive.org/wiki/W3C_MMI "W3C MMI")  **·** [Markup Validation Service](https://web.archive.org/wiki/W3C_Markup_Validation_Service "W3C Markup Validation Service")  **·** [Web Accessibility Initiative](https://web.archive.org/wiki/Web_Accessibility_Initiative "Web Accessibility Initiative")  
  
Deprecated

| 

[C-HTML](https://web.archive.org/wiki/C-HTML "C-HTML")  **·** [HDML](https://web.archive.org/wiki/Handheld_Device_Markup_Language "Handheld Device Markup Language")  **·** [JSSS](https://web.archive.org/wiki/JavaScript_Style_Sheets "JavaScript Style Sheets")  **·** [PGML](https://web.archive.org/wiki/Precision_Graphics_Markup_Language "Precision Graphics Markup Language")  **·** [VML](https://web.archive.org/wiki/Vector_Markup_Language "Vector Markup Language")  
  
Organizations | 

[World Wide Web Foundation](https://web.archive.org/wiki/World_Wide_Web_Foundation "World Wide Web Foundation")  **·** [SVG Working Group](https://web.archive.org/wiki/SVG_Working_Group "SVG Working Group")  **·** [WebOnt](https://web.archive.org/wiki/WebOnt "WebOnt")  **·** [W3C Device Description Working Group](https://web.archive.org/wiki/W3C_Device_Description_Working_Group "W3C Device Description Working Group")  **·** [WHATWG](https://web.archive.org/wiki/Web_Hypertext_Application_Technology_Working_Group "Web Hypertext Application Technology Working Group")  
  
Software | 

[Agora](https://web.archive.org/wiki/Agora_\(web_browser\) "Agora \(web browser\)")  **·** [Argo](https://web.archive.org/wiki/Argo_\(web_browser\) "Argo \(web browser\)")  **·** [Arena](https://web.archive.org/wiki/Arena_\(web_browser\) "Arena \(web browser\)")  **·** [Amaya](https://web.archive.org/wiki/Amaya_\(web_browser\) "Amaya \(web browser\)")  **·** [CERN httpd](https://web.archive.org/wiki/CERN_httpd "CERN httpd")  **·** [Libwww](https://web.archive.org/wiki/Libwww "Libwww")  **·** [Line Mode Browser](https://web.archive.org/wiki/Line_Mode_Browser "Line Mode Browser")  
  
Conference-related | 

[IW3C2](https://web.archive.org/wiki/The_International_World_Wide_Web_Conferences_Steering_Committee "The International World Wide Web Conferences Steering Committee")  **·** [World Wide Web Conference](https://web.archive.org/wiki/World_Wide_Web_Conference "World Wide Web Conference")  **·** [WWW1](https://web.archive.org/wiki/World_Wide_Web_Conference_1 "World Wide Web Conference 1")
