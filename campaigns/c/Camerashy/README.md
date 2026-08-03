# Camerashy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Camerashy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Camerashy:

* [US](https://vuldb.com/country/us)
* [FR](https://vuldb.com/country/fr)

## Actors

These _actors_ are associated with Camerashy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Naikon](https://vuldb.com/actor/naikon) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Camerashy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [50.117.115.89](https://vuldb.com/ip/50.117.115.89) | - | [Naikon](https://vuldb.com/actor/naikon) | High
2 | [50.117.115.90](https://vuldb.com/ip/50.117.115.90) | - | [Naikon](https://vuldb.com/actor/naikon) | High
3 | [65.19.141.203](https://vuldb.com/ip/65.19.141.203) | shibakov.org | [Naikon](https://vuldb.com/actor/naikon) | High
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-425 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | T1068 | CWE-264, CWE-269, CWE-272, CWE-284 | Execution with Unnecessary Privileges | High
7 | ... | ... | ... | ...

There are 22 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Camerashy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `- yudao-module-digitalcourse/yudao-module-digitalcourse-biz/src/main/java/cn/iocoder/yudao/module/digitalcourse/util/PPTUtil.java` | High
2 | File | `.authlie` | Medium
3 | File | `.xserverrc` | Medium
4 | File | `/+CSCOE+/logon.html` | High
5 | File | `/370project/process/eprocess.php` | High
6 | File | `/?\_route=customers/edit/` | High
7 | File | `/add-category-function.php` | High
8 | File | `/add_sales_print.php` | High
9 | File | `/admin/aboutus.php` | High
10 | File | `/admin/add-subadmins.php` | High
11 | File | `/admin/admin_feature.php` | High
12 | File | `/admin/ajax.php?action=get_cart_items` | High
13 | File | `/admin/ajax.php?action=save_order` | High
14 | File | `/admin/block_status.php` | High
15 | File | `/admin/check_studid.php` | High
16 | File | `/admin/delete_activity.php` | High
17 | File | `/admin/doctor_action.php` | High
18 | File | `/admin/index.php` | High
19 | File | `/admin/jobs-admins/delete-jobs.php` | High
20 | File | `/admin/manage-users.php` | High
21 | File | `/admin/manage_register.php` | High
22 | File | `/admin/manage_user.php` | High
23 | File | `/admin/navbar.php` | High
24 | File | `/admin/send_message.php` | High
25 | File | `/admin/tools.php` | High
26 | File | `/admin/update-image1.php` | High
27 | File | `/admin/update_s4.php` | High
28 | File | `/Administrator/PHP/AdminEditCategory.php` | High
29 | File | `/Administrator/PHP/AdminUpdateCategory.php` | High
30 | File | `/airag/knowledge/doc/edit` | High
31 | File | `/ajax.php?action=chk_prod_availability` | High
32 | File | `/ajax.php?action=save_category` | High
33 | File | `/ajax.php?action=save_expired` | High
34 | File | `/ajax.php?action=save_product` | High
35 | File | `/ajax.php?action=save_receiving` | High
36 | File | `/ajax.php?action=save_type` | High
37 | File | `/api/admin/plugins/install/actions/download` | High
38 | File | `/api/admin/sys-file/upload` | High
39 | File | `/api/ai-scanner/status-webhook` | High
40 | File | `/api/av/removeUnusedAttributeView` | High
41 | File | `/api/channels` | High
42 | File | `/api/google/authorize` | High
43 | File | `/api/Security/` | High
44 | File | `/api/suppliers/v1/suppliers//false` | High
45 | File | `/api/system/user/getAvatar` | High
46 | File | `/api/v1/account/reset-password` | High
47 | File | `/api/v1/mail/send` | High
48 | File | `/api/v1/public-chatbotConfig/:id` | High
49 | File | `/app/controller/share.class.php` | High
50 | File | `/appointments.php` | High
51 | File | `/AssignmentSection/submission/upload.php` | High
52 | File | `/backend/app/api/v1/module_common/file/controller.py` | High
53 | File | `/backend/app/api/v1/module_system/params/controller.py` | High
54 | File | `/bin/httpd` | Medium
55 | File | `/blog` | Low
56 | File | `/boaform/formLoopBack` | High
57 | File | `/boaform/formSamba` | High
58 | File | `/boaform/formTracert` | High
59 | File | `/boafrm/formDdns` | High
60 | File | `/boafrm/formDosCfg` | High
61 | File | `/boafrm/formOpMode` | High
62 | File | `/boafrm/formVpnConfigSetup` | High
63 | File | `/boafrm/formWlanSetup` | High
64 | File | `/cgi-bin/app_mgr.cgi` | High
65 | File | `/cgi-bin/cstecgi.cgi` | High
66 | File | `/cgi-bin/download_mgr.cgi` | High
67 | File | `/cgi-bin/file_center.cgi` | High
68 | File | `/cgi-bin/firewall.cgi` | High
69 | File | `/cgi-bin/hedwig.cgi` | High
70 | File | `/cgi-bin/login.cgi` | High
71 | File | `/cgi-bin/mbox-config?method=SET&section=update_interface_png` | High
72 | File | `/cgi-bin/nas.cgi` | High
73 | File | `/cgi-bin/wireless.cgi` | High
74 | File | `/cgi/timepro.cgi` | High
75 | File | `/checkupdatestatus.php` | High
76 | File | `/check_availability.php` | High
77 | File | `/company` | Medium
78 | File | `/console` | Medium
79 | File | `/console/api/installed-apps/conversations/` | High
80 | File | `/controller.php?action=add` | High
81 | File | `/controllers/Installer.php` | High
82 | File | `/create-ticket.php` | High
83 | File | `/curvus2/signup.php` | High
84 | File | `/data/pagesdata.txt` | High
85 | File | `/datasource/getTableField` | High
86 | File | `/dbfood/contact.php` | High
87 | ... | ... | ...

There are 772 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* http://cdn2.hubspot.net/hubfs/454298/Project_CAMERASHY_ThreatConnect_Copyright_2015.pdf

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
