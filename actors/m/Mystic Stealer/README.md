# Mystic Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [Mystic Stealer](https://vuldb.com/actor/mystic_stealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/mystic_stealer](https://vuldb.com/actor/mystic_stealer)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Mystic Stealer:

* [MY](https://vuldb.com/country/my)
* [US](https://vuldb.com/country/us)
* [LA](https://vuldb.com/country/la)
* ...

There are 9 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Mystic Stealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [3.111.145.27](https://vuldb.com/ip/3.111.145.27) | ec2-3-111-145-27.ap-south-1.compute.amazonaws.com | - | Medium
2 | [5.42.64.18](https://vuldb.com/ip/5.42.64.18) | - | - | High
3 | [5.42.64.20](https://vuldb.com/ip/5.42.64.20) | - | - | High
4 | [5.42.65.126](https://vuldb.com/ip/5.42.65.126) | - | - | High
5 | [5.42.92.43](https://vuldb.com/ip/5.42.92.43) | hosted-by.yeezyhost.net | - | High
6 | [5.42.92.88](https://vuldb.com/ip/5.42.92.88) | hosted-by.yeezyhost.net | - | High
7 | [5.42.92.211](https://vuldb.com/ip/5.42.92.211) | . | - | High
8 | [5.42.94.125](https://vuldb.com/ip/5.42.94.125) | juicy-milk.aeza.network | - | High
9 | [5.75.183.169](https://vuldb.com/ip/5.75.183.169) | static.169.183.75.5.clients.your-server.de | - | High
10 | [5.188.87.45](https://vuldb.com/ip/5.188.87.45) | - | - | High
11 | [5.196.93.222](https://vuldb.com/ip/5.196.93.222) | 934.gra.abcvg.ovh | - | High
12 | [13.200.127.74](https://vuldb.com/ip/13.200.127.74) | ec2-13-200-127-74.ap-south-1.compute.amazonaws.com | - | Medium
13 | [13.208.166.206](https://vuldb.com/ip/13.208.166.206) | ec2-13-208-166-206.ap-northeast-3.compute.amazonaws.com | - | Medium
14 | [13.232.156.210](https://vuldb.com/ip/13.232.156.210) | ec2-13-232-156-210.ap-south-1.compute.amazonaws.com | - | Medium
15 | [23.163.0.179](https://vuldb.com/ip/23.163.0.179) | mail.pnet-asp.tech | - | High
16 | [34.88.245.41](https://vuldb.com/ip/34.88.245.41) | 41.245.88.34.bc.googleusercontent.com | - | Medium
17 | [37.139.129.70](https://vuldb.com/ip/37.139.129.70) | - | - | High
18 | [41.208.73.44](https://vuldb.com/ip/41.208.73.44) | 41.208.73.44.static.ltt.ly | - | High
19 | ... | ... | ... | ...

There are 71 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Mystic Stealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Mystic Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.well-known/oauth-authorization-server` | High
2 | File | `/?page=user` | Medium
3 | File | `/action.php` | Medium
4 | File | `/add-new-officer.php` | High
5 | File | `/add-office.php` | High
6 | File | `/addCandidate.php` | High
7 | File | `/addmem.php` | Medium
8 | File | `/addProduct.php` | High
9 | File | `/addrecord.php` | High
10 | File | `/add_librarian.php` | High
11 | File | `/add_member.php` | High
12 | File | `/add_query_reserve.php` | High
13 | File | `/add_to_cart` | Medium
14 | File | `/admin.php` | Medium
15 | File | `/admin.php?id=inbox` | High
16 | File | `/admin/` | Low
17 | File | `/admin/?page=city` | High
18 | File | `/admin/?page=establishment` | High
19 | File | `/admin/?page=people` | High
20 | File | `/admin/?page=state` | High
21 | File | `/admin/?page=system_info` | High
22 | File | `/admin/?page=user` | High
23 | File | `/admin/?page=zone` | High
24 | File | `/admin/add-module.php` | High
25 | File | `/Admin/additems.php` | High
26 | File | `/admin/add_account.php` | High
27 | File | `/admin/add_admin.php` | High
28 | File | `/admin/add_area.php` | High
29 | File | `/admin/add_category.php` | High
30 | File | `/admin/add_distributor.php` | High
31 | File | `/admin/add_payroll.php` | High
32 | File | `/admin/add_product.php` | High
33 | File | `/admin/add_retailer.php` | High
34 | File | `/admin/add_unit.php` | High
35 | File | `/admin/admin_feature.php` | High
36 | File | `/admin/admin_football.php` | High
37 | File | `/admin/admin_index.php` | High
38 | File | `/admin/admin_product.ph` | High
39 | File | `/admin/admin_running.php` | High
40 | File | `/admin/app/login_crud.php` | High
41 | File | `/admin/archives_add.php` | High
42 | File | `/admin/articles/add` | High
43 | File | `/admin/blog/comment/create` | High
44 | File | `/admin/bwdates-reports-details.php` | High
45 | File | `/Admin/changepassword.php` | High
46 | File | `/admin/checklogin.php` | High
47 | File | `/admin/cms/category/addtitle` | High
48 | File | `/admin/cms/material/add` | High
49 | File | `/Admin/Controller/CustomController.class.php` | High
50 | File | `/admin/customer-list.php` | High
51 | File | `/admin/deletemanager.php` | High
52 | File | `/admin/deletemanagerclinic.php` | High
53 | File | `/admin/delete_student.php` | High
54 | File | `/admin/delete_user.php` | High
55 | File | `/admin/editsite.php` | High
56 | File | `/admin/edit_account.php` | High
57 | File | `/admin/edit_admin_query.php` | High
58 | File | `/admin/file_manager/export` | High
59 | File | `/admin/freelist_main.php` | High
60 | File | `/admin/index.php` | High
61 | File | `/admin/index.php/advtext/add` | High
62 | File | `/admin/index.php/datafile/delfile` | High
63 | File | `/admin/index.php/datafile/download` | High
64 | File | `/admin/index2.html` | High
65 | File | `/admin/invoiceprint.php` | High
66 | File | `/admin/login.php` | High
67 | File | `/admin/login_query.php` | High
68 | File | `/admin/manage-ambulance.php` | High
69 | File | `/admin/newsletterdel.php` | High
70 | File | `/admin/products/index.php?view=add` | High
71 | File | `/admin/products/index.php?view=edit` | High
72 | File | `/admin/quesadd.php` | High
73 | File | `/admin/receipt.php` | High
74 | File | `/admin/reservation.php` | High
75 | File | `/admin/reset-password.php` | High
76 | File | `/admin/roombook.php` | High
77 | File | `/admin/roomdel.php` | High
78 | File | `/admin/save_student.php` | High
79 | File | `/admin/save_user.php` | High
80 | File | `/admin/search-invoices.php` | High
81 | File | `/admin/search.php` | High
82 | File | `/admin/search1.php` | High
83 | File | `/admin/siteconfig.php` | High
84 | File | `/admin/spec_add.php` | High
85 | File | `/admin/stateadd.php` | High
86 | File | `/admin/templets_one_edit.php` | High
87 | File | `/admin/update-progress.php` | High
88 | File | `/admin/update_student.php` | High
89 | File | `/admin/update_user.php` | High
90 | File | `/admin/user-bookings.php` | High
91 | File | `/admin/user/index.php?view=edit` | High
92 | File | `/admin/useragentdelete.php` | High
93 | File | `/admin/userbuilderdelete.php` | High
94 | File | `/admin/userdelete.php` | High
95 | File | `/admin/usersetting.php` | High
96 | File | `/admin/usersettingdel.php` | High
97 | File | `/admin/view-appointment.php` | High
98 | File | `/admin/view-member-report.php` | High
99 | File | `/admin/view-progress-report.php` | High
100 | File | `/admin/view_products.php` | High
101 | File | `/admin/view_unit.php` | High
102 | File | `/admin/wangkan_list.php` | High
103 | ... | ... | ...

There are 908 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/3bfdcee7-1163-4cb5-a421-c89ebe581fb3
* https://app.any.run/tasks/6a907458-4ae2-4bbf-a4cd-120e7c7c5b60
* https://app.any.run/tasks/83e1bcf1-7e3f-46d1-b87f-9dc761b34cd0
* https://app.any.run/tasks/342f5538-7e82-4f54-908e-18efa2cc2669
* https://app.any.run/tasks/b15ddaaf-9197-4310-af15-d2f45ef44c91
* https://app.any.run/tasks/d1a96aea-a514-4f86-acd7-e9391a8ec959
* https://blog.pulsedive.com/identifying-mystic-stealer-control-panels/
* https://github.com/threatlabz/iocs/blob/main/mystic_stealer/c2s.txt
* https://pulsedive.com/threat/Mystic%20Stealer
* https://threatfox.abuse.ch
* https://www.zscaler.com/blogs/security-research/mystic-stealer
* https://x.com/Xanderuxsf5/status/1940324451046031670

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
