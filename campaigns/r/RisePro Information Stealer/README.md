# RisePro Information Stealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _RisePro Information Stealer_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RisePro Information Stealer:

* [MY](https://vuldb.com/country/my)
* [LA](https://vuldb.com/country/la)
* [US](https://vuldb.com/country/us)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with RisePro Information Stealer or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Russia Unknown](https://vuldb.com/actor/russia_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RisePro Information Stealer.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [5.42.92.73](https://vuldb.com/ip/5.42.92.73) | hosted-by.yeezyhost.net | [Russia Unknown](https://vuldb.com/actor/russia_unknown) | High
2 | [37.120.237.196](https://vuldb.com/ip/37.120.237.196) | - | [Russia Unknown](https://vuldb.com/actor/russia_unknown) | High
3 | [77.91.77.81](https://vuldb.com/ip/77.91.77.81) | plastic.aeza.network | [Russia Unknown](https://vuldb.com/actor/russia_unknown) | High
4 | ... | ... | ... | ...

There are 9 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within RisePro Information Stealer. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during RisePro Information Stealer. This data is unique as it uses our predictive model for actor profiling.

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
41 | File | `/admin/app/profile_crud.php` | High
42 | File | `/admin/archives_add.php` | High
43 | File | `/admin/articles/add` | High
44 | File | `/admin/blog/comment/create` | High
45 | File | `/admin/bwdates-reports-details.php` | High
46 | File | `/Admin/changepassword.php` | High
47 | File | `/admin/checklogin.php` | High
48 | File | `/admin/cms/category/addtitle` | High
49 | File | `/admin/cms/material/add` | High
50 | File | `/Admin/Controller/CustomController.class.php` | High
51 | File | `/admin/customer-list.php` | High
52 | File | `/admin/deletemanager.php` | High
53 | File | `/admin/deletemanagerclinic.php` | High
54 | File | `/admin/delete_student.php` | High
55 | File | `/admin/delete_user.php` | High
56 | File | `/admin/dl_sendmail.php` | High
57 | File | `/admin/editsite.php` | High
58 | File | `/admin/edit_account.php` | High
59 | File | `/admin/edit_admin_query.php` | High
60 | File | `/admin/file_manager/export` | High
61 | File | `/admin/freelist_main.php` | High
62 | File | `/admin/index.php` | High
63 | File | `/admin/index.php/advtext/add` | High
64 | File | `/admin/index.php/datafile/delfile` | High
65 | File | `/admin/index.php/datafile/download` | High
66 | File | `/admin/index2.html` | High
67 | File | `/admin/invoiceprint.php` | High
68 | File | `/admin/login.php` | High
69 | File | `/admin/login_query.php` | High
70 | File | `/admin/newsletterdel.php` | High
71 | File | `/admin/products/index.php?view=add` | High
72 | File | `/admin/products/index.php?view=edit` | High
73 | File | `/admin/quesadd.php` | High
74 | File | `/admin/receipt.php` | High
75 | File | `/admin/reservation.php` | High
76 | File | `/admin/reset-password.php` | High
77 | File | `/admin/roombook.php` | High
78 | File | `/admin/roomdel.php` | High
79 | File | `/admin/save_student.php` | High
80 | File | `/admin/save_user.php` | High
81 | File | `/admin/search-invoices.php` | High
82 | File | `/admin/search.php` | High
83 | File | `/admin/search1.php` | High
84 | File | `/admin/siteconfig.php` | High
85 | File | `/admin/spec_add.php` | High
86 | File | `/admin/stateadd.php` | High
87 | File | `/admin/templets_one_edit.php` | High
88 | File | `/admin/update-progress.php` | High
89 | File | `/admin/update_student.php` | High
90 | File | `/admin/update_user.php` | High
91 | File | `/admin/user-bookings.php` | High
92 | File | `/admin/user/index.php?view=edit` | High
93 | File | `/admin/useragentdelete.php` | High
94 | File | `/admin/userbuilderdelete.php` | High
95 | File | `/admin/userdelete.php` | High
96 | File | `/admin/usersetting.php` | High
97 | File | `/admin/usersettingdel.php` | High
98 | File | `/admin/view-appointment.php` | High
99 | File | `/admin/view-member-report.php` | High
100 | File | `/admin/view-progress-report.php` | High
101 | File | `/admin/view_products.php` | High
102 | File | `/admin/view_unit.php` | High
103 | File | `/admin/wangkan_list.php` | High
104 | File | `/admin79f2ec220c7e.php?c=api&m=demo&name=mobile` | High
105 | File | `/admind45f74adbd95.php?c=email&m=add` | High
106 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=0` | High
107 | File | `/admind45f74adbd95.php?c=field&m=add&rname=site&rid=1&page=1` | High
108 | File | `/admindetail.php?action=edit` | High
109 | File | `/adminlogin.php` | High
110 | File | `/adminPage/conf/reload` | High
111 | File | `/admin_area/index.php` | High
112 | File | `/admin_class.php` | High
113 | File | `/admin_delete.php` | High
114 | File | `/admin_topic.php?action=delall` | High
115 | File | `/advisers.php` | High
116 | File | `/ajax.php` | Medium
117 | ... | ... | ...

There are 1038 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://blogs.blackberry.com/en/2024/06/threat-analysis-insight-risepro-information-stealer

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
