# H0lyGh0st - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _H0lyGh0st_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with H0lyGh0st:

* [VN](https://vuldb.com/country/vn)
* [CN](https://vuldb.com/country/cn)
* [UA](https://vuldb.com/country/ua)

## Actors

These _actors_ are associated with H0lyGh0st or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DEV-0530](https://vuldb.com/actor/dev-0530) | High
2 | [H0lyGh0st](https://vuldb.com/actor/h0lygh0st) | High
3 | [North Korea Unknown](https://vuldb.com/actor/north_korea_unknown) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of H0lyGh0st.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [127.0.0.1](https://vuldb.com/ip/127.0.0.1) | localhost | [H0lyGh0st](https://vuldb.com/actor/h0lygh0st) | High
2 | [193.56.29.123](https://vuldb.com/ip/193.56.29.123) | - | [North Korea Unknown](https://vuldb.com/actor/north_korea_unknown) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within H0lyGh0st. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25, CWE-29 | Path Traversal | High
2 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
4 | T1068 | CWE-250, CWE-264, CWE-269, CWE-270, CWE-284 | Execution with Unnecessary Privileges | High
5 | T1083 | CWE-548, CWE-552 | File and Directory Information Exposure | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during H0lyGh0st. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/?explorer/index/zip` | High
3 | File | `/?page=reserve` | High
4 | File | `/about.php` | Medium
5 | File | `/academy/tutor/filter` | High
6 | File | `/actuator/heapdump` | High
7 | File | `/add-company.php` | High
8 | File | `/addCandidate.php` | High
9 | File | `/addcat.php` | Medium
10 | File | `/addproduct.php` | High
11 | File | `/admin` | Low
12 | File | `/admin.php?id=inbox` | High
13 | File | `/admin/?page=maintenance/brand` | High
14 | File | `/admin/?page=reports` | High
15 | File | `/admin/aboutus.php` | High
16 | File | `/admin/add-module.php` | High
17 | File | `/admin/add-team.php` | High
18 | File | `/admin/admin-profile.php` | High
19 | File | `/admin/api/theme-edit/` | High
20 | File | `/admin/app/login_crud.php` | High
21 | File | `/admin/asign-single-student-subjects.php` | High
22 | File | `/admin/attachment/download` | High
23 | File | `/admin/bookings/manage_booking.php` | High
24 | File | `/admin/bwdates-report-details.php` | High
25 | File | `/admin/category.php` | High
26 | File | `/admin/category/add.do` | High
27 | File | `/admin/check_admin.php` | High
28 | File | `/admin/clientview.php` | High
29 | File | `/admin/communitymanagement.php` | High
30 | File | `/admin/contactus.php` | High
31 | File | `/admin/create_product.php` | High
32 | File | `/admin/deleteitem.php` | High
33 | File | `/admin/delete_user.php` | High
34 | File | `/admin/departments/view_department.php` | High
35 | File | `/admin/edit-doc.php` | High
36 | File | `/admin/edit.php` | High
37 | File | `/admin/edit_content.php` | High
38 | File | `/admin/edit_posts.php` | High
39 | File | `/admin/edit_room.php` | High
40 | File | `/admin/forgot-password.php` | High
41 | File | `/admin/freelist_main.php` | High
42 | File | `/admin/group/edit.do` | High
43 | File | `/admin/home.php` | High
44 | File | `/admin/index.php` | High
45 | File | `/admin/index.php?act=reset_admin_psw` | High
46 | File | `/admin/lab.php` | High
47 | File | `/admin/login.php` | High
48 | File | `/admin/manage-students.php` | High
49 | File | `/admin/manage_station.php` | High
50 | File | `/admin/modules/lesson/index.php` | High
51 | File | `/admin/modules/product/controller.php?action=add` | High
52 | File | `/admin/network/ajax_getChannelList` | High
53 | File | `/admin/newsletterdel.php` | High
54 | File | `/admin/productadd_back.php` | High
55 | File | `/admin/profile.php` | High
56 | File | `/admin/quote-details.php` | High
57 | File | `/admin/robot/approval/list` | High
58 | File | `/admin/room.php` | High
59 | File | `/admin/sales-reports-detail.php` | High
60 | File | `/admin/search-appointment.php` | High
61 | File | `/admin/search-directory.php.` | High
62 | File | `/admin/store/edit/` | High
63 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
64 | File | `/admin/tag.php` | High
65 | File | `/admin/theme/Upload.html` | High
66 | File | `/admin/update-progress.php` | High
67 | File | `/admin/update-user.php` | High
68 | File | `/admin/user.php` | High
69 | File | `/admin/user/controller.php?action=photos` | High
70 | File | `/admin/user/manage_user.php` | High
71 | File | `/admin/users.php` | High
72 | File | `/Adminadd.php` | High
73 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
74 | File | `/Administrator/PHP/AdminAddCategory.php` | High
75 | File | `/Administrator/PHP/AdminViewSongs.php` | High
76 | File | `/adminLogin.php` | High
77 | File | `/adminPage/conf/saveCmd` | High
78 | File | `/admin_class.php` | High
79 | File | `/ajax.php` | Medium
80 | File | `/ajax.php?action=login` | High
81 | File | `/all-orders.php` | High
82 | File | `/apartment-visitor/edit-apartment.php` | High
83 | File | `/api/advanced-search` | High
84 | File | `/api/article/del` | High
85 | File | `/api/backend/v1/user/create` | High
86 | File | `/api/blocks/{block_id}/execute` | High
87 | File | `/api/client/editemedia.php` | High
88 | File | `/api/code/upload` | High
89 | File | `/api/course/enroll-course` | High
90 | File | `/api/file` | Medium
91 | File | `/api/users/{id}/preferences` | High
92 | File | `/api/v1/assignments/{assignment_id}/tasks/{task_id}/sub_file` | High
93 | File | `/api/v1/getbaseconfig` | High
94 | File | `/api/v1/text-to-speech/generate` | High
95 | File | `/api/website/title` | High
96 | File | `/app/ajax/search_sales_report.php` | High
97 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
98 | File | `/application/index/controller/Datament.php` | High
99 | File | `/application/index/controller/Icon.php` | High
100 | File | `/application/pay/controller/Api.php` | High
101 | File | `/artist-display.php` | High
102 | File | `/att_single_view.php` | High
103 | File | `/backend/admin/his_admin_add_vendor.php` | High
104 | File | `/bin/httpd` | Medium
105 | ... | ... | ...

There are 933 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://community.blueliv.com/#!/s/62d1143282df41552632f957
* https://www.microsoft.com/en-us/security/blog/2022/07/14/north-korean-threat-actor-targets-small-and-midsize-businesses-with-h0lygh0st-ransomware/
* https://www.microsoft.com/security/blog/2022/07/14/north-korean-threat-actor-targets-small-and-midsize-businesses-with-h0lygh0st-ransomware/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
