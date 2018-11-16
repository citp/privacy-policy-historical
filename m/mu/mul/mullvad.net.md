> *The following text is extracted and transformed from the mullvad.net privacy policy that was archived on 2018-11-16. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20181116102520id_/https%3A//mullvad.net/en/guides/no-logging-data-policy) for the most accurate reproduction.*

# Privacy policy - Guides | Mullvad VPN

At Mullvad, we do not store activity logs of any kind. We strongly believe in having a minimal data retention policy because we want you to remain anonymous.

In this policy, we give you an overview of what we mean by "activity logs," why we actively refrain from storing any user's activity, and the data we do handle to monitor our system.  
 

## Contents below

  * Our anonymous, numbered accounts
  * How we handle payment information
  * Information that we do not log
  * Data that we do handle
  * Cookies used on our site
  * How we handle emails and problem reports
  * Your right to a registry extract
  * Your right to be forgotten  
 



## Our anonymous, numbered accounts

We want you to remain anonymous. When you sign up for Mullvad, we do not ask for any personal information – no username, no password, no email address. Instead, a random account number is generated, a so-called numbered account. This number is the only identifier a person needs in order to use a Mullvad account. This is a fundamental difference that sets us apart from most other services.

Anyone at anytime can create as many numbered accounts as they wish on our website. An account can be used by multiple people or by someone other than the person who initially generated it.

A Mullvad account has two properties: the account number and the time remaining on that account. When an account is created, it comes loaded with three hours to try Mullvad for free. At once the countdown starts. After those three hours have passed, the account has no time left. Using it to connect to Mullvad is no longer possible unless it is loaded with more time.

**Question:**  How many numbered accounts does Mullvad have?  
**Answer:**  At the time of writing this post, Mullvad has 555,541 numbered accounts. These accounts could have been created by 555,541 unique people, or by one person 555,541 times.

This is the data we store for an account¹:
    
    
    account number | expiry date
    xxxxxxxxxxx    | 20170730
    
    
    

## How Mullvad handles payment information

Let's take a transparent look at the information we do store in order to handle payments.

You can pay money to the numbered account and therefore acquire more VPN time. Mullvad accepts cash, Bitcoin, Bitcoin Cash, bank wire, credit card, PayPal, and Swish. Here's how we handle each type of payment.

### Cash

Put the money in an envelope together with the account number in question and send it to us. We will open the envelope, add time to the account (corresponding to the amount of cash sent), and then use a shredder to destroy the envelope and its non-money contents. We have no way of knowing who made the payment and who the account belongs to. Even if a person were to address the envelope, there is still no way to prove that he or she generated the account or is even using it.

This is what we store when a cash payment comes in¹:
    
    
    payment | account number | amount | currency | timestamp
    xxxxxx  | xxxxxxxxxxxx   | 5.0    | USD      | 2016-12-09 10:38:23
    

###   
Bitcoin and Bitcoin Cash

This is digital cash, so the process is the same as with physical cash but without humans or any third parties involved. We run our own full node in the blockchains (one for each of the cryptocurrencies) and we verify incoming payments ourselves. Again, we don't use third parties for any step in the bitcoin or bitcoin cash payment process, from the generation of QR codes to adding time to accounts.

We store these payment details for bitcoin and bitcoin cash¹:
    
    
    payment | account number | amount  | currency | timestamp           | bitcoin address 
    xxxxxx  | xxxxxxxxxxxx   | 0.00564 | BTC      | 2016-12-10 06:36:12 | xxxxxxxxxx
    

###   
Credit card, PayPal, Swish, and bank wire

For credit card, PayPal, Swish, and bank wire, we do use third parties: Stripe, PayPal, and our bank SEB (which handles both Swish and bank wire). These kinds of companies log everything. For that reason alone, it is out of our control that they have records showing which people have paid us money. They store this data for many years.

As a customer of their services, these entities would allow us to request this information if we chose to do so. In short, your payment actions with these two methods are not anonymous, and there is nothing we can do about it.

Here's the information we store for bank wires¹:
    
    
    payment | account number | amount | currency | timestamp
    xxxxxx  | xxxxxxxxxxxx   | 30     | EUR      | 2016-12-09 00:01:06
    

Here's the information we store for credit card payments via Stripe¹:
    
    
    payment | account number | amount | currency | timestamp           | stripe_charge_id
    xxxxxx  | xxxxxxxxxxxx   | 10     | EUR      | 2016-12-15 20:42:26 | xxxxxxxxx

Here's the information we store for swish¹:
    
    
    payment | account number | amount | currency | timestamp           | swich_request_id
    xxxxxx  | xxxxxxxxxxxx   | 50     | SEK      | 2016-12-15 20:42:26 | xxxxxxxxx

The value under stripe_charge_id is a unique token that, in the Stripe payment system, can be linked to your credit card and this unique payment.

Here's the information we store for PayPal transactions¹:
    
    
    payment | account number | amount | currency | timestamp           | transaction_id* | e-mail*
    xxxxxx  | xxxxxxx        | 15     | EUR      | 2016-12-10 06:40:00 | xxxxxxxxxxxxx   | name@emailacct.com 
    

