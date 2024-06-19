MFA or Multi-factor authentication

**Factors**: Things that provide evidence for your identity, generally 4 factors

**Knowledge**: What you KNOW that can be used for login. Examples: Username, Password, permanent pin, email etc
**Posession**: What you HAVE that can be used for login. Examples: Your credit card in an ATM, MFA device: A temporary PIN (like MFA), etc
**Inherent**: Things that are related to your body or brain. Examples: Facial scan, voice identifier, etc
**Location**: Where you try to login from, this could be digital or physical location. Examples: Restrict login to only your corporate network

How is an MFA generated? 

1- You enter the username and password for your identity
2- AWS generates the secret code and gathers other information about you
3- It uses the information to generate a QR code
4- You scan that QR code using authenticator applications 
5- The MFA will be added to your application

One MFA application can contain multiple **virtual devices**, one for each identity.