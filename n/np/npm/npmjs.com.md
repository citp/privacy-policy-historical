> *The following text is extracted and transformed from the npmjs.com privacy policy that was archived on 2016-11-24. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20161124003842id_/https%3A//www.npmjs.com/policies/privacy) for the most accurate reproduction.*

# npm

We track data about users of the npm website, the npm public registry and any other services we may offer from time to time.

This page tells you what we track, and what we do with it.

## The npm Registry

All requests to the registry are logged and retained by npm, Inc. These requests include non-personally identifiable information such as the package requested and the time of the request, as well as potentially personally identifiable information such as the IP address of the requester.

For example, this is a sample of the kind of data we track in our logs when you download a package:
    
    
    2014-05-05T23:17:52Z 50.1.57.179 "-" "GET /npm-test-blerg" 200 "npm/1.4.10 node/v0.10.26 darwin x64" "install npm-test-blerg" "1db337334dbd3fc1" "MISS" "shield__cache_v41_ASH__ashburn_va_us" "cache-v41-ASH"
    2014-05-05T23:17:53Z 50.1.57.179 "-" "GET /npm/public/registry/npm-test-blerg/_attachments/npm-test-blerg-0.1000.1.tgz" 200 "npm/1.4.10 node/v0.10.26 darwin x64" "install npm-test-blerg" "1db337334dbd3fc1" "MISS" "shield__cache_c99_CHI__chi_il_us" "cache-c99-CHI"
    

This includes a number of things:

  1. The date and time.
  2. The IP address of the requester.
  3. The HTTP request URL and method.
  4. The HTTP response status code.
  5. The `user-agent` string, which includes the versions of Node and npm in use.
  6. Data about the CDN cache.
  7. A random `npm-session` header, unique to a single invocation of the `npm` command line utility.
  8. A `referer` header, which will indicate the command that was invoked.



For example, if you type `npm install express`, then all HTTP requests as a result of that command will indicate that they are related to a single action, and that the originating request was for the `express` module.

Note that different versions of npm may send different information, so some of the fields may not be tracked for all requests.

## The npm Website

Like most website operators, npm, Inc. collects non-personally-identifying information of the sort that web browsers and servers typically make available, such as the browser type, language preference, referring site, and the date and time of each visitor request. npm, Inc.'s purpose in collecting non-personally identifying information is to better understand how npm's visitors use its website. From time to time, npm, Inc. may release non-personally-identifying information in the aggregate, e.g., by publishing a report on trends in website usage.

npm, Inc. also collects potentially personally-identifying information like Internet Protocol (IP) addresses. npm, Inc. does not use such information to identify its visitors, however, and does not disclose such information, other than under the same circumstances that it uses and discloses personally-identifying information, as described below.

The npm website uses Google Analytics to monitor and analyze user behavior. This service provides npm, Inc. with information on users' demographics, age, location, and interest categories, when such information is available. This information is not used to identify individual users, but can in some cases be very specific. You can learn more about the information gathered and retained by this service at the [Google Analytics privacy policy](https://support.google.com/analytics/answer/2700409?hl=en&utm_id=ad). You can opt out of Google Analytics entirely with the [Google Analytics opt-out browser addon](https://support.google.com/analytics/answer/181881?hl=en&ref_topic=2919631).