*transaction_id and e-mail are automatically deleted after 6 months.

  
**Question:**  Why do you store transaction_id and e-mail?  
**Answer:**   Since we support 30-day refunds and because we encounter certain transaction issues from PayPal (for example, double payments and subscription problems), we need to be able to track payments in order to give customers the service we offer. We only duplicate the information since PayPal already has it.

It's important to note that PayPal does not have your Mullvad account number since we encrypt it. If, however, you send a bank wire or Swish payment, the account number will exist in the "message" field of the transaction.

###   
Activation codes

Here's the information we store for activation codes¹:
    
    
    payment | account number | amount | timestamp           | voucher_id | activation_code
    xxxxxx  | xxxxxxxxxxxx   | 30     | 2016-12-09 00:01:06 | xxxxxx     | xxxxxxxxxxx

## What we don't log

We log nothing whatsoever that can be connected to a numbered account's activity:

  * no logging of traffic
  * no logging of DNS requests
  * no logging of connections, including when one is made, when it disconnects, for how long, or any kind of timestamp
  * no logging of IP addresses
  * no logging of user bandwidth
  * no logging of account activity except total simultaneous connections (explained below) and the payment information detailed in this post.



Our OpenVPN server log configuration:
    
    
    verb 0
    log-append /dev/null
    

  
**Question:** How can you limit the maximum number of simultaneous connections if you're not logging that information?  
**Answer:** Each VPN server reports to a central service. When a customer connects to a VPN server, the server asks the central service to validate the account number, whether or not the account has any remaining time, if the account has reached its allowed number of connections, and so on. Everything is performed in temporary memory only; none of this information is permanently stored to disk.

##   
Data that we do handle

Our VPN servers send three types of data to our monitoring system:

  * total number of current connections
  * CPU load per core
  * total bandwidth used per server.



We log the total sum of each of these statistics in order to monitor the health of each individual VPN server. We ensure that the system isn't overloaded, and we monitor the servers for potential attacks, bugs, and network issues.

We also monitor the real-time state of total connections per account as we only allow for five connections simultaneously. As we do not save this information, we cannot, for example, tell you how many connections your account had five minutes ago.

With regard to our web servers, we handle certain types of information in the following ways:

  * We store normal Nginx logs for up to 1 hour.
  * Information older than 1 hour is deleted, and only aggregated information about the number of hits and visitors to our website is saved.
  * We refrain from sending usage statistics to external parties such as Google Analytics.
  * Our website utilizes a minimum amount of cookies, which we go into detail about below.  
 



## Cookies

At Mullvad, we never store data that isn't absolutely necessary, and if it is, then only upon the active request of a customer. This choice is deeply rooted in our culture and tied to our belief that everyone has a right to privacy.

As a result, our website utilizes only the following few cookies, all of which are essential for us to provide certain services and created only if a user actively chooses that service:

  * **sessionid** (expires after one hour) – is created when you log into an account and automatically logs you out after an hour
  * **language** (expires when the browser window is closed) – is created when you choose a language preference for this website
  * **csrftoken** (expires when the browser window is closed) – is created when you view almost any form on this website and prevents a malicious website from tricking you into submitting a POST request to us, otherwise known as cross-site request forgery
  * **__stripe_sid** (expires after 30 minutes) – is implemented by Stripe and created when you proceed to the Stripe payment page
  * **__stripe_mid** (expires after one year) – is implemented by Stripe and created when you proceed to the Stripe payment page.  
 



## How we handle emails and problem reports

Our support staff answers questions, resolves problems, and gives general support to customers who actively send an email to support@mullvad.net or submit a problem report via our app/client.

Please consider the following statements about how we handle support-related communication should you ever need to contact us.

  1. If privacy is of utmost concern, we recommend that you refrain from communicating any personal data to us since plain-text email is not a safe media for communication. If necessary, [use PGP-encrypted email](https://mullvad.net/sv/guides/using-encrypted-email/).
  2. After "solving" or "closing" a support case, all related emails are archived (removed from the inbox).
  3. After 6 months, all emails sent to our support address are automatically, permanently erased (from inbox, deleted items, sent items, trash, and archives).
  4. We do use a third party to operate our email service, so we remind you to carefully read #1 again.
  5. No private information – not even your email address – will ever actively be passed to third parties, unless you explicitly ask us to.  
 



## Your right to a registry extract

You have the right to obtain a listing of your actively provided information, if any, that we have stored. If you would like to exercise this right, please contact [support@mullvad.net](mailto:support@mullvad.net) for more information.  
 

## Your right to be forgotten

Mullvad automatically deletes all user-provided information – such as the email address provided during PayPal payments – after six months. But you have the right to be forgotten sooner.

In this case, please contact [support@mullvad.net](mailto:support@mullvad.net) for more information. Please note that exercising this right will limit our ability to provide support that requires such information, such as as issuing a refund or finding a lost account.  
 

## Notes

¹The table's format and header names have been simplified for the purpose of making the principles mentioned in this post easy to understand.
