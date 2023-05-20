<img width="807" alt="justpass-me-front-page" src="https://github.com/justpass-me/.github/assets/100665288/76fb832c-711a-499c-88ca-9742c4d115ae">

# [justpass.me](https://www.justpass.me): Passkeys as a Service for your Web and Mobile Apps

justpass.me offers seemless biometric authentication to your users improving user satisfaction and
security. It is built on leading industry standards for federated authentication (OpenID) and passwordless
authentication (FIDO) to provide both interoperability, compliance and ease of use.

Read more about our [features](#features) below.


## Table of Contents

-   [Get started for free](#get-started)
-   [Features](#features)
-   [SDKs](#sdks)

## Get started
Sign up for free at [accounts.justpass.me](https://accounts.justpass.me). After signing up and creating an organization, getting started is as easy as configuring your backend client ID and secret settings. If you want to support mobile apps as well, you can do so by installing the mobile SDK's

## Features

justpass.me uses industry leading OpenID standard for logging in to the service. Additionally it extends the 
standard to allow secure registration of new credentials based on your backend needs. This bring significant
advantages in scaling and ease of use allowing you to implement all your authentication needs:

### - Single Factor authentication
User calls login endpoint with no credentials and gets redirected to justpass.me for authentication.
### - Second Factor Authentication
User calls login endpoint with first factor credentials and once validated is redirected.
to justpass.me for authentication

### - Migrating Existing users
Registration process is completely controlled from your backend server. Registration starts at your server backend and is authenticated before being redirected for registration.

## SDKs

-   Server Libraries:
    -   Python (Django): [repo link](https://github.com/justpass-me/justpass-me-django)
    -   Firebase Extension: [repo link](https://github.com/justpass-me/justpass-me-firebase-ext)
-   Mobile SDK's:
    -   iOS: [repo link](https://github.com/justpass-me/justpass-me-iOS-sdk)
    -   Android: [package link](https://mavenlibs.com/maven/dependency/tech.amwal.justpassme)
    -   React Native: [repo link](https://github.com/justpass-me/justpass-me-react-native) [package link](https://www.npmjs.com/package/@justpass-me/justpass-me-react-native)