The npm website uses Oracle Marketing Cloud to collect and manage leads for marketing purposes. Information on what data Oracle Marketing Cloud stores about users, how it is collected, and how it is used are available in [Oracle Marketing Cloud & Oracle Data Cloud Privacy Policy](http://www.oracle.com/us/legal/privacy/marketing-cloud-data-cloud-privacy-policy).

The npm website uses Optimizely to test the effects of changes to the npm website on users' browsing experiences. Information on what data Optimizely stores about users, how it is collected, and how it is used are available in [Optimizely's privacy policy](https://www.optimizely.com/privacy/).

## Collection of Personally Identifying Information

In order to write information into the npm registry database (for example, to publish packages, bookmark packages, edit metadata, etc.) users may decide to provide certain personally identifying information including but not limited to: email address, username, password, personal website, and account names on other services such as GitHub, Twitter, and IRC.

When packages are published in the npm registry, the user responsible for the publish action is saved, along with the date and time of the publish. This information is shared on the website.

If you create an account or publish a package, your email address will be publicly disclosed.

If users do not want their information tracked in this manner, they can opt to not create an account. However, this means that some features of npm and the npm website will be unavailable to them.

## Use of Personally Identifying Information

We may use personally identifying information we have collected about you, including your email address, to provide you with news, notes, and recommendations. You can opt out of receiving such messages at any time by using the "unsubscribe" links or directions at the ends of messages you receive. In addition, we use collected personally identifying information to operate our business and the npm service. We do not disclose your personal information to unaffiliated third parties who may want to offer you their own products and services unless you have requested or authorized us to do so.

We may share your personal information with third parties or affiliates where it is necessary for us to complete a transaction or do something you have asked us to do. Likewise, we may share your personal information with third parties or affiliates with whom we have contracted to perform services on our behalf. Companies that act on our behalf are required to keep the personal information we provide to them confidential and to use the personal information we share only to provide the services we ask them to perform.

In addition, we may disclose personal information in the good faith belief that we are lawfully authorized to do so, or that doing so is reasonably necessary to comply with legal process or authorities, respond to any claims, or to protect the rights, property, or personal safety of npm, our users, our employees, or the public. In addition, information about our users, including personal information, may be disclosed or transferred as part of, or during negotiations of, any merger, sale of company assets, or acquisition.

## Cookies

A cookie is a string of information that a website stores on a visitor's computer, and that the visitor's browser provides to the website each time the visitor returns.

The npm website uses cookies to help identify and track visitors, their usage of the npm website, and their website access credentials. npm website visitors who do not wish to have cookies placed on their computers should set their browsers to refuse cookies before using npm, Inc.'s websites, with the drawback that certain features of npm, Inc.'s websites may not function properly without the aid of cookies.

## Packages Published to The npm Registry

Most packages published to the npm registry are open source, and freely available to all users of the npm service. We show basic package metadata on the npm website, in a variety of forms, so as to assist users in finding a package that meets their needs.

We may also inspect the contents of published packages to investigate any claims of malicious contents, or to debug problems that may occur in the process of running the service. For open source packages, we may also analyze the contents of published packages in an automated fashion to gain information about how people use npm packages. This information may be disclosed to third parties on our website, or in other forms. (Note that it is already freely available to anyone who downloads the packages themselves.)

If a package is published to the npm registry in such a way as to restrict read-access to the package, then we may still need to inspect the package contents on rare occasions. However, we never disclose information about a private package--including the fact that the package exists--to third parties who are not granted access to the package by the package's owners.

## Disclosure of Log Information

All user information is retained in raw form for such time as deemed appropriate by npm, Inc. It is shared with employees and contractors of npm, Inc., as needed to process information on npm, Inc.'s behalf.

Raw log data is not shared with third parties, but may be shared in aggregate. For example, every page on the npm includes a report on the number of downloads that module has received, and occasionally npm, Inc. may publish blog posts or reports on registry or website usage.

We also analyze log data for a variety of reasons, including counting up downloads and unique visitors, debugging production problems, tracking which versions of Node.js and npm are in use in the wild, and researching how npm packages are used together with one another. This helps us to better understand the usage patterns of npm, and make better decisions about the npm product.

## Use by Minors

The npm service is not intended for use by minor children (under the age of 18). Parents and guardians should monitor the use of the npm service by minor children. Children under age 13 should not use the npm service at all. If a child under age 13 submits personal information through any part of the service, and we become aware that the person submitting the information is under age 13, we will attempt to delete the information as soon as reasonably possible.

## Links to Other Websites

The npm service may contain links to other websites. Any personal information you provide on the linked pages is provided directly to that third party and is subject to that third party's privacy policy. Except as described above, we are not responsible for the content or privacy and security practices and policies of websites to which we link. Links from the npm service to third parties or to other sites are provided for your convenience. We encourage you to learn about their privacy and security practices and policies before providing them with personal information.

## United States Jurisdiction

The npm service is hosted in the United States. This Privacy Policy is intended to comply with privacy laws in the United States and may not comply with all privacy laws in other countries.

If you are a non-US user of the service, by using our service and providing us with data, you acknowledge, agree and provide your consent that your personal information may be processed in the United States for the purposes identified in this Privacy Policy. In addition, such data may be stored on servers located outside your resident jurisdiction, which may have less stringent privacy practices than your own. By using the npm service and providing us with your data, you consent to the transfer of such data and any less stringent privacy practices.

## Contact Information

If you have any questions or concerns about how we track user information, or how that information is used, please contact us at once.

You may contact npm, Inc. via our [contact form](http://www.npmjs.com/contact), by emailing [legal@npmjs.com](mailto:legal@npmjs.com), or via snail mail at:

npm, Inc.  
1999 Harrison Street  
Suite 1150  
Oakland CA 94612  
USA

## Privacy Policy Changes

Although most changes are likely to be minor, npm, Inc. may change its Privacy Policy from time to time, and in npm, Inc.'s sole discretion. Any such changes will be posted on [the npm blog](http://blog.npmjs.org/), and the detailed history of changes can be found in [the git repository history for this document](https://github.com/npm/policies/commits/master/privacy.md).

npm, Inc. encourages visitors to frequently check this page for any changes to its Privacy Policy. Your continued use of the npm website and the npm public registry after any change in this Privacy Policy will constitute your acceptance of such change.

## Credit and License

Parts of this policy document were originally included in the [WordPress.org privacy policy](https://wordpress.org/about/privacy/), used with permission.

This document may be reused under a [Creative Commons Attribution-ShareAlike License](http://creativecommons.org/licenses/by-sa/4.0/).
