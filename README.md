# Networked.Community Wiki (temporary)

> This temporary wiki for networked.community is intended to guide users through the onboarding process to our identity provider and Mastodon

1. To get an account on our Mastodon instance, you will need to first register for a username on our new identity provider that will provide a Single Sign-On (SSO) login experience. This is so that one username and password can be used to access all of Networked.Community's applications.
2. Get the invite link to our Networked.Community Identity (NCI) from Joe or Berin (don't sign up directly on our Mastodon). Our identity provider is located at https://id.networked.community and is provided from an open source project called [authentik](https://goauthentik.io/).
3. When you sign up for a username, keep in mind that this username will be your username on Mastodon and all our future applications.
4. After you submit the User Registration form, you will be sent a confirmation email to verify your email address.

![](/assets/email-verify.png)

5. After verifying your email address, you will be prompted to set up Two Factor Authentication (2FA). The onscreen dialog isn't great and we're working on improving it but basically click the first option (TOTP) to set up 2FA with Google Authenticator and similar apps. The second option (WebAuthn) is for using Hardware Security Keys like a Yubikey for 2FA .

![](/assets/nci-2fa.png)

6. Once your logged in to NCI, you'll see that Mastodon is there as an application. Click that to go to our Mastodon instance located at https://social.networked.community and at Mastodon, ignore the email/password login and click on `Log in with Networked.Community Identity`.

![](/assets/mastodon-login.png)

7. You will be taken to NCI and after approving the sharing of your profile to our Mastodon instance, a new Mastodon account will be created for you using your NCI username and name that you supplied during user registration.
8. If you have any questions, please post in our Human Union General room on element/matrix.
