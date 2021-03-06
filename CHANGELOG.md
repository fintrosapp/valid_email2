## Version 1.2.5
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/51, https://github.com/lisinge/valid_email2/pull/52 and https://github.com/lisinge/valid_email2/pull/53)

## Version 1.2.4
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/48, https://github.com/lisinge/valid_email2/pull/49 and https://github.com/lisinge/valid_email2/pull/50)

## Version 1.2.3
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/45)

## Version 1.2.2
Removed false positive email domains (https://github.com/lisinge/valid_email2/pull/43 and https://github.com/lisinge/valid_email2/pull/44)

## Version 1.2.1
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/41, https://github.com/lisinge/valid_email2/pull/42 and https://github.com/lisinge/valid_email2/commit/8b99a799dc126229d9bc4d79d473a0344e788d34)

## Version 1.2.0
Disposable email providers have started to use random subdomains so valid_email2
will now correctly match against subdomains https://github.com/lisinge/valid_email2/issues/40  
Updated list of disposable email providers.

## Version 1.1.13
Removed husmail.com and nevar.com from the disposable email list (https://github.com/lisinge/valid_email2/pull/38)

## Version 1.1.12
Removed fastmail.fm from the disposable email list (https://github.com/lisinge/valid_email2/pull/37)

## Version 1.1.11
Removed poczta.onet.pl from the disposable_emails list (https://github.com/lisinge/valid_email2/issues/34)
Added a whitelist to the internal pull_mailchecker_emails so that poczta.onet.pl
can't sneak back in again.

## Version 1.1.10
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/32)
Added script that pulls disposable emails (https://github.com/lisinge/valid_email2/pull/33)

## Version 1.1.9
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/22,
https://github.com/lisinge/valid_email2/pull/23, https://github.com/lisinge/valid_email2/pull/24,
https://github.com/lisinge/valid_email2/pull/25, https://github.com/lisinge/valid_email2/pull/26,
https://github.com/lisinge/valid_email2/pull/27, https://github.com/lisinge/valid_email2/pull/29
and https://github.com/lisinge/valid_email2/pull/30)

## Version 1.1.8
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/21)

## Version 1.1.7
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/18 and https://github.com/lisinge/valid_email2/pull/19)

## Version 1.1.6
Fix a regression which changed validation on domains that caused domains with
multiple consecutive dots to be valid.

## Version 1.1.5
Be more lenient on the mail gem version dependency to allow people to use v2.6.
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/14 and https://github.com/lisinge/valid_email2/pull/15)

## Version 1.1.4
Added more disposable email domains (https://github.com/lisinge/valid_email2/commit/aedb51fadd5a05461d7f5ef7ea6942d7769f0c58)

## Version 1.1.3
Added more disposable email domains (https://github.com/lisinge/valid_email2/commit/a29ce30d4bc22a23283a0b3f9f6d4560309784ca)

## Version 1.1.2
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/11 and https://github.com/lisinge/valid_email2/pull/13 and https://github.com/lisinge/valid_email2/commit/81e20eb8a14759b88dfee3c343e21512aa7d8da4)

## Version 1.1.1
Added more disposable email domains (https://github.com/lisinge/valid_email2/pull/9 and https://github.com/lisinge/valid_email2/pull/10)

## Version 1.1.0
Added support to locally blacklist emails

## Version 1.0.0

Moved EmailValidator to seperate file
