> *The following text is extracted and transformed from the mageia.org privacy policy that was archived on 2016-05-12. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20160512102019id_/http%3A//www.mageia.org/en/about/policies/privacy) for the most accurate reproduction.*

# Privacy policy - Mageia wiki

### From Mageia wiki

[](https://web.archive.org/en/File:Notepad.png)

**Please note!**  
This privacy policy has not been written by lawyers and is subject to enhancement. Please open a bug report on bugs.mageia.org if you notice issues or think that some parts should be improved.

There are 3 different domains: 

  1. the **Mageia operating system** , that you may install and use on your own computing devices; 
  2. the **mageia.org web sites** as an unauthenticated visitor; 
  3. the **mageia.org web sites and tools** , as a registered user and a contributor. 



In case of question regarding this policy, please contact the Council or Board via contact AT mageia DOT org. 

In case of emergency regarding something related to this policy or user or systems behavior, please mail contact AT mageia DOT org. 

These policy are still/always in the making, so we can improve over time. 

During this process, we start to disclose what we do, what we would like to do, what principles we would like to follow, and study what other projects do. 

No private data is collected by Mageia.Org via your using of the Mageia operating system. For specific applications by third parties, you need to refer to their own privacy policies. 

##  Web sites and services access logs 

Most (if not all) **web services keep access logs** , that include: IP address, browser user-agent (and potentially any request header your user agent send to our servers). These logs are kept at least for one full year (see French law requirements below). They might be used by sysadmins to debug issues with services (e.g. if a given user can't connect to a service due to unwanted blacklisting). 

You can check <https://bugs.mageia.org/buglist.cgi?keywords=logs> for related bugs/requests/etc. 

##  Web sites analytics 

No collection of user data is made for web sites analytics currently. If you notice any mageia.org service that seems to collect data and is not described in this privacy policy, please notify the Board at contact AT mageia DOT org or open a bug report on bugs.mageia.org so that we can investigate it, as it would likely be a mistake. 

We use a LDAP directory to store all registered users/contributors (username, public name, email, hashed password, SSH public key if provided) for: association members management, community members management, non-commercial email notification, authentication across Mageia apps and services. This data is registered, updated and accessed through <https://identity.mageia.org/>. 

Part of this data is transferred to/by other services, on the person's request, mostly for authentication: wiki.mageia.org, forums.mageia.org, blog.mageia.org, bugs.mageia.org, svn.mageia.org, git.mageia.org, ml.mageia.org. 

Your location is inferred from your IP address and used by our download scripts (using MaxMind geoip lite database) to redirect you to a "best matching" mirror. 

##  User contributed content 

Mageia is a collaborative, public project, and all contributions (be it code, documentation, media, designs or discussions - in forums, wikis, bug trackers, code repositories, mailing-lists, IRC channels, etc.) are recorded, stored and made publicly available for further review. Unless specified otherwise, code contributions are under the GPL license and media contributions are under the Creative Commons Attribution - Share Alike 3.0 license. 

##  Projects 

  * a **dashboard** may gather and cross some of this data to build: group/team pages, user pages, and on each, link to related docs through mageia.org resources (all packages/bugs relative to someone, or a team/group for instance) (see <https://bugs.mageia.org/show_bug.cgi?id=1045>) 
  * a **contributors' map** may publish users location (opt-in only) (see <https://bugs.mageia.org/show_bug.cgi?id=998>) 
  * a service to aggregate logs (web, mirrors, bugzilla, buildsystem, code repositories) and provide the possibility to visualize/extract useful patterns/info from it 



Mageia servers are hosted in Marseille, France and under French legislation. 

##  Data retention 

  * <http://www.legifrance.gouv.fr/affichTexte.do?cidTexte=JORFTEXT000023646013>
  * [http://www.legifrance.gouv.fr/affichTexteArticle.do?cidTexte=JORFTEXT000000801164&idArticle=LEGIARTI000006421546](http://www.legifrance.gouv.fr/affichTexteArticle.do?cidTexte=JORFTEXT000000801164&idArticle=LEGIARTI000006421546)



By this, we have to keep identifying log data for one year for all contribution activities (that is, when you create, modify or delete content). 

  * if you are only a Mageia user, you're not affected by this; 
  * if you are only a visitor of our Web services, that only includes your IP address and browser HTTP request headers; 
  * if you have a Mageia user or contributor account, that includes your IP address, browser HTTP headers, uid, nicknames, email addresses, phone numbers, real name if you provided those, the contents/modifications you post, times of access and password hash (whatever useless this can be) - this does not include your public key. 



This applies to (OK/TODO): 

  * [http://www.mageia.org](http://www.mageia.org/) : OK; contents get published through svn.mageia.org (see below); it dynamically includes feeds of information fetched from other sites; 
  * [http://blog.mageia.org](http://blog.mageia.org/): OK; contents are published through WordPress instances; 
  * svn.mageia.org: OK; commits are not anonymous, commit rights are given through LDAP 
  * git.mageia.org: OK; commits are not anonymous, commit rights are given through LDAP 
  * [https://bugs.mageia.org](https://bugs.mageia.org/): OK; contents are published through a Bugzilla instance; users need to authenticate through LDAP to post there 
  * [https://wiki.mageia.org](https://wiki.mageia.org/): OK; contents are published through a Mediawiki instance; users need to authenticate through LDAP to post there 
  * [https://forum.mageia.org](https://forum.mageia.org/) TODO 
  * else? 



##  Potential use of that data 

This data may be transferred to judicial authorities for investigation, if appropriately scoped and asked. Any such query, if it ever occurs, will of course be publicly [notified in our Bugzilla with keyword "data-request"](https://bugs.mageia.org/buglist.cgi?keywords=data-request). 
