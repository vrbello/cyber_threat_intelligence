# Spalax - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Spalax_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Spalax:

* [US](https://vuldb.com/country/us)
* [DE](https://vuldb.com/country/de)
* [BR](https://vuldb.com/country/br)
* ...

There are 50 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Spalax or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Spalax](https://vuldb.com/actor/spalax) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Spalax.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [128.90.108.132](https://vuldb.com/ip/128.90.108.132) | undefined.hostname.localhost | [Spalax](https://vuldb.com/actor/spalax) | High
2 | [128.90.108.177](https://vuldb.com/ip/128.90.108.177) | undefined.hostname.localhost | [Spalax](https://vuldb.com/actor/spalax) | High
3 | [128.90.112.34](https://vuldb.com/ip/128.90.112.34) | undefined.hostname.localhost | [Spalax](https://vuldb.com/actor/spalax) | High
4 | [128.90.112.142](https://vuldb.com/ip/128.90.112.142) | undefined.hostname.localhost | [Spalax](https://vuldb.com/actor/spalax) | High
5 | [128.90.115.100](https://vuldb.com/ip/128.90.115.100) | undefined.hostname.localhost | [Spalax](https://vuldb.com/actor/spalax) | High
6 | [128.90.115.244](https://vuldb.com/ip/128.90.115.244) | undefined.hostname.localhost | [Spalax](https://vuldb.com/actor/spalax) | High
7 | [179.14.171.7](https://vuldb.com/ip/179.14.171.7) | Dinamic-Tigo-179-14-171-7.tigo.com.co | [Spalax](https://vuldb.com/actor/spalax) | High
8 | [179.14.173.93](https://vuldb.com/ip/179.14.173.93) | Dinamic-Tigo-179-14-173-93.tigo.com.co | [Spalax](https://vuldb.com/actor/spalax) | High
9 | [181.49.90.193](https://vuldb.com/ip/181.49.90.193) | dynamic-ip-1814990193.cable.net.co | [Spalax](https://vuldb.com/actor/spalax) | High
10 | [181.52.100.157](https://vuldb.com/ip/181.52.100.157) | static-ip-cr181520100157.cable.net.co | [Spalax](https://vuldb.com/actor/spalax) | High
11 | [181.52.102.87](https://vuldb.com/ip/181.52.102.87) | static-ip-cr18152010287.cable.net.co | [Spalax](https://vuldb.com/actor/spalax) | High
12 | [181.52.103.140](https://vuldb.com/ip/181.52.103.140) | static-ip-cr181520103140.cable.net.co | [Spalax](https://vuldb.com/actor/spalax) | High
13 | [181.52.104.2](https://vuldb.com/ip/181.52.104.2) | static-ip-cr1815201042.cable.net.co | [Spalax](https://vuldb.com/actor/spalax) | High
14 | ... | ... | ... | ...

There are 51 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Spalax. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Spalax. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/?g=log_import_save` | High
3 | File | `/?page=manage_reservation` | High
4 | File | `/accomodation.php` | High
5 | File | `/admin/Add%20notice/notice.php` | High
6 | File | `/admin/add-category.php` | High
7 | File | `/admin/add-customer.php` | High
8 | File | `/admin/adddoctorclinic.php` | High
9 | File | `/admin/add_room.php` | High
10 | File | `/admin/admin_edit_menu.php` | High
11 | File | `/admin/admin_edit_supplier.php` | High
12 | File | `/admin/admin_members.php?ac=search` | High
13 | File | `/admin/admin_user.php` | High
14 | File | `/admin/ajax.php?action=login2` | High
15 | File | `/admin/asign-single-student-subjects.php` | High
16 | File | `/admin/check_availability.php` | High
17 | File | `/admin/code/tce_edit_group.php` | High
18 | File | `/admin/conferences/list/` | High
19 | File | `/admin/config/list.html` | High
20 | File | `/admin/contactus.php` | High
21 | File | `/admin/delete-session.php` | High
22 | File | `/admin/deleteitem.php` | High
23 | File | `/admin/delete_bloodGroup.php` | High
24 | File | `/admin/display-teacher.php` | High
25 | File | `/admin/edit-class.php?cid=1` | High
26 | File | `/admin/enquiry` | High
27 | File | `/admin/login.php` | High
28 | File | `/admin/manage-notices.php` | High
29 | File | `/admin/Member/index.html` | High
30 | File | `/admin/mod_amenities/index.php?view=add` | High
31 | File | `/admin/network/diag_traceroute6` | High
32 | File | `/admin/plugins/NP_Referrer.php` | High
33 | File | `/admin/receipt.php` | High
34 | File | `/admin/roomdelete.php` | High
35 | File | `/admin/save_user.php` | High
36 | File | `/admin/settings/index.php?page=accounts` | High
37 | File | `/admin/teacher-attendance.php` | High
38 | File | `/admin/teacher-salary.php` | High
39 | File | `/admin/updateabout.php` | High
40 | File | `/admin/update_s3.php` | High
41 | File | `/admin/update_s4.php` | High
42 | File | `/admin/update_s7.php` | High
43 | File | `/admin/user.php` | High
44 | File | `/admin/user/manage_user.php` | High
45 | File | `/admin/v1/blog/edit` | High
46 | File | `/admin/yesterday-reg-users.php` | High
47 | File | `/admindetail.php?action=edit` | High
48 | File | `/admin_search_student.php` | High
49 | File | `/admin_state.php` | High
50 | File | `/advisers.php` | High
51 | File | `/api/av/removeUnusedAttributeView` | High
52 | File | `/api/dept/build` | High
53 | File | `/api/endpoint` | High
54 | File | `/api/events/in` | High
55 | File | `/api/extclients/` | High
56 | File | `/api/Security/` | High
57 | File | `/api/smartfilters/testexecutions` | High
58 | File | `/api/System.php` | High
59 | File | `/api/v1/admin/` | High
60 | File | `/api/v1/editor/` | High
61 | File | `/api/v1/serve/awel/flow/import` | High
62 | File | `/api/vanna/v2/` | High
63 | File | `/api/wizard/getCapability` | High
64 | File | `/app/login` | Medium
65 | File | `/application/models/Crud_model.php` | High
66 | File | `/assetsGroupReport/assetsService.j%73p` | High
67 | File | `/att_single_view.php` | High
68 | File | `/auth/userkey/logout.php` | High
69 | File | `/Base/BaseHandler.ashx` | High
70 | File | `/Base/BaseService.asmx/DataService` | High
71 | File | `/bidlog.php` | Medium
72 | File | `/bin/httpd` | Medium
73 | File | `/bin/netis.cgi` | High
74 | File | `/binutils/debug.c` | High
75 | File | `/Blood/A+.php` | High
76 | File | `/boaform/formSamba` | High
77 | File | `/boafrm/formIpQoS` | High
78 | File | `/boafrm/formReflashClientTbl` | High
79 | File | `/boafrm/formSetLg` | High
80 | File | `/boafrm/formSysCmd` | High
81 | File | `/book-appointment.php` | High
82 | File | `/borrowedequip.php` | High
83 | File | `/borrowedtool.php` | High
84 | File | `/borrowed_equip_report.php` | High
85 | File | `/C6/Jhsoft.Web.officesupply/OfficeSupplyTypeRight.aspx` | High
86 | File | `/catageory.php` | High
87 | File | `/cgi-bin/adm.cgi` | High
88 | File | `/cgi-bin/cstecgi.cgi` | High
89 | File | `/cgi-bin/hd_config.cgi` | High
90 | File | `/cgi-bin/hedwig.cgi` | High
91 | File | `/cgi-bin/internet.cgi` | High
92 | ... | ... | ...

There are 812 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://github.com/eset/malware-ioc/tree/master/spalax

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
