> *The following text is extracted and transformed from the freedom-to-tinker.com privacy policy that was archived on 2016-05-05. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20160505064753id_/https%3A//freedom-to-tinker.com/blog/tag/privacy) for the most accurate reproduction.*

# Privacy

[](http://www.cs.rice.edu/~dwallach/ "Visit dwallach’s website")

## [On distracted driving and required phone searches](https://freedom-to-tinker.com/blog/dwallach/on-distracted-driving-and-required-phone-searches/)

April 15, 2016 by [3 Comments](https://freedom-to-tinker.com/blog/dwallach/on-distracted-driving-and-required-phone-searches/#comments)

A recent [Arstechnica article](http://arstechnica.com/tech-policy/2016/04/first-came-the-breathalyzer-now-meet-the-roadside-police-textalyzer/) discussed several U.S. states that are considering adding a “roadside textalyzer” that operates analogously to roadside Breathalyzer tests. In the same way that alcohol and drugs can impair a driver’s ability to navigate the road, so can paying attention to your phone rather than the world beyond. Many states “require” drivers to consent to Breathalyzer tests, where that “requirement” boils down to serious penalties if the driver declines. Vendors like [Cellebrite](http://www.cellebrite.com/) are pushing for analogous requirements, for which they just happen to sell products.  
[[Read more…]](https://freedom-to-tinker.com/blog/dwallach/on-distracted-driving-and-required-phone-searches/)

[](http://www.cs.cornell.edu/~shmat "Visit vitaly’s website")

## [Gone In Six Characters: Short URLs Considered Harmful for Cloud Services](https://freedom-to-tinker.com/blog/vitaly/gone-in-six-characters-short-urls-considered-harmful-for-cloud-services/)

_[This is a guest post by Vitaly Shmatikov, professor at Cornell Tech and once upon a time my adviser at the University of Texas at Austin. — Arvind Narayanan.]_

**TL;DR: short URLs produced by bit.ly, goo.gl, and similar services are so short that they can be scanned by brute force.  Our scan discovered a large number of Microsoft OneDrive accounts with private documents.  Many of these accounts are unlocked and allow anyone to inject malware that will be automatically downloaded to users’ devices.  We also discovered many driving directions that reveal sensitive information for identifiable individuals, including their visits to specialized medical facilities, prisons, and adult establishments.**

URL shorteners such as [bit.ly](https://bitly.com/) and [goo.gl](https://goo.gl/) perform a straightforward task: they turn long URLs into short ones, consisting of a domain name followed by a 5-, 6-, or 7-character token.  This simple convenience feature turns out to have an unintended consequence.  The tokens are so short that the entire set of URLs can be scanned by brute force.  The actual, long URLs are thus effectively public and can be discovered by anyone with a little patience and a few machines at her disposal.

Today, we are releasing our [study](http://arxiv.org/pdf/1604.02734v1.pdf), 18 months in the making, of what URL shortening means for the security and privacy of cloud services.  We did not perform a comprehensive scan of all short URLs (as our analysis shows, such a scan would have been within the capabilities of a more powerful adversary), but we sampled enough to discover interesting information and draw important conclusions.  Our study focused on two cloud services that directly integrate URL shortening: Microsoft OneDrive cloud storage (formerly known as SkyDrive) and Google Maps.  In both cases, whenever a user wants to share a link to a document, folder, or map with another user, the service offers to generate a short URL – which, as we show, unintentionally makes the original URL public.  
[[Read more…]](https://freedom-to-tinker.com/blog/vitaly/gone-in-six-characters-short-urls-considered-harmful-for-cloud-services/)

[](http://www.cs.princeton.edu/~feamster/ "Visit Nick Feamster’s website")

## [Who Will Secure the Internet of Things?](https://freedom-to-tinker.com/blog/feamster/who-will-secure-the-internet-of-things/)

January 19, 2016 by [Nick Feamster](https://freedom-to-tinker.com/blog/author/feamster/)

Over the past several months, CITP-affiliated Ph.D. student [Sarthak Grover](http://www.cs.princeton.edu/~sgrover/) and fellow [Roya Ensafi](https://www.cs.princeton.edu/~rensafi/) been investigating various security and privacy vulnerabilities of Internet of Things (IoT) devices in the home network, to get a better sense of the current state of smart devices that many consumers have begun to install in their homes.

To explore this question, we purchased a collection of popular IoT devices, connected them to a laboratory network at CITP, and monitored the traffic that these devices exchanged with the public Internet. We initially expected that end-to-end encryption might foil our attempts to monitor the traffic to and from these devices. The devices we explored included a [Belkin WeMo Switch](http://www.amazon.com/WeMo-Insight-Electronics-anywhere-Compatible/dp/B00EOEDJ9W/ref=sr_1_3?s=hi&ie=UTF8&qid=1453225162&sr=1-3&keywords=belkin+wemo+switch), the [Nest Thermostat](http://www.amazon.com/Nest-Learning-Thermostat-2nd-Generation/dp/B009GDHYPQ/ref=sr_1_2?s=hi&ie=UTF8&qid=1453225128&sr=1-2&keywords=nest+thermostat), an [Ubi Smart Speaker](http://www.theubi.com/), a [Sharx Security Camera](http://www.amazon.com/gp/product/B005WFZD0U?psc=1&redirect=true&ref_=oh_aui_search_detailpage), a [PixStar Digital Photoframe](http://www.amazon.com/Pix-Star-Digital-FotoConnect-Providers-Android/dp/B0056HNTAU/ref=sr_1_1?s=hi&ie=UTF8&qid=1453225305&sr=8-1&keywords=pixstar+photoframe), and a [Smartthings hub](http://www.amazon.com/Samsung-SmartThings-Hub-2nd-Generation/dp/B010NZV0GE/ref=sr_1_cc_1?s=aps&ie=UTF8&qid=1453225268&sr=1-1-catcorr&keywords=smartthings+hub).

#### What We Found: Be Afraid!

**Many devices fail to encrypt at least some of the traffic that they send and receive.  **Investigating the traffic to and from these devices turned out to be much easier than expected, as many of the devices exchanged personal or private information with servers on the Internet  _in the clear_ , completely unencrypted.

We recently presented a [summary of our findings](https://www.dropbox.com/s/36nxibezelxrduk/FTC-PrivacyCon-2016.pdf) to the Federal Trade Commission, last week at [PrivacyCon](https://www.ftc.gov/news-events/events-calendar/2016/01/privacycon).  The video of Sarthak’s talk is available from the FTC website, as well as [on YouTube](https://www.youtube.com/watch?v=-778aD_XVKI).  Among some of the more striking findings include:

  * The Nest thermostat was revealing location information of the home and weather station, including the user’s zip code, in the clear.  (Note: Nest promptly fixed this bug after we notified them.)
  * The Ubi uses unencrypted HTTP to communicate information to its portal, including voice chats, sensor readings (sound, temperature, light, humidity). It also communicates to the user using unencrypted email. Needless to say, much of this information, including the sensor readings, could reveal critical information, such as whether the user was home, or even movements within a house.
  * The Sharx security camera transmits video over unencrypted FTP; if the server for the video archive is outside of the home, this traffic could also be intercepted by an eavesdropper.
  * All traffic to and from the PixStar photoframe was sent unencrypted, revealing many user interactions with the device.



Traffic capture from Nest Thermostat in Fall 2015, showing user zip code and other information in cleartext.

| 

Traffic capture from Ubi, which sends sensor values and states in clear text.  
  
---|---  
  
**Some devices encrypt data traffic, but encryption may not be enough.** A natural reaction to some of these findings might be that these devices should encrypt all traffic that they send and receive. Indeed, some devices we investigated ( _e.g._ , the Smartthings hub) already do so. Encryption may be a good starting point, but by itself, it appears to be insufficient for preserving user privacy.  For example, user interactions with these devices generate traffic signatures that reveal information, such as when power to an outlet has been switched on or off. It appears that simple traffic features such as traffic volume over time may be sufficient to reveal certain user activities.

In all cases, DNS queries from the devices clearly indicate the presence of these devices in a user’s home. Indeed, even when the data traffic itself is encrypted, other traffic sent in the clear, such as DNS lookups, may reveal not only the presence of certain devices in your home, but likely also information about both usage and activity patterns.

Of course, there is also the concern about how these companies may use and share the data that they collect, even if they manage to collect it securely. And, beyond the obvious and more conventional privacy and security risks, there are also potential  _physical_ risks to infrastructure that may result from these privacy and security problems.

**Old problems, new constraints.** Many of the security and privacy problems that we see with IoT devices sound familiar, but these problems arise in a new, unique context, which present unique challenges:

  * _Fundamentally insecure._  Manufacturers of consumer products have little interest in releasing software patches and may even design the device without any interfaces for patching the software in the first place.  There are [various examples of insecure devices](http://www.forbes.com/sites/kashmirhill/2013/07/26/smart-homes-hack/) that ordinary users may connect to the network without any attempts to secure them (or any means of doing so).  Occasionally, these insecure devices can result in “[stepping stones](http://internet.watch.impress.co.jp/cda/news/2004/10/06/4882.html)” into the home for attackers to mount more extensive attacks. A [recent study](https://dl.acm.org/citation.cfm?doid=1920261.1920276) identified more than 500,000 insecure, publicly accessible embedded networked devices.
  * _Diverse._  Consumer IoT settings bring a diversity of devices, manufacturers, firmware versions, and so forth. This diversity can make it difficult for a consumer (or the consumer’s ISP) to answer even simple questions such as exhaustively identifying the set of devices that are connected to the network in the first place, let alone detecting behavior or network traffic that might reveal an anomaly, compromise, or attack.
  * _Constrained._ Many of the devices in an IoT network are severely resource-constrained: the devices may have limited processing or storage capabilities, or even limited battery life, and they often lack a screen or intuitive user interface. In some cases, a user may not even be able to log into the device.  



Complicating matters, a user has limited control over the IoT device, particularly as compared to a general-purpose computing platform. When we connect a general purpose device to a network, we typically have at least a modicum of choice and control about what software we run (e.g., browser, operating system), and perhaps some more visibility or control into how that device interacts with other devices on the network and on the public Internet. When we connect a camera, thermostat, or sensor to our network, the hardware and software are much more tightly integrated, and our visibility into and control over that device is much more limited. At this point, we have trouble, for example, even knowing that a device might be sending private data to the Internet, let alone being able to stop it.

Compounding all of these problems, of course, is the access a consumer gives an untrusted IoT device to  _other_ data or devices on the home network, simply by connecting it to the network—effectively placing it behind the firewall and giving it full network access, including in many cases the shared key for the Wi-Fi network.

#### A Way Forward

Ultimately, multiple stakeholders may be involved with ensuring the security of a networked IoT device, including consumers, manufacturers, and Internet service providers. There remain many unanswered questions concerning both who is able to (and responsible for) securing these devices, but we should start the discussion about how to improve the security for networks with IoT devices.

This discussion will include both policy aspects (including who bears the ultimate responsibility for device insecurity, whether devices need to adopt standard practices or behavior, and for how long their manufacturers should continue to support them), as well as technical aspects (including how we design the network to better monitor and control the behavior of these often-insecure devices).

**Devices should be more transparent.  **The first step towards improving security and privacy for IoT should be to work with manufacturers to improve the  _transparency_ of these IoT devices, so that consumers (and possibly ISPs) have more visibility into what software the devices are running, and what traffic they are sending and receiving. This, of course, is a Herculean effort, given the vast quantity and diversity of device manufacturers; an alternative would be trying to  _infer_ what devices are connected to the network based on their traffic behavior, but doing so in a way that is both comprehensive, accurate, and reasonably informative seems extremely difficult.

Instead, some IoT device manufacturers might standardize on a manifest protocol that announces basic information, such as the device type, available sensors, firmware version, the set of destinations the device expects to communicate with (and whether the traffic is encrypted), and so forth. (Of course, such a manifest poses its own security risks.)

**Network infrastructure can  play a role. **Given such basic information, anomalous behavior that is suggestive of a compromise or data leak would be more evident to network intrusion detection systems and firewalls—in other words, we could bring more of our standard network security tools to bear on these devices, once we have a way to identify what the devices are and what their expected behavior should be. Such a manifest might also serve as a concise (and machine readable!) privacy statement; a concise manifest might be one way for consumers to evaluate their comfort with a certain device, even though it may be far from a complete privacy statement.

Armed with such basic information about the devices on the network, smart network switches would have a much easier way to implement network security policies. For example, a user could specify that the smart camera should never be able to communicate with the public Internet, or that the thermostat should only be able to interact with the window locks if someone is present.

Current network switches don’t provide easy mechanisms for consumers to either express or implement these types of policies. Advances in Software-Defined Networking (SDN) in software switches such as [Open vSwitch](http://openvswitch.org/) may make it possible to implement policies that resolve contention for shared resources and conflicts, or to isolate devices on the network from one another, but even if that is a reasonable engineering direction, this technology will only take us part of the way, as users will ultimately need far better interfaces to both monitor network activity and express policies about how these devices should behave and exchange traffic.

_Update [20 Jan 2015]: After[significant](http://mashable.com/2016/01/20/nest-smart-thermostat-leak/#ZV1u.s.FU5qx) [press](http://consumerist.com/2016/01/20/nest-thermostats-have-been-leaking-users-home-locations-over-wifi/) [coverage](http://www.popularmechanics.com/technology/security/a19062/nest-thermostats-releasing-address-information-on-internet/), Nest has contacted the media to clarify that the information being leaked in cleartext was not the zip code of the thermostat, but merely the zip code that the user enters when configuring the device. (Clarifying statement [here](http://thenextweb.com/gadgets/2016/01/20/dont-trust-the-internet-of-things).) Of course, when would a user ever enter a zip code other than that of their home, where the thermostat was located?_

## [The Web Privacy Problem is a Transparency Problem: Introducing the OpenWPM measurement tool](https://freedom-to-tinker.com/blog/englehardt/the-web-privacy-problem-is-a-transparency-problem-introducing-the-openwpm-measurement-tool/)

January 14, 2016 by [Steven Englehardt](https://freedom-to-tinker.com/blog/author/englehardt/)

In a previous [blog post](https://freedom-to-tinker.com/blog/englehardt/retrospective-look-at-canvas-fingerprinting/) I explored the success of our study, [The Web Never Forgets](https://securehomes.esat.kuleuven.be/~gacar/persistent/), in having a positive impact on web privacy. To ensure a lasting impact, we’ve been doing monthly, automated 1-million-site measurement of tracking and privacy. Soon we’ll be releasing these datasets and our findings. But in this post I’d like to introduce our web measurement platform OpenWPM that we’ve built for this purpose. OpenWPM has been quickly gaining adoption — it has already been used by at least 6 other research groups, as well as journalists, regulators, and students for class projects. In this post, I’ll explain why we built OpenWPM, describe a previously unmeasured type of tracking we found using the tool, and show you how you can participate and contribute to this community effort.

> This post is based on a talk I gave at the FTC’s [PrivacyCon](https://www.ftc.gov/news-events/events-calendar/2016/01/privacycon). You can watch the video online [here](https://youtu.be/o2DlNNXD74w).

**Why monthly, large-scale measurements are necessary**

In my previous post, I showed how measurements from academic studies can help improve online privacy, but I also pointed out how they can fall short. Measurement results often have an immediate impact on online privacy. Unless that impact leads to a technical, policy, or legal solution, the impact will taper off over time as the measurements age.

Technical solutions do not always exist for privacy violations. I discussed how canvas fingerprinting can’t be prevented without sacrificing usability in my [previous blog post](https://freedom-to-tinker.com/blog/englehardt/retrospective-look-at-canvas-fingerprinting/), but there are others as well. For example, it has proven difficult to find a satisfactory solution to the [privacy concerns](https://bugzilla.mozilla.org/show_bug.cgi?id=959893) surrounding WebRTC’s access to local IPs. This is also highlighted in the [unofficial W3C draft](https://w3c.github.io/fingerprinting-guidance/) on Fingerprinting Guidance for Web Specification Authors, which states: “elimination of the capability of browser fingerprinting by a determined adversary through solely technical means that are widely deployed is implausible.”

It seems inevitable that measurement results will go out of date, for two reasons. Most obviously, there is a high engineering cost to running privacy studies. Equally important is the fact that academic papers in this area are published as much for their methodological novelty as for their measurement results. Updating the results of an earlier study is unlikely to lead to a publication, which takes away the incentive to do it at all. [1]

**OpenWPM: our platform for automated, large-scale web privacy measurements**

We built OpenWPM ([Github](https://github.com/citp/OpenWPM), [technical report](http://www.cs.princeton.edu/~ste/papers/openwpm_03-2015.pdf)), a generic platform for online tracking measurement. It provides the stability and instrumentation necessary to run many online privacy studies. Our goal in developing OpenWPM is to decrease the initial engineering cost of studies and make running a measurement as effortless as possible. It has already been used in [several](http://www.jbonneau.com/doc/RB14-COSN-understanding_facebook_login_permissions.pdf) [published](http://www.ieee-security.org/TC/SPW2015/W2SP/papers/W2SP_2015_submission_20.pdf) [studies](http://www.jbonneau.com/doc/KB15-NDSS-hsts_pinning_survey.pdf) [from](http://techscience.org/a/2015121502/download.pdf) [multiple](https://www.internetsociety.org/sites/default/files/Upgrading%20HTTPS%20in%20Mid-Air-%20An%20Empirical%20Study%20of%20Strict%20Transport%20Security%20and%20Key%20Pinning.pdf) institutions to detect and reverse engineer online tracking.

OpenWPM also makes it possible to run large-scale measurements with Firefox, a real consumer browser [2]. Large scale measurement lets us compare the privacy practices of the most popular sites to those in the long tail. This is especially important when observing the use of a tracking technique highlighted in a measurement study. For example, we can check if it’s removed from popular sites but added to less popular sites.

**Transparency through measurement, on 1 million sites**

We are using OpenWPM to run the Princeton Transparency Census, a monthly web-scale measurement of tracking techniques and privacy issues, comprising 1 million sites. With it, we will be able to detect and measure many of the known privacy violations reported by researchers so far: the use of stateful tracking mechanisms, browser fingerprinting, cookie synchronization, and more.

During the measurements, we’ll collect data in three categories: (1)  network traffic — all HTTP requests and response headers (2) client-side state — cookies, Flash cookies, etc. (3) execution traces — we trap and record targeted JavaScript API calls that have been known to be used for tracking. In addition to releasing all of the raw data collected during the census, we’ll release the results of our own automated analysis.

Alongside the 1 million site measurement, we are also running smaller, targeted measurements with different browser configurations. Examples include crawling deeper into the site or browsing with a privacy extension, such as [Ghostery](https://www.ghostery.com/) or [AdBlock Plus](https://adblockplus.org/). These smaller crawls will provide additional insight into the privacy threats faced by real users.

**Detecting WebRTC local IP discovery**

As a case study of the ease of introducing a new measurement into the infrastructure, I’ll walk through the steps I took to measure scripts using WebRTC to discover a machine’s local IP address [3]. For machines behind a home router, this technique may reveal an IP of the form 192.168.1.*. Users of corporate or university networks may return a unique local IP address from within that organization’s IP range.

A user’s local IP address adds additional information to a browser fingerprint. For example, it can be used as a way to differentiate multiple users behind a NAT without requiring browser state. The amount of identifying information it provides for the average user hasn’t been studied. However, both [Chrome](https://chromium.googlesource.com/chromium/src/+/7c98bab02128ae9fdc4fcc9a9df38588af86290e%5E!/chrome/common/pref_names.cc) and [Firefox](https://groups.google.com/forum/#!topic/mozilla.dev.media/L6Rx9ubSjMc) [4] have implemented opt-in solutions to prevent the technique. The first reported use that I could find for this technique [in the wild](https://twitter.com/incloud/status/619624021123010560) was a third-party on nytimes.com in July 2015.

After examining [a demo script](http://net.ipcalf.com/), I decided to record all property access and all method calls of the[ RTCPeerConnection](https://developer.mozilla.org/en-US/docs/Web/API/RTCPeerConnection) interface, the primary interface for WebRTC. The additional instrumentation necessary for this interface is just a [single line of Javascript](https://github.com/citp/OpenWPM/blob/master/automation/Extension/firefox/data/content.js#L341-L342) in OpenWPM’s Firefox extension.

A preliminary analysis [5] of a 50,000 site pilot measurement from October 2015 suggests that WebRTC local IP discovery is used on the homepages of over 100 sites, from over 20 distinct scripts. Only 1 of these scripts would be blocked by [EasyList or EasyPrivacy](https://easylist.adblockplus.org/en/).

**How can this be useful for you**

We envision several ways researchers and other members of the community can make use of  OpenWPM and our measurements. I’ve listed them here from least involved to most involved.

(1) _Use our measurement data for their own tools._ In my [analysis](https://freedom-to-tinker.com/blog/englehardt/retrospective-look-at-canvas-fingerprinting/) of canvas fingerprinting I mentioned that Disconnect [incorporated](https://blog.disconnect.me/disconnect-blocks-new-tracking-device-that-makes-your-computer-draw-a-unique-image/) our research results into their blocklist. We want to make it easy for privacy tools to make use of the analysis we run, by releasing analysis data in a structured, machine readable way.

(2) _Use the data collected during our measurements, and build their own analysis on top of it_. We know we’ll never be able to take the human element out of these studies. Detection methodologies will change, new features of the browser will be released and others will change. The depth of the Transparency measurements should make it easy test new ideas, with the option of contributing them back to the regular crawls.

(3) _Use OpenWPM to collect and release their own data_. This is the model we see most web privacy researchers opting for, and a model we plan to use for most of our [own](https://github.com/citp/TheWebNeverForgets) [studies](https://github.com/englehardt/cookies-that-give-you-away). The platform can be used and tweaked as necessary for the individual study, and the measurement results and data can be shared publicly after the study is complete.

(4) _Contribute to OpenWPM through pull requests._ This is the deepest level of involvement we see. Other developers can write new features into the infrastructure for their own studies or to be run as part of our transparency measurements. Contributions here will benefit all users of OpenWPM.

Over the coming months we will release new blog posts and research results on the measurements I’ve discussed in this post. You can follow our progress here on Freedom to Tinker, on Twitter [@s_englehardt](https://twitter.com/s_englehardt), and on our Github [repository](https://github.com/citp/OpenWPM).

[1] Notable exceptions include the study of cookie respawning: [2009](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=1446862), [2011](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=1898390), [2011](https://www.cylab.cmu.edu/files/pdfs/tech_reports/CMUCyLab11001.pdf), [2014](https://securehomes.esat.kuleuven.be/~gacar/persistent/the_web_never_forgets.pdf). and the statistics on stateful tracking use and third-party inclusion: [2009](https://dl.acm.org/citation.cfm?id=1526782), [2012](https://www.usenix.org/system/files/conference/nsdi12/nsdi12-final17.pdf), [2012](https://www.law.berkeley.edu/centers/bclt/research/privacy-at-bclt/web-privacy-census/june-2012-web-privacy-census/), [2012](https://www.law.berkeley.edu/centers/bclt/research/privacy-at-bclt/web-privacy-census/), [2015](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=2703814).

[2] Crawling with a real browser is important for two reasons: (1) it’s less likely to be detected as a bot, meaning we’re less likely to receive different treatment from a normal user, and (2) a real browser supports all the modern web features (e.g. WebRTC, HTML5 audio and video), plugins (e.g. Flash), and extensions (e.g. Ghostery, HTTPS Everywhere). Many of these additional features play a large role in the average user’s privacy online.

[3] There is an additional concern that WebRTC can be used to determine a VPN user’s actual IP address, however this attack is distinct from the one described in this post.

[4] [uBlock Origin](http://www.ghacks.net/2015/07/02/you-can-block-webrtc-from-leaking-your-ip-now-in-ublock-origin/) also provides an option to prevent WebRTC local IP discovery on Firefox.

[5] We are in the process of running and verifying this analysis on a our 1 million site measurements, and will release an updated analysis with more details in the future.

## [Do privacy studies help? A Retrospective look at Canvas Fingerprinting](https://freedom-to-tinker.com/blog/englehardt/retrospective-look-at-canvas-fingerprinting/)

January 12, 2016 by [Steven Englehardt](https://freedom-to-tinker.com/blog/author/englehardt/)

It seems like every month we hear of some new online privacy violation in the news, on topics such as [fingerprinting](http://techcrunch.com/2015/08/04/battery-attributes-can-be-used-to-track-web-users/) or [web](http://www.zdnet.com/article/facebook-cookie-case-why-even-the-like-button-infringes-eu-informed-consent-privacy-law/) [tracking](http://www.information-age.com/technology/security/123459843/new-york-times-breaches-user-privacy-tracking-private-ip-addresses). Many of these news stories highlight academic research. What we don’t see is whether these studies and the subsequent news stories have any impact on privacy.

Our 2014 canvas fingerprinting measurement offers an opportunity for me to provide that insight, as we ended up receiving a surprising amount of press coverage after releasing the paper. In this post I’ll examine the reaction to the paper and explore which aspects contributed to its positive impact on privacy. I’ll also explore how we can use this knowledge when designing future studies to maximize their impact.

**What we found in 2014**

The 2014 measurement paper, [The Web Never Forgets](https://securehomes.esat.kuleuven.be/~gacar/persistent/), is a collaboration with researchers at KU Leuven. In it, we measured the prevalence of three persistent tracking techniques online: canvas fingerprinting, cookie respawning, and cookie syncing [1]. They are persistent in that are hard to control, hard to detect, and resilient to blocking or removing.

We found that 5% of the top 100,000 sites were utilizing the HTML5 Canvas API as a fingerprinting vector. The overwhelming majority of which, 97%, was caused by the top two providers. The ability to use the HTML5 Canvas as a fingerprinting vector was first introduced in a [2012 paper](http://w2spconf.com/2012/papers/w2sp12-final4.pdf) by Mowery and Shacham. In the time between that 2012 paper and our 2014 measurement, approximately 20 sites and trackers started using canvas to fingerprint their visitors.

Several examples of the text written to the canvas for fingerprinting purposes. Each of these images would be converted to strings and then hashed to create an identifier.

**The reaction to our study**

Shortly after we released our paper publicly, we saw a significant amount of press coverage, including articles on [ProPublica](http://w2spconf.com/2012/papers/w2sp12-final4.pdf), [BBC](http://www.bbc.co.uk/news/technology-28423257), [Der Spiegel](http://www.spiegel.de/netzwelt/web/canvas-fingerprinting-macht-internetnutzung-nachverfolgbar-a-982280.html), and [more](https://securehomes.esat.kuleuven.be/~gacar/persistent/#press). The amount of coverage our paper received was a surprise for us; we weren’t the creators of the method, and we certainly weren’t the first to report on the fingerprintability of browsers [2]. Just two days later, [AddThis stopped](https://www.addthis.com/blog/2014/07/23/the-facts-about-our-use-of-a-canvas-element-in-our-recent-rd-test/) using canvas fingerprinting. The second largest provider at the time, Ligatus, [also stopped](http://www.propublica.org/article/meet-the-online-tracking-device-that-is-virtually-impossible-to-block) using the technique.

As can be expected, we saw many users take their frustrations to Twitter. There are users who wondered why publishers would fingerprint them:

> oh look, t-online.de uses canvas fingerprinting and violates my privacy. the company behind de-mail… source: <https://t.co/QzILn8jrg9> [#wtf](https://twitter.com/hashtag/wtf?src=hash)
> 
> — tom (@tomquas) [July 24, 2014](https://twitter.com/tomquas/status/492212242352721920)

complained about AddThis:

> I feel gross, because I used [@addthis](https://twitter.com/addthis) to share this article. But, everyone should know about [#canvasfingerprinting](https://twitter.com/hashtag/canvasfingerprinting?src=hash) <http://t.co/DHCbPbl845>
> 
> — Alex Sherer (@cymcyms) [July 22, 2014](https://twitter.com/cymcyms/status/491724007201177600)

> Remove AddThis from your website right now – > Clear Your Cookies? You Can’t Escape Canvas Fingerprinting <http://t.co/QPM9b614U8>
> 
> — Xavier Ashe (@XavierAshe) [July 25, 2014](https://twitter.com/XavierAshe/status/492522404586225664)

and expressed their dislike for canvas fingerprinting in general:

> Canvas fingerprinting is a technological way of stalking
> 
> — James King (@JamesKingMe) [July 24, 2014](https://twitter.com/JamesKingMe/status/492414250993086467)

> Hadn’t heard of this. Yikes: [#ProPublica](https://twitter.com/hashtag/ProPublica?src=hash): advertiser’s new solution to cookie blocking, [#canvasfingerprinting](https://twitter.com/hashtag/canvasfingerprinting?src=hash): <http://t.co/pztVMNL0dd>
> 
> — Jstheater (@jstheater) [July 23, 2014](https://twitter.com/jstheater/status/491776645901336576)

We even saw a user [question](https://support.mozilla.org/en-US/questions/1011864) as to why Mozilla does not protect against canvas fingerprinting in Firefox:  


However a general technical solution which preserves the API’s usefulness and usability doesn’t exist [3]. Instead the best solutions are either blocking the feature or blocking the trackers which use it.

The developer community responded by releasing canvas blocking extensions for [Firefox](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/) and [Chrome](https://chrome.google.com/webstore/detail/canvasfingerprintblock/ipmjngkmngdcdpmgmiebdmfbkcecdndc?hl=en-US), tools which are used by over 18,000 users in total. [AdBlockPlus](https://adblockplus.org/blog/adblock-plus-and-the-canvas-fingerprinting-threat) and [Disconnect](https://blog.disconnect.me/disconnect-blocks-new-tracking-device-that-makes-your-computer-draw-a-unique-image/) both commented that the large trackers are already on their block lists, with Disconnect mentioning that the additional, lesser-known parties from our study would be added to their lists.

**Why was our study so impactful?**

Much of the online privacy problem is actually a transparency problem. By default, users have very little information on the privacy practices of the websites they visit, and of the trackers included on those sites. Without this information users are unable to differentiate between sites which take steps to protect their privacy and sites which don’t. This leads to less of an incentive for site owners to protect the privacy of their users, as online privacy often comes at the expense of additional ad revenue or third-party features.

With our study, we were not only able to remove this information asymmetry [4], but were able to do so in a way that was relatable to users. The visual representation of canvas fingerprinting proved particularly helpful in removing that asymmetry of information; it was very intuitive to see how the shapes drawn to a canvas could produce a unique image. The [ProPublica article](https://www.propublica.org/article/meet-the-online-tracking-device-that-is-virtually-impossible-to-block) even included a demo where users could see their fingerprint built in real time.

While writing the paper we made it a point to include not only the trackers responsible for fingerprinting, but to also include the sites on which the fingerprinting was taking place. Instead of reading that tracker A was responsible for fingerprinting, they could understand that it occurs when they visit publishers X, Y and Z. If a user is frustrated by a technique, and is only familiar with the tracker responsible, there isn’t much they can do. By knowing the publishers on which the technique is used, they can voice their frustrations or choose to visit alternative sites. Publishes, which have in interest in keeping users, will then have an incentive to change their practices.

The technique wasn’t only news to users, even some site owners were unaware that it was being used on their sites. ProPublica [updated](http://www.propublica.org/article/meet-the-online-tracking-device-that-is-virtually-impossible-to-block) their original story with a message from YouPorn stating, “[the website was] completely unaware that AddThis contained a tracking software…”, and had since removed it. This shows that measurement work can even help remove the information asymmetry between trackers and the sites upon which they track.

**How are things now?**

In a re-run of the measurements in January 2016 [5], I’ve observed that the number of distinct trackers utilizing canvas fingerprinting has more than doubled since our 2014 measurement. While the overall number of publisher sites on which the tracking occurs is still below that of our previous measurement, the use of the technique has at least partially revived since AddThis and Ligatus stopped the practice.

This made me curious if we see similar trends for other tracking techniques. In our 2014 paper we also studied cookie respawning [6]. This technique was well studied in the past, both in [2009](http://papers.ssrn.com/sol3/papers.cfm?abstract_id=1446862) and [2011](http://ashkansoltani.org/2011/08/11/respawn-redux-flash-cookies/), making it a good candidate to analyze the longitudinal effects of measurement.  As is the case with our measurement, these studies also received a [bit of press](http://www.wired.com/2011/07/undeletable-cookie/) coverage when released.

The 2009 study, which found HTTP cookie respawning on 6 of the top 100 sites, resulted in a [$2.4 million settlement](http://www.wired.com/2010/12/zombie-cookie-settlement/). The 2011 follow-up study found that the use of respawning decreased to just 2 sites in the top 100, and likewise resulted in a [$500 thousand settlement](http://www.mediapost.com/publications/article/191409/kissmetrics-finalizes-supercookies-settlement.html). In 2014 we observed respawning on [7 of the top 100](https://securehomes.esat.kuleuven.be/~gacar/persistent/#results) sites, however none of these sites or trackers were US-based entities. This suggests that lawsuits can have an impact, but that impact may be limited by the global nature of the web.

**What we’ve learned**

Providing transparency into privacy violations online has the potential for huge impact. We saw users unhappy with the trackers that use canvas fingerprinting, with the sites that include those trackers, and even with the browsers they use to visit those sites. It is important that studies visit a large number of sites, and list those on which the privacy violation occurs.

The pressure of transparency affects the larger players more than the long tail. A tracker which is present on a large number of sites, or is present on sites which receive more traffic is more likely to be the focus of news articles or subject to lawsuits. Indeed, our 2016 measurements support it: we’ve seen a large increase in the number of parties involved, but the increase is limited to parties with a much smaller presence.

In the absence of a lawsuit, policy change, or technical solution, we see that canvas fingerprinting use is beginning to grow again. Without constant monitoring and transparency, level of privacy violations can easily creep back to where they were. A single, well-connected tracker can re-introduce a tracking technique to a large number of first-parties.

The developer community will help, we just need to provide them with the data they need. Our detection methodology served as the foundation for blocking tools, which intercept the same calls we used for detection. The script lists we included in our paper and on our website were incorporated into current blocklists.

In a follow-up post, I’ll discuss the work we’re doing to make regular, large scale measurements of web tracking a reality. I’ll show how the tools we’ve built make it possible to run automated, million site crawls can run every month, and I’ll introduce some new results we’re planning to release.

[1] The [paper’s website](https://securehomes.esat.kuleuven.be/~gacar/persistent/) provides a short description of each of these techniques.

[2] See: the EFF’s [Panopticlick](https://panopticlick.eff.org/), and academic papers [Cookieless Monster](https://seclab.cs.ucsb.edu/media/uploads/papers/sp2013_cookieless.pdf) and [FPDetective](https://securewww.esat.kuleuven.be/cosic/publications/article-2334.pdf).

[3] For example, adding noise to canvas readouts has the potential to cause problems for non-tracking use cases and can still be defeated by a determined tracker. The Tor Browser’s solution of [prompting the user](https://trac.torproject.org/projects/tor/ticket/6253) on certain canvas calls does work, however it requires a user’s understanding that the technique can be used for tracking and provides for a less than optimal user experience.

[4] For a nice discussion of information asymmetry and the web: [Privacy and the Market for Lemons, or How Websites Are Like Used Cars](http://33bits.org/2011/03/18/privacy-and-the-market-for-lemons-or-how-websites-are-like-used-cars/)

[5] These measurements were run using the [canvas instrumentation](https://github.com/citp/OpenWPM/blob/master/automation/Extension/firefox/data/content.js#L336-L339) portion of [OpenWPM](https://github.com/citp/OpenWPM).

[6] For a detailed description of cookie respawning, I suggest reading through Ashkan Soltani’s [blog post](http://ashkansoltani.org/2011/08/11/respawn-redux-flash-cookies/) on the subject.

Thanks to [Arvind Narayanan](http://randomwalker.info/) for his helpful comments.

[](http://www.jbonneau.com/ "Visit jbonneau’s website")

## [Provisions: how Bitcoin exchanges can prove their solvency](https://freedom-to-tinker.com/blog/jbonneau/provisions-how-bitcoin-exchanges-can-prove-their-solvency/)

October 26, 2015 by [Joseph Bonneau](https://freedom-to-tinker.com/blog/author/jbonneau/)

Millions of Bitcoin users store their bitcoins with online  _exchanges_ (e.g. [Coinbase](https://www.coinbase.com/), [Kraken](https://www.kraken.com/)) which store bitcoins on their customers’ behalf. They present an interface that looks somewhat like an online bank, allowing users to log in and request payments to other users or withdrawals. For many users this approach makes a lot more sense than the traditional approach of storing private keys on your laptop or phone and interacting with the Bitcoin network directly. Online exchanges require no software installation, enable a familiar password-based authentication model, and can guard against the risk of losing funds with a stolen laptop. Online exchanges can also improve the scalability and efficiency of Bitcoin by settling many logical transactions between users without actually moving funds on the block chain.

Of course, users must trust these exchanges not to get hacked or simply abscond with their money, both of which happened frequently in the early days of Bitcoin (nearly half of exchanges studied in a [2013 research paper](http://fc13.ifca.ai/proc/1-2.pdf) failed). Famously, Mt. Gox was the largest online exchange until 2014 when it lost most of its customers’ funds under murky circumstances.

It has long been a goal of the Bitcoin community for exchanges to be able to cryptographically prove solvency—that is, to prove that they still control enough bitcoins to cover all of their customers’ accounts. Greg Maxwell first proposed an [approach using Merkle trees](https://iwilcox.me.uk/2014/proving-bitcoin-reserves) [in 2013](https://people.xiph.org/~greg/bitcoin-wizards-fraud-proof.log.txt), but this requires revealing (at a minimum) the total value of the exchange’s assets and which addresses the exchange controls. Exchanges have [specifically cited these privacy risks](https://www.kraken.com/security/audit) as a reason they have not deployed proofs of solvency, relying on trusted audit instead.

In [a new paper](http://www.jbonneau.com/doc/DBBCB15-CCS-provisions.pdf) presented this month at [CCS](http://www.sigsac.org/ccs/CCS2015/) (co-authored with Gaby G. Dagher, Benedikt Bünz, Jeremy Clark and Dan Boneh), we present Provisions, the first cryptographic proof-of-solvency with strong privacy guarantees. Our protocol is suitable for Bitcoin but would work for most other cryptocurrencies (e.g. Litecoin, Ethereum). Our protocol hides the total assets and liabilities of the exchange, proving only that assets are strictly greater than liabilities. If desired, the value of this surplus can be proven. Provisions also hides all customer balances and hides which Bitcoin addresses the bank controls within a configurable anonymity set of other addresses on the block chain. The proofs are large, but reasonable to compute on a daily basis (in the tens of GB for a large exchange, computable in about an hour). Best of all, it is very simple and fast for each user to verify that they have been correctly included. We can even extend the protocol to prevent collusion between exchanges. The details are in the paper, the full version of [which is now online](https://eprint.iacr.org/2015/1008.pdf).

While our Provisions protocol removes the privacy concerns of performing a cryptographic proof-of-solvency, there are still some practical deployment questions because the proof requires the exchange to compute using its private keys. Exchanges rightly go to great lengths to protect these keys, often keeping them offline and/or in hardware security modules. Performing a regular solvency proof requires careful thinking about the right internal procedure for accessing these keys.

These deployment questions can be solved. We hope that cryptographic proofs of solvency will soon be expected of upstanding exchanges. Incidents like that of Mt. Gox have greatly damaged public perception of the entire Bitcoin ecosystem. While solvency proofs can’t prevent exchange compromises, they would have made Mt. Gox’s troubles public earlier and more clearly. They would also shore up confidence in today’s exchanges which are (presumably) solvent.

Taking a step back, solvency proofs are yet another example where we can replace an  expensive and trust-laden process in the offline world (financial inspection by a trusted auditor) with a “trustless” cryptographic protocol. It’s always exciting to take a new step in that direction. There remain limits as to what cryptography can do though. Critically, solvency proofs do not create a binding obligation to pay. A malicious exchange could complete a Provisions proof and then immediately abscond with all of the money. For this reason, some form of government regulation of online exchanges makes sense. Though regulation is dreaded by many in the Bitcoin community, it appears to be on the horizon. Bills have been proposed in several states, largely aimed at exchanges. Interestingly, the [model regulatory framework proposed by the Conference of State Bank Supervisors](https://www.csbs.org/regulatory/ep/pages/framework.aspx) in September already mentions cryptographic solvency proofs as a means of demonstrating solvency. We hope this recommendation is enacted in law and solvency proofs are a tool to avoid the cost of the heavyweight auditing requirements traditionally demanded of banks, while simultaneously increasing transparency for exchange customers.

[](https://www.bartongellman.com/ "Visit bgellman’s website")

## [Classified material in the public domain: what’s a university to do?](https://freedom-to-tinker.com/blog/bgellman/classified-material-in-the-public-domain-whats-a-university-to-do/)

October 8, 2015 by [Barton Gellman](https://freedom-to-tinker.com/blog/author/bgellman/)

Yesterday I posted [some thoughts](https://medium.com/@tcfdotorg/scholarship-security-and-spillage-on-campus-15aa8fb8f38) about Purdue University’s decision to destroy a video recording of my [keynote address](http://eventmobi.com/dawnordoom/agenda/90674/605774) at its [Dawn or Doom](https://www.purdue.edu/dawnordoom/) colloquium. The organizers had gone dark, and a promised public link was not forthcoming. After a couple of weeks of hoping to resolve the matter quietly, I did some digging and decided to write up what I learned. I posted on the web site of the [Century Foundation](http://tcf.org/), my main professional home:

> It turns out that Purdue has wiped all copies of my video and slides from university servers, on grounds that I displayed classified documents briefly on screen. A breach report was filed with the university’s Research Information Assurance Officer, also known as the Site Security Officer, under the terms of [Defense Department Operating Manual 5220.22-M](http://www.dss.mil/documents/odaa/nispom2006-5220.pdf). I am told that Purdue briefly considered, among other things, whether to destroy the projector I borrowed, lest contaminants remain.

I was, perhaps, naive, but pretty much all of that came as a real surprise.

> Let’s rewind. Information Assurance? Site Security?
> 
> These are familiar terms elsewhere, but new to me in a university context. I learned that Purdue, like a number of its peers, has a “facility security clearance” to perform classified U.S. government research. The manual of regulations runs to 141 pages. (Its [terms](http://www.purdue.edu/bot/meeting-documents/2014/july/stated/sr.managerial%20group.pdf) forbid uncleared trustees to ask about the work underway on their campus, but that’s a subject for another day.) The pertinent provision here, spelled out at length in a manual called [Classified Information Spillage](https://www.fas.org/sgp/library/cnssp-18.pdf), requires “sanitization, physical removal, or destruction” of classified information discovered on unauthorized media.

Two things happened in rapid sequence around the time I told Purdue about my post.

First, the university broke a week-long silence and expressed a measure of regret:

> **_UPDATE_** _: Just after posting this item I received an email from Julie Rosa, who heads strategic communications for Purdue. She confirmed that Purdue wiped my video after consulting the Defense Security Service, but the university now believes it went too far._
>
>> _“In an overreaction while attempting to comply with regulations, the video was ordered to be deleted instead of just blocking the piece of information in question. Just FYI: The conference organizers were not even aware that any of this had happened until well after the video was already gone.”_
>
>> _“I’m told we are attempting to recover the video, but I have not heard yet whether that is going to be possible. When I find out, I will let you know and we will, of course, provide a copy to you.”_

Then Edward Snowden [tweeted the link](https://twitter.com/bartongellman/status/651861068793409537), and the Century Foundation’s web site melted down. It now redirects to Medium, where you can find the full story.

I have not heard back from Purdue today about recovery of the video. It is not clear to me how recovery is even possible, if Purdue followed Pentagon guidelines for secure destruction. Moreover, although the university seems to suggest it could have posted most of the video, it does not promise to do so now. Most importantly, the best that I can hope for here is that my remarks and slides will be made available in redacted form — with classified images removed, and some of my central points therefore missing. There would be one version of the talk for the few hundred people who were in the room on Sept. 24, and for however many watched the live stream, and another version left as the only record.

For our purposes here, the most notable questions have to do with academic freedom in the context of national security. How did a university come to “sanitize” a public lecture it had solicited, on the subject of NSA surveillance, from an author known to possess the Snowden documents? How could it profess to be _shocked to find that spillage is going on_ at such a talk? The beginning of an answer came, I now see, in the question and answer period after my Purdue remarks. A post-doctoral research engineer stood up to ask whether the documents I had put on display were unclassified. “No,” I replied. “They’re classified still.” Eugene Spafford, a professor of computer science there, later attributed that concern to “junior security rangers” on the faculty and staff. But the display of Top Secret material, he said, “once noted, … is something that cannot be unnoted.”

Someone reported my answer to Purdue’s Research Information Assurance Officer, who reported in turn to Purdue’s representative at the Defense Security Service. By the terms of its Pentagon agreement, Purdue decided it was now obliged to wipe the video of my talk in its entirety. I regard this as a rather devout reading of the rules, which allowed Purdue to “realistically consider the potential harm that may result from compromise of spilled information.” The slides I showed had been viewed already by millions of people [online](https://www.washingtonpost.com/people/barton-gellman). Even so, federal funding might be at stake for Purdue, and the [notoriously vague terms](http://fas.org/irp/congress/2012_hr/071112sales.pdf) of the Espionage Act hung over the decision. For most lawyers, “abundance of caution” would be the default choice. Certainly that kind of thinking is commonplace, and sometimes appropriate, in military and intelligence services.

> But universities are not secret agencies. They cannot lightly wear the shackles of a [National Industrial Security Program](http://www.dss.mil/isp/index.html), as Purdue agreed to do. The values at their core, in principle and often in practice, are open inquiry and expression.
> 
> I do not claim I suffered any great harm when Purdue purged my remarks from its conference proceedings. I do not lack for publishers or public forums. But the next person whose talk is disappeared may have fewer resources.
> 
> More importantly, to my mind, Purdue has compromised its own independence and that of its students and faculty. It set an unhappy precedent, even if the people responsible thought they were merely following routine procedures.

One can criticize the university for its choices, and quite a few have since I published my post. What interests me is how nearly the results were foreordained once Purdue made itself eligible for Top Secret work.

> Think of it as a classic case of mission creep. Purdue invited the secret-keepers of the Defense Security Service into one cloistered corner of campus (“a small but significant fraction” of research in certain fields, as the university counsel [put it](https://www.purdue.edu/bot/meeting-documents/2014/july/stated/sr.managerial%20group.pdf)). The trustees accepted what may have seemed a limited burden, confined to the precincts of classified research.
> 
> Now the security apparatus claims jurisdiction over the campus (“facility”) at large. The university finds itself “sanitizing” a conference that has nothing to do with any government contract.

I am glad to see that Princeton [takes the view](http://www.princeton.edu/dof/policies/publ/fac/rules_toc/chapter8/#comp000045d572a900000003d24af9) that “[s]ecurity regulations and classification of information are at variance with the basic objectives of a University.” It does not permit faculty members to do classified work on campus, which avoids Purdue’s “facility” problem. And even so, at Princeton and elsewhere, there may be an undercurrent of self-censorship and informal restraint against the use of documents derived from unauthorized leaks.

Two of my best students nearly dropped a course I taught a few years back, called “Secrecy, Accountability and the National Security State,” when they learned the syllabus would include documents from Wikileaks. Both had security clearances, for summer jobs, and feared losing them. I told them I would put the documents on Blackboard, so they need not visit the Wikileaks site itself, but the readings were mandatory. Both, to their credit, stayed in the course. They did so against the advice of some of their mentors, including faculty members. The advice was purely practical. The U.S. government will not give a clear answer when asked whether this sort of exposure to published secrets will harm job prospects or future security clearances. Why take the risk?

Every student and scholar must decide for him- or herself, but I think universities should push back harder, and perhaps in concert. There is a treasure trove of primary documents in the archives made available by Snowden and Chelsea Manning. The government may wish otherwise, but that information is irretrievably in the public domain. Should a faculty member ignore the Snowden documents when designing a course on network security architecture? Should a student write a dissertation on modern U.S.-Saudi relations without consulting the numerous diplomatic cables on Wikileaks? To me, those would be abdications of the basic duty to seek out authoritative sources of knowledge, wherever they reside.

I would be interested to learn how others have grappled with these questions. I expect to write about them in my forthcoming book on surveillance, privacy and secrecy.

Filed Under: Uncategorized Tagged With: [Academic Freedom](https://freedom-to-tinker.com/blog/tag/academic-freedom/), [access to information](https://freedom-to-tinker.com/blog/tag/access-to-information/), [censorship](https://freedom-to-tinker.com/blog/tag/censorship/), [chilling effects](https://freedom-to-tinker.com/blog/tag/chilling-effects/), [Edward Snowden](https://freedom-to-tinker.com/blog/tag/edward-snowden/), [free expression](https://freedom-to-tinker.com/blog/tag/free-expression/), [free speech](https://freedom-to-tinker.com/blog/tag/free-speech/), [NSA](https://freedom-to-tinker.com/blog/tag/nsa/), [Privacy](https://freedom-to-tinker.com/blog/tag/privacy/), [Secrecy](https://freedom-to-tinker.com/blog/tag/secrecy/), [Security](https://freedom-to-tinker.com/blog/tag/security/)

## [Ancestry.com can use your DNA to target ads](https://freedom-to-tinker.com/blog/paulellenbogen/ancestry-com-can-use-your-dna-to-target-ads/)

September 7, 2015 by [Paul Ellenbogen](https://freedom-to-tinker.com/blog/author/paulellenbogen/)

With the reduction in costs of genotyping technology, [genetic genealogy](https://en.wikipedia.org/wiki/Genetic_genealogy) has become accessible to more people. Various websites such as Ancestry.com offer genetic genealogy services. Users of these services are mailed an envelope with a DNA collection kit, in which users deposit their saliva. The users then mail their kits back to the service and their samples are processed. The genealogy company will try to match the user’s DNA against other users in its genealogy and genetic database. As these services become more popular, we need more public discourse about the implications of releasing our genetic information to commercial enterprises.

Given that genetic information can be very sensitive, I found that the [privacy policy](https://web.archive.org/web/20150812163728/https://dna.ancestry.com/legal/privacyStatement) of Ancestry’s DNA services has some surprising disclosures about how they could use your genetic information.

Here are some excerpts with the worrying parts in bold:

> Subject to the restrictions described in this Privacy Statement and applicable law, we may use personal information for any reasonable purpose related to the business, including to communicate with you, to provide you information about Ancestry’s and AncestryDNA’s products and services, to respond to your requests, to update our product offerings, to improve the content and User experience on the AncestryDNA Website, **to help you and others discover more about your family, to let you know about offers of interest from AncestryDNA or Ancestry, and to prepare and perform demographic, benchmarking, advertising, marketing, and promotional studies.**
> 
> …
> 
> **To distribute advertisements: AncestryDNA strives to show relevant advertisements. To that end, AncestryDNA may use the information you provide to us** , as well as any analyses we perform, aggregated demographic information (such as women between the ages of 45-60), anonymized data compared to data from third parties, or the placement of cookies and other tracking technologies… In these ways, **AncestryDNA can display relevant ads on the AncestryDNA Website, third party websites, or elsewhere.**

The privacy policy gives Ancestry permission to use its users’ genetic information for advertising purposes. When I inquired with Ancestry, they pointed to the following part of their privacy policy:

> We do not provide advertisers with access to individual account information. AncestryDNA does not sell, rent or otherwise distribute the personal information you provide us to these advertisers unless you have given us your consent to do so.

However, it is not clear how your personal information can be used to display “relevant ads” unless either Ancestry operates as an ad network itself or Ancestry communicates some personal information to third party advertisers in order to target the ads. Below, I expand on concerns raised by this privacy policy:

**Users may “consent” to the use of their genetic data unknowingly.** The privacy policy says Ancestry can distribute users’ private information if Ancestry gets permission first. That permission could be granted by a dialog that users click through without much thought. [Research has shown](http://dl.ifip.org/db/conf/interact/interact2011-4/Bravo-LilloCDKS11.pdf) that users are already desensitized to privacy and security warnings.

**Even if only Ancestry is using the personal information to target ads, the data might accidentally find its way to third parties.** Researchers have demonstrated how it can be difficult to avoid information leakage through [URLs or cookies](http://www2.research.att.com/~bala/papers/wosn09.pdf) or [more sophisticated attacks](http://repository.cmu.edu/cgi/viewcontent.cgi?article=1066&context=jpc). If Ancestry categorizes its users according to their genetic traits and then stores and transfers these categories in cookies and URL parameters (a common practice for the analogous “behavioral segment” categories used for many targeted ads), then the genetic data can easily leak to third parties.

**The genetic data collected by these services may endanger the privacy of users and their families.** A genome is not something easily made [unlinkable](https://freedom-to-tinker.com/blog/felten/are-genomes-anonymous-data/). Only [33 bits of entropy](http://blogs.wsj.com/digits/2010/08/04/the-information-that-is-needed-to-identify-you-33-bits/) are necessary to uniquely identify a person. The DNA profiles used by law enforcement in the US today take samples from 13 location on the genome, and have about [54 bits of entropy](http://33bits.org/2009/12/02/the-entropy-of-a-dna-profile/). The test that Ancestry uses samples [700,000 locations](https://web.archive.org/web/20150827183757/https://dna.ancestry.com/legal/faq#about-3) on the genome, which will likely have much more than 33 bits of entropy. In fact, I believe this is enough entropy to compromise not only an individual’s privacy, but also the privacy of family members. With the 13 CODIS locations, law enforcement can already do [familial searches](https://en.wikipedia.org/wiki/DNA_profiling#Familial_DNA_searching) for close family members. I hope to touch on the familial aspects of DNA privacy at a later date. The compromise of familial privacy is in part what makes collecting and distributing DNA even more sensitive that just collecting an individual’s full name or address.

**Genetic data can be used to discriminate against people on the basis of characteristics they cannot control.** More than identity, DNA data may allow someone to infer [behavior](https://en.wikipedia.org/wiki/Behavioural_genetics) and health attributes. Major concerns about the impact of genetic information on employment and health insurance led Congress to pass the [Genetic Information Nondiscrimination Act](https://en.wikipedia.org/wiki/Genetic_Information_Nondiscrimination_Act), which makes it illegal to use genetics to decide hiring or health insurance pricing. However, GINA may not effectively deter people who 1) are not employers or insurers (e.g., landlords discriminating in their choice of tenants, which is prohibited by California state law but not by the federal provisions in GINA); 2) do not believe they will be caught; or 3) are not aware that they are discriminating, as discussed next.

**Unintentional discrimination may occur.** The [big data report](https://www.whitehouse.gov/sites/default/files/docs/big_data_privacy_report_may_1_2014.pdf) from the White House warns that the “increasing use of algorithms to make eligibility decisions must be carefully monitored for potential discriminatory outcomes for disadvantaged groups, even absent discriminatory intent.” An algorithm that takes genetic information as an input likely will lead to results that differ based on genes. This outcome already discriminates on the basis of genetics, and because genes are correlated with other sensitive attributes, it can also discriminate on the basis of characteristics such as race or health status. The discrimination occurs whether or not the algorithm’s user intended it.

[](http://randomwalker.info/ "Visit randomwalker’s website")

## [What should we do about re-identification? A precautionary approach to big data privacy](https://freedom-to-tinker.com/blog/randomwalker/what-should-we-do-about-re-identification-a-precautionary-approach-to-big-data-privacy/)

March 19, 2015 by [Arvind Narayanan](https://freedom-to-tinker.com/blog/author/randomwalker/)

Computer science research on re-identification has repeatedly demonstrated that sensitive information can be inferred even from de-identified data in a wide variety of domains. This has posed a vexing problem for practitioners and policy makers. If the absence of “personally identifying information” cannot be relied on for privacy protection, what are the alternatives? Joanna Huey, Ed Felten, and I tackle this question in a new paper “[A Precautionary Approach to Big Data Privacy](http://randomwalker.info/publications/precautionary.pdf)”. Joanna presented the paper at the [Computers, Privacy & Data Protection](http://www.cpdpconferences.org/) conference earlier this year.

[[Read more…]](https://freedom-to-tinker.com/blog/randomwalker/what-should-we-do-about-re-identification-a-precautionary-approach-to-big-data-privacy/)

[](http://www.princeton.edu/~aylinc/ "Visit aylin’s website")

## [We can de-anonymize programmers from coding style. What are the implications?](https://freedom-to-tinker.com/blog/aylin/we-can-de-anonymize-programmers-from-coding-style-what-are-the-implications/)

February 26, 2015 by [aylin](https://freedom-to-tinker.com/blog/author/aylin/)

In a [recent post](https://freedom-to-tinker.com/blog/aylin/anonymous-programmers-can-be-identified-by-analyzing-coding-style/ "Anonymous programmers can be identified by analyzing coding style"), I talked about our [paper](https://www.cs.drexel.edu/~ac993/papers/caliskan_deanonymizing.pdf "De-anonymizing Programmers via Code Stylometry") showing how to identify anonymous programmers from their coding styles. We used a combination of lexical features (e.g., variable name choices), layout features (e.g., spacing), and syntactic features (i.e., grammatical structure of source code) to represent programmers’ coding styles. The previous post focused on the overall results and techniques we used. Today I’ll talk about applications and explain how source code authorship attribution can be used in software forensics, plagiarism detection, copyright or copyleft investigations, and other domains.

[[Read more…]](https://freedom-to-tinker.com/blog/aylin/we-can-de-anonymize-programmers-from-coding-style-what-are-the-implications/)
