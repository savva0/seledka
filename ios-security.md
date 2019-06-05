# Security features of iOS

## iOS devices support a variety of authentication methods:
* Touch ID, a fingerprint recognition feature.
* Face ID, a face recognition feature.
* Passcode of variable length
* Alphanumeric passcode

## iOS updates
iOS updates are signed by Apple and each update procedure has to be authorized by Apple.<sup>[1]</sup>
Apple routinely denies iOS downgrade.

## App Store, distribution platform for 3rd party applications
App Store is a marketplace for 3rd party applications on iOS platform.
Apple does not normally allow installation of 3rd party applications from other sources.
Access to App Store is vetted by Apple and apps undergo a review process by Apple for compliance with strict rules regarding privacy and API usage.<sup>[2]</sup>

## Enterprise program
Sometimes applications are not intended to be used by general public but to be used within organization internally, for that enterprise customers can apply for Enterprise Development Program to develop and distribute applications internally within organization.<sup>[3]</sup>
These application explicitly disallowed by Apple to be distributed outside organization.
There were several high profile cases where Apple revoked enterprise certificates of major companies.<sup>[4]</sup>

## Testflight
Testflight, a beta software distribution platform.
Application developers can use Testflight to distribute beta versions of apps for testing.<sup>[5]</sup>

## Keychain Services, secure secret storage.
Keychain Services, an encrypted database which stores user's secrets in a secure way, including but not limited to passwords, credit card numbers, notes, private keys.<sup>[6]</sup>

## Secure Enclave, device's hardware-based key manager.
With iPhone 5S Apple introduced Secure Enclave, a hardware-based key manager.
It's purpose is generation and secure storage of private keys.
The key cannot be exported.
And pregenerated key cannot be imported.<sup>[7]</sup>

## Trust Store, iOS preinstalled root certificates
Apple follows industry-standard practices regarding root trust transparency and publishes list of all preinstalled root certificates.<sup>[8]</sup>

### References:
1. [iOS 12.3, May 2019](https://www.apple.com/business/site/docs/iOS_Security_Guide.pdf) (retrieved 4 June 2019)

2. [App Store Review Guidelines](https://developer.apple.com/app-store/review/guidelines/) (retrieved 4 June 2019)

3. [Apple Developer Enterprise Program](https://developer.apple.com/programs/enterprise/) (retrieved 4 June 2019)

4. [Apple revokes Google’s enterprise iOS certificate, shuts down internal apps.](https://arstechnica.com/gadgets/2019/01/apple-shuts-down-googles-internal-ios-apps-just-like-facebook/) (retrieved 4 June 2019)

5. [Apple Testflight](https://developer.apple.com/testflight/) (retrieved 4 June 2019)

6. [Keychain Services](https://developer.apple.com/documentation/security/keychain_services) (retrieved 4 June 2019)

7. [Storing Keys in the Secure Element](https://developer.apple.com/documentation/security/certificate_key_and_trust_services/keys/storing_keys_in_the_secure_enclave) (retrieved 4 June 2019)

8. [List of available trusted root certificates in iOS](https://support.apple.com/en-us/HT204132) (retrieved 4 June 2019)
