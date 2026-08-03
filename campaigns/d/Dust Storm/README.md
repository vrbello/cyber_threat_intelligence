# Dust Storm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Dust Storm_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dust Storm:

* [CN](https://vuldb.com/country/cn)
* [US](https://vuldb.com/country/us)

## Actors

These _actors_ are associated with Dust Storm or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Dust Storm](https://vuldb.com/actor/dust_storm) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dust Storm.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [6.9.2.1](https://vuldb.com/ip/6.9.2.1) | - | [Dust Storm](https://vuldb.com/actor/dust_storm) | High
2 | [23.238.229.128](https://vuldb.com/ip/23.238.229.128) | - | [Dust Storm](https://vuldb.com/actor/dust_storm) | High
3 | [27.255.72.68](https://vuldb.com/ip/27.255.72.68) | - | [Dust Storm](https://vuldb.com/actor/dust_storm) | High
4 | [27.255.72.69](https://vuldb.com/ip/27.255.72.69) | - | [Dust Storm](https://vuldb.com/actor/dust_storm) | High
5 | [27.255.72.78](https://vuldb.com/ip/27.255.72.78) | - | [Dust Storm](https://vuldb.com/actor/dust_storm) | High
6 | [59.120.59.2](https://vuldb.com/ip/59.120.59.2) | 59-120-59-2.hinet-ip.hinet.net | [Dust Storm](https://vuldb.com/actor/dust_storm) | High
7 | [59.188.13.133](https://vuldb.com/ip/59.188.13.133) | - | [Dust Storm](https://vuldb.com/actor/dust_storm) | High
8 | ... | ... | ... | ...

There are 27 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Dust Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Dust Storm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?r=recruit/resume/edit&op=status` | High
2 | File | `/a/` | Low
3 | File | `/a/sys/user/save` | High
4 | File | `/abs.php` | Medium
5 | File | `/action.php` | Medium
6 | File | `/add-normal-ticket.php` | High
7 | File | `/addpro.php` | Medium
8 | File | `/add_drive.php` | High
9 | File | `/add_new_supplier.php` | High
10 | File | `/add_personal_details.php` | High
11 | File | `/add_user.php` | High
12 | File | `/admin#article/edit?id=2` | High
13 | File | `/admin.php?id=inbox` | High
14 | File | `/Admin/add-admin.php` | High
15 | File | `/admin/add-category.php` | High
16 | File | `/admin/add-services.php` | High
17 | File | `/admin/add-student.php` | High
18 | File | `/admin/add-subadmin.php` | High
19 | File | `/admin/addpackage.php` | High
20 | File | `/admin/addroom.php` | High
21 | File | `/admin/add_candidate_modal.php.` | High
22 | File | `/admin/admin_football.php` | High
23 | File | `/admin/admin_running.php` | High
24 | File | `/admin/allemployees.php` | High
25 | File | `/admin/archives_add.php` | High
26 | File | `/admin/article.php` | High
27 | File | `/admin/booking-search.php` | High
28 | File | `/admin/bwdates-report-result.php` | High
29 | File | `/admin/bwdates-reports-details.php` | High
30 | File | `/admin/change-password.php` | High
31 | File | `/admin/combo.php` | High
32 | File | `/admin/comment/list` | High
33 | File | `/admin/contactus.php` | High
34 | File | `/admin/content/book` | High
35 | File | `/Admin/Controller/CustomController.class.php` | High
36 | File | `/Admin/createClass.php` | High
37 | File | `/admin/delete_judge.php` | High
38 | File | `/admin/delete_student.php` | High
39 | File | `/admin/edit-category-detail.php` | High
40 | File | `/admin/edit-propertytype.php` | High
41 | File | `/admin/edit-user-profile.php` | High
42 | File | `/Admin/EditCity.php` | High
43 | File | `/admin/edit_class.php` | High
44 | File | `/admin/edit_customer.php` | High
45 | File | `/admin/edit_product.php` | High
46 | File | `/admin/edit_room.php` | High
47 | File | `/admin/educloud/videobind.html` | High
48 | File | `/admin/forgot-password.php` | High
49 | File | `/admin/goods/update` | High
50 | File | `/Admin/Http/Controllers/FileManagerController.php` | High
51 | File | `/admin/index.php` | High
52 | File | `/admin/index.php?r=banner%2Fbanner-create` | High
53 | File | `/admin/login` | Medium
54 | File | `/admin/login.php` | High
55 | File | `/admin/maintenance/manage_department.php` | High
56 | File | `/admin/manage-services.php` | High
57 | File | `/admin/member_save.php` | High
58 | File | `/admin/operations/travellers.php` | High
59 | File | `/admin/product.php` | High
60 | File | `/admin/readenq.php` | High
61 | File | `/admin/registered-users.php` | High
62 | File | `/admin/save_student.php` | High
63 | File | `/admin/search-pass.php` | High
64 | File | `/admin/sms_setting.php` | High
65 | File | `/admin/student-registration.php` | High
66 | File | `/admin/subscriber-csv.php` | High
67 | File | `/admin/sys/admin.html` | High
68 | File | `/admin/twitter.php` | High
69 | File | `/admin/update_room.php` | High
70 | File | `/admin/update_s8.php` | High
71 | File | `/Admin/User.php` | High
72 | File | `/admin/user.php` | High
73 | File | `/admin/user/manage_user.php` | High
74 | File | `/admin/userdelete.php` | High
75 | File | `/admin/userlist.php` | High
76 | File | `/admin/view-enquiry.php` | High
77 | File | `/admin/view_unit.php` | High
78 | File | `/admin/voters_delete.php` | High
79 | File | `/Administrator/PHP/AdminDeleteCategory.php` | High
80 | File | `/adplanet/PlanetUser` | High
81 | File | `/adposition/queryAll` | High
82 | File | `/agent/profile/edit` | High
83 | File | `/ajax.php?action=delete_category` | High
84 | File | `/ajax.php?action=delete_product` | High
85 | File | `/ajax.php?action=delete_receiving` | High
86 | File | `/ajax.php?action=delete_sales` | High
87 | File | `/ajax.php?action=delete_user` | High
88 | File | `/ajax.php?action=save_company` | High
89 | File | `/ajax.php?action=save_plan` | High
90 | File | `/ajax/action.php` | High
91 | File | `/api/admin/system/store/order/list` | High
92 | File | `/api/backend/ext/import-data/import-channel` | High
93 | File | `/api/code/upload` | High
94 | File | `/api/easyquery/models/nwind/fetch` | High
95 | File | `/api/front/search/books` | High
96 | File | `/api/login/auth` | High
97 | File | `/api/system/user/getAvatar` | High
98 | File | `/Api/TinyMce/UploadAjax.ashx` | High
99 | File | `/api/users/updateEmail/` | High
100 | File | `/api/v2/open/rowsInfo` | High
101 | File | `/api/v2/open/tablesInfo` | High
102 | File | `/app-api/v1/orders/` | High
103 | File | `/app/admin/controller/Images.php` | High
104 | File | `/app/api/v1/openvpn.py` | High
105 | File | `/app/Http/Controllers/ImageController.php` | High
106 | File | `/app/sys/article/optimize` | High
107 | File | `/application/pay/controller/Index.php` | High
108 | File | `/applyleave.php` | High
109 | File | `/authentication.cgi` | High
110 | File | `/backend/admin/his_admin_register_patient.php` | High
111 | File | `/bank/statements.php` | High
112 | File | `/base/safe_setting/` | High
113 | File | `/billing/test_accesscodelogin.php` | High
114 | File | `/bin/httpd` | Medium
115 | File | `/bishe/register` | High
116 | File | `/bmp-account-detail/` | High
117 | File | `/boaform/formPing` | High
118 | ... | ... | ...

There are 1042 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.threatminer.org/report.php?q=Op_Dust_Storm_Report.pdf&y=2016

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
