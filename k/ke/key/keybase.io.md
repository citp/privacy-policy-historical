> *The following text is extracted and transformed from the keybase.io privacy policy that was archived on 2019-12-31. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20191231002527id_/https%3A//keybase.io/docs/privacypolicy) for the most accurate reproduction.*

# Privacypolicy | Keybase Docs

## Keybase – Privacy Policy

Effective: January 9, 2020 (Posted December 9, 2019). See also: [previous version](https://web.archive.org/web/20191231002527id_/https%3A//keybase.io/docs/privacypolicy-old)

At Keybase, our mission is to help you protect your privacy and your data. This privacy policy explains how we process your personal information in service of that mission.

### Summary

We hope you will read this entire privacy policy. However, if you’re in a hurry, here are the key points:

  * Keybase won’t sell or rent your data or content for any reason.
  * By design, Keybase can’t access, sell, transmit, or use your encrypted content.
  * We use a public blockchain to protect our users from [misbehaving servers](https://keybase.io/docs/sigchain#footnote-1-pgp-key-servers-and-lying-by-omission). Because of that, you can’t delete your publicly announced account information and account activity once you post it to your signature chain. You can, however, revoke it. Revoking, in Keybase, means retracting the original statement, indicating that it’s no longer true, or that the information has changed.



### Our Business Model

We’ll never run an ad-supported business. And Keybase will never sell your data.

Eventually, we plan to offer a paid service and extra features for corporate teams, primarily. Until then, we're building a product to bring public keys to the masses.

### What personal information do we collect?

_Contact and account information_ : We collect the information you provide to us, such as your name, avatar picture, email address, and social media handles. Note: Keybase never requires a phone number and no longer requires an email address in order to open and maintain an account.

_Team names and membership_ : If you create or join a team on Keybase, we collect and store the names of the teams and subteams, their membership, and when they were formed.

_Hashed password_ : We collect and store information about your Keybase password that allows you to prove you know your password; that [“stretched”](https://en.wikipedia.org/wiki/Key_stretching) password is sent to Keybase’s servers. See [here](https://keybase.io/docs/api/1.0/call/login) for more information.

_Account activity_ : We collect information about your activity while using the Services, such as proving you control a certain Twitter username, announcing your public key, editing your biographical information, or editing any of your social media usernames. Some of this information is aggregated, summarized, and published into the Bitcoin blockchain in order to detect and guard against certain vulnerabilities. See “Disclosures to your signature chain, the Merkle tree, and the Bitcoin blockchain” below for information on how we treat this data.

_Files and Data_. We collect and store files and information that you transmit to other parties using Keybase or that you elect to store on the Services. This data is always encrypted on our servers, except for documents in your public folder and your public chats. Those are not encrypted because you choose to make those publicly accessible.

_Do Not Track_. Keybase does not collect personally identifiable information from you to track you across third-party websites. As a result, Keybase does not specifically respond to web browser Do Not Track signals.

_Unique personal identifiers_. We collect and store information to identify you, such as your Keybase user ID and your IP address (which is stored only temporarily).

_Network usage and activity_. We collect certain technical and analytics data, for example the type of device you’re using to access our Services or the operating system you’re running. Keybase is designed to store the minimum amount of technical data for the shortest time necessary in order for you to have the Services across all the devices you add.

_Interactions with us_ : If you email us, we may keep the content of your message, your email address, and your contact information to respond to the request and otherwise follow up as necessary.

### How do we use your information?

Here’s how we use your information:

  * To provide the Services to you on all the devices you add.
  * To protect our Services and users. For example, we will use it to investigate suspicious activity and attacks.
  * To improve Keybase for all our users. For example, we will make development decisions based on what features our users are using.
  * To communicate with you about Keybase. You can unsubscribe from those messages (unless they are specifically about your account, and then we have to send them to you).



### Disclosures to your signature chain, the Merkle tree and the Bitcoin blockchain

**How and why do we use your signature chain, the Merkle tree and the Bitcoin blockchain?**

Every Keybase account has a public signature chain (called a sigchain), which is an ordered list of statements about how the account has changed over time. [Meet the sigchains!](https://keybase.io/docs/sigchain) Specifically, we announce into your sigchain your Keybase username, when you add a public key, additions or changes to your identity proofs (Twitter, Github, your website, etc.), public bitcoin address announcements, public follower statements, and device additions and revocations. The list of statements grows over time as you change and add to your account.

Every time you add to or change data in your sigchain, those changes are aggregated with the data that everyone else on Keybase adds or changes. Those aggregated changes are summarized (aka “hashed”) into the root of Keybase’s [Merkle tree](https://en.wikipedia.org/wiki/Merkle_tree).

Every 12 hours, that summary/hash in the Merkle tree gets published into the Bitcoin blockchain.

We do this to increase the security of your information. It helps us to detect whether our servers have been compromised and are lying by omission or have been forked.

**Can I delete information from my sigchain?**

No. For your protection from, and detection of, hackers and other undesirable intrusions into the Services, it is not possible to delete data from your sigchain, or to change the hashes/summaries in the Merkle tree and the Bitcoin blockchain. If you want to alter information that you have provided, the previously provided information cannot be deleted and can only be revoked.

For example, if you change your Twitter username, your old Twitter username will not be deleted from your sigchain. Instead, you will append a new statement to your sigchain, revoking the old Twitter username. Nobody is able to retroactively change the hashes into the Merkle tree and Bitcoin blockchain: the fact that the hashes cannot be changed is the essence of this security feature. All of this means that _people will be able to discover your old Twitter username by looking at your sigchain._

**Where can I find out more?**

For a technical explanation of how Keybase supports “revocations” instead of “deletions”, how they are chained together, and how they are hashed into the Merkle tree and Bitcoin blockchain, please read our paper documentation about our [server security](https://keybase.io/docs/server_security) and how we use the Bitcoin blockchain to [improve security](https://keybase.io/docs/server_security/merkle_root_in_bitcoin_blockchain).

The content of your chat messages and private files is end-to-end encrypted. Only you and those you communicate with will have the ability to see them. Keybase and third parties do not have access to this information.

Service providers: We use the following service providers to process your personal information:

  * Amazon Web Services for content storage;
  * Kraken.io for resizing unencrypted images such as user profile pictures;
  * Note: Users can also opt in, via the chat interface, to Google location services (with the /location command) and Giphy (with the /giphy command) but those services don’t receive personal information about you.



_Law & Order_: We may disclose your information to third parties if we determine that such disclosure is reasonably necessary to: (a) comply with a valid legal process; (b) protect any person from death or serious bodily injury; (c) prevent fraud or abuse; or (d) protect our rights, property, safety, or interest.

_Cookies_ : We use cookies to manage user sessions. You can set your browser to not accept cookies, but this may limit your ability to use the Services. Our systems currently don’t respond to DNT:1 signals from browsers visiting our websites.

_Sale or transfer of our business_. If we sell, merge, reorganize, enter bankruptcy, or transfer any part of our business, we may be required to share your information before and after such an event. If we do complete one of those transactions, we will notify you about any changes or transfers and this Privacy Policy will apply to the new entity.

_We do not share or sell your personal information with third parties for their marketing purposes._

### Where do we store your information?

We transfer, process, and store your personal information in the United States.

### How do we secure your information?

Keybase takes reasonable security measures such as password protection, two-factor authentication for internal logins, client-side encryption, and a whitelist of employees who can deploy changes to the server, as we deem appropriate to protect the information we collect from misuse, unauthorized access, disclosure, alteration and destruction. Some hosting details for the technically-minded:

  * The Services are currently hosted on Amazon’s AWS;
  * All data is transferred with industry standard TLS during transmission; and
  * Keybase’s website does not serve any 3rd party hosted JavaScript.



While we do use care to protect your information, no data transmission over the Internet or other network can be guaranteed to be 100% secure. As a result, we cannot and do not guarantee the security of any information you transmit on or through the Services, and you do so at your own risk.

### What are our lawful bases for processing your information?

We rely on contractual necessity to process your data in order to provide and protect the Keybase Services. We rely on our legitimate interests to perform research and development.

### How long do we store your information?

All of your chat messages and attachments are stored, encrypted, until you delete or explode them. If you delete documents from KBFS, they remain encrypted on our servers for two weeks and are then deleted. We store certain metadata for varying lengths of time in order for you to have access to Keybase over multiple devices or add new people to existing conversations.

### How can you exercise your rights over your information?

You have control over your personal information and how it is collected, used, and shared. For example, you have a right to:

  * Delete your account and all your associated data. You can do this through your Keybase client.
  * Erase or delete particular files and data. You can do this through your Keybase client. You can also set messages to delete automatically.
  * Change or correct personal data. You can do this through your Keybase client.
  * Access and take your data to another service. You can download your files through the Keybase client. Contact us at [privacy@keybase.io](mailto:privacy@keybase.io) with any other questions or to make a data subject access request.



### Will this privacy policy ever change?

We will update this Privacy Policy from time to time. If we make any changes that reduce or negatively affect your privacy rights, you will be notified either through email or the Services. If we only make minor changes that don’t reduce your rights (like changing an email address or rewording paragraphs to make them clearer), we will just post the revised policy here. Those changes will go into effect on the “Effective Date” shown at the top of the updated Privacy Policy. Your continued use of the Services after the Effective Date means you agree to the new Privacy Policy.

### Other questions?

Contact [privacy@keybase.io](mailto:privacy@keybase.io). We typically respond to requests within 30 days.
