> *The following text is extracted and transformed from the simpletax.ca privacy policy that was archived on 2018-09-06. Please check the [original snapshot on the Wayback Machine](https://web.archive.org/web/20180906043434id_/https%3A//simpletax.ca/privacy) for the most accurate reproduction.*

# SimpleTax: Privacy Policy

We know you are trusting us with some of your most personal and private information. Here's how we collect, protect, and use your data.

### Personally Identifiable Information

When you sign up for a SimpleTax account, we'll ask for your email address. Your email address is the only personally identifiable information that we can access without your password. All other information you provide is encrypted.

### Your Email Address

Your email address will never be sold and will only be used to inform you of product updates and future versions. We will never send you third-party marketing emails. We comply with [CASL](http://www.fightspam.gc.ca/eic/site/030.nsf/eng/home) and give you the option to unsubscribe. We hate spam too.

### Data Ownership & Encryption

Your data is yours. We will never, ever, sell it.

Your tax data is encrypted on our servers using your password as the key. You are the only person who can access your account; we can't decrypt your data without your password. If you lose your password, we are not able to reset or recover it for you.

Your password is salted with a 9 byte salt and hashed with MD5 before being sent over HTTPS to our server. This hash is never stored in a cache or on disk. We take this hash and salt it again with an 8 byte salt and hash it using PBKDF2 with SHA1 for 60,000 iterations. The resulting signature is what we store in our database.

Your tax data is sent over HTTPS to our server where it is encrypted using AES in CTR mode. The IV is a 128 bit number generated with a cryptographically secure random number generator. We also store an HMAC of the data which is packed along with it. The cryptographic key is derived from the second to last hash pulled from the PBKDF2 algorithm used to hash the password. This ensures that the key cannot be derived from anything stored in our database. The key must be transmitted from the client and a full hash run each time the data is encrypted or decrypted.

You can delete your account, and all your data, at any time.

### SSL/TLS and HSTS

The connection between you and our servers uses high-grade encryption. We use HTTPS across all our services with an Extended Validation (EV) certificate from [DigiCert](https://www.digicert.com/). We have an [A+ rating](https://www.ssllabs.com/ssltest/analyze.html?d=simpletax.ca&hideResults=on&latest) from SSL Labs. We also use [HSTS](http://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security) to ensure your browser only uses HTTPS. We are on the HSTS preloaded lists for both Chrome and Firefox.

### Cookies

We use cookies, a small amount of data stored locally in your web browser. These cookies will never contain any personally identifiable information and can be safely deleted without impacting your saved data.

Some of our analytics and advertising partners also use cookies. You can choose to disable or block these third-party cookies. Learn more about opting-out on the [Digital Advertising Alliance of Canada](http://youradchoices.ca/understanding-online-advertising/) website.

### Data Storage

Your data resides only in Canada. We utilize Tier III/IV data centres located in Toronto, ON and Halifax, NS. Our hosting partners share our high standards for security and privacy.

### Disclosure of Information

We comply with the Canadian Personal Information Protection and Electronic Documents Act (PIPEDA). If required by law, we may disclose your information, in its encrypted form, to law enforcement officials. We are unable to disclose your decrypted information.

### Credit Card Data

If you choose to pay, your credit card details will be tokenized and sent to Stripe, our [secure payments provider](https://stripe.com/help/security). We are [PCI DSS](https://www.pcisecuritystandards.org/security_standards/) compliant and we do not store any credit card data on our servers.

### Diagnostic and Usage Data

We collect diagnostic and usage data to improve SimpleTax and ensure everything is working properly. For example, if an error is detected, we may capture details about your browser to help us fix the problem. This data is for internal use only and will never contain sensitive information.

### Questions or Concerns

Should you have any questions or concerns, or would simply like to better understand the way we do things at SimpleTax, please don't hesitate to [contact us](mailto:hello@simpletax.ca).

We last updated our Privacy Policy on March 2, 2016.
