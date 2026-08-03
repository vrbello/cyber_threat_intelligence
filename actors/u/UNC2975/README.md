# UNC2975 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [UNC2975](https://vuldb.com/actor/unc2975). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/unc2975](https://vuldb.com/actor/unc2975)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UNC2975:

* [VN](https://vuldb.com/country/vn)
* [CN](https://vuldb.com/country/cn)
* [UA](https://vuldb.com/country/ua)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UNC2975.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [8.209.99.230](https://vuldb.com/ip/8.209.99.230) | - | - | High
2 | [34.16.181.0](https://vuldb.com/ip/34.16.181.0) | 0.181.16.34.bc.googleusercontent.com | - | Medium
3 | [35.203.111.228](https://vuldb.com/ip/35.203.111.228) | 228.111.203.35.bc.googleusercontent.com | - | Medium
4 | ... | ... | ... | ...

There are 7 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UNC2975_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-25, CWE-29 | Path Traversal | High
2 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
3 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
4 | T1068 | CWE-250, CWE-264, CWE-269, CWE-270, CWE-284 | Execution with Unnecessary Privileges | High
5 | T1078.001 | CWE-259 | Use of Hard-coded Password | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UNC2975. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/?page=reserve` | High
3 | File | `/about.php` | Medium
4 | File | `/academy/tutor/filter` | High
5 | File | `/actuator/heapdump` | High
6 | File | `/add-company.php` | High
7 | File | `/addCandidate.php` | High
8 | File | `/addcat.php` | Medium
9 | File | `/addproduct.php` | High
10 | File | `/admin` | Low
11 | File | `/admin-cp/media` | High
12 | File | `/admin/?page=maintenance/brand` | High
13 | File | `/admin/?page=reports` | High
14 | File | `/admin/aboutus.php` | High
15 | File | `/admin/add-module.php` | High
16 | File | `/admin/add-team.php` | High
17 | File | `/admin/admin-profile.php` | High
18 | File | `/admin/api/theme-edit/` | High
19 | File | `/admin/app/login_crud.php` | High
20 | File | `/admin/asign-single-student-subjects.php` | High
21 | File | `/admin/attachment/download` | High
22 | File | `/admin/bookings/manage_booking.php` | High
23 | File | `/admin/bwdates-report-details.php` | High
24 | File | `/admin/category.php` | High
25 | File | `/admin/category/add.do` | High
26 | File | `/admin/check_admin.php` | High
27 | File | `/admin/clientview.php` | High
28 | File | `/admin/communitymanagement.php` | High
29 | File | `/admin/contactus.php` | High
30 | File | `/admin/create_product.php` | High
31 | File | `/admin/deleteitem.php` | High
32 | File | `/admin/delete_user.php` | High
33 | File | `/admin/departments/view_department.php` | High
34 | File | `/admin/edit-doc.php` | High
35 | File | `/admin/edit.php` | High
36 | File | `/admin/edit_content.php` | High
37 | File | `/admin/edit_posts.php` | High
38 | File | `/admin/edit_room.php` | High
39 | File | `/admin/forgot-password.php` | High
40 | File | `/admin/freelist_main.php` | High
41 | File | `/admin/group/edit.do` | High
42 | File | `/admin/home.php` | High
43 | File | `/admin/index.php` | High
44 | File | `/admin/index.php?act=reset_admin_psw` | High
45 | File | `/admin/login.php` | High
46 | File | `/admin/manage-students.php` | High
47 | File | `/admin/manage_station.php` | High
48 | File | `/admin/modules/lesson/index.php` | High
49 | File | `/admin/modules/product/controller.php?action=add` | High
50 | File | `/admin/network/ajax_getChannelList` | High
51 | File | `/admin/newsletterdel.php` | High
52 | File | `/admin/productadd_back.php` | High
53 | File | `/admin/profile.php` | High
54 | File | `/admin/quote-details.php` | High
55 | File | `/admin/robot/approval/list` | High
56 | File | `/admin/search-appointment.php` | High
57 | File | `/admin/search-directory.php.` | High
58 | File | `/admin/store/edit/` | High
59 | File | `/admin/system/dict/add.json?sqlid=system.dict.save` | High
60 | File | `/admin/tag.php` | High
61 | File | `/admin/theme/Upload.html` | High
62 | File | `/admin/update-user.php` | High
63 | File | `/admin/user.php` | High
64 | File | `/admin/user/controller.php?action=photos` | High
65 | File | `/admin/user/manage_user.php` | High
66 | File | `/admin/users.php` | High
67 | File | `/Adminadd.php` | High
68 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
69 | File | `/Administrator/PHP/AdminAddCategory.php` | High
70 | File | `/Administrator/PHP/AdminViewSongs.php` | High
71 | File | `/adminLogin.php` | High
72 | File | `/adminPage/conf/saveCmd` | High
73 | File | `/admin_class.php` | High
74 | File | `/ajax.php` | Medium
75 | File | `/ajax.php?action=login` | High
76 | File | `/all-orders.php` | High
77 | File | `/apartment-visitor/edit-apartment.php` | High
78 | File | `/api/advanced-search` | High
79 | File | `/api/article/del` | High
80 | File | `/api/backend/v1/user/create` | High
81 | File | `/api/blocks/{block_id}/execute` | High
82 | File | `/api/client/editemedia.php` | High
83 | File | `/api/code/upload` | High
84 | File | `/api/file` | Medium
85 | File | `/api/users/{id}/preferences` | High
86 | File | `/api/v1/getbaseconfig` | High
87 | File | `/api/v1/text-to-speech/generate` | High
88 | File | `/api/website/title` | High
89 | File | `/app/ajax/search_sales_report.php` | High
90 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
91 | File | `/application/index/controller/Datament.php` | High
92 | File | `/application/pay/controller/Api.php` | High
93 | File | `/artist-display.php` | High
94 | File | `/att_single_view.php` | High
95 | File | `/backend/admin/his_admin_add_vendor.php` | High
96 | File | `/bidnow.php` | Medium
97 | File | `/bin/httpd` | Medium
98 | File | `/Blood/A-.php` | High
99 | File | `/boafrm/formIpQoS` | High
100 | File | `/boafrm/formOneKeyAccessButton` | High
101 | File | `/boafrm/formStaticDHCP` | High
102 | File | `/boafrm/formSysLog` | High
103 | ... | ... | ...

There are 911 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cloud.google.com/blog/topics/threat-intelligence/detecting-disrupting-malvertising-backdoors/?hl=en

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
