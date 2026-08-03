# OpBlueRaven - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _OpBlueRaven_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with OpBlueRaven:

* [RU](https://vuldb.com/country/ru)
* [US](https://vuldb.com/country/us)
* [CN](https://vuldb.com/country/cn)
* ...

There are 13 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with OpBlueRaven or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [FIN7](https://vuldb.com/actor/fin7) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of OpBlueRaven.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.252.177.23](https://vuldb.com/ip/5.252.177.23) | 5-252-177-23.mivocloud.com | [FIN7](https://vuldb.com/actor/fin7) | High
2 | [5.252.177.37](https://vuldb.com/ip/5.252.177.37) | no-rdns.mivocloud.com | [FIN7](https://vuldb.com/actor/fin7) | High
3 | [23.83.133.119](https://vuldb.com/ip/23.83.133.119) | - | [FIN7](https://vuldb.com/actor/fin7) | High
4 | [37.1.211.239](https://vuldb.com/ip/37.1.211.239) | ourdrops.org | [FIN7](https://vuldb.com/actor/fin7) | High
5 | [37.1.215.4](https://vuldb.com/ip/37.1.215.4) | - | [FIN7](https://vuldb.com/actor/fin7) | High
6 | [37.1.215.72](https://vuldb.com/ip/37.1.215.72) | - | [FIN7](https://vuldb.com/actor/fin7) | High
7 | [37.252.4.131](https://vuldb.com/ip/37.252.4.131) | - | [FIN7](https://vuldb.com/actor/fin7) | High
8 | [45.77.60.230](https://vuldb.com/ip/45.77.60.230) | 45.77.60.230.vultr.com | [FIN7](https://vuldb.com/actor/fin7) | Medium
9 | [45.77.204.130](https://vuldb.com/ip/45.77.204.130) | 45.77.204.130.vultr.com | [FIN7](https://vuldb.com/actor/fin7) | Medium
10 | [45.87.152.64](https://vuldb.com/ip/45.87.152.64) | free.pq.hosting | [FIN7](https://vuldb.com/actor/fin7) | High
11 | [45.133.216.25](https://vuldb.com/ip/45.133.216.25) | lisulisimp.example.com | [FIN7](https://vuldb.com/actor/fin7) | High
12 | ... | ... | ... | ...

There are 44 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74, CWE-643 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during OpBlueRaven. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?p=products` | Medium
2 | File | `/?r=recruit/resume/edit&op=status` | High
3 | File | `/account/delivery` | High
4 | File | `/admin/` | Low
5 | File | `/admin/?page=user/list` | High
6 | File | `/admin/about-us.php` | High
7 | File | `/admin/action/add_con.php` | High
8 | File | `/admin/action/edit_chicken.php` | High
9 | File | `/admin/action/new-father.php` | High
10 | File | `/admin/action/new-feed.php` | High
11 | File | `/admin/add-category.php` | High
12 | File | `/admin/admin-profile.php` | High
13 | File | `/admin/api/theme-edit/` | High
14 | File | `/admin/app/product.php` | High
15 | File | `/admin/application-bwdates-reports-details.php` | High
16 | File | `/admin/article/article-edit-run.php` | High
17 | File | `/admin/attendance_row.php` | High
18 | File | `/admin/cashadvance_row.php` | High
19 | File | `/admin/clientview.php` | High
20 | File | `/admin/company/controller.php` | High
21 | File | `/admin/deduction_row.php` | High
22 | File | `/admin/del_feedback.php` | High
23 | File | `/admin/edit-accepted-appointment.php` | High
24 | File | `/admin/edit-admin.php` | High
25 | File | `/admin/edit-services.php` | High
26 | File | `/admin/employee_row.php` | High
27 | File | `/admin/index2.html` | High
28 | File | `/admin/invoice.php` | High
29 | File | `/admin/list_localuser.php` | High
30 | File | `/admin/login.php` | High
31 | File | `/admin/maintenance/brand.php` | High
32 | File | `/admin/maintenance/view_designation.php` | High
33 | File | `/admin/makehtml_freelist_action.php` | High
34 | File | `/admin/manage-users.php` | High
35 | File | `/admin/pages/student-print.php` | High
36 | File | `/admin/read.php?mudi=getSignal` | High
37 | File | `/admin/regester.php` | High
38 | File | `/admin/suppliers/view_details.php` | High
39 | File | `/admin/sys_sql_query.php` | High
40 | File | `/admin/vacancy/index.php` | High
41 | File | `/admin_route/inc_service_credits.php` | High
42 | File | `/ajax.php?action=read_msg` | High
43 | File | `/api.php` | Medium
44 | File | `/api/baskets/{name}` | High
45 | File | `/api/sys/login` | High
46 | File | `/api/sys/set_passwd` | High
47 | File | `/api/wechat/app_auth` | High
48 | File | `/app/api/controller/default/Sqlite.php` | High
49 | File | `/app/middleware/TokenVerify.php` | High
50 | File | `/application/index/controller/Databasesource.php` | High
51 | File | `/application/index/controller/File.php` | High
52 | File | `/application/index/controller/Icon.php` | High
53 | File | `/application/index/controller/Screen.php` | High
54 | File | `/application/index/controller/Unity.php` | High
55 | File | `/application/pay/controller/Api.php` | High
56 | File | `/application/plugins/controller/Upload.php` | High
57 | File | `/application/websocket/controller/Setting.php` | High
58 | File | `/apply.cgi` | Medium
59 | File | `/apply/index.php` | High
60 | File | `/apps/login_auth.php` | High
61 | File | `/apps/system/api/user.go` | High
62 | File | `/App_Resource/UEditor/server/upload.aspx` | High
63 | File | `/assets/php/upload.php` | High
64 | File | `/auth/auth.php?user=1` | High
65 | File | `/author/list?limit=10&offset=0&order=desc` | High
66 | File | `/b2b-supermarket/shopping-cart` | High
67 | File | `/backend/admin/his_admin_register_patient.php` | High
68 | File | `/bin/boa` | Medium
69 | File | `/blog` | Low
70 | File | `/boafrm/formFilter` | High
71 | File | `/boafrm/formMapDelDevice` | High
72 | File | `/browse` | Low
73 | File | `/bsms_ci/index.php` | High
74 | File | `/building/backmgr/urlpage/mobileurl/configfile/jx2_config.ini` | High
75 | File | `/cancel.php` | Medium
76 | File | `/cas/logout` | Medium
77 | File | `/cgi-bin/cstecgi.cgi` | High
78 | File | `/cgi-bin/cstecgi.cgi?action=login` | High
79 | File | `/cgi-bin/nas_sharing.cgi` | High
80 | File | `/cgi-bin/wlogin.cgi` | High
81 | File | `/chaincity/user/ticket/create` | High
82 | File | `/classes/Master.php?f=delete_category` | High
83 | File | `/classes/Master.php?f=delete_sub_category` | High
84 | File | `/classes/Users.php?f=save` | High
85 | File | `/cloudstore/ecode/setup/ecology_dev.zip` | High
86 | File | `/collection/all` | High
87 | File | `/common/info.cgi` | High
88 | File | `/company/store` | High
89 | File | `/config/pw_changeusers.html` | High
90 | ... | ... | ...

There are 796 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/prodaft/malware-ioc/tree/master/OpBlueRaven

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
