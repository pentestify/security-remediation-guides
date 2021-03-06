[![CloudSploit](https://cloudsploit.com/img/logo-new-big-text-100.png "CloudSploit")](https://cloudsploit.com)

# GOOGLE / Cryptographic Keys / Key Rotation

## Quick Info

| | |
|-|-|
| **Plugin Title** | Key Rotation |
| **Cloud** | GOOGLE |
| **Category** | Cryptographic Keys |
| **Description** | Ensures Cryptographic keys are set to rotate on a regular schedule |
| **More Info** | All Cryptographic keys should have key rotation enabled. Google will handle the rotation of the encryption key itself, as well as storage of previous keys, so previous data does not need to be re-encrypted before the rotation occurs. |
| **GOOGLE Link** | https://cloud.google.com/vpc/docs/using-cryptoKeys |
| **Recommended Action** | Restrict TCP port 5900 to known IP addresses |

## Detailed Remediation Steps

