# XenoRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [XenoRAT](https://vuldb.com/actor/xenorat). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/xenorat](https://vuldb.com/actor/xenorat)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with XenoRAT:

* [MY](https://vuldb.com/country/my)
* [US](https://vuldb.com/country/us)
* [DE](https://vuldb.com/country/de)
* ...

There are 11 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of XenoRAT.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [1.229.183.193](https://vuldb.com/ip/1.229.183.193) | - | - | High
2 | [2.58.85.196](https://vuldb.com/ip/2.58.85.196) | sunucuduragi.com | - | High
3 | [5.14.110.90](https://vuldb.com/ip/5.14.110.90) | 5-14-110-90.residential.rdsnet.ro | - | High
4 | [23.234.88.233](https://vuldb.com/ip/23.234.88.233) | static-23-234-88-233.cust.tzulo.com | - | High
5 | [27.102.138.166](https://vuldb.com/ip/27.102.138.166) | - | - | High
6 | [34.229.235.165](https://vuldb.com/ip/34.229.235.165) | ec2-34-229-235-165.compute-1.amazonaws.com | - | Medium
7 | [45.8.22.113](https://vuldb.com/ip/45.8.22.113) | - | - | High
8 | [45.32.188.16](https://vuldb.com/ip/45.32.188.16) | 45.32.188.16.vultrusercontent.com | - | Medium
9 | [45.66.231.63](https://vuldb.com/ip/45.66.231.63) | - | - | High
10 | [45.133.174.133](https://vuldb.com/ip/45.133.174.133) | - | - | High
11 | [45.141.215.75](https://vuldb.com/ip/45.141.215.75) | - | - | High
12 | [45.141.215.133](https://vuldb.com/ip/45.141.215.133) | exit-pl-004.tor.0xcc01.de | - | High
13 | [45.150.34.192](https://vuldb.com/ip/45.150.34.192) | - | - | High
14 | [49.194.29.240](https://vuldb.com/ip/49.194.29.240) | n49-194-29-240.per2.wa.optusnet.com.au | - | High
15 | ... | ... | ... | ...

There are 55 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _XenoRAT_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 17 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by XenoRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/.well-known/oauth-authorization-server` | High
2 | File | `/?page=user` | Medium
3 | File | `/accomodation.php` | High
4 | File | `/action.php` | Medium
5 | File | `/add-new-officer.php` | High
6 | File | `/add-office.php` | High
7 | File | `/addCandidate.php` | High
8 | File | `/addmem.php` | Medium
9 | File | `/addProduct.php` | High
10 | File | `/addrecord.php` | High
11 | File | `/add_librarian.php` | High
12 | File | `/add_member.php` | High
13 | File | `/add_query_reserve.php` | High
14 | File | `/add_result.php` | High
15 | File | `/add_to_cart` | Medium
16 | File | `/admin-cp/file-manager/upload` | High
17 | File | `/admin.php` | Medium
18 | File | `/admin.php?id=inbox` | High
19 | File | `/admin/` | Low
20 | File | `/admin/?page=city` | High
21 | File | `/admin/?page=establishment` | High
22 | File | `/admin/?page=people` | High
23 | File | `/admin/?page=state` | High
24 | File | `/admin/?page=system_info` | High
25 | File | `/admin/?page=system_info/contact_info` | High
26 | File | `/admin/?page=user` | High
27 | File | `/admin/?page=zone` | High
28 | File | `/admin/add-module.php` | High
29 | File | `/Admin/additems.php` | High
30 | File | `/admin/add_account.php` | High
31 | File | `/admin/add_admin.php` | High
32 | File | `/admin/add_area.php` | High
33 | File | `/admin/add_category.php` | High
34 | File | `/admin/add_distributor.php` | High
35 | File | `/admin/add_payroll.php` | High
36 | File | `/admin/add_product.php` | High
37 | File | `/admin/add_retailer.php` | High
38 | File | `/admin/add_unit.php` | High
39 | File | `/admin/admin_edit_menu_action.php` | High
40 | File | `/admin/admin_feature.php` | High
41 | File | `/admin/admin_football.php` | High
42 | File | `/admin/admin_index.php` | High
43 | File | `/admin/admin_product.ph` | High
44 | File | `/admin/admin_running.php` | High
45 | File | `/admin/app/login_crud.php` | High
46 | File | `/admin/archives_add.php` | High
47 | File | `/admin/articles/add` | High
48 | File | `/admin/blog/comment/create` | High
49 | File | `/admin/bwdates-reports-details.php` | High
50 | File | `/admin/category/controller.php` | High
51 | File | `/Admin/changepassword.php` | High
52 | File | `/admin/checklogin.php` | High
53 | File | `/admin/cms/category/addtitle` | High
54 | File | `/admin/cms/material/add` | High
55 | File | `/admin/code/tce_edit_group.php` | High
56 | File | `/Admin/Controller/CustomController.class.php` | High
57 | File | `/admin/create_product.php` | High
58 | File | `/admin/customer-list.php` | High
59 | File | `/admin/customermanagementframework/customers/list` | High
60 | File | `/admin/deletemanager.php` | High
61 | File | `/admin/deletemanagerclinic.php` | High
62 | File | `/admin/delete_pending.php` | High
63 | File | `/admin/delete_student.php` | High
64 | File | `/admin/delete_user.php` | High
65 | File | `/admin/editsite.php` | High
66 | File | `/admin/edit_account.php` | High
67 | File | `/admin/edit_admin_query.php` | High
68 | File | `/admin/freelist_main.php` | High
69 | File | `/admin/index.php` | High
70 | File | `/admin/index.php/advtext/add` | High
71 | File | `/admin/index.php/datafile/delfile` | High
72 | File | `/admin/index.php/datafile/download` | High
73 | File | `/admin/invoiceprint.php` | High
74 | File | `/admin/login.php` | High
75 | File | `/admin/login_query.php` | High
76 | File | `/admin/manage-users.php` | High
77 | File | `/admin/newsletterdel.php` | High
78 | File | `/admin/products/index.php?view=add` | High
79 | File | `/admin/products/index.php?view=edit` | High
80 | File | `/admin/quesadd.php` | High
81 | File | `/admin/receipt.php` | High
82 | File | `/Admin/registration.php` | High
83 | File | `/admin/reservation.php` | High
84 | File | `/admin/reset-password.php` | High
85 | File | `/admin/roombook.php` | High
86 | File | `/admin/roomdel.php` | High
87 | File | `/admin/save_student.php` | High
88 | File | `/admin/save_user.php` | High
89 | File | `/admin/search-invoices.php` | High
90 | File | `/admin/search.php` | High
91 | File | `/admin/search1.php` | High
92 | File | `/admin/siteconfig.php` | High
93 | File | `/admin/spec_add.php` | High
94 | File | `/admin/stateadd.php` | High
95 | File | `/admin/templets_one_edit.php` | High
96 | File | `/admin/update-image1.php` | High
97 | File | `/admin/update-progress.php` | High
98 | File | `/admin/update_s7.php` | High
99 | File | `/admin/update_student.php` | High
100 | File | `/admin/update_user.php` | High
101 | File | `/admin/user-bookings.php` | High
102 | File | `/admin/user/index.php?view=edit` | High
103 | File | `/admin/useragentdelete.php` | High
104 | File | `/admin/userbuilderdelete.php` | High
105 | File | `/admin/userdelete.php` | High
106 | File | `/admin/usersetting.php` | High
107 | File | `/admin/usersettingdel.php` | High
108 | File | `/admin/view-appointment.php` | High
109 | File | `/admin/view-member-report.php` | High
110 | File | `/admin/view-progress-report.php` | High
111 | File | `/admin/view_products.php` | High
112 | File | `/admin/view_unit.php` | High
113 | File | `/admin/wangkan_list.php` | High
114 | File | `/admin79f2ec220c7e.php?c=api&m=demo&name=mobile` | High
115 | ... | ... | ...

There are 1015 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://bazaar.abuse.ch/sample/c8ed2f537f20c0085836325c810c2603be6b29251ece8c9f8e2e8873ba5b23e5/
* https://netresec.com/?b=258f641
* https://threatfox.abuse.ch
* https://urlhaus.abuse.ch/url/3522571/
* https://urlhaus.abuse.ch/url/3584881/
* https://urlhaus.abuse.ch/url/3696637/
* https://urlhaus.abuse.ch/url/3730045/
* https://urlhaus.abuse.ch/url/3753481/
* https://urlhaus.abuse.ch/url/3765315/
* https://www.threat.rip/file/35f630210dee3ce3fd8bcacc563359429faaea0f9887935641d0ba13d925fce2/config
* https://www.virustotal.com/gui/file/b07dd7e831fe0a30ac139bb29d9ac836f0fb1e1034f4e00ad62f427423bc5a7f
* https://x.com/malwrhunterteam/status/1891402914024882374

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
