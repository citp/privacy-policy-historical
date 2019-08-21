> *The following text is extracted and transformed from the mullvad.net privacy policy that was archived on 2019-08-21. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20190821124511id_/https%3A//mullvad.net/en/guides/no-logging-data-policy) for the most accurate reproduction.*

# No-logging of user activity policy - Guides | Mullvad VPN

  


We do not keep activity logs of any kind. Learn more about what this means and why we choose to operate this way.

## What this policy covers

  * Policy overview
  * Our anonymous, numbered accounts
  * How we handle payment information
  * Information that we do not log
  * Other data that we do handle
  * How we handle emails and problem reports



### All of our policies regarding data and its storage

  * [No logging of user activity policy](https://mullvad.net/guides/no-logging-data-policy/)
  * [Cookie policy](http://mullvad.net/guides/cookie-policy)
  * [Privacy policy](http://mullvad.net/guides/privacy-policy) (including GDPR)
  * [Swedish legislation relevant to us as a VPN provider](https://www.mullvad.net/guides/swedish-legislation/)
  * [Terms of service](https://mullvad.net/guides/terms-service/)



## Policy overview

The underlying policy of Mullvad is that we never store any activity logs of any kind. We strongly believe in having a minimal data retention policy because we want you to remain anonymous.

However, in some situations we might process your personal data if you, for example, are making payments by a bank wire, PayPal, Swish, Stripe or are sending an e-mail or reporting a problem. In those cases, we might process your personal data and the General Data Protection Regulation (“GDPR”) and other data protection laws may apply. For more information please [read our Privacy Policy](https://mullvad.net/guides/privacy-policy).




## Our anonymous, numbered accounts

We want you to remain anonymous. When you sign up for Mullvad, we do not ask for any personal information – no username, no password, no email address. Instead, a random account number is generated, a so-called numbered account. This number is the only identifier a person needs in order to use a Mullvad account. This is a fundamental difference that sets us apart from most other services.

Anyone at anytime can create as many numbered accounts as they wish on our website. An account can be used by multiple people or by someone other than the person who initially generated it.

A Mullvad account has two properties: the account number and the time remaining on that account.

**Question:** How many numbered accounts does Mullvad have?  
**Answer:** At the time of writing this post, Mullvad has 555,541 numbered accounts. These accounts could have been created by 555,541 unique people, or by one person 555,541 times.

Data that we store for an account¹
    
    
    account number | expiry date
    xxxxxxxxxxx    | 20170730
    

Data stored for WireGuard configuration (if used)
    
    
    account number | pubkey    | tunnel address
    xxxxxxxxxxxx   | xxxxxxxx  | x

Data stored for port-forward configuration (if used)
    
    
    account number | port | wg_peer
    xxxxxxxxxxxx   | x    | x

## How Mullvad handles payment information

Let's take a transparent look at the information we do store in order to handle payments.

You can pay money to the numbered account and therefore acquire more VPN time. Mullvad accepts cash, Bitcoin, Bitcoin Cash, bank wire, credit card, PayPal, and Swish. You can find more information on how we handle each type of payment below.

Some types of payment mean that personal data will be processed (such as e.g. bank account number and PayPal-ID). If you choose a payment method where you are providing your personal data to Mullvad, such as PayPal, we will process and protect your information according to the GDPR and other applicable legislations. For more information please read our [Privacy policy](http://mullvad.net/guides/privacy-policy/).

### Cash

Put the money in an envelope together with the account number in question and send it to us. We will open the envelope, add time to the account (corresponding to the amount of cash sent), and then use a shredder to destroy the envelope and its non-money contents.

We have no way of knowing who made the payment and who the account belongs to. Even if a person were to address the envelope, there is still no way to prove that he or she generated the account or is even using it. Please avoid writing your name or address on the envelope.

The GDPR does not apply in this case since the personal data on the envelope does not form a part of a filing system and are not intended to form part of a filing system.

This is what we store when a cash payment comes in¹:
    
    
    payment | account number | amount | currency | timestamp
    xxxxxx  | xxxxxxxxxxxx   | 5.0    | USD      | 2016-12-09 10:38:23
    

### Bitcoin and Bitcoin Cash

This is digital cash, so the process is the same as with physical cash but without humans or any third parties involved. We run our own full node in the blockchains (one for each of the cryptocurrencies) and we verify incoming payments ourselves. Again, we don't use third parties for any step in the bitcoin or bitcoin cash payment process, from the generation of QR codes to adding time to accounts.

We store these payment details for bitcoin and bitcoin cash¹:
    
    
    payment | account number | amount  | currency | timestamp           | bitcoin address 
    xxxxxx  | xxxxxxxxxxxx   | 0.00564 | BTC      | 2016-12-10 06:36:12 | xxxxxxxxxx
    

### Credit card, PayPal, Swish, and bank wire

For credit card, PayPal, Swish, and bank wire, we do use third parties: Stripe, PayPal, and our bank SEB (which handles both Swish and bank wire). These kinds of companies log everything. For that reason alone, it is out of our control that they have records showing which people have paid us money (i.e. processing of personal data).

As a customer of their services, these entities would allow us to request this information if we chose to do so. In short, your payment actions with these two methods are not anonymous and the GDPR and other relevant data protection regulations may apply if you are making a payment by credit card, PayPal, Swish or by bank wire.

The data must be kept for the statutory retention period described in  applicable local laws such as the Swedish Accounting Act (some information must be stored for seven years from the end of the fiscal year). If not required by law, the data will be stored for no longer than necessary for the purpose. After the periods, the data will be permanently deleted.

Here's the information we store for bank wires¹:
    
    
    payment | account number | amount | currency | timestamp           | transaction_id*
    xxxxxx  | xxxxxxxxxxxx   | 30     | EUR      | 2016-12-09 00:01:06 | xxxxxxxxx
    

`*transacion_id is automatically deleted 45 days after that payment expired `

Here's the information we store for credit card payments via Stripe¹:
    
    
    payment | account number | amount | currency | timestamp*          | stripe_charge_id*
    xxxxxx  | xxxxxxxxxxxx   | 10     | EUR      | 2016-12-15 20:42:26 | xxxxxxxxx
    

`*stripe_charge_id is automatically deleted 45 days after that payment expired and the time part (hh:mm:ss) of timestamp is deleted`

Here's the information we store for Swish¹:
    
    
    payment | account number | amount | currency | timestamp           | swich_request_id
    xxxxxx  | xxxxxxxxxxxx   | 50     | SEK      | 2016-12-15 20:42:26 | xxxxxxxxx
    

The value under stripe_charge_id is a unique token that, in the Stripe payment system, can be linked to your credit card and this unique payment.

Here's the information we store for PayPal transactions¹:
    
    
    payment | account number | amount | currency | timestamp*          | transaction_id* | e-mail*
    xxxxxx  | xxxxxxx        | 15     | EUR      | 2016-12-10 06:40:00 | xxxxxxxxxxxxx   | name@emailacct.com 

`*transaction_id and e-mail are automatically deleted 45 days after that payment expired and the time part (hh:mm:ss) of timestamp is deleted `  
 

**Question:** Why do you store transaction_id and e-mail?  
**Answer:** Since we support 30-day refunds and because we encounter certain transaction issues from PayPal (for example, double payments and subscription problems), we need to be able to track payments in order to give customers the service we offer. We only duplicate the information since PayPal already has it.

It's important to note that PayPal does not have your Mullvad account number since we encrypt it. If, however, you send a bank wire payment, the account number will exist in the "message" field of the transaction.

### Activation codes

Here's the information we store for activation codes¹:
    
    
    payment | account number | amount | timestamp           | voucher_id | activation_code
    xxxxxx  | xxxxxxxxxxxx   | 30     | 2016-12-09 00:01:06 | xxxxxx     | xxxxxxxxxxx
    

### Partner accounts

For accounts created by partners, we don't store payment information.  
Instead we store information on when time was added to or refunded from an account:
    
    
    event id | time added/removed | account number | timestamp          
    xxxxxx   | 1234               | xxxxxxxxxxxx   | 2016-12-09 00:01:06
    

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

## Other data that we do handle

Our servers send two types of data to our monitoring system:

  * aggregated application data, such as total number of current vpn connections
  * generic system metrics, such as CPU load per core and total bandwidth used by the server.



We log the total sum of each of these statistics in order to monitor the health of each individual VPN server. We ensure that the system isn't overloaded, and we monitor the servers for potential attacks, bugs, and network issues.

We also monitor the real-time state of total connections per account as we only allow for five connections simultaneously. As we do not save this information, we cannot, for example, tell you how many connections your account had five minutes ago.

With regard to our web servers, we handle certain types of information in the following ways:

  * We store Nginx access logs for up to 5 minutes in the following format (which does not contain IPs): $server_name [$time_local] $request $status
  * Information older than 5 minutes is deleted, and only aggregated information about the number of requests and their response codes is saved.
  * We refrain from sending usage statistics to external parties such as Google Analytics.
  * Our website utilizes a minimum amount of cookies. Please read [our cookie policy](http://mullvad.net/guides/cookie-policy) for more information.



## How we handle emails and problem reports

Our support staff answers questions, resolves problems, and gives general support to customers who actively send an email to support@mullvad.net or submit a problem report via our app/client.

Please consider the following statements about how we handle support-related communication should you ever need to contact us.

  1. If privacy is of utmost concern, we recommend that you refrain from communicating any personal data to us since plain-text email is not a safe media for communication. If necessary, [use PGP-encrypted email](https://mullvad.net/sv/guides/using-encrypted-email/).
  2. After "solving" or "closing" a support case, all related emails are archived (removed from the inbox).
  3. After 6 months, all emails sent to our support address are automatically, permanently erased (from inbox, deleted items, sent items, trash, and archives).
  4. We do use a third party to operate our email service, so we remind you to carefully read #1 again.
  5. No private information  not even your email address  will ever actively be passed to third parties (except the third party which operates our email service on behalf of us), unless you explicitly ask us to.
  6. Please note that an e-mail address is generally considered as personal data and even the information in the e-mail message may include personal data.



## Notes

¹The table's format and header names have been simplified for the purpose of making the principles mentioned in this post easy to understand.
