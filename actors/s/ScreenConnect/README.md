# ScreenConnect - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [ScreenConnect](https://vuldb.com/actor/screenconnect). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/screenconnect](https://vuldb.com/actor/screenconnect)

## Campaigns

The following _campaigns_ are known and can be associated with ScreenConnect:

* Fake ClawdBot Agent VS Code Extension

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ScreenConnect:

* [US](https://vuldb.com/country/us)
* [SH](https://vuldb.com/country/sh)
* [CH](https://vuldb.com/country/ch)
* ...

There are 15 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ScreenConnect.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.101.82.22](https://vuldb.com/ip/5.101.82.22) | vm38432.hyper.hosting | - | High
2 | [23.94.153.157](https://vuldb.com/ip/23.94.153.157) | 23-94-153-157-host.colocrossing.com | - | High
3 | [23.95.173.124](https://vuldb.com/ip/23.95.173.124) | 23-95-173-124-host.colocrossing.com | - | High
4 | [31.57.147.191](https://vuldb.com/ip/31.57.147.191) | - | - | High
5 | [31.129.22.45](https://vuldb.com/ip/31.129.22.45) | 106558.ip-ptr.tech | - | High
6 | [38.240.58.33](https://vuldb.com/ip/38.240.58.33) | - | - | High
7 | [45.13.237.121](https://vuldb.com/ip/45.13.237.121) | 121.237.13.45.in-addr.arpa | - | High
8 | [45.83.31.75](https://vuldb.com/ip/45.83.31.75) | - | - | High
9 | [45.88.186.54](https://vuldb.com/ip/45.88.186.54) | - | - | High
10 | [45.88.186.67](https://vuldb.com/ip/45.88.186.67) | - | - | High
11 | [45.138.16.87](https://vuldb.com/ip/45.138.16.87) | 45.138.16.87.powered.by.rdp.sh | - | High
12 | ... | ... | ... | ...

There are 44 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _ScreenConnect_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by ScreenConnect. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `- src/main/java/com/rymcu/forest/web/api/user/UserInfoController.java` | High
2 | File | `/?explorer/index/zip` | High
3 | File | `/action.php` | Medium
4 | File | `/activation.php` | High
5 | File | `/add-pig.php` | Medium
6 | File | `/addcat.php` | Medium
7 | File | `/addmem.php` | Medium
8 | File | `/add_command` | Medium
9 | File | `/add_result.php` | High
10 | File | `/add_stock.php` | High
11 | File | `/admin-api/mp/material/upload-news-image` | High
12 | File | `/admin-api/system/tenant/get-by-website` | High
13 | File | `/admin/?page=state` | High
14 | File | `/admin/?page=zone` | High
15 | File | `/admin/aboutus.php` | High
16 | File | `/admin/actions/check-attendance.php` | High
17 | File | `/admin/Add%20notice/notice.php` | High
18 | File | `/admin/add-category.php` | High
19 | File | `/admin/add-table.php` | High
20 | File | `/admin/adddoctor.php` | High
21 | File | `/admin/addpackage.php` | High
22 | File | `/admin/admin-profile.php` | High
23 | File | `/admin/adminHome.php` | High
24 | File | `/admin/admin_class_novo.php` | High
25 | File | `/admin/admin_football.php` | High
26 | File | `/admin/admin_running.php` | High
27 | File | `/admin/ajax.php?action=delete_application` | High
28 | File | `/admin/ajax.php?action=login2` | High
29 | File | `/admin/ajax.php?action=save_recruitment_status` | High
30 | File | `/admin/ajax.php?action=save_user` | High
31 | File | `/admin/article.php` | High
32 | File | `/admin/asign-single-student-subjects.php` | High
33 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/dymanic_table.php` | High
34 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/empty_table.php` | High
35 | File | `/admin/bwdates-reports-details.php` | High
36 | File | `/admin/category/controller.php` | High
37 | File | `/admin/changeimage.php` | High
38 | File | `/Admin/changepassword.php` | High
39 | File | `/admin/completed-requests.php` | High
40 | File | `/admin/contactus.php` | High
41 | File | `/admin/core/import_users.php` | High
42 | File | `/admin/courses/manage_course.php` | High
43 | File | `/admin/courses/view_course.php` | High
44 | File | `/Admin/delete-fee.php` | High
45 | File | `/admin/delete_file.php` | High
46 | File | `/admin/delete_s3.php` | High
47 | File | `/admin/delete_s6.php` | High
48 | File | `/admin/delete_user.php` | High
49 | File | `/admin/edit-art-product-detail.php?editid=2` | High
50 | File | `/admin/edit-category.php` | High
51 | File | `/admin/edit-teacher-detail.php` | High
52 | File | `/admin/edit-user.php` | High
53 | File | `/admin/edit_account.php` | High
54 | File | `/admin/edit_expenses.php` | High
55 | File | `/admin/edit_room.php` | High
56 | File | `/admin/edit_student_query.php` | High
57 | File | `/admin/extend/list.html` | High
58 | File | `/admin/includes/edit_post.php` | High
59 | File | `/admin/index.php` | High
60 | File | `/admin/index.php?page=user-profile` | High
61 | File | `/Admin/login.php` | High
62 | File | `/admin/login.php` | High
63 | File | `/admin/manage-admins.php` | High
64 | File | `/admin/manage-foreigners-ticket.php` | High
65 | File | `/admin/manage_movie.php` | High
66 | File | `/admin/mechanics/manage_mechanic.php` | High
67 | File | `/admin/menu.php` | High
68 | File | `/admin/modules/room/index.php` | High
69 | File | `/admin/navbar.php` | High
70 | File | `/admin/network/diag_traceroute` | High
71 | File | `/admin/new-autoortaxi-entry-form.php` | High
72 | File | `/admin/operation/user.php` | High
73 | File | `/admin/patients/view_history.php` | High
74 | File | `/admin/product.php` | High
75 | File | `/admin/profile.php` | High
76 | File | `/admin/registration.php` | High
77 | File | `/admin/replymsg.php` | High
78 | File | `/admin/rooms.php` | High
79 | File | `/admin/save_student.php` | High
80 | File | `/admin/search-report-details.php` | High
81 | File | `/admin/search.php` | High
82 | File | `/admin/search_student.php` | High
83 | File | `/admin/send_message.php` | High
84 | File | `/admin/students/manage_academic.php` | High
85 | File | `/admin/tags/save` | High
86 | File | `/admin/teacher-attendance.php` | High
87 | File | `/admin/transaction/deposit` | High
88 | File | `/admin/update-progress.php` | High
89 | File | `/admin/update_main_topic_img.php?topic_id=529` | High
90 | File | `/admin/update_s3.php` | High
91 | File | `/admin/update_s6.php` | High
92 | File | `/admin/update_s7.php` | High
93 | File | `/admin/user-bookings.php` | High
94 | File | `/admin/user/index.php?view=edit` | High
95 | File | `/admin/user/user-move-run.php` | High
96 | File | `/admin/wangkan_list.php` | High
97 | File | `/admin/yesterday-reg-users.php` | High
98 | File | `/admin79f2ec220c7e.php?c=api&m=demo&name=mobile` | High
99 | File | `/Adminadd.php` | High
100 | File | `/adminapi/system/file/openfile` | High
101 | File | `/Admindelete.php` | High
102 | File | `/administrator/addcategory.php` | High
103 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
104 | File | `/adminPage/conf/check` | High
105 | File | `/ajax.php?action=calculate_payroll` | High
106 | File | `/ajax.php?action=delete_supplier` | High
107 | File | `/ajax.php?action=login` | High
108 | File | `/ajax.php?action=save_payroll` | High
109 | File | `/ajax.php?action=save_plan` | High
110 | File | `/ajax.php?action=save_product` | High
111 | File | `/ajax.php?action=save_sales` | High
112 | File | `/ajax.php?action=save_type` | High
113 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
114 | File | `/ajax/php/leaf_search.php` | High
115 | File | `/alphaware/summary.php` | High
116 | File | `/api/admin/common/download/templates` | High
117 | File | `/api/esps` | Medium
118 | File | `/api/File/downloadFile` | High
119 | File | `/api/files/recipepictures/` | High
120 | File | `/api/jobs` | Medium
121 | File | `/api/login/auth` | High
122 | File | `/api/settings` | High
123 | File | `/api/sys/login` | High
124 | File | `/api/v1/status-page/:url` | High
125 | File | `/api/wizard/getCapability` | High
126 | File | `/api/wizard/getNetworkStatus` | High
127 | ... | ... | ...

There are 1128 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.securelayer7.net/clawdbot-vs-code-trojan-openclaw-security/
* https://github.com/sophoslabs/IoCs/blob/master/2024-02_Payloads_associated_with_ScreenConnect_attacks.csv
* https://thedfirreport.com/2023/09/25/from-screenconnect-to-hive-ransomware-in-61-hours/
* https://urlhaus.abuse.ch/url/3535241/
* https://urlhaus.abuse.ch/url/3535242/
* https://urlhaus.abuse.ch/url/3535243/
* https://urlhaus.abuse.ch/url/3535246/
* https://urlhaus.abuse.ch/url/3535247/
* https://urlhaus.abuse.ch/url/3535248/
* https://urlhaus.abuse.ch/url/3535249/
* https://urlhaus.abuse.ch/url/3535250/
* https://urlhaus.abuse.ch/url/3535251/
* https://urlhaus.abuse.ch/url/3535252/
* https://urlhaus.abuse.ch/url/3535253/
* https://urlhaus.abuse.ch/url/3535254/
* https://urlhaus.abuse.ch/url/3535255/
* https://urlhaus.abuse.ch/url/3535256/
* https://urlhaus.abuse.ch/url/3538650/
* https://urlhaus.abuse.ch/url/3578977/
* https://urlhaus.abuse.ch/url/3582040/
* https://urlhaus.abuse.ch/url/3586099/
* https://urlhaus.abuse.ch/url/3592996/
* https://urlhaus.abuse.ch/url/3601203/
* https://urlhaus.abuse.ch/url/3601206/
* https://urlhaus.abuse.ch/url/3601212/
* https://urlhaus.abuse.ch/url/3601213/
* https://urlhaus.abuse.ch/url/3601214/
* https://urlhaus.abuse.ch/url/3751246/
* https://urlhaus.abuse.ch/url/3775493/
* https://urlhaus.abuse.ch/url/3782928/
* https://urlhaus.abuse.ch/url/3782930/
* https://urlhaus.abuse.ch/url/3782934/
* https://urlhaus.abuse.ch/url/3782937/
* https://urlhaus.abuse.ch/url/3782941/
* https://urlhaus.abuse.ch/url/3782942/
* https://urlhaus.abuse.ch/url/3782944/
* https://urlhaus.abuse.ch/url/3782948/
* https://urlhaus.abuse.ch/url/3782950/
* https://urlhaus.abuse.ch/url/3782952/
* https://urlhaus.abuse.ch/url/3782953/
* https://urlhaus.abuse.ch/url/3784258/
* https://urlhaus.abuse.ch/url/3786964/
* https://urlhaus.abuse.ch/url/3787432/
* https://urlhaus.abuse.ch/url/3805348/
* https://urlhaus.abuse.ch/url/3806841/
* https://urlhaus.abuse.ch/url/3812992/
* https://urlhaus.abuse.ch/url/3814787/
* https://urlhaus.abuse.ch/url/3874718/
* https://www.microsoft.com/en-us/security/blog/2026/05/26/poisoned-search-results-gpu-mining-cryptojacking-campaign-abusing-screenconnect-microsoft-net-utilities/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
