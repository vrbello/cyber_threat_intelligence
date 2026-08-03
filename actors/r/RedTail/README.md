# RedTail - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [RedTail](https://vuldb.com/actor/redtail). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/redtail](https://vuldb.com/actor/redtail)

## Campaigns

The following _campaigns_ are known and can be associated with RedTail:

* Docker API

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with RedTail:

* [US](https://vuldb.com/country/us)
* [CN](https://vuldb.com/country/cn)
* [BR](https://vuldb.com/country/br)
* ...

There are 18 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of RedTail.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.182.211.148](https://vuldb.com/ip/5.182.211.148) | - | Docker API | High
2 | [14.46.136.77](https://vuldb.com/ip/14.46.136.77) | - | - | High
3 | [31.57.216.121](https://vuldb.com/ip/31.57.216.121) | - | - | High
4 | [31.77.156.62](https://vuldb.com/ip/31.77.156.62) | - | - | High
5 | [36.140.33.10](https://vuldb.com/ip/36.140.33.10) | - | Docker API | High
6 | [45.79.187.247](https://vuldb.com/ip/45.79.187.247) | 45-79-187-247.ip.linodeusercontent.com | - | High
7 | [45.94.209.196](https://vuldb.com/ip/45.94.209.196) | vmi3338359.contaboserver.net | - | High
8 | [45.128.232.200](https://vuldb.com/ip/45.128.232.200) | - | Docker API | High
9 | [45.132.180.51](https://vuldb.com/ip/45.132.180.51) | - | - | High
10 | [45.148.10.68](https://vuldb.com/ip/45.148.10.68) | - | - | High
11 | [45.148.10.112](https://vuldb.com/ip/45.148.10.112) | - | - | High
12 | [45.148.10.113](https://vuldb.com/ip/45.148.10.113) | - | - | High
13 | [45.148.10.144](https://vuldb.com/ip/45.148.10.144) | - | - | High
14 | [45.148.10.145](https://vuldb.com/ip/45.148.10.145) | - | - | High
15 | [45.148.10.208](https://vuldb.com/ip/45.148.10.208) | - | - | High
16 | ... | ... | ... | ...

There are 59 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _RedTail_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-27, CWE-29, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-266, CWE-268, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 26 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by RedTail. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.git/` | Low
2 | File | `/action.php` | Medium
3 | File | `/add-company.php` | High
4 | File | `/add-customer.php` | High
5 | File | `/addproduct.php` | High
6 | File | `/add_book.php` | High
7 | File | `/adicionar-cliente.php` | High
8 | File | `/admin-manage-user.php` | High
9 | File | `/admin/?/layout/add` | High
10 | File | `/admin/?page=system_info/contact_info` | High
11 | File | `/admin/aboutus.php` | High
12 | File | `/admin/add_payroll.php` | High
13 | File | `/admin/admin/save` | High
14 | File | `/Admin/adminlogin.php` | High
15 | File | `/admin/ajax.php?action=confirm_order` | High
16 | File | `/admin/ajax.php?action=delete_application` | High
17 | File | `/admin/ajax_products_list.php` | High
18 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
19 | File | `/Admin/changepassword.php` | High
20 | File | `/admin/class-result.php` | High
21 | File | `/admin/cms_content.php` | High
22 | File | `/admin/contactus.php` | High
23 | File | `/admin/content/editor` | High
24 | File | `/Admin/Controller/CustomController.class.php` | High
25 | File | `/admin/deleteroom.php` | High
26 | File | `/admin/dialog/select_images_post.php` | High
27 | File | `/admin/edit-subadmin.php` | High
28 | File | `/admin/edit_teacher.php` | High
29 | File | `/admin/eligibility.php` | High
30 | File | `/admin/emp-profile-avatar.php` | High
31 | File | `/admin/index.php/datafile/download` | High
32 | File | `/admin/login.php` | High
33 | File | `/admin/manage-normal-ticket.php` | High
34 | File | `/admin/manage_register.php` | High
35 | File | `/admin/member_save.php` | High
36 | File | `/admin/mod_room/index.php?view=edit` | High
37 | File | `/admin/network/wifi_schedule` | High
38 | File | `/admin/overtime_add.php` | High
39 | File | `/admin/pass-bwdates-reports-details.php` | High
40 | File | `/admin/positions_row.php` | High
41 | File | `/admin/property-details.php` | High
42 | File | `/Admin/Proses_Edit_Akun.php` | High
43 | File | `/admin/publishnews.php` | High
44 | File | `/admin/quote-details.php` | High
45 | File | `/admin/run_ajax.php` | High
46 | File | `/admin/search-medicalcard.php` | High
47 | File | `/admin/services/manage_service.php` | High
48 | File | `/admin/settings/users/edit/` | High
49 | File | `/admin/student_edit_photo.php` | High
50 | File | `/admin/tag/save` | High
51 | File | `/admin/team-ontheway-requests.php` | High
52 | File | `/admin/team_save.php` | High
53 | File | `/admin/user/user-move-run.php` | High
54 | File | `/admin_class.php` | High
55 | File | `/aim/storage/query.py` | High
56 | File | `/ajax.php` | Medium
57 | File | `/ajax.php?action=login` | High
58 | File | `/ajax.php?action=save_employee_attendance` | High
59 | File | `/ajax.php?action=save_payroll` | High
60 | File | `/ajax_state.php` | High
61 | File | `/alphaware/summary.php` | High
62 | File | `/animalsadd.php` | High
63 | File | `/api/` | Low
64 | File | `/api/admin/common/download/templates` | High
65 | File | `/api/admin/store/product/save` | High
66 | File | `/api/data.php` | High
67 | File | `/api/deploy/upload` | High
68 | File | `/api/deploy/upload /api/database/upload` | High
69 | File | `/api/role` | Medium
70 | File | `/api/upload` | Medium
71 | File | `/api/v1.index.article/getList.html` | High
72 | File | `/api/wizard/setsyncpppoecfg` | High
73 | File | `/app/ConfirmSmsCode` | High
74 | File | `/app/login` | Medium
75 | File | `/application/index/controller/Databasesource.php` | High
76 | File | `/application/models/ApplicationDataObject.class.php` | High
77 | File | `/ASDKAPI/api/v8.6/item/addfile` | High
78 | File | `/assets/php/upload.php` | High
79 | File | `/attributecategory/queryAll` | High
80 | File | `/att_single_view.php` | High
81 | File | `/backend/app/api/v1/module_system/user/controller.py` | High
82 | File | `/bank/statements.php` | High
83 | File | `/bloodrequest.php` | High
84 | File | `/boafrm/formDosCfg` | High
85 | File | `/boafrm/formFilter` | High
86 | File | `/boafrm/formNtp` | High
87 | File | `/boafrm/formStats` | High
88 | File | `/boafrm/formVpnConfigSetup` | High
89 | File | `/boafrm/formWsc` | High
90 | ... | ... | ...

There are 790 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://app.any.run/tasks/be4841ee-3014-4a88-ae31-71b5e89a98a5
* https://app.any.run/tasks/da4117c2-5243-4fdb-a2de-67e7427dcf5a
* https://bazaar.abuse.ch/sample/9875fb1a96f06fb4ffde6c24cbaaa15eacd9df8652756e25e6e13f125f2019ec
* https://beelzebub.ai/blog/redtail-cryptominer-first-evidence-of-docker-api-targeting/
* https://isc.sans.edu/diary/32608
* https://threatfox.abuse.ch
* https://twitter.com/NullBlue67
* https://urlhaus.abuse.ch/url/3733110/
* https://urlhaus.abuse.ch/url/3739809/
* https://urlhaus.abuse.ch/url/3790371/
* https://urlhaus.abuse.ch/url/3811128/
* https://urlhaus.abuse.ch/url/3835211/
* https://urlhaus.abuse.ch/url/3835855/
* https://urlhaus.abuse.ch/url/3848791/
* https://urlhaus.abuse.ch/url/3849687/
* https://urlhaus.abuse.ch/url/3861889/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
