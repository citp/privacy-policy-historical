> *The following text is extracted and transformed from the pi-hole.net privacy policy that was archived on 2018-12-14. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20181214192045id_/https%3A//pi-hole.net/privacy) for the most accurate reproduction.*

# Privacy – Pi-hole®: A black hole for Internet advertisements

This page will provide specific examples of what information we can see from our end and how it may affect you.  Only Pi-hole administrators can see this information and it is not shared outside of our team.

This is our main Webpage and is mostly used as a place for us to publish blog posts (which are replicated to discourse.pi-hole.net) as well as other important pages.

Our Webpage is powered by WordPress and Jetpack.  Through Jetpack’s dashboard, we are able to see how many unique visitors are visiting our site,

referral information, top viewed pages, and outbound clicks.

This information is limited to content only on the base pi-hole.net Webpage(s).

## How We Use WordPress/Jetpack’s Information

We use it for capacity planning and to see if certain posts we do are worthwhile, such as the iterations of [_What really happens on your network?_](https://pi-hole.net/2017/02/22/what-really-happens-on-your-network-find-out-with-pi-hole/)

If you want to block any of this information using your Pi-hole, just blacklist pixel.wp.com and stats.wp.com (these are often already part of the default lists Pi-hole ships with).

[Discourse is the open source software](https://www.discourse.org/) that powers our user forums.  We’re able to see the statistics Discourse has built in.  We can see your email address (the _Show_ button must be clicked in order to see it) and your IP address;

activity about your account;

top searches (cumulative of all users);

and several other general statistics (some of which are [available publicly](https://discourse.pi-hole.net/about)).

You can learn more about Discourse and their [software here](https://github.com/discourse/discourse).

## How We Use Discourse’s Information

We use it to learn what pages people view in order to see common problems and issues people run into and if they warrant the creation of an FAQs.

You can see [everything our Content Delivery Network offers](https://bunnycdn.com/features).  They offer some basic statistics.

## How We Use BunnyCDN’s Information

We use it for capacity planning and deciding where we may need to position our servers or load balancers for the best performance.

Until we’re able to host our own DNS, we need to rely on third parties; we currently use [DNSMadeEasy](https://cp.dnsmadeeasy.com/u/133706), which offers numerical stats.

## How We Use DNSMadeEasy’s Information

Capacity planning.

Twitter has built-in analytics.

## How We Use Twitter’s Information

General interest.

GitHub offers some built in stats, such as unique clones.  Since our installer clones our repo, we have a general idea of how many installs might be out there, but it’s likely more than we might know considering we [accidentally DDoSed GitHub](https://pi-hole.net/2018/01/02/that-time-we-ddosed-github/).

## How We Use GitHub’s Information

After [a recent blunder](https://pi-hole.net/2018/01/02/that-time-we-ddosed-github/), we consider these values when we code our software.
