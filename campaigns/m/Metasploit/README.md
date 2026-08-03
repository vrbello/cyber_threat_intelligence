# Metasploit - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Metasploit_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Metasploit:

* [US](https://vuldb.com/country/us)
* [GB](https://vuldb.com/country/gb)
* [DE](https://vuldb.com/country/de)
* ...

There are 3 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Metasploit or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Andariel](https://vuldb.com/actor/andariel) | High
2 | [Metasploit](https://vuldb.com/actor/metasploit) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Metasploit.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [1.94.52.128](https://vuldb.com/ip/1.94.52.128) | ecs-1-94-52-128.compute.hwclouds-dns.com | [Metasploit](https://vuldb.com/actor/metasploit) | High
2 | [4.233.216.36](https://vuldb.com/ip/4.233.216.36) | - | [Metasploit](https://vuldb.com/actor/metasploit) | High
3 | [31.57.35.90](https://vuldb.com/ip/31.57.35.90) | - | [Metasploit](https://vuldb.com/actor/metasploit) | High
4 | [34.58.122.143](https://vuldb.com/ip/34.58.122.143) | 143.122.58.34.bc.googleusercontent.com | [Metasploit](https://vuldb.com/actor/metasploit) | Medium
5 | [34.58.195.70](https://vuldb.com/ip/34.58.195.70) | 70.195.58.34.bc.googleusercontent.com | [Metasploit](https://vuldb.com/actor/metasploit) | Medium
6 | [34.124.148.215](https://vuldb.com/ip/34.124.148.215) | 215.148.124.34.bc.googleusercontent.com | [Metasploit](https://vuldb.com/actor/metasploit) | Medium
7 | ... | ... | ... | ...

There are 22 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Metasploit. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Metasploit. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.git/` | Low
2 | File | `/.ssh/authorized_keys` | High
3 | File | `/collect/PortV4/downLoad.html` | High
4 | File | `/dataSet/resolveSql` | High
5 | File | `/fort/portal_login` | High
6 | File | `/forum/away.php` | High
7 | File | `/index.php` | Medium
8 | File | `/modules/Planner/resources_addQuick_ajaxProcess.php` | High
9 | File | `/oauth/idp/.well-known/openid-configuration` | High
10 | File | `/spip.php` | Medium
11 | File | `ActivityManagerShellCommand.java` | High
12 | ... | ... | ...

There are 90 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://asec.ahnlab.com/en/59318/
* https://asec.ahnlab.com/en/64034/
* https://thedfirreport.com/2023/09/25/from-screenconnect-to-hive-ransomware-in-61-hours/
* https://thedfirreport.com/2023/12/18/lets-opendir-some-presents-an-analysis-of-a-persistent-actors-activity/
* https://urlhaus.abuse.ch/url/3550439/
* https://urlhaus.abuse.ch/url/3555537/
* https://urlhaus.abuse.ch/url/3556172/
* https://urlhaus.abuse.ch/url/3560065/
* https://urlhaus.abuse.ch/url/3560530/
* https://urlhaus.abuse.ch/url/3561847/
* https://urlhaus.abuse.ch/url/3561983/
* https://urlhaus.abuse.ch/url/3577026/
* https://urlhaus.abuse.ch/url/3597138/
* https://urlhaus.abuse.ch/url/3609344/
* https://urlhaus.abuse.ch/url/3610001/
* https://urlhaus.abuse.ch/url/3611202/
* https://urlhaus.abuse.ch/url/3665958/
* https://urlhaus.abuse.ch/url/3697792/
* https://urlhaus.abuse.ch/url/3697846/
* https://urlhaus.abuse.ch/url/3700520/
* https://urlhaus.abuse.ch/url/3720323/
* https://urlhaus.abuse.ch/url/3732097/
* https://urlhaus.abuse.ch/url/3754652/
* https://urlhaus.abuse.ch/url/3784045/
* https://urlhaus.abuse.ch/url/3787616/
* https://urlhaus.abuse.ch/url/3788957/
* https://urlhaus.abuse.ch/url/3792037/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
