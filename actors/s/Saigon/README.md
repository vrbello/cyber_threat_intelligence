# Saigon - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [Saigon](https://vuldb.com/actor/saigon). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/saigon](https://vuldb.com/actor/saigon)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Saigon:

* [VN](https://vuldb.com/country/vn)
* [CN](https://vuldb.com/country/cn)
* [UA](https://vuldb.com/country/ua)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Saigon.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [127.0.0.1](https://vuldb.com/ip/127.0.0.1) | localhost | - | High
2 | [146.0.72.76](https://vuldb.com/ip/146.0.72.76) | - | - | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Saigon_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25, CWE-29 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Saigon. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/?explorer/index/zip` | High
3 | File | `/?page=reserve` | High
4 | File | `/about.php` | Medium
5 | File | `/academy/tutor/filter` | High
6 | File | `/actuator/heapdump` | High
7 | File | `/ad/queryAll` | Medium
8 | File | `/add-company.php` | High
9 | File | `/addCandidate.php` | High
10 | File | `/addcat.php` | Medium
11 | File | `/addproduct.php` | High
12 | File | `/admin.php?id=inbox` | High
13 | File | `/admin/?page=maintenance/brand` | High
14 | File | `/admin/?page=reports` | High
15 | File | `/admin/aboutus.php` | High
16 | File | `/admin/action/new-feed.php` | High
17 | File | `/admin/add-module.php` | High
18 | File | `/admin/add-team.php` | High
19 | File | `/admin/add_room.php` | High
20 | File | `/admin/admin-profile.php` | High
21 | File | `/admin/all-applied-leave.php` | High
22 | File | `/admin/api/theme-edit/` | High
23 | File | `/admin/app/login_crud.php` | High
24 | File | `/admin/asign-single-student-subjects.php` | High
25 | File | `/admin/attachment/download` | High
26 | File | `/admin/bookings/manage_booking.php` | High
27 | File | `/admin/bwdates-report-details.php` | High
28 | File | `/admin/category.php` | High
29 | File | `/admin/category/add.do` | High
30 | File | `/admin/check_admin.php` | High
31 | File | `/admin/clientview.php` | High
32 | File | `/admin/communitymanagement.php` | High
33 | File | `/admin/contactus.php` | High
34 | File | `/admin/create_product.php` | High
35 | File | `/admin/deleteitem.php` | High
36 | File | `/admin/delete_user.php` | High
37 | File | `/admin/departments/view_department.php` | High
38 | File | `/admin/edit-doc.php` | High
39 | File | `/admin/edit.php` | High
40 | File | `/admin/edit_content.php` | High
41 | File | `/admin/edit_posts.php` | High
42 | File | `/admin/edit_room.php` | High
43 | File | `/admin/forgot-password.php` | High
44 | File | `/admin/freelist_main.php` | High
45 | File | `/admin/group/edit.do` | High
46 | File | `/admin/home.php` | High
47 | File | `/admin/index.php` | High
48 | File | `/admin/index.php/datafile/delfile` | High
49 | File | `/admin/index.php?act=reset_admin_psw` | High
50 | File | `/admin/lab.php` | High
51 | File | `/admin/login.php` | High
52 | File | `/admin/manage-students.php` | High
53 | File | `/admin/manage_station.php` | High
54 | File | `/admin/modules/lesson/index.php` | High
55 | File | `/admin/modules/product/controller.php?action=add` | High
56 | File | `/admin/modules/room/index.php` | High
57 | File | `/admin/network/ajax_getChannelList` | High
58 | File | `/admin/newsletterdel.php` | High
59 | File | `/admin/productadd_back.php` | High
60 | File | `/admin/profile.php` | High
61 | File | `/admin/quote-details.php` | High
62 | File | `/admin/robot/approval/list` | High
63 | File | `/admin/room.php` | High
64 | File | `/admin/sales-reports-detail.php` | High
65 | File | `/admin/search-appointment.php` | High
66 | File | `/admin/search-directory.php.` | High
67 | File | `/admin/store/edit/` | High
68 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
69 | File | `/admin/tag.php` | High
70 | File | `/admin/teachers.php` | High
71 | File | `/admin/theme/Upload.html` | High
72 | File | `/admin/update-progress.php` | High
73 | File | `/admin/update-user.php` | High
74 | File | `/admin/user.php` | High
75 | File | `/admin/user/controller.php?action=photos` | High
76 | File | `/admin/user/manage_user.php` | High
77 | File | `/admin/users.php` | High
78 | File | `/Adminadd.php` | High
79 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
80 | File | `/Administrator/PHP/AdminAddCategory.php` | High
81 | File | `/Administrator/PHP/AdminViewSongs.php` | High
82 | File | `/adminLogin.php` | High
83 | File | `/adminPage/conf/saveCmd` | High
84 | File | `/admin_class.php` | High
85 | File | `/ajax.php` | Medium
86 | File | `/ajax.php?action=login` | High
87 | File | `/all-orders.php` | High
88 | File | `/api/advanced-search` | High
89 | File | `/api/article/del` | High
90 | File | `/api/backend/v1/user/create` | High
91 | File | `/api/blocks/{block_id}/execute` | High
92 | File | `/api/client/editemedia.php` | High
93 | File | `/api/code/upload` | High
94 | File | `/api/course/enroll-course` | High
95 | File | `/api/file` | Medium
96 | File | `/api/users/{id}/preferences` | High
97 | File | `/api/v1/assignments/{assignment_id}/tasks/{task_id}/sub_file` | High
98 | File | `/api/v1/getbaseconfig` | High
99 | File | `/api/v1/text-to-speech/generate` | High
100 | File | `/api/website/title` | High
101 | File | `/app/ajax/search_sales_report.php` | High
102 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
103 | File | `/application/index/controller/Datament.php` | High
104 | File | `/application/index/controller/Icon.php` | High
105 | File | `/application/pay/controller/Api.php` | High
106 | File | `/artist-display.php` | High
107 | File | `/att_single_view.php` | High
108 | File | `/backend/admin/his_admin_add_vendor.php` | High
109 | ... | ... | ...

There are 963 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://www.fireeye.com/blog/threat-research/2020/01/saigon-mysterious-ursnif-fork.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
