# RansomHub - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _RansomHub_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RansomHub:

* [US](https://vuldb.com/country/us)
* [RU](https://vuldb.com/country/ru)
* [CN](https://vuldb.com/country/cn)
* ...

There are 4 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with RansomHub or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [RansomHub](https://vuldb.com/actor/ransomhub) | High
2 | [Scattered Spider](https://vuldb.com/actor/scattered_spider) | High
3 | [ShadowSyndicate](https://vuldb.com/actor/shadowsyndicate) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RansomHub.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.8.63.178](https://vuldb.com/ip/5.8.63.178) | 5-8-63-178.static.x5x.tech | [RansomHub](https://vuldb.com/actor/ransomhub) | High
2 | [5.181.86.158](https://vuldb.com/ip/5.181.86.158) | - | [RansomHub](https://vuldb.com/actor/ransomhub) | High
3 | [8.211.2.97](https://vuldb.com/ip/8.211.2.97) | - | [RansomHub](https://vuldb.com/actor/ransomhub) | High
4 | [20.37.139.187](https://vuldb.com/ip/20.37.139.187) | - | [Scattered Spider](https://vuldb.com/actor/scattered_spider) | High
5 | [23.92.31.138](https://vuldb.com/ip/23.92.31.138) | 23-92-31-138.ip.linodeusercontent.com | [RansomHub](https://vuldb.com/actor/ransomhub) | High
6 | [23.227.193.172](https://vuldb.com/ip/23.227.193.172) | 23-227-193-172.static.hvvc.us | [RansomHub](https://vuldb.com/actor/ransomhub) | High
7 | [31.216.148.33](https://vuldb.com/ip/31.216.148.33) | 31-216-148-33.ip.dclux.com | [ShadowSyndicate](https://vuldb.com/actor/shadowsyndicate) | High
8 | [37.1.212.18](https://vuldb.com/ip/37.1.212.18) | - | [RansomHub](https://vuldb.com/actor/ransomhub) | High
9 | [37.120.143.202](https://vuldb.com/ip/37.120.143.202) | - | [RansomHub](https://vuldb.com/actor/ransomhub) | High
10 | [38.135.54.24](https://vuldb.com/ip/38.135.54.24) | - | [RansomHub](https://vuldb.com/actor/ransomhub) | High
11 | [38.146.28.93](https://vuldb.com/ip/38.146.28.93) | - | [RansomHub](https://vuldb.com/actor/ransomhub) | High
12 | [38.180.81.153](https://vuldb.com/ip/38.180.81.153) | - | [RansomHub](https://vuldb.com/actor/ransomhub) | High
13 | [38.180.139.56](https://vuldb.com/ip/38.180.139.56) | - | [RansomHub](https://vuldb.com/actor/ransomhub) | High
14 | [38.180.195.187](https://vuldb.com/ip/38.180.195.187) | - | [RansomHub](https://vuldb.com/actor/ransomhub) | High
15 | ... | ... | ... | ...

There are 57 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within RansomHub. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during RansomHub. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/+CSCOE+/logon.html` | High
2 | File | `/.ssh/authorized_keys` | High
3 | File | `/?r=recruit/resume/edit&op=status` | High
4 | File | `/about.php` | Medium
5 | File | `/add-category.php` | High
6 | File | `/admin/` | Low
7 | File | `/admin/?page=user/list` | High
8 | File | `/admin/about-us.php` | High
9 | File | `/admin/aboutus.php` | High
10 | File | `/admin/action/add_con.php` | High
11 | File | `/admin/action/edit_chicken.php` | High
12 | File | `/admin/action/new-father.php` | High
13 | File | `/admin/action/new-feed.php` | High
14 | File | `/admin/add-category.php` | High
15 | File | `/admin/add_student.php` | High
16 | File | `/admin/add_teacher.php` | High
17 | File | `/admin/admin-profile.php` | High
18 | File | `/admin/app/product.php` | High
19 | File | `/admin/application-bwdates-reports-details.php` | High
20 | File | `/admin/article/article-edit-run.php` | High
21 | File | `/admin/clientview.php` | High
22 | File | `/admin/company/controller.php` | High
23 | File | `/admin/del_feedback.php` | High
24 | File | `/admin/edit-accepted-appointment.php` | High
25 | File | `/admin/edit-admin.php` | High
26 | File | `/admin/edit-services.php` | High
27 | File | `/admin/file_manage_view` | High
28 | File | `/admin/index.php` | High
29 | File | `/admin/invoice.php` | High
30 | File | `/admin/list_localuser.php` | High
31 | File | `/admin/login.php` | High
32 | File | `/admin/maintenance/brand.php` | High
33 | File | `/admin/makehtml_freelist_action.php` | High
34 | File | `/admin/manage-pages.php` | High
35 | File | `/admin/manage-users.php` | High
36 | File | `/admin/media.php?action=upload&sid=0` | High
37 | File | `/admin/pages/student-print.php` | High
38 | File | `/admin/profile.php` | High
39 | File | `/admin/regester.php` | High
40 | File | `/admin/search-vehicle.php` | High
41 | File | `/admin/student.php` | High
42 | File | `/admin/suppliers/view_details.php` | High
43 | File | `/admin/sys_sql_query.php` | High
44 | File | `/admin/vacancy/index.php` | High
45 | File | `/admins/{adminId}` | High
46 | File | `/admin_route/inc_service_credits.php` | High
47 | File | `/api.php` | Medium
48 | File | `/api/dept` | Medium
49 | File | `/api/jolokia org.jolokia.http.HttpRequestHandler#handlePostRequest` | High
50 | File | `/api/runscript` | High
51 | File | `/api/sys/login` | High
52 | File | `/api/sys/set_passwd` | High
53 | File | `/api/v1/public-chatflows/id` | High
54 | File | `/api/v1/terminal/sessions/?limit=1` | High
55 | File | `/app/admin/controller/Upload.php` | High
56 | File | `/app/api/controller/default/Sqlite.php` | High
57 | File | `/app/middleware/TokenVerify.php` | High
58 | File | `/application/index/controller/Databasesource.php` | High
59 | File | `/application/index/controller/File.php` | High
60 | File | `/application/index/controller/Icon.php` | High
61 | File | `/application/index/controller/Screen.php` | High
62 | File | `/application/index/controller/Unity.php` | High
63 | File | `/application/pay/controller/Api.php` | High
64 | File | `/application/plugins/controller/Upload.php` | High
65 | File | `/application/websocket/controller/Setting.php` | High
66 | File | `/apply/index.php` | High
67 | File | `/apps/login_auth.php` | High
68 | File | `/apps/system/api/user.go` | High
69 | File | `/assets/php/upload.php` | High
70 | File | `/auth/auth.php?user=1` | High
71 | File | `/b2b-supermarket/shopping-cart` | High
72 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
73 | File | `/backend/admin/his_admin_register_patient.php` | High
74 | File | `/bin/boa` | Medium
75 | File | `/blog/blog.php` | High
76 | File | `/boafrm/formFilter` | High
77 | File | `/boafrm/formMapDelDevice` | High
78 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
79 | File | `/cancel.php` | Medium
80 | File | `/cas/logout` | Medium
81 | ... | ... | ...

There are 710 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://darktrace.com/blog/ransomhub-ransomware-darktraces-investigation-of-the-newest-tool-in-shadowsyndicates-arsenal
* https://darktrace.com/blog/ransomhub-revisited-new-front-runner-in-the-ransomware-as-a-service-marketplace
* https://search.censys.io/hosts/162.252.173.12
* https://search.censys.io/hosts/185.33.86.15
* https://search.censys.io/hosts/185.219.220.175
* https://search.censys.io/hosts/193.203.49.90
* https://thedfirreport.com/2025/06/30/hide-your-rdp-password-spray-leads-to-ransomhub-deployment/
* https://threatfox.abuse.ch
* https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-242a
* https://www.guidepointsecurity.com/blog/ransomhub-affiliate-leverage-python-based-backdoor/
* https://www.reliaquest.com/blog/scattered-spider-x-ransomhub-a-new-partnership/
* https://www.trendmicro.com/en_us/research/24/i/how-ransomhub-ransomware-uses-edrkillshifter-to-disable-edr-and-.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
