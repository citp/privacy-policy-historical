> *The following text is extracted and transformed from the base64decode.org privacy policy that was archived on 2019-12-30. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20191230150751id_/https%3A//www.base64decode.org/privacy) for the most accurate reproduction.*

# Base64 Decode and Encode - Online - Privacy policy

This document was last updated on Dec 15, 2019 We are committed to protect and respect your privacy. This privacy policy describes and governs our information collection, use, and sharing practices. Before you submit/upload any information or file to our websites, please carefully review this policy.

 **Preliminary**

  * We DO NOT keep or inspect any information (e.g.: text, setting) or file submitted/uploaded to our websites.
  * We DO NOT ask for, or require any personal information (e.g.: name, username, password, email address, credit card) at our websites.



 **Data controller**

For the purpose of data protection laws applicable from time to time to you in the location that you provide your information, we are the "data controller" for the information you provide through our websites. There may be other controllers as well (e.g.: advertisers), and we encourage you to consult their privacy policies to learn more about their privacy practices.

Our primary data controller's contact:

Zoltan Hajdu  
Email: [contact@base64decode.org](mailto:contact@base64decode.org)  
Mobile: [+36-30-608-85-50](tel:+36306088550)

 **Data storage and usage purposes**

Please note that this privacy policy applies only to information collected through our websites and not to information you may provide to any third-party sites to which we may link to.

  * We make use of web server log files. The information inside these log files are IP address, date/time stamp, referring/exit page, and type of browser. We use this information solely to administer our websites.
  * We use third-party ad server services Google Adsense and Crispox Ads; web analytics service Google Analytics, and consent management platform from Quantcast.



We and our third-party service providers (detailed above) may also store and collect data related to your use of our websites for the following purposes. You can review or update the related consent with the button labeled "Update consent" at the bottom of our pages. Please note that by rejecting any or all of them, you may not have access to certain features or offerings of our websites.

  * Information storage and access. The storage of information, or access to information that is already stored, on your device such as advertising identifiers, device identifiers, cookies, and similar technologies.
  * Personalisation. The collection and processing of information about your use of this service to subsequently personalise advertising and/or content for you in other contexts, such as on other websites or apps, over time.
  * Ad selection, delivery, reporting. The collection of information, and combination with previously collected information, to select and deliver advertisements for you, and to measure the delivery and effectiveness of such advertisements.
  * Content selection, delivery, reporting. The collection of information, and combination with previously collected information, to select and deliver content for you, and to measure the delivery and effectiveness of such content.
  * Measurement. The collection of information about your use of the content, and combination with previously collected information, used to measure, understand, and report on your usage of the service.



This consent applies to all of our "Online tool sites", including domains: base64decode.org, base64encode.org, urldecoder.org, urlencoder.org, minifyjson.org, beautifyjson.org, uglifyjs.net, prettifyjs.net, uglifycss.com, prettifycss.com, pwdgen.org, numgen.org, strlength.com, strreverse.com, pdfmrg.com, pdfspl.com, convzone.com.

 **Data retention**

  * Our web server log files are deleted after 90 days.
  * Our Google Analytics tracking code is configured to store data that is associated with cookies, user identifiers, or advertising identifiers for up to 14 months.



 _If you require more information or have any questions about our privacy policy, please feel free to contact us._

 __About

Meet Base64 Decode and Encode, a simple online tool that does exactly what it says; decodes Base64 encoding and encodes into it quickly and easily. Base64 encode your data in a hassle-free way, or decode it into human-readable format.

Base64 encoding schemes are commonly used when there is a need to encode binary data that needs be stored and transferred over media that are designed to deal with textual data. This is to ensure that the data remains intact without modification during transport. Base64 is used commonly in a number of applications including email via MIME, and storing complex data in XML.

 **Easy to use**

Begin with the "type (or paste) here..." area to enter your data, then hit the "encode" or "decode" buttons respectively. After a blink of any eye, the results will be shown below these buttons. Alternatively, use the "click (or tap) here..." area to select a file from your device, then hit the corresponding button. Once the upload and processing completes, you will be notified to download the resulting decoded/encoded file. That's all!

 **Completely free**

Our tool is free to use. From now you don't have to download any software for such tasks.

 **Safe and secure**

All communications with our servers are made through secure SSL encrypted connections (https). Uploaded files are deleted from our servers immediately after the decode or encode process, and the resulting downloadable file is deleted right after the first download attempt, or 15 minutes of inactivity. We do not keep or inspect the contents of the entered data or uploaded files in any way. Read our privacy policy below for more details.

 **Details of the Base64 encoding**

Base64 is a generic term for a number of similar encoding schemes that encode binary data by treating it numerically and translating it into a base 64 representation. The Base64 term originates from a specific MIME content transfer encoding.

 _Design_

The particular choice of characters to make up the 64 characters required for base varies between implementations. The general rule is to choose a set of 64 characters that is both part of a subset common to most encodings, and also printable. This combination leaves the data unlikely to be modified in transit through systems, such as email, which were traditionally not 8-bit clean. For example, MIME's Base64 implementation uses A-Z, a-z, and 0-9 for the first 62 values. Other variations, usually derived from Base64, share this property but differ in the symbols chosen for the last two values; an example is UTF-7.

 _Example_

A quote snippet from Thomas Hobbes's Leviathan:

" _Man is distinguished, not only by his reason, but ..._ "

represented as an ASCII byte sequence is encoded in MIME's Base64 scheme as follows:

TWFuIGlzIGRpc3Rpbmd1aXNoZWQsIG5vdCBvbmx5IGJ5IGhpcyByZWFzb24sIGJ1dCAuLi4=

In the above quote the encoded value of _Man_ is _TWFu_. Encoded in ASCII, _M_ , _a_ , _n_ are stored as the bytes 77, 97, 110, which are 01001101, 01100001, 01101110 in base 2. These three bytes are joined together in a 24 bit buffer producing 010011010110000101101110. Packs of 6 bits (6 bits have a maximum of 64 different binary values) are converted into 4 numbers (24 = 4 * 6 bits) which are then converted to their corresponding values in Base64.

Text content| M| a| n  
---|---|---|---  
ASCII| 77| 97| 110  
Bit pattern| 0| 1| 0| 0| 1| 1| 0| 1| 0| 1| 1| 0| 0| 0| 0| 1| 0| 1| 1| 0| 1| 1| 1| 0  
Index| 19| 22| 5| 46  
Base64-encoded| T| W| F| u  
  
As this example illustrates, Base64 encoding converts 3 uncoded bytes (in this case, ASCII characters) into 4 encoded ASCII characters.
