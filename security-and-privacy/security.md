# Security

## Data security

Every piece of data is encrypted at rest and stored in Microsoft Azure data centers located in the US. In transit, all payloads are also transmitted across encrypted channels. Our systems are protected behind firewalls to restrict access from external networks.

### Access to the app

* All access to the Better Reports app is restricted to HTTPS encrypted connections
* Authentication leverages a [Strict SameSite cookie policy](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie/SameSite#Strict)
* When a user logs out, it is immediately logged out from all devices

### Connector data

* Connectors import application data via secure tokens and channels \(the exact method depends on the API authentication mechanism used by the underlying app\).
* When disconnecting an app, all the associated data is immediately and permanently deleted

### Access by support staff

PII data such as phone numbers, street addresses, email addresses, IP addresses and other personal data fields are obfuscated. Our support staff may not see this information unless you explicitly authorized it.

### Contact Us

Have a question or concern?  
Please email us at [security@betterreports.com](mailto:security@betterreports.com)

