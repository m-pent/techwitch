+++
date = '2025-09-21T17:12:11+01:00'
title = 'Password Managers and 2FA'
author = 'gothintheshell'
draft = false
+++

Moving on from browsers, browser extensions and search engines, I'm going to discuss password managers and multi-factor authentication (MFA). I figured as many of us have a large number of accounts and services we're required to log into online, why not share the ways in which using a password manager can increase your password strength (and security) and make logging in easier - as you no longer need to remember your password! As well as how you can add an additional layer of security to your most important accounts with MFA. 

## Wait, what's wrong with memorising my passwords?!

The main issue with this approach is that often, in order to make it easily memorable, the passwords we'll come up with are often shorter, less complex, and may contain easily guessible details related to our personal lives. 

<div style="width:100%;height:0;padding-bottom:44%;position:relative;"><iframe src="https://giphy.com/embed/xT0GqJfdLcrcpSbZf2" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><br> 

Don't believe me, or want to read more? While I don't love the title of this article, here's some in-depth analysis that was done around password use in 2025 by [Cybernews](https://cybernews.com/security/password-leak-study-unveils-2025-trends-reused-and-lazy/).

In addition, if you need to remember a password for an increasing number of websites and services, the tempation to re-use passwords or only slightly modify the existing password is high, which can be disasterous if someone is able to get hold of this password, as now they have access to any of your other accounts which utilise that same username/email and password combination. (Such as can happen with [credential stuffing](https://owasp.org/www-community/attacks/Credential_stuffing) attacks.)

## Benefits of using a password manager

Password managers can help by creating a unique and complex password for each website (or service) you use, and stores it securely. Then the next time you go to that site, you can use the auto-fill feature of the password manager to fill in your sign in credentials for you! The URL of the sign-in page is also usually stored with the credentials, so this also adds another layer of protection when it comes to potential phishing attacks (eg. what if you've clicked link from an email or text, but the website you are sent to ***is not*** the genuine website, but one trying to steal those login details. Chances are your password manager will recognise it's not the correct URL and warn you before entering any details on the website.)

Modern password managers also often many related services such as: 
- monitoring for breached passwords (and notifying you if one of yours is on a list!) 
- storing of secure notes, keys, passkeys, and identity information
- integrated two-factor authenticator (2FA), for accounts where you use a second factor for enhanced account protection
- family vaults and/or the ability to share individual items within your vault
- designating emergency access, or a trusted contact who may request access to your vault, in the case of an emergency (or death)

## Where to begin

If you’re not using a password manager, all you need to do is sign-up for a reputable service and I also recommend downloading their browser extensions and/or mobile apps, so that your passwords are easily available no matter where you need them. 

In terms of potential options, I will only share those I am familiar with but I would suggest checking out: 
- [Bitwarden](https://bitwarden.com) 
- [Proton Pass](https://proton.me/pass)
- [1Password](https://1password.com)

## Want to change your password manager?

Nowadays I find moving from one password manager to another is generally a seamless process, as long as you’re comfortable with downloading (or exporting) a file with the contents of your current vault, which are then uploaded (or imported) to the new password manager. I always opt for one that has both web and mobile apps, so that I can use it on my computer and my mobile.

## Multi-factor authentication (MFA)

At this point I feel it's important to note that if you are utilising a password manager ***please ensure you’re using a strong master password and use MFA for access to your vault***, as this is the only thing preventing others from having access to your passwords and any other secure information stored within your vault!

As I've brought it up, what is MFA and how can it help? 

Multi-factor authentication (MFA), means using more than one factor (or verfication steps) to ensure that it's actually you logging into your account. Often this involves something you know (or your password manager knows, such as your username + password) + something you have (authenticator app, mobile phone) or something you are (using biometrics such as your fingerprint or face.) So if someone does manage to gain access to your username and password, they won't be able to fully sign-in and access your account without knowing the additional verification info from your second factor. 

<div style="width:100%;height:0;padding-bottom:75%;position:relative;"><iframe src="https://giphy.com/embed/fnuSiwXMTV3zmYDf6k" width="100%" height="100%" style="position:absolute" frameBorder="0" class="giphy-embed" allowFullScreen></iframe></div><br> 

Even if you choose not to use MFA for all of your accounts, I do recommend it for any of your critical accounts such as your primary email account, financial or banking institutions, social media accounts, etc.

The settings and options for MFA may vary from service to service, but are generally found in your account security settings. While some may only offer text or email-based code offerings, others will offer more robust options such as authenticator apps or biometrics. Regardless of robustness, any additional factor is better than no additional factor when it comes to keeping your accounts secure. 

I'm realising now there could be much more I could say about MFA, including how to setup an Authenticator app, for example, but I'll leave it as is for another day and a potential future post. As always, thanks for reading! 

If you're enjoying these posts, please feel free to connect on social media (currently Mastodon and Bluesky) using the buttons near the top right of this page.