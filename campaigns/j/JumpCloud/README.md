# JumpCloud - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _JumpCloud_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with JumpCloud:

* [US](https://vuldb.com/country/us)
* [CH](https://vuldb.com/country/ch)
* [RU](https://vuldb.com/country/ru)
* ...

There are 16 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with JumpCloud or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [DPRK](https://vuldb.com/actor/dprk) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of JumpCloud.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [23.29.115.171](https://vuldb.com/ip/23.29.115.171) | 23-29-115-171.static.hvvc.us | [DPRK](https://vuldb.com/actor/dprk) | High
2 | [23.95.182.5](https://vuldb.com/ip/23.95.182.5) | 23-95-182-5-host.colocrossing.com | [DPRK](https://vuldb.com/actor/dprk) | High
3 | [45.82.250.186](https://vuldb.com/ip/45.82.250.186) | - | [DPRK](https://vuldb.com/actor/dprk) | High
4 | [51.254.24.19](https://vuldb.com/ip/51.254.24.19) | - | [DPRK](https://vuldb.com/actor/dprk) | High
5 | ... | ... | ... | ...

There are 15 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-35, CWE-36, CWE-37 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during JumpCloud. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/add-subadmin.php` | High
3 | File | `/addmem.php` | Medium
4 | File | `/addProduct.php` | High
5 | File | `/add_user.php` | High
6 | File | `/admin.php` | Medium
7 | File | `/admin/?page=zone` | High
8 | File | `/admin/aboutus.php` | High
9 | File | `/admin/actions/check-attendance.php` | High
10 | File | `/admin/add-module.php` | High
11 | File | `/admin/add-table.php` | High
12 | File | `/admin/add_expenses.php` | High
13 | File | `/admin/add_subject.php` | High
14 | File | `/admin/admin_running.php` | High
15 | File | `/admin/changeimage.php` | High
16 | File | `/Admin/changepassword.php` | High
17 | File | `/admin/checklogin.php` | High
18 | File | `/admin/class.php` | High
19 | File | `/admin/completed-requests.php` | High
20 | File | `/admin/content/editor` | High
21 | File | `/admin/controller/faculty_controller.php` | High
22 | File | `/admin/deleteuser.php` | High
23 | File | `/admin/delete_s6.php` | High
24 | File | `/admin/delete_user.php` | High
25 | File | `/admin/edit-art-product-detail.php?editid=2` | High
26 | File | `/admin/edit-user.php` | High
27 | File | `/admin/edit_class.php` | High
28 | File | `/admin/edit_expenses_query.php` | High
29 | File | `/admin/edit_room.php` | High
30 | File | `/admin/edit_subject.php` | High
31 | File | `/admin/includes/edit_post.php` | High
32 | File | `/admin/index.php` | High
33 | File | `/admin/index.php?page=user-profile` | High
34 | File | `/admin/invoiceprint.php` | High
35 | File | `/Admin/login.php` | High
36 | File | `/admin/login.php` | High
37 | File | `/admin/mechanics/manage_mechanic.php` | High
38 | File | `/admin/modules/room/index.php` | High
39 | File | `/admin/profile.php` | High
40 | File | `/admin/quesadd.php` | High
41 | File | `/admin/receipt.php` | High
42 | File | `/Admin/resultdetails.php` | High
43 | File | `/admin/tags/save` | High
44 | File | `/admin/twitter.php` | High
45 | File | `/admin/user-bookings.php` | High
46 | File | `/admin/user/index.php?view=edit` | High
47 | File | `/admin/voters_delete.php` | High
48 | File | `/admin/yesterday-reg-users.php` | High
49 | File | `/adminapi/system/file/openfile` | High
50 | File | `/administrator/addcategory.php` | High
51 | File | `/Administrator/PHP/AdminAddUser.php` | High
52 | File | `/Administrator/PHP/AdminDeleteUser.php` | High
53 | File | `/Administrator/PHP/AdminEditUser.php` | High
54 | File | `/Administrator/PHP/AdminReply.php` | High
55 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
56 | File | `/Administrator/PHP/AdminViewSongs.php` | High
57 | File | `/advancesearch.php` | High
58 | File | `/adv_mac_filter.php` | High
59 | File | `/ajax.php?action=delete_member` | High
60 | File | `/ajax.php?action=delete_product` | High
61 | File | `/ajax.php?action=delete_user` | High
62 | File | `/ajax.php?action=login` | High
63 | File | `/ajax.php?action=save_deductions` | High
64 | File | `/ajax.php?action=save_payroll` | High
65 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
66 | File | `/alphaware/summary.php` | High
67 | File | `/api/File/downloadFile` | High
68 | File | `/api/settings` | High
69 | File | `/api/sys/login` | High
70 | File | `/api/wizard/getCapability` | High
71 | File | `/api/wizard/getDualbandSync` | High
72 | File | `/api/wizard/setLanguage` | High
73 | File | `/api/workspace/:workspace-slug/update` | High
74 | File | `/app/api/controller/collect.php` | High
75 | File | `/app/api/v1/openvpn.py` | High
76 | File | `/app/controller/Api.php` | High
77 | File | `/app/register.php?action=reg` | High
78 | File | `/app/sys1.php` | High
79 | File | `/assetsGroupReport/assetsService.j%73p` | High
80 | File | `/auth.asp` | Medium
81 | File | `/authentication.cgi` | High
82 | File | `/backend/doc/his_doc_update-account.php` | High
83 | File | `/bin/httpd` | Medium
84 | File | `/biurl_grou` | Medium
85 | File | `/boaform/formSysCmd` | High
86 | File | `/boafrm/formDdns` | High
87 | File | `/boafrm/formDefRoute` | High
88 | File | `/boafrm/formDMZ` | High
89 | File | `/boafrm/formFilter` | High
90 | File | `/boafrm/formFirewallAdv` | High
91 | File | `/boafrm/formNtp` | High
92 | File | `/boafrm/formParentControl` | High
93 | File | `/boafrm/formPingDiagnosticRun` | High
94 | File | `/boafrm/formPinManageSetup` | High
95 | ... | ... | ...

There are 837 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://jumpcloud.com/support/july-2023-iocs

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
