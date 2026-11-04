# xssil-email-verification

Deployment package for the existing Xssil email Lambda.

Function: xssil-email-verification
Runtime: Node.js 22.x
Handler: index.handler

## Package to upload

https://github.com/supaafrikan/xssil-email-verification/raw/main/xssil-email-verification-purpose.zip

This file is not deployed until it is uploaded to the existing function. Do not unzip it first.

It keeps signed requests, the existing public key, DynamoDB replay protection, and the sender Xssil Security <no-reply@xssil.com>. Subjects are fixed:

- Verify your Xssil email address / Vérifiez votre adresse e-mail Xssil
- Your Xssil sign-in code / Votre code de connexion Xssil
- Confirm your Xssil account change / Confirmez la modification de votre compte Xssil

A proof without a purpose still uses the verification message.
