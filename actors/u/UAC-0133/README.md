# UAC-0133 - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [UAC-0133](https://vuldb.com/actor/uac-0133). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/uac-0133](https://vuldb.com/actor/uac-0133)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with UAC-0133:

* [US](https://vuldb.com/country/us)
* [DE](https://vuldb.com/country/de)
* [SE](https://vuldb.com/country/se)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of UAC-0133.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.74.11](https://vuldb.com/ip/5.45.74.11) | free.ispiria.net | - | High
2 | [5.45.75.45](https://vuldb.com/ip/5.45.75.45) | mail.virtual-businessman.com | - | High
3 | [88.80.145.239](https://vuldb.com/ip/88.80.145.239) | - | - | High
4 | ... | ... | ... | ...

There are 13 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _UAC-0133_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-26, CWE-35, CWE-36 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-250, CWE-264, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 23 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by UAC-0133. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.github/workflows/combine-prs.yml` | High
2 | File | `/?_route=settings/users-view/` | High
3 | File | `/accomodation.php` | High
4 | File | `/addbill.php` | Medium
5 | File | `/addcategory.php` | High
6 | File | `/add_new_supplier.php` | High
7 | File | `/add_student/` | High
8 | File | `/admin#themes` | High
9 | File | `/admin-api/infra/file/upload` | High
10 | File | `/admin-api/mp/material/upload-permanent` | High
11 | File | `/admin-cp/theme/editor/default` | High
12 | File | `/admin/add-single-student-results.php` | High
13 | File | `/admin/addmanagerclinic.php` | High
14 | File | `/admin/adminHome.php` | High
15 | File | `/admin/admin_class_novo.php` | High
16 | File | `/admin/admin_edit_menu_action.php` | High
17 | File | `/admin/ajax.php?action=delete_cart` | High
18 | File | `/admin/ajax.php?action=login` | High
19 | File | `/admin/ajax.php?action=save_user` | High
20 | File | `/admin/app/asset_crud.php` | High
21 | File | `/admin/appointment_action.php` | High
22 | File | `/admin/article.php` | High
23 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
24 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/html_table.php` | High
25 | File | `/admin/assigned-requests.php` | High
26 | File | `/admin/blocks` | High
27 | File | `/admin/candidates_delete.php` | High
28 | File | `/admin/categories/save` | High
29 | File | `/admin/changeimage1.php` | High
30 | File | `/admin/changeimage2.php` | High
31 | File | `/admin/core/drop_user.php` | High
32 | File | `/admin/course_action.php` | High
33 | File | `/admin/deletedoctorclinic.php` | High
34 | File | `/admin/display-teacher.php` | High
35 | File | `/admin/edit-ambulance.php` | High
36 | File | `/admin/edit-brand.php` | High
37 | File | `/admin/edit_area.php` | High
38 | File | `/admin/edit_fuel.php` | High
39 | File | `/admin/edit_room.php` | High
40 | File | `/admin/edit_student_query.php` | High
41 | File | `/admin/edit_user.php` | High
42 | File | `/admin/idcProData_deal.php?mudi=del` | High
43 | File | `/admin/index.php` | High
44 | File | `/Admin/login.php` | High
45 | File | `/admin/login.php` | High
46 | File | `/admin/mod_amenities/controller.php?action=add` | High
47 | File | `/admin/navbar.php` | High
48 | File | `/admin/network/diag_iperf` | High
49 | File | `/admin/pages/list` | High
50 | File | `/admin/property-details.php` | High
51 | File | `/admin/request-received-bydonar.php` | High
52 | File | `/admin/search-maid.php` | High
53 | File | `/Admin/student.php` | High
54 | File | `/admin/team_update.php` | High
55 | File | `/admin/update-clients.php` | High
56 | File | `/admin/updatestudent.php` | High
57 | File | `/admin/update_s1.php` | High
58 | File | `/admin/upgrade` | High
59 | File | `/Admin/user-record.php` | High
60 | File | `/admin/view-request.php` | High
61 | File | `/admin/view_sendlist.php` | High
62 | File | `/admin/visitors-form.php` | High
63 | File | `/admin/voters_delete.php` | High
64 | File | `/admin/yesterday-reg-users.php` | High
65 | File | `/Administrator/PHP/AdminUpdateCategory.php` | High
66 | File | `/adminPage/main/upload` | High
67 | File | `/adminPage/www/addOver` | High
68 | File | `/admin_ping.htm` | High
69 | File | `/admin_search_student.php` | High
70 | File | `/airag/airagModel/test` | High
71 | File | `/ajax.php` | Medium
72 | File | `/ajax.php?action=calculate_payroll` | High
73 | File | `/ajax.php?action=delete_member` | High
74 | File | `/ajax.php?action=delete_receiving` | High
75 | File | `/ajax.php?action=save_customer` | High
76 | File | `/ajax.php?action=signup` | High
77 | File | `/ajax.php?action=update_account` | High
78 | File | `/alphaware/summary.php` | High
79 | File | `/ample/app/action/edit_product.php` | High
80 | File | `/api/admin/sys-file/upload` | High
81 | File | `/api/authentication/login` | High
82 | File | `/api/discoveries/` | High
83 | File | `/api/extract` | Medium
84 | File | `/api/info/long_task` | High
85 | File | `/api/job/add/` | High
86 | ... | ... | ...

There are 760 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://cert.gov.ua/article/6278706

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
