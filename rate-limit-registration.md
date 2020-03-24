Hello [] Team,

## Summary:

I have identified that the registration form `[]` is vulnerable to brute force attack.

## Steps to reproduce:

1- Go the form ``
2- Fill the complete form
3- Capture request using burp suite.
4- set intruder attack on email address
5- start attack from at least 100 requests
6- You can see that all the registrations has been successful and accounts has been created.

## Fix / Patch:

For rate limit protection add CAPTCHA on registration form.

Regards,
@Splint3r7
