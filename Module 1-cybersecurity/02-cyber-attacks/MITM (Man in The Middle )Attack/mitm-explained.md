# Man-in-the-Middle(MITM) Attack

## Definition

An attacker intercepts communication between two parties.
Example : attcker placed between facebook and the user and sees the data user transfered

## Attack Flow

Victim
↓
Attacker
↓
Server

## Risks

- Credential theft
- Data manipulation
- Session hijacking

## Prevention

- HTTPS
- VPN
- TLS Certificates

### TLS Certificates
A TLS certificate is a digital identity card for a website.

Example :

Suppose you visit:

https://google.com

Before sending any sensitive data, your browser asks:

"How do I know you're really Google?"

Google's server replies:

"Here's my TLS certificate."

The certificate contains:

Website name (google.com)
Public key
Certificate issuer (Certificate Authority)
Expiration date
Digital signature

## SOC Detection

- Certificate warnings
- DNS anomalies
- Unusual network traffic