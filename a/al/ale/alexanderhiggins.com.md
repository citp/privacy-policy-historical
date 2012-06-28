> *The following text is extracted and transformed from the alexanderhiggins.com privacy policy that was archived on 2012-06-28. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20120628234501id_/http%3A//blog.alexanderhiggins.com/2012/04/26/national-cyber-security-services-pilot-privacy-impact-assessment-127201) for the most accurate reproduction.*

# National Cyber Security Services Pilot Privacy Impact Assessment

  Posted by ****\- April 26, 2012 at 3:21 pm -[Permalink ](http://blog.alexanderhiggins.com/2012/04/26/national-cyber-security-services-pilot-privacy-impact-assessment-127201/ "Permanent Link to National Cyber Security Services Pilot Privacy Impact Assessment") \- [Source ]( "Source Link To National Cyber Security Services Pilot Privacy Impact Assessment") via [Alexander Higgins Blog]( "Link To Alexander Higgins Blog")

### Riddled with carefully parsed and misleading statements here is the latest privacy impact assessment of the DHS Cyber Security program.

The current DHS cybersecurity pilot being implemented by the federal government will soon become entangled in every aspect of your daily life.

Digging through the currently available documentation on the US government website the massive scale and the gravity of the current program becomes clear.

Carefully parsed statements attempt to mitigate operations in one document but further disclosure in another document reveals sinister motivations.

This document reveals many things, such as how the government avoids admitting [**sharing data collected of federal network s directly with India and Israel with absolutely no oversight or controls**](http://blog.alexanderhiggins.com/2012/04/26/dhs-forwarding-federal-internet-data-israel-india-127101/) reveal in the Einstein program impact assessment.

Furthermore, this assessment reveals how the carefully parsed words in the Einstein assessment fail to reveal the implications, depth, or severity of information being collection.

Among other things, it shows how the federal government has redefined common computer phrases such as a database to store and mine data in ways that get around laws and legislation enacted by congress to limit the government’s ability to spy without a warrant or proper oversight.

[](http://cdn1.alexanderhiggins.com/wp-content/uploads/2012/04/National-Cyber-Security-Services-Pilot-Privacy-Impact-Assessment.png)

National Cyber Security Services Pilot Privacy Impact Assessment

### Privacy Impact Assessment  
for the

## National Cyber Security Division  
Joint Cybersecurity Services Pilot (JCSP)  
DHS/NPPD-021

### January 13, 2012

**Contact Point**

Brendan Goode  
Director, Network Security Deployment  
National Cyber Security Division  
National Protection and Programs Directorate  
Department of Homeland Security  
(703) 235-2853

**Reviewing Official**

Mary Ellen Callahan  
Chief Privacy Officer  
Department of Homeland Security  
(703) 235-078

### Abstract

The Department of Homeland Security (DHS) and the Department of Defense (DoD) are jointly undertaking a proof of concept known as the Joint Cybersecurity Services Pilot (JCSP).The JCSP extends the existing operations of the Defense Industrial Base (DIB) Exploratory Cybersecurity Initiative (DIB Opt-In Pilot) and shifts the operational relationship with the CSPs in the pilot to DHS. The JCSP is part of overall efforts by DHS and DoD to enable the provision of cybersecurity capabilities enhanced by U.S. government information to protect critical infrastructure information systems and networks. The purpose of the JCSP is to enhance the cybersecurity of participating DIB critical infrastructure entities and to protect sensitive DoD information and DIB intellectual property that directly supports DoD missions or the development of DoD capabilities from unauthorized access, exfiltration, and exploitation. The National Protection and Programs Directorate (NPPD) is conducting this Privacy Impact Assessment (PIA) on behalf of DHS because some known or suspected cyber threat information shared under the JCSP may contain information that could be considered personally identifiable information (PII).

### Overview

The Joint Cybersecurity Services Pilot (JCSP) is being conducted pursuant to authorityderived from the Homeland Security Act, including 6 U.S.C. §§ 121, 143; 10 U.S.C. § 2224; the Federal Information Security Management Act (FISMA), including 44 U.S.C. § 3544; Homeland Security Presidential Directive 7, Critical Infrastructure Identification, Prioritization, and Protection; and Homeland Security Presidential Directive 23, Cybersecurity Policy.

During the Defense Industrial Base (DIB) Exploratory Cybersecurity Initiative (DIB Opt-In Pilot), 1 DoD shared classified indicators associated with cyber threat countermeasure2 capabilities directly with commercial service providers (CSPs)3 in order to protect information on DIB company networks. The DIB Opt-In Pilot focused on two cyber threat countermeasures:1) the ability to block Domain Network System (DNS) traffic to malicious domains (referred to as DNS Sinkholing), and 2) e-mail filtering that would include quarantining incoming infected messages. The JCSP seeks to build upon the DIB Opt-In Pilot and allow DHS, through the National Cyber Security Division (NCSD) U.S. Computer Emergency Readiness Team (US-CERT), to share indicators and other information about known or suspected cyber threats directly with CSPs to enhance the protection of JCSP participants, including certain DIB companies and any participating federal agencies.

1 **<http://dodcio.defense.gov/docs/DIB%20CS-IA%20PIA_FINAL_signed_30jun2011_VMSS_GGMR_RC.pdf>[ ](http://dodcio.defense.gov/docs/DIB%20CS-IA%20PIA_FINAL_signed_30jun2011_VMSS_GGMR_RC.pdf)** and established procedures and agreements with DIB participants.

2 A countermeasure is an action, process, device, or system that can prevent, or mitigate the effects of, threats to a computer, server or network.

3 The term Commercial Service Providers, or CSP, refers to internet, network and communications providers

**Indicators of Known or Suspected Cyber Threats**

As part of its mission to promote the protection of cyber infrastructure, NCSD, through the US-CERT, collects information that is specific to identifying known or suspected cyberthreats from a number of sources. These “indicators” can be used to create intrusion detection signatures or other means of detecting and mitigating cyber threats. Sources for indicators may include individuals with expertise, domestic and international private sector organizations, and international, federal or state agencies with a vested interest in promoting cybersecurity. Indicators about known or suspected cyber threats may also be collected from EINSTEIN4  sensors placed on federal agency network collection points.5

US-CERT typically characterizes these indicators into five categories:

  1. IP addresses;
  2. Domains;
  3. E-mail headers;
  4. Files; and
  5. Strings



Each category of indicators contains specific features or characteristics. For instance:

  * IP and Domain Indicators can contain the associated port, WHOIS6 information, and Uniform Resource Identifiers (URI); 7
  * E-mail Indicators can contain message attributes such as the sent date, subject, links, attachments, sender’s name and sender’s e-mail address;
  * File Indicators can contain information on malicious software (malware) that is designed specifically to damage or disrupt a computer system, such as the file’s size, hash values, and behavior; and
  * String Indicators consist of persistent and unique identifiers specific to malicious activity.



4 Privacy Impact Assessments for DHS cybersecurity programs, including EINSTEIN can be found at **<http://www.dhs.gov/files/publications/editorial_0514.shtm#4>**.

5 These sensors capture flow records that identify the Internet Protocol (IP) address of the computer that connects to the federal system, the port the source uses to communicate, the time the communication occurred, the federal destination IP address, the protocol used to communicate, and the destination port.

6 WHOIS is a Transmission Control Protocol (TCP)-based transaction-oriented query/response protocol that is widely used to provide information services to Internet users. While originally used to provide “white pages” services and information about registered domain names, current deployments cover a much broader range of information services. The protocol delivers its content in a human-readable format.( **[http://www.ietf.org/rfc/rfc3912.txt](http://www.dhs.gov/files/publications/editorial_0514.shtm#4)** )

7 URI is the generic term for all types of names and addresses that refer to objects on the World Wide Web. A Uniform Resource Locator (URL) is one kind of URI.

NCSD is not a classification authority. Classification of identified indicators is dictated by its source, including the JCSP. However, the majority of information the US-CERT manages and analyzes is unclassified and therefore potentially available for dissemination to a large majority of its mission partners. Classified indicators are managed on secure media and only disseminated within those protected and authorized boundaries. The risk for PII is minimized because US-CERT operates with domain names and simple mail transfer protocol (SMTP)strings, neither of which includes PII.

Indicators can contain any of the above at varying levels of detail and one indicator can have a relationship with another indicator. For example: an e-mail can contain an attachment and that attachment can contain malware. These indicators whether separately or grouped together are referred to and submitted as “indicator reports.” Indicator reports can be produced with any combination of indicators and can have either a single indicator or multiple types of indicators and multiple entries for each type therein. For example: a certain indicator report may contain one email, one file, and one domain; other indicator reports may contain four files, or two domains and three IP addresses.

**Indicator Sharing Under the JCSP**

As part of the JCSP, US-CERT shares indicators with CSPs through secure channels. The CSPs will configure the indicators into “signatures,” which are machine-readable software code that enable automated detection of the known or suspected cyber threats associated with the indicator described above.

The JCSP will use the same two cyber threat countermeasures used in DoD’s DIB Opt-in Pilot: 1) DNS Sinkholing and 2) email filtering that would include quarantining infected messages.

When CSPs implement a signature on behalf of a DIB company and that signature triggers an alert, the CSP notifies the participating DIB company in accordance with its commercial agreement and any applicable security requirements. The CSP may, with the permission of the participating DIB company, also provide some limited information about the incident to US-CERT sufficient to capture the fact of occurrence. US-CERT may share the fact of occurrence information with DoD pursuant to existing US-CERT procedures in an effort to increase DoD’s understanding of the threats to their critical assets that reside within the DIB companies’ networks and system. The CSPs may voluntarily choose to send US-CERT information related to cyber threat indicators or other possible known or suspected cyber threats.

When a CSP implements a signature on behalf of a participating federal civilian agency and that signature triggers an alert, the CSP reports both the fact of occurrence and the additional details regarding the incident. The nature of the reporting will be consistent with data collected and analyzed under the DHS EINSTEIN efforts and agency responsibilities under FISMA for securing federal agency information systems.

US-CERT will share information it receives under JCSP consistent with its existing policies and procedures, including to other U.S. government entities with cybersecurity responsibilities.

US-CERT maintains its information involved in JCSP in the National Cybersecurity Protection System (NCPS) Mission Operating Environment (MOE), a protected system on  a protected network accessible to only authorized NCSD personnel with a need to know. JCSP participants and CSPs maintain information in accordance with information sharing agreements. At the end of JCSP, JCSP participants and CSPs must return all government furnished information or dispose of it in accordance with establishing information sharing agreements. They may also voluntarily provide NCSD with end-of-pilot lessons learned or other general feedback about JCSP technical or operational issues and solutions.

**Privacy Considerations**

The JCSP is a voluntary program based on mutual sharing of cybersecurity information between the U.S. government, service providers, and the organizations being protected by the CSPs. US-CERT provides cybersecurity indicators to CSPs for the purpose of enhancing the protection of JCSP participants. The CSPs, at the request of participants, in turn use such indicators to look for known or suspected cyber threats within JCSP Participant traffic. As part of the JCSP, CSPs may share summary information with US-CERT about the fact that known or suspected cyber threats were detected. This “fact of” information will not contain PII. When the JCSP ends and NCSD solicits feedback on the project, NCSD will not collect PII.

Participants in the JCSP have determined that their policies, practices, and activities related to the JCSP comply with applicable legal requirements and include measures that the participants determined are sufficient to ensure authorized user consent to the interception, monitoring, access, use and disclosure of electronic communications or data residing on or transiting their systems, including the disclosure of related information to the U.S. government.

Indicators of known or suspected cyber threats that are shared as part of the JCSP may contain information that could be considered PII, such as e-mail addresses and other information that might be included in the message header or subject line. This type of information would only be shared if it was reviewed and pre-determined to be an indicator of a known or suspected cyber threat. All information that could be considered PII is handled in accordance with existing US-CERT standard operating procedures (SOPs), which describe the necessary procedures, defines the terms and outlines roles and responsibilities

US-CERT collects contact information from representatives of the DIB companies, the CSPs, and federal agencies participating in the JCSP. This information is used by US-CERT during the pilot to verify any reported known or suspected cyber threats and to follow up for additional action that may be required regarding the particular cyber threats, or any other aspect of the operation of the pilot.

## Section 1.0 Authorities and Other Requirements

### 1.1 What specific legal authorities and/or agreements permit and define the collection of information by the project in question?

The JCSP is being conducted pursuant to authority derived from the Homeland Security Act, including 6 U.S.C. §§ 121, 143; 10 U.S.C. § 2224; the Federal Information Security Management Act, including 44 U.S.C. § 3544; Homeland Security Presidential Directive 7, Critical Infrastructure Identification, Prioritization, and Protection; and Homeland Security Presidential Directive 23, Cybersecurity Policy . There are agreements in place between DHS and the CSPs as well as between DoD and participating DIB companies. The relationship between CSPs and participating entities will be governed through commercial transactions.

### 1.2 What Privacy Act System of Records Notice(s) (SORN(s)) apply to the information?

With regard to indicators or other information related to a known or suspected cyberthreat, US-CERT does not maintain that information in a “system of record.” As defined by the Privacy Act, a “system of records” is a group of any records under the control of any agency from which information is maintained and retrieved by a personal identifier. Only when there is actual retrieval of record by a personal identifier does the Privacy Act require a SORN. US-CERT does not retrieve this information by personal identifier, thus a SORN is not required for the JCSP.

US-CERT collects the contact information from representatives of the DIB companies, the CSPs, and federal agencies participating in the JCSP. This information is used by US-CERT during the pilot to verify any reported known or suspected cyber threats and to follow up for additional action that may be required regard the particular cyber threats, or any other aspect of the operation of the pilot. This collection of personal information is covered by the DHS systems of records titled, DHS/All- 002 Department of Homeland Security (DHS) Mailing and Other Lists System, November 25, 2008, 73 FR 71659.

### 1.3 Has a system security plan been completed for the information system(s) supporting the project?

JCSP information will be stored in the NCPS MOE, which is the network designated to perform threat analysis and other functions. For the JCSP, US-CERT will share indicators of known or suspected cyber threats from the MOE with CSPs. The MOE received re-certification and accreditation on July 28, 2010, and is covered by the system security plan. The re-certification is valid for three years.

### 1.4 Does a records retention schedule approved by the National Archives and Records Administration (NARA) exist?

The Department is currently working with the NPPD Records Manager to develop a disposition schedule. Once completed, the schedule will be sent to the National Archives and Records Administration for approval.

### 1.5  If the information is covered by the Paperwork Reduction Act(PRA), provide the OMB Control number and the agency number for the collection. If there are multiple forms, include a list in an appendix.

DHS is not using a form to collect the same information from 10 or more persons, therefore the PRA does not apply

## Section 2.0 Characterization of the Information

### 2.1 Identify the information the project collects, uses, disseminates, or maintains.

The JCSP is a voluntary program based on mutual sharing of indicators of known or suspected cyber threats and reporting of incidents of detected cyber threats. US-CERT provides indicators to CSPs for the purpose of enhancing the protection of JCSP participants. The CSPs, at the request of participants, in turn use such indicators to look for known or suspected cyberthreats within the traffic to or from JCSP Participant computer networks. As part of the JCSP, the CSP may, with the permission of the participating DIB company, also provide some limited information about the incident to US-CERT sufficient to capture the fact of occurrence. This “fact of” reporting will not contain information that could be considered PII.

The following information that could be considered PII may be part of indicators shared through the JCSP: email address and information from and associated with email messages, as well as other information that could be contained in the message header, to/from free-flow text fields, or subject line from individuals using federal websites or JCSP participants’ networks and systems. US-CERT will review all information it receives during the JCSP and only retain information that could be considered PII if that information is analytically relevant, otherwise, US-CERT will delete it.

As part of the JCSP, US-CERT collects contact information from representatives of JCSP Participants, to include employee name, business address, business telephone number, and business email address. This information is used by US-CERT during the pilot to verify any reported known or suspected cyber threats and to follow up for additional action that may be required regarding the particular cyber threats, or any other aspect of the operation of the pilot.

### 2.2 What are the sources of the information and how is the information collected for the project?

Indicators and other cyber threat related information are received by US-CERT from a number of sources including the following: analysis by US-CERT’s operations teams; data submitted to US-CERT from other government departments and agencies; and reports received from mission and industry partners. Indicators can be parsed as received reports and submitted by analysts from US-CERT and other government departments/agencies or from information received by mission and industry partners, including the EINSTEIN efforts. The JCSP will also allow US-CERT to accept indicators from DoD and provide cyber indicators and alerting information back to DoD.

### 2.3 Does the project use information from commercial sources or publicly available data? If so, explain why and how this information is used.

US-CERT can use information from a range of sources, including commercial sources and publicly available data on cybersecurity threats. As an example, indicator information obtained from WHOIS can be used to help resolve cybersecurity-related threats and for historical reference of similar threats.

### 2.4 Discuss how accuracy of the data is ensured.

Both classified and unclassified indicators are vetted through trusted and validated sources, using unclassified references for indicators whenever possible. The indicators are tested for false positive and false negative results in a pre-staged, EINSTEIN test sensor before they are provided to the CSPs. Further, additional testing is performed in the production environment to test for true positive and true negative results.

### 2.5 Privacy Impact Analysis: Related to Characterization of the Information

**Privacy Risk:** There is a risk that information that could be considered PII is included in an indicator when that information does not add any value to the prevention of a known or suspected cyber threat.

**Mitigation:** US-CERT only collects data that is necessary to accomplish its mission; cyber threat (i.e., indicator) information may include IP and host addresses and flow data, and any actions taken.

Analysts attempt to confirm the integrity of the data received. Only information determined to be directly relevant and necessary to accomplish the specific purposes of the program will be retained, otherwise, the data is deleted.

US-CERT will conduct periodic reviews on cyber indicators to ensure all standards and responsibilities are met.

**Privacy Risk:** There is a risk that the indicator does not meet the US-CERT standards of quality or applicability and is shared to the detriment of individuals who communicate electronically with the users’ organizations or agency.

**Mitigation:** US-CERT has established a process by which only trained and authorized users have access to the indicators. Users must abide by specific rules of behaviors and responsibilities with regard to access and to the quality of the data in NCPS systems. US-CERT analysts conduct analysis on all cyber threats received. If information submitted contains information that could be considered PII, the analyst must determine if that information is related to the cyber threat. If the information is not related to the cyber threat, it is deleted.

## Section 3.0 Uses of the Information

### 3.1 Describe how and why the project uses the information.

The JCSP is a voluntary program based on mutual sharing of information. US- CERT provides indicators of known or suspected cyber threats to CSPs for the purpose of enhancing the protecting of JCSP participants. The CSPs, at the request of participants, in turn use such indicators to look for known or suspected cyber threats in the traffic to or from the JCSP Participant’s network. As part of the JCSP, the CSP may, with the permission of the participating DIB company, also provide some limited information about the incident to US- CERT sufficient to capture the fact of occurrence. This information will not contain information that could be considered PII.

### 3.2 Does the project use technology to conduct electronic searches, queries, or analyses in an electronic database to discover or locate a predictive pattern or an anomaly? If so, state how DHS plans to use such results.

No; the JCSP does not use technology to conduct electronic searches, queries, or analyses in an electronic database to discover or locate a predictive pattern or an anomaly.

### 3.3 Are there other components with assigned roles and responsibilities within the system?

There are no other components with assigned roles and responsibilities within the JCSP.

### 3.4 Privacy Impact Analysis: Related to the Uses of Information

**Privacy Risk:** There is a privacy risk that PII inadvertently obtained will not be properly protected and will be disseminated to other entities with a potential to lead to unauthorized use of the PII.

**Mitigation:** DHS will not directly receive PII from the CSP and would only receive PII from the participating entities if those entities share it in connection with a known or suspected cyber threat. Aspects of the JCSP are governed by information sharing agreements, internal US-CERT SOPs, and this PIA, which covers the uses of government furnished information, including indicators, collected or maintained.

In addition, DIB companies are bound by established information sharing agreements, or contractual relationships established between the DIB companies and their respective CSPs.

US-CERT analysts supporting the JCSP are trained on both DHS and US-CERT specific privacy protection procedures. Analysts, administrators and information assurance personnel receive training upon hire, and are required to take refresher training each year on Security Education and Awareness Training (SEAT). In addition, US-CERT maintains SOPs which describe necessary procedures, defines the terms and outlines roles and responsibilities for handling PII.

In addition, access to US-CERT systems is restricted to individuals with demonstrated need for access, and such access must be approved by the supervisor as well as the NCSD Information System Security Officer. Users must sign Rules of Behavior which identify the need to protect PII prior to gaining access. Access is only available via two factor authentication. Users’ actions are logged and they are aware of that condition. Failure to abide by the Rules of Behavior may result in disciplinary measures and potential termination of employment.

## Section 4.0 Notice

### 4.1 How does the project provide individuals notice prior to the collection of information? If notice is not provided, explain why not.

This PIA serves as notice of the JCSP. Notice is also provided through DoD’s published PIA on DoD’s DIB Cyber Security and Information Assurance program, which the DoD DIB Opt-in Pilot leveraged. This PIA covers the JCSP overall pilot process and previously published PIAs that support the overall US-CERT program. All DHS cybersecurity PIAs as well as other information on federal government cybersecurity programs and protections are available on the DHS Privacy Office cybersecurity webpage.

Participants in the JCSP have determined that their policies, practices, and activities related to the JCSP comply with applicable legal requirements and include measures that the participants determined are sufficient to ensure authorized user consent to the interception, monitoring, access, use and disclosure of electronic communications or data residing on or transiting their systems, including the disclosure of related information to the U.S. government

### 4.2 What opportunities are available for individuals to consent to uses, decline to provide information, or opt out of the project?

Federal agencies are required to post notices on their websites as well as at other major points of entry that computer security information is being collected and their system monitored. Furthermore, users of federal computer systems are provided with logon banners and sign user agreements that specifically notify them of the computer network monitoring. Users have the opportunity to read these notices and can then decide if they wish to use the system or not, and decide what information they want to transmit.

Participants in the JCSP have determined that their policies, practices, and activities related to the JCSP comply with applicable legal requirements and include measures that the participants determined are sufficient to ensure authorized user consent to the interception, monitoring, access, use and disclosure of electronic communications or data residing on or transiting their systems, including the disclosure of related information to the U.S. government.

### 4.3 Privacy Impact Analysis: Related to Notice

**Privacy Risk:** There is a privacy risk that an individual may choose to not read a notice or banner provided or be aware of the information collection.

**Mitigation:** Participants in the JCSP have determined that their policies, practices, and activities related to the JCSP comply with applicable legal requirements and include measures that the participants determined are sufficient to ensure authorized user consent to the interception, monitoring, access, use and disclosure of electronic communications or data residing on or transiting their systems, including the disclosure of related information to the U.S. government. Users of federal systems have also been provided notice of, and consented to, network security activities including the potential collection of their communications.

## Section 5.0 Data Retention by the Project

### 5.1 Explain how long and for what reason the information is retained.

DHS is currently working to determine the appropriate length of time for cyber indicators and related information, including PII identified as related to malicious activity to be retained and stored.

The Department is currently working with the NPPD Records Manager to develop a disposition schedule. Once completed, the schedule will be sent to the National Archives and Records Administration for approval.

### 5.2 Privacy Impact Analysis: Related to Retention

**Privacy Risk:** There is a risk that PII may be retained beyond what is necessary to appropriately analyze or address a cyber threat or investigation. Additional risks may exist if necessary and appropriate PII is either prematurely deleted or not retained and is pertinent to a cyber threat or investigation.

**Mitigation:** DHS is currently working to determine the appropriate length of time for

cyber indicators and related information, including PII identified as related to malicious activity to be retained and stored.

US-CERT analysts will only retain indicators associated with known or suspected cyber threats, reports and other products generated as a result of known or suspected cyber threats. JCSP information will be stored in the NCPS MOE, a protected system on a protected network accessible to only authorized NCSD personnel with a need to know the information. In the event information collected does contain PII but it is judged irrelevant to the cyber threat, the PII is deleted in accordance with US-CERT SOPs.

US-CERT maintains SOPs which describe the necessary procedures, defines the terms and outlines roles and responsibilities.

## Section 6.0 Information Sharing

### 6.1 Is information shared outside of DHS as part of the normal agency operations? If so, identify the organization(s) and how the information is accessed and how it is to be used.

Under the JCSP, US-CERT shares indicators with CSPs and DoD for the purpose of enhancing the protection of JCSP participants. The sharing of information between the parties is accomplished through secure communication. Only those individuals that maintain appropriate security clearances and have completed the appropriate training will be granted access to the information.

Contact information from representatives of the DIB companies, the CSPs, and the participating federal agencies will not be shared outside of normal agency or JCSP operations.

### 6.2 Describe how the external sharing noted in 6.1 is compatible with the SORN noted in 1.2.

Collection of personal information described in 6.1 is covered by the DHS systems of records titled, DHS/All-002 Department of Homeland Security (DHS) Mailing and Other Lists System, November 25, 2008, 73 FR 71659. DHS will share this data in a manner that is compatible with the purpose of this systems of records notice.

### 6.3 Does the project place limitations on re-dissemination?

US-CERT is not prohibited from using or disseminating additional cyber threat indicators, including additional IP addresses or domain names, derived from cybersecurity incident information as long as such indicators do not identify the source of such information and are not otherwise attributable to JCSP Participants.

DIB companies are bound by established information sharing agreements or contractual relationships established between the DIB companies and their respective CSPs.

### 6.4 Describe how the project maintains a record of any disclosures outside of the Department.

As a general rule, US-CERT provides cyber-related information to the public, federal departments/agencies, state, local, tribal and international entities through a variety of products, many of which are available on the US-CERT.gov website. No formal report contains PII. Each report is numbered and catalogued and references exist in all products (including those associated with indicators shared through the JCSP) to tie back to a single incident or series of incidents which precipitated the product itself.

In the event that PII must be released, it is released with the written approval of the NCSD Director after consultation with the SOPs.

### 6.5 Privacy Impact Analysis: Related to Information Sharing

**Privacy Risk:** There is a privacy risk that US-CERT may share indicators with CSPs that contain PII that is not associated with a known or suspected cyber threat.

**Mitigation:** The risk of unauthorized disclosure is mitigated through various means, including US-CERT standard operating procedures. US-CERT SOPs provide procedures for removing unnecessary PII, encrypting certain information, and marking and handling of PII data collected.

## Section 7.0 Redress

### 7.1 What are the procedures that allow individuals to access their information?

Individuals seeking access to any record containing information that is part of a DHS system of records, or seeking to amend the accuracy of its content may submit a Freedom of Information Act (FOIA) or Privacy Act (PA) request to the DHS/NPPD FOIA Officer at 245 Murray Lane SW, Washington, D.C. 20528-0380. Individuals may obtain directions on how to submit a FOIA/PA request at **<http://www.dhs.gov/xfoia/editorial_0316.shtm>**. Given the nature of some information in the US-CERT systems, DHS may not always permit the individual to gain access to or request amendment of his or her record.

### 7.2 What procedures are in place to allow the subject individual to correct inaccurate or erroneous information?

There are no separate procedures for individual correction of indicators since the information generated is an exact copy of computer network traffic.

JCSP Participants seeking to correct contact information collected by US-CERT during the JCSP may contact US-CERT operations directly or submit a written request to DHS/NPPD FOIA Officer at 245 Murray Lane SW, Washington, D.C. 20528-0380, to have their inaccurate or erroneous PII corrected. See additional information in Section 7.1.

### 7.3 How does the project notify individuals about the procedures for correcting their information?

As part the normal US-CERT operations, US-CERT provides notice about procedures for correcting PII to those individuals that submit information regarding a suspected or known cyber threat through the applicable SORN, this PIA and related US-CERT PIAs.

An individual can submit a written request to DHS/NPPD FOIA Officer at 245 Murray Lane SW, Washington, D.C. 20528-0380, to have their inaccurate or erroneous PII corrected. See additional information in Section 7.1.

### 7.4 Privacy Impact Analysis: Related to Redress

There are no redress procedures beyond those described above and afforded under the Privacy Act and FOIA.

## Section 8.0 Auditing and Accountability

### 8.1 How does the project ensure that the information is used in accordance with stated practices in this PIA?

The US-CERT Oversight and Compliance Officer ensures adequate guidelines and procedures are in place and that all US-CERT personnel working in support of the JCSP are familiar with, understand and adhere to those guidelines. The US-CERT Oversight and Compliance Officer conducts quarterly internal reviews to evaluate the program and assess its compliance with applicable guidelines, procedures, and applicable laws and regulations.

### 8.2 Describe what privacy training is provided to users either generally or specifically relevant to the project.

Access to US-CERT systems is restricted to individuals with demonstrated need for access, and such access must be approved by the supervisor as well as the NCSD ISSO. Users must sign Rules of Behavior which identify the need to protect PII prior to gaining access. Access is only available via two factor authentication. All users are trained to protect privacy information. Their actions are logged, and they are aware of that condition. Failure to abide by the Rules of Behavior may result in disciplinary measures and potential termination of employment.

All DHS employees are required to complete annual Privacy Awareness Training. When each DHS employee completes the training, it is recorded in the employee’s file online. NPPD employees are also required to complete annual Security Education and Awareness Training (SEAT). In addition, US‐CERT analysts and other persons who might come into contact with sensor or other data receive annual training on privacy, legal, and policy issues specifically related to US-CERT operations. This training includes how to address privacy during the development of new signatures, how to generate a report that minimizes the privacy impact, and how to report when a signature seems to be collecting more network traffic than is directly required to analyze the malicious activity.

In addition NCSD is in the process of developing JCSP training specifically for analysts supporting on the pilot.

### 8.3 What procedures are in place to determine which users may access the information and how does the project determine who has access?

Users must obtain a favorable DHS suitability determination8 prior to acquiring access to all DHS systems. All users supporting the JCSP have a valid requirement to access the systems and only the type of access required to meet their professional responsibilities. Access is based upon the role identified on the access form (i.e. analyst, user, general user, system admin., network admin., etc.). The access form must be completed by the government supervisor within the branch that the individual will be supporting. The user’s role is defined by the branch manager and validated by the Network Manager and ISSO. Accounts are reviewed monthly by the ISSO to ensure that accounts are maintained current. In addition, user account activity is logged, and the logs reviewed each day.

US-CERT also maintains SOPs which describe the necessary procedures to protect PII, defines the terms and outlines roles and responsibilities. SOPs are provided to all US-CERT employees during training.

8 The suitability determination is a process that evaluates a federal or contractor employees’ personal conduct throughout their careers. Suitability refers to fitness for employment or continued employment referring to identifiable character traits and past conduct that is sufficient to determine whether or not an individual is likely to carry out the duties of the position with efficiency, effectiveness, and in the best interests of the agency.

### 8.4 How does the project review and approve information sharing agreements, MOUs, new uses of the information, new access to the system by organizations within DHS and outside?

The Memoranda of Agreements (MOAs) developed between DHS, DoD, the CSPs, and other federal departments and agencies are based on an approved template that has been fully coordinated through the program manager, system owner, Office of the General Counsel and NPPD Office of Privacy. The relationship between CSPs and JCSP Participants will be governed through commercial transactions.

## Responsible Officials

Brendan Goode  
Director, Network Security Deployment  
National Cyber Security Division  
National Protection and Programs Directorate  
Department of Homeland Security

### Approval Signature

[Original signed copy on file with the DHS Privacy Office]

Mary Ellen Callahan  
Chief Privacy Officer  
Department of Homeland Security

* * *

For more information:

## DHS Data Mining Reports

The Data Mining Report, which is provided to Congress each year, describes DHS programs, both operational and in development, that involve data mining as defined by the Federal Agency Data Mining Reporting Act of 2007.

  * [2011 Data Mining Report](http://www.dhs.gov/xlibrary/assets/privacy/dhsprivacy_2011dataminingreport.pdf)  _(PDF, 37 pages – 1.61 MB)_.
  * [2010 Data Mining Report](http://www.dhs.gov/xlibrary/assets/privacy/2010-dhs-data-mining-report.pdf)  _(PDF, 35 pages – 517 KB)_.
  * [2009 Data Mining Report](http://www.dhs.gov/xlibrary/assets/privacy/privacy_rpt_datamining_2009_12.pdf)  _(PDF, 34 pages – 378 KB)._
  * [2008 Data Mining Report](http://www.dhs.gov/xlibrary/assets/privacy/privacy_rpt_datamining_200812.pdf) ( _PDF, 47 pages – 467 KB)_.
  * [2008 Data Mining Letter Report](http://www.dhs.gov/xlibrary/assets/privacy/privacy_rpt_datamining_2008.pdf)  _(PDF, 46 pages – 441 KB)_.
  * [2007 Data Mining Report](http://www.dhs.gov/xlibrary/assets/privacy/privacy_rpt_datamining_2007.pdf)  _(PDF, 42 pages – 446 KB)_.
  * [2006 Data Mining Report](http://www.dhs.gov/xlibrary/assets/privacy/privacy_data_%20mining_%20report.pdf) _July 6, 2006_ ( _PDF, 36 pages – 340 KB_ ).



## Cybersecurity

The Privacy Office works closely with the [Office of Cybersecurity & Communications](http://www.dhs.gov/xabout/structure/gc_1185202475883.shtm) (CS&C), and, within CS&C, the [National Cybersecurity Division](http://www.dhs.gov/xabout/structure/editorial_0839.shtm) and the [United States Computer Emergency Readiness Team (US-CERT )](http://www.us-cert.gov/), to integrate privacy protections into the Department’s cybersecurity activities. The following resources provide background on these efforts:

### EINSTEIN Program-Related Privacy Impact Assessments

  * [Privacy Compliance Review of the EINSTEIN Program](http://www.dhs.gov/xlibrary/assets/privacy/privacy_privcomrev_nppd_ein.pdf), January 3, 2012 _(PDF, 9 pages – 112 KB)._ The DHS National Protection and Programs Directorate (NPPD) National Cyber Security Division (NCSD) launched the EINSTEIN program in 2004 as a computer network intrusion detection system to help protect federal executive agency information technology enterprises. NCSD conducted PIAs for each phase of the EINSTEIN program, which the DHS Privacy Office reviewed and approved. As NCSD looks ahead toward the next phase of the program to EINSTEIN 3, the DHS Privacy Office determined that conducting a PCR would be timely to ensure the accuracy of compliance documentation and transparency of the EINSTEIN program moving forward. The DHS Privacy Office found NPPD/NCSD generally compliant with the requirements outlined in the EINSTEIN 2 PIA and Initiative 3 Exercise PIA. Specifically, NPPD/NCSD is fully compliant on collection of information, use of information, internal sharing and external sharing with federal agencies, and accountability requirements. PRIV identified actions taken to address retention and training requirements as outlined in the relevant EINSTEIN PIAs, but additional actions by the program are needed to bring them into full compliance with these requirements. The DHS Privacy Office is making five recommendations to strengthen program oversight, external sharing, and bring NPPD/NCSD into full compliance with retention and training requirements. NPPD agreed with our findings and is taking steps to address our recommendations.
  * [National Cyber Security Division Joint Cybersecurity Services Pilot (JCSP)](http://www.dhs.gov/xlibrary/assets/privacy/privacy_nppd_jcsp_pia.pdf), January 13, 2012 _(PDF, 16pages – 248 KB)._ The Department of Homeland Security (DHS) and the Department of Defense (DoD) are jointly undertaking a proof of concept known as the Joint Cybersecurity Services Pilot (JCSP). The JCSP extends the existing operations of the Defense Industrial Base (DIB) Exploratory Cybersecurity Initiative (DIB Opt-In Pilot) and shifts the operational relationship with the CSPs in the pilot to DHS. The JCSP is part of overall efforts by DHS and DoD to enable the provision of cybersecurity capabilities enhanced by U.S. government information to protect critical infrastructure information systems and networks. The purpose of the JCSP is to enhance the cybersecurity of participating DIB critical infrastructure entities and to protect sensitive DoD information and DIB intellectual property that directly supports DoD missions or the development of DoD capabilities from unauthorized access, exfiltration, and exploitation. The National Protection and Programs Directorate (NPPD) is conducting this Privacy Impact Assessment (PIA) on behalf of DHS because some known or suspected cyber threat information shared under the JCSP may contain information that could be considered personally identifiable information (PII). Associated SORN(s): [DHS/ALL-002 – Department of Homeland Security (DHS) Mailing and Other Lists System](http://edocket.access.gpo.gov/2008/E8-28053.htm) November 25, 2008, 73 FR 71659.
  * [US-CERT: Initiative Three Exercise](http://www.dhs.gov/xlibrary/assets/privacy/privacy_pia_nppd_initiative3exercise.pdf). March 18, 2010 _(PDF 19 pages – 457 KB)_ Pursuant to Initiative Three of the Comprehensive National Cybersecurity Initiative, DHS is engaging in an exercise to demonstrate a suite of technologies that could be included in the next generation of the Department’s EINSTEIN network security program. This demonstration, (commonly referred to as the “Initiative Three Exercise” or, more simply, as “the Exercise”) will use a modified complement of system components currently providing the EINSTEIN 1 and EINSTEIN 2 capabilities, as well as a DHS test deployment of technology developed by the National Security Agency (NSA) that includes an intrusion prevention capability (collectively referred to as “the Exercise technology”). The purpose of the Exercise is to demonstrate the ability of an existing Internet Service Provider that is a designated as a Trusted Internet Connection Access Provider (TICAP) to select and redirect Internet traffic from a single participating government agency through the Exercise technology, for US-CERT to apply intrusion detection and prevention measures to that traffic and for US-CERT to generate automated alerts about selected cyber threats. This PIA is being conducted because the Exercise will analyze Internet traffic which may contain personally identifiable information (PII).
  * [EINSTEIN 1 PIA Update](http://www.dhs.gov/xlibrary/assets/privacy/privacy_pia_nppd_einstein1michigan.pdf). February 19, 2010 ( _PDF, 12 pages – 194 KB_ ) DHS and the State of Michigan (“Michigan”) plan to engage in a 12-month proof of concept to determine the benefits and issues presented by deploying the EINSTEIN 1 capability to Michigan government networks managed by the Michigan Department of Information Technology (MDIT). This PIA updates the previous EINSTEIN PIAs listed below in one narrow aspect: the use of EINSTEIN 1 technology in a proof of concept with Michigan.
  * [EINSTEIN 2 Privacy Impact Assessment](http://www.dhs.gov/xlibrary/assets/privacy/privacy_pia_einstein2.pdf). May 19, 2008 ( _PDF, 23 pages – 423 KB_ ). This is the Privacy Impact Assessment (PIA) for an updated version of the EINSTEIN System. EINSTEIN is a computer network intrusion detection system (IDS) used to help protect federal executive agency information technology (IT) enterprises. EINSTEIN 2 will incorporate network intrusion detection technology capable of alerting the US-CERT to the presence of malicious or potentially harmful computer network activity in federal executive agencies’ network traffic.
  * [EINSTEIN 1 Privacy Impact Assessment](http://www.dhs.gov/xlibrary/assets/privacy/privacy_pia_eisntein.pdf). September 2004 _(PDF, 12 pages – 153 KB_ ) This PIA examines the privacy implications of US-CERT’s EINSTEIN Program. The EINSTEIN Program is an automated process for collecting, correlating, analyzing, and sharing computer security information across the federal civilian government. By collecting information from participating federal government agencies, US-CERT builds and enhances our nation’s cyber-related situational awareness.



### Other Cybersecurity Privacy Impact Assessments

  * [Malware Lab Network](http://www.dhs.gov/xlibrary/assets/privacy/privacy_pia_nppd_mln.pdf) May 4, 2010 _(PDF, 13 pages – 172 KB)_ The goal of the Department of Homeland Security (DHS or Department) National Protection and Programs Directorate (NPPD) is to advance the risk-reduction segment of the Department’s overall mission. To meet this goal, the NPPD/U.S. Computer Emergency Readiness Team (US-CERT) provides key capabilities in four cyber mission areas: 1) Alert, Warning, and Analysis; 2) Coordination and Collaboration; 3) Response and Assistance; and 4) Protection and Detection. The Malware Lab Network (MLN) contributes critical support to existing tools used by US-CERT to better meet these cyber mission areas. The MLN collects, uses, and maintains analytically relevant information in order to support the Department’s cyber security mission, including the prevention and mitigation of cyber attacks, protection of information infrastructure, the assessment of cyber vulnerabilities, and response to cyber incidents. DHS is conducting this PIA to publicly analyze and evaluate the personally identifiable information (PII) within the MLN.
  * [24×7 Incident Handling and Response Center](http://www.dhs.gov/xlibrary/assets/privacy/privacy_pia_nppd_24x7.pdf), April 2, 2007 _(PDF, 17 pages -265 KB_ ) The 24×7 Incident Handling and Response Center (“24×7″) focuses on ways to gather cyber information prior to attacks and to use that information to prevent attacks, protect computing infrastructure, and respond/restore where attacks are successful. 24×7 serves as a communication hub for the United States Computer Readiness Team (US-CERT) program, issuing regular security and warning bulletins, serving as a gateway for public contribution and outreach, and also serving as a ticketing center through which tasks may be delegated out to the various US-CERT programs.



### Other Cybersecurity Resources

  * [White Paper on Computer Network Security & Privacy Protection](http://www.dhs.gov/xlibrary/assets/privacy/privacy_cybersecurity_white_paper.pdf). February 19, 2010 ( _PDF, 11 pages – 114 KB_ ). Provides an overview of the Department’s cybersecurity responsibilities, the role of the EINSTEIN system in implementing those responsibilities, and the integrated privacy protections.
  * [White House Cybersecurity Site](http://www.whitehouse.gov/cybersecurity). The White House recently launched a site dedicated to the federal government’s cybersecurity efforts, [www.whitehouse.gov/cybersecurity](http://www.whitehouse.gov/cybersecurity), including the declassified description of the [Comprehensive National Cybersecurity Initiative](http://www.whitehouse.gov/cybersecurity/comprehensive-national-cybersecurity-initiative).



## Passenger Name Records

The 2007 Passenger Name Record (PNR) Agreement between the United States and the European Union (EU) made possible the transfer of certain passenger data to Customs and Border Protection (CBP) in order to facilitate safe and efficient travel. The documents below demonstrate the progression of the Agreement since its inception and include subsequent reviews conducted by both the United States and the EU to ensure compliance with the Agreement.

  * [European Commission Report on the Joint Review of the U.S.-E.U. Passenger Name Record Agreement](http://www.dhs.gov/xlibrary/assets/privacy/privacy_eu_pnr_aircarriers_feb_2010.pdf) April 7, 2010 ( _PDF, 34 pages – 409 KB_ )
  * [Department Response to the European Commission’s Report on the Joint Review of the U.S.-E.U. Passenger Name Record Agreement](http://www.dhs.gov/xlibrary/assets/privacy/privacy_dhs_response_european_commission_report_2010-03-31.pdf), March 31, 2010 ( _PDF, 6 pages – 199 KB_ )
  * [U.S.-EU Joint Statement, February 10, 2010](http://www.dhs.gov/xabout/international/gc_1266508780782.shtm)
  * [Update to the 2008 Report Concerning Passenger Name Record Information Derived from Flights Between the U.S. and the European Union](http://www.dhs.gov/xlibrary/assets/privacy/privacy_pnr_review2010update_2010-02-05.pdf), February 2010 _(PDF, 7 pages – 158 KB)_
  * [Privacy Office Report Concerning Passenger Name Record Information Derived from Flights Between the U.S. and the European Union](http://www.dhs.gov/xlibrary/assets/privacy/privacy_pnr_report_20081218.pdf), December 2008 ( _PDF, 60 pages – 2.93 MB_ )
  * [CBP Passenger Name Record Privacy Statement for PNR Data Received in Connection with Flights Between the U.S. and the European Union](http://www.dhs.gov/xlibrary/assets/privacy/privacy_stmt_pnr.pdf)  _(PDF, 3 pages – 142 KB)_.
    * [Answers to Frequently Asked Questions](http://www.dhs.gov/xlibrary/assets/privacy/privacy_faq_pnr_cbp.pdf)  _(PDF, 5 pages – 27 KB)_
  * [2007 PNR Agreement between the U.S. and the European Union](http://www.dhs.gov/xlibrary/assets/pnr-2007agreement-usversion.pdf)  _(PDF, 7 pages – 1.7 MB)_
  * [Letter from the Council of the European Union to the U.S.](http://www.dhs.gov/xlibrary/assets/pnr-2007agreement-eultrtous.pdf)  _(PDF, 3 pages – 1.5 MB)_
  * [Letter from the U.S. to the Council of the European Union](http://www.dhs.gov/xlibrary/assets/pnr-2007agreement-usltrtoeu.pdf)  _(PDF, 5 pages – 4. 5 MB)_
  * [Privacy Office Report Concerning Passenger Name Record Information Derived from Flights Between the U.S. and the European Union](http://www.dhs.gov/xlibrary/assets/privacy/dhsprivacy-pnr-privacyofficefinalreport-september2005.pdf), September 19, 2005 ( _PDF, 30 pages – 306 KB_ )



### PNR and the Automated Targeting System

PNR data is stored in the Automated Targeting System (ATS). CBP uses ATS to improve the collection, use, analysis, and dissemination of information that is gathered for the primary purpose of targeting, identifying, and preventing potential terrorists and terrorist weapons from entering the United States. For more background information, please consult our [ATS Privacy Impact Assessments](http://www.dhs.gov/files/publications/gc_1281020492905.shtm#ats).

## Other Homeland Security Privacy Reports

The following are public reports issued by the Privacy Office:

  * [Assessment of CBP Training Materials on Border Searches of Electronic Devices](http://www.dhs.gov/xlibrary/assets/privacy/privacy-report-cbp-training-border-searches-electronic-devices.pdf) ( _PDF, 6 pages – 138 KB_ ) In August 2009, Secretary Napolitano issued new directives regarding searches of electronic media at the border. In coordination with the release of the directives, the Privacy Office, Customs and Border Protection, and the Office for Civil Rights and Civil Liberties were instructed to assess the CBP training materials and course matter on the border search of electronic devices. This report presents a summary of this joint review.
  * [Interim Report on the EU Approach to the Commercial Collection of Personal Data for Security Purposes](http://www.dhs.gov/xlibrary/assets/privacy/privacy_rpt_hotel_int.pdf): The Special Case of Hotel Guest Registration Data, conducted pursuant to Section 222(b)(1)(B) of the Homeland Security Act, in order to enforce the provisions of Article 5 of the 2007 Passenger Name Records (PNR) Agreement. January 16, 2009 _(PDF 43 pages – 1.19 MB)_
  * [CCTV: Developing Best Practices, Report on the DHS Privacy Office Public Workshop, December 17 and 18, 2007](http://www.dhs.gov/xlibrary/assets/privacy/privacy_rpt_cctv_2007.pdf) ( _PDF, 66 pages – 528 KB)_ Report summarizing the CCTV workshop panels and resources to help identify and address privacy concerns, including _Best Practices for Government Use of CCTV_ (Appendix B); _Template for Privacy Impact Assessment for the Use of CCTV by DHS Program_ (Appendix C); _Template for Privacy Impact Assessment for the Use of CCTV by State and Local Entities_ (Appendix D); and _Template for Civil Liberties Impact Assessments (CLIA)_ (Appendix E).
  * [ADVISE Report](http://www.dhs.gov/xlibrary/assets/privacy/privacy_rpt_advise.pdf), _(PDF, 25 pages – 411 KB)_ Review of the Analysis, Dissemination, Visualization, Insight and Semantic Enhancement (ADVISE) Program including recommendations.
  * [Secure Flight Report](http://www.dhs.gov/xlibrary/assets/privacy/privacy-secure-flight-122006.pdf), December 2006 _(PDF, 18 pages – 694.60 KB)_ DHS Privacy Office Report to the Public on the Transportation Security Administration’s Secure Flight Program and Privacy Recommendations.
  * [MATRIX Report](http://www.dhs.gov/xlibrary/assets/privacy/privacy-matrix-122006.pdf), December 2006 _(PDF, 9 pages – 386.97KB)_ DHS Privacy Office Report to the Public Concerning the Multistate Anti-Terrorism Information Exchange (MATRIX) Pilot Project.
  * [Report Assessing the Impact of the Automatic Selectee and No Fly Lists](http://www.dhs.gov/xlibrary/assets/privacy/privacy_rpt_nofly.pdf), April 27, 2006 _(PDF, 29 pages – 242 KB)_.
  * Report to the Public on [Events Surrounding jetBlue Data Transfer](http://www.dhs.gov/xlibrary/assets/privacy/privacy_rpt_jetblue.pdf) February 20, 2004 _(PDF, 10 pages – 65 KB)_



**Stay up to date with the latest news:**

Twitter: [https://twitter.com/#!/kr3at](https://twitter.com/#%21/kr3at)  
Facebook: <http://facebook.com/alexhiggins732>  
Website: [The Alexander Higgins Blog](http://blog.alexanderhiggins.com/)  
Headlines: [Real-time News Headlines](http://blog.alexanderhiggins.com/)
