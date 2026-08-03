# Winos - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [Winos](https://vuldb.com/actor/winos). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/winos](https://vuldb.com/actor/winos)

## Campaigns

The following _campaigns_ are known and can be associated with Winos:

* Catena
* Taiwanese Organizations

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Winos:

* [US](https://vuldb.com/country/us)
* [DE](https://vuldb.com/country/de)
* [BR](https://vuldb.com/country/br)
* ...

There are 49 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Winos.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [24.152.36.243](https://vuldb.com/ip/24.152.36.243) | 24-152-36-243.masterdaweb.com | - | High
2 | [27.122.59.71](https://vuldb.com/ip/27.122.59.71) | - | - | High
3 | [43.226.125.44](https://vuldb.com/ip/43.226.125.44) | - | - | High
4 | [47.83.184.193](https://vuldb.com/ip/47.83.184.193) | - | - | High
5 | [47.86.28.28](https://vuldb.com/ip/47.86.28.28) | - | - | High
6 | [47.238.125.85](https://vuldb.com/ip/47.238.125.85) | - | - | High
7 | [103.46.185.44](https://vuldb.com/ip/103.46.185.44) | undefined.hostname.localhost | Catena | High
8 | [103.46.185.73](https://vuldb.com/ip/103.46.185.73) | undefined.hostname.localhost | - | High
9 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Winos_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Winos. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `../mtd/Config/Sha1Account1` | High
2 | File | `/?g=log_import_save` | High
3 | File | `/?page=manage_reservation` | High
4 | File | `/accomodation.php` | High
5 | File | `/admin/Add%20notice/notice.php` | High
6 | File | `/admin/add-category.php` | High
7 | File | `/admin/adddoctorclinic.php` | High
8 | File | `/admin/add_room.php` | High
9 | File | `/admin/admin_edit_menu.php` | High
10 | File | `/admin/admin_edit_supplier.php` | High
11 | File | `/admin/admin_members.php?ac=search` | High
12 | File | `/admin/admin_user.php` | High
13 | File | `/admin/ajax.php?action=login2` | High
14 | File | `/admin/asign-single-student-subjects.php` | High
15 | File | `/admin/check_availability.php` | High
16 | File | `/admin/code/tce_edit_group.php` | High
17 | File | `/admin/conferences/list/` | High
18 | File | `/admin/config/list.html` | High
19 | File | `/admin/contactus.php` | High
20 | File | `/admin/delete-session.php` | High
21 | File | `/admin/deleteitem.php` | High
22 | File | `/admin/delete_bloodGroup.php` | High
23 | File | `/admin/display-teacher.php` | High
24 | File | `/admin/edit-class.php?cid=1` | High
25 | File | `/admin/enquiry` | High
26 | File | `/admin/login.php` | High
27 | File | `/admin/manage-notices.php` | High
28 | File | `/admin/Member/index.html` | High
29 | File | `/admin/mod_amenities/index.php?view=add` | High
30 | File | `/admin/navbar.php` | High
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
77 | File | `/boafrm/formDdns` | High
78 | File | `/boafrm/formFilter` | High
79 | File | `/boafrm/formIpQoS` | High
80 | File | `/boafrm/formNtp` | High
81 | File | `/boafrm/formPortFw` | High
82 | File | `/boafrm/formReflashClientTbl` | High
83 | File | `/boafrm/formSetLg` | High
84 | File | `/boafrm/formSysCmd` | High
85 | File | `/boafrm/formSysLog` | High
86 | File | `/book-appointment.php` | High
87 | File | `/borrowedequip.php` | High
88 | File | `/borrowedtool.php` | High
89 | File | `/borrowed_equip_report.php` | High
90 | File | `/C6/Jhsoft.Web.officesupply/OfficeSupplyTypeRight.aspx` | High
91 | File | `/catageory.php` | High
92 | File | `/cgi-bin/adm.cgi` | High
93 | ... | ... | ...

There are 819 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://github.com/rapid7/Rapid7-Labs/blob/main/IOCs/nsis-abuse-srdi-winos4/iocs.txt
* https://threatfox.abuse.ch
* https://www.fortinet.com/blog/threat-research/threat-group-targets-companies-in-taiwan
* https://www.malwarebytes.com/blog/threat-intel/2026/01/how-real-software-downloads-can-hide-remote-backdoors
* https://www.rapid7.com/blog/post/2025/05/22/nsis-abuse-and-srdi-shellcode-anatomy-of-the-winos-4-0-campaign/
* https://www.virustotal.com/gui/file/2d379424e6efae364807f515ff7e5cef56a46a98c812b14afa7a8211d263cdc9

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
