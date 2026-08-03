# Sage - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [Sage](https://vuldb.com/actor/sage). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/sage](https://vuldb.com/actor/sage)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Sage:

* [AT](https://vuldb.com/country/at)
* [US](https://vuldb.com/country/us)
* [DE](https://vuldb.com/country/de)
* ...

There are 12 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Sage.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.45.6.138](https://vuldb.com/ip/5.45.6.138) | 138-006-045-005.ip-addr.inexio.net | - | High
2 | [5.45.17.36](https://vuldb.com/ip/5.45.17.36) | - | - | High
3 | [5.45.24.236](https://vuldb.com/ip/5.45.24.236) | - | - | High
4 | [5.45.100.133](https://vuldb.com/ip/5.45.100.133) | domain-butler.com | - | High
5 | [5.45.107.161](https://vuldb.com/ip/5.45.107.161) | nobody.yourvserver.net | - | High
6 | [5.45.107.167](https://vuldb.com/ip/5.45.107.167) | v22014011960816232.yourvserver.net | - | High
7 | [5.45.129.52](https://vuldb.com/ip/5.45.129.52) | - | - | High
8 | [5.45.140.6](https://vuldb.com/ip/5.45.140.6) | - | - | High
9 | [5.45.159.19](https://vuldb.com/ip/5.45.159.19) | - | - | High
10 | [5.45.208.36](https://vuldb.com/ip/5.45.208.36) | proxy-minsk03.cdn.yandex.net | - | High
11 | ... | ... | ... | ...

There are 40 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Sage_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-25 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Sage. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/a/sys/user/save` | High
2 | File | `/aboutus.php` | Medium
3 | File | `/Actions.php` | Medium
4 | File | `/add-course.php` | High
5 | File | `/add-table.php` | High
6 | File | `/add-users.php` | High
7 | File | `/admin-api/bpm/model/deploy` | High
8 | File | `/admin-api/infra/file/upload` | High
9 | File | `/admin.php` | Medium
10 | File | `/admin/aboutus.php` | High
11 | File | `/admin/addroom.php` | High
12 | File | `/admin/add_content.php` | High
13 | File | `/admin/add_course.php` | High
14 | File | `/admin/admin-profile.php` | High
15 | File | `/admin/admin_login.php` | High
16 | File | `/admin/all-request.php` | High
17 | File | `/admin/app/role_crud.php` | High
18 | File | `/admin/app/web_crud.php` | High
19 | File | `/admin/booking-details.php` | High
20 | File | `/admin/budget/manage_budget.php` | High
21 | File | `/admin/bwdates-passreports-details.php` | High
22 | File | `/admin/bwdates-reports-details.php` | High
23 | File | `/admin/candidates_delete.php` | High
24 | File | `/admin/carousels/save` | High
25 | File | `/admin/category/add.do` | High
26 | File | `/admin/change-password.php` | High
27 | File | `/admin/check_availability.php` | High
28 | File | `/admin/contactus.php` | High
29 | File | `/admin/DBbackup/` | High
30 | File | `/admin/delete-doctor.php` | High
31 | File | `/admin/delete-row.php` | High
32 | File | `/admin/department/add` | High
33 | File | `/admin/doctors.php` | High
34 | File | `/admin/edit-pass-detail.php` | High
35 | File | `/admin/goods/update` | High
36 | File | `/admin/index.php` | High
37 | File | `/Admin/match.php` | High
38 | File | `/admin/operations/booking.php` | High
39 | File | `/admin/print1.php` | High
40 | File | `/admin/update_user.php` | High
41 | File | `/admin/upload/upimage.html` | High
42 | File | `/admin/user-search.php` | High
43 | File | `/admin/user/updatePwd` | High
44 | File | `/admin/users_photo.php` | High
45 | File | `/admin/view-appointment.php?viewid=11` | High
46 | File | `/admin/view-pass-detail.php` | High
47 | File | `/administrator/index.php` | High
48 | File | `/Administrator/PHP/AdminAddAlbum.php` | High
49 | File | `/admin_delete.php` | High
50 | File | `/ajax.php?action=delete_user` | High
51 | File | `/ajax_state.php` | High
52 | File | `/api/article/del` | High
53 | File | `/api/semantic/database/testConnect` | High
54 | File | `/api/wizard/getSpecs` | High
55 | File | `/att_add.php` | Medium
56 | File | `/authentication/logout.php` | High
57 | File | `/bank/show.php` | High
58 | File | `/billing/pms_check.php` | High
59 | File | `/bin/boa` | Medium
60 | File | `/Blood/A-.php` | High
61 | File | `/Bloodgroop_process.php` | High
62 | File | `/boafrm/formIpv6Setup` | High
63 | File | `/boafrm/formPortFw` | High
64 | File | `/boat-details.php` | High
65 | ... | ... | ...

There are 565 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/06/threat-roundup-0531-0607.html
* https://blog.talosintelligence.com/2019/09/threat-roundup-0830-0906.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
