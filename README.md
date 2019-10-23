# serverless-top-10


# How to ~~hack~~ secure a serverless app on Azure

The OWASP Top 10 is the standard for security professionals to understand risks and attacks that their web applications may face. 

In Serverless applications, a lot of the heavy lifting, mostly the administration of the server, is taken care of by the cloud provider. But we musn't become complacent because of this. Our serverless applications still execute code, and therefore may still be vulnerable. 

[Heavy Lifting GIF/Image]()

In 2018 OWASP published the [OWASP Serverless Top 10](https://github.com/OWASP/Serverless-Top-10-Project). This is an effort to address the common application security risks and attacks that a serverless application may face. Here they are:

1. Injection
2. Broken Authentication
3. Sensitive Data Exposure
4. XML External Entities
5. Broken Access Control
6. Security Misconfiguration
7. Cross-Site-Scripting
8. Insecure De-Serialization
9. Using Components with Known Vulnerabilities
10. Insufficient Logging and Monitoring

Wait a minute.... the eagle eyed among you may be thinking 'These look familiar'. Yup, I had to double take too. You're right, they're exactly the same list as the OWASP Top 10, the order is even exactly the same. So what does this mean? 

As I said earlier, our serverless applications still run and execute code, if that code is written insecurely, then it's going to be vulnerable to the same application level attacks as our traditional applications. 

In most cases, the attacks will be very similar, but what you can't tell from a list of ten headings 🙃 is that there are some serverless specific variations of these attacks. There are variations for each category, but in my opinion, and to keep this at blog post length, as opposed to book length, the most cloud/serverless fundamental variations are found in the following categories.

1. Broken Authentication
2. Broken Access Control
3. Security Misconfiguration
4. Insufficient Logging / Monitoring

These are the three that we'll be looking at examples of for Microsoft Azure in this article. 

## Broken Authentication


 What is is

 Easy AUth in Azure Functions - AD B2C for more adavanced.


## Broken Access Control

Lot os different resources make up a serverless system. Attackers will exploit the connections between these, so a strong access control policy is very important here. 

- Least Privilege
- No keys in App Settings, use Key Vault instead, but limited keys

## Security Misconfiguration

- Remember serverless is more than just functions...
-SEcurity center reccomendations
- Storage security guide (link)
- Functions best practices (link)












