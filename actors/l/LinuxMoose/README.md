# LinuxMoose - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [LinuxMoose](https://vuldb.com/actor/linuxmoose). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/linuxmoose](https://vuldb.com/actor/linuxmoose)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with LinuxMoose:

* [NL](https://vuldb.com/country/nl)
* [US](https://vuldb.com/country/us)
* [RU](https://vuldb.com/country/ru)
* ...

There are 23 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of LinuxMoose.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [27.124.41.11](https://vuldb.com/ip/27.124.41.11) | - | - | High
2 | [27.124.41.31](https://vuldb.com/ip/27.124.41.31) | - | - | High
3 | [27.124.41.33](https://vuldb.com/ip/27.124.41.33) | - | - | High
4 | [27.124.41.52](https://vuldb.com/ip/27.124.41.52) | - | - | High
5 | [42.119.173.138](https://vuldb.com/ip/42.119.173.138) | - | - | High
6 | [62.210.6.34](https://vuldb.com/ip/62.210.6.34) | 62-210-6-34.rev.poneytelecom.eu | - | High
7 | [77.247.177.31](https://vuldb.com/ip/77.247.177.31) | - | - | High
8 | [77.247.177.36](https://vuldb.com/ip/77.247.177.36) | - | - | High
9 | [77.247.177.87](https://vuldb.com/ip/77.247.177.87) | - | - | High
10 | [77.247.178.177](https://vuldb.com/ip/77.247.178.177) | - | - | High
11 | [79.176.26.142](https://vuldb.com/ip/79.176.26.142) | bzq-79-176-26-142.red.bezeqint.net | - | High
12 | [82.146.63.15](https://vuldb.com/ip/82.146.63.15) | ebay2.com | - | High
13 | ... | ... | ... | ...

There are 48 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _LinuxMoose_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by LinuxMoose. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.travis.yml` | Medium
2 | File | `/+CSCOE+/logon.html` | High
3 | File | `/admin-api/upload_image` | High
4 | File | `/admin/admin-profile.php` | High
5 | File | `/admin/create_product.php` | High
6 | File | `/admin/subnets/ripe-query.php` | High
7 | File | `/api/front/search/books` | High
8 | File | `/api/mjkj-chat/chat/mng/update/questionCou` | High
9 | File | `/api/trpc/user.register` | High
10 | File | `/api/wizard/setsyncpppoecfg` | High
11 | File | `/application/index/controller/Screen.php` | High
12 | File | `/apply.cgi` | Medium
13 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
14 | File | `/bin/boa` | Medium
15 | File | `/cap.js` | Low
16 | File | `/cgi-bin/wireless.cgi` | High
17 | File | `/comments` | Medium
18 | File | `/core/conditions/AbstractWrapper.java` | High
19 | File | `/dcim/sites/add/` | High
20 | File | `/debug/pprof` | Medium
21 | File | `/dev/shm` | Medium
22 | File | `/download` | Medium
23 | File | `/ebics-server/ebics.aspx` | High
24 | File | `/etc/shadow` | Medium
25 | File | `/export` | Low
26 | File | `/file?action=download&file` | High
27 | File | `/forum/away.php` | High
28 | File | `/goform/aspForm` | High
29 | File | `/goform/form2RepeaterStep2.cgi` | High
30 | File | `/goform/form2Wl5RepeaterStep2.cgi` | High
31 | File | `/goform/form2WlanBasicSetup.cgi` | High
32 | File | `/guestbook` | Medium
33 | File | `/hardware` | Medium
34 | File | `/include/chart_generator.php` | High
35 | File | `/include/file.php` | High
36 | File | `/include/makecvs.php` | High
37 | File | `/librarian/bookdetails.php` | High
38 | File | `/modules/Planner/resources_addQuick_ajaxProcess.php` | High
39 | ... | ... | ...

There are 332 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/moose
* https://ioc.hatenablog.com/entry/2015/05/28/000000
* https://www.threatminer.org/report.php?q=Dissecting-LinuxMoose.pdf&y=2015

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
