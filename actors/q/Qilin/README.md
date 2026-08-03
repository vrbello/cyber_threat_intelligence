# Qilin - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [Qilin](https://vuldb.com/actor/qilin). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/qilin](https://vuldb.com/actor/qilin)

## Campaigns

The following _campaigns_ are known and can be associated with Qilin:

* CVE-2025-31324
* CVE-2026-50751

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Qilin:

* [US](https://vuldb.com/country/us)
* [CN](https://vuldb.com/country/cn)
* [GB](https://vuldb.com/country/gb)
* ...

There are 21 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Qilin.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [23.27.140.108](https://vuldb.com/ip/23.27.140.108) | - | - | High
2 | [23.27.143.170](https://vuldb.com/ip/23.27.143.170) | - | - | High
3 | [31.41.244.100](https://vuldb.com/ip/31.41.244.100) | - | - | High
4 | [31.57.38.155](https://vuldb.com/ip/31.57.38.155) | - | - | High
5 | [31.57.147.229](https://vuldb.com/ip/31.57.147.229) | - | - | High
6 | [38.54.88.201](https://vuldb.com/ip/38.54.88.201) | - | CVE-2026-50751 | High
7 | [38.54.107.167](https://vuldb.com/ip/38.54.107.167) | - | CVE-2026-50751 | High
8 | [38.60.157.139](https://vuldb.com/ip/38.60.157.139) | - | CVE-2026-50751 | High
9 | [45.76.26.42](https://vuldb.com/ip/45.76.26.42) | 45.76.26.42.vultrusercontent.com | CVE-2026-50751 | Medium
10 | ... | ... | ... | ...

There are 36 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Qilin_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-23, CWE-27, CWE-28, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-264, CWE-266, CWE-269, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Qilin. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/abs.php` | Medium
2 | File | `/Account/login.php` | High
3 | File | `/act/ActDao.xml` | High
4 | File | `/action.php` | Medium
5 | File | `/action/docker/open_subshell` | High
6 | File | `/activation.php` | High
7 | File | `/ad-list` | Medium
8 | File | `/add-admin.php` | High
9 | File | `/add-table.php` | High
10 | File | `/admin#themes` | High
11 | File | `/admin/?page=categories/view_category` | High
12 | File | `/admin/add-doctor.php` | High
13 | File | `/admin/admin_feature.php` | High
14 | File | `/admin/admin_login.php` | High
15 | File | `/admin/ajax.php?action=login` | High
16 | File | `/admin/bookList?page=1&limit=10` | High
17 | File | `/admin/case-type` | High
18 | File | `/admin/contact-us.php` | High
19 | File | `/admin/create_product.php` | High
20 | File | `/admin/div_data/data` | High
21 | File | `/admin/edit_manufacturer.php` | High
22 | File | `/admin/index.php` | High
23 | File | `/admin/ind_backstage.php` | High
24 | File | `/admin/login.php` | High
25 | File | `/admin/manage-services.php` | High
26 | File | `/admin/media_folders` | High
27 | File | `/admin/memberOnline_deal.php?mudi=del&dataType=&dataID=6` | High
28 | File | `/admin/menu.php` | High
29 | File | `/admin/robot.php` | High
30 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
31 | File | `/admin/users.php` | High
32 | File | `/admin/user_update.php` | High
33 | File | `/ajax.php` | Medium
34 | File | `/ajax.php?action=delete_tenant` | High
35 | File | `/api/controllers/merchant/shop/PosterController.php` | High
36 | File | `/api/system/other` | High
37 | File | `/api/upload` | Medium
38 | File | `/api/wizard/getBasicInfo` | High
39 | File | `/app/platform/controllers/ResetpwdController.php` | High
40 | File | `/AttendanceMonitoring/report/index.php` | High
41 | File | `/authMonitCallcenter` | High
42 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
43 | File | `/backend/admin/his_admin_register_patient.php` | High
44 | File | `/backend/register.php` | High
45 | File | `/bin/boa` | Medium
46 | File | `/bloodrequest.php` | High
47 | File | `/boafrm/formFilter` | High
48 | File | `/booklist.php` | High
49 | File | `/bsms_ci/index.php/book` | High
50 | File | `/cgi-bin/cstecgi.cgi` | High
51 | File | `/cgi-bin/downloadFile.cgi` | High
52 | File | `/cgi-bin/hd_config.cgi` | High
53 | File | `/cgi-bin/mainfunction.cgi/apmcfgupload` | High
54 | File | `/cgi-bin/photocenter_mgr.cgi` | High
55 | File | `/cgi-bin/wapopen` | High
56 | File | `/classes/Master.php` | High
57 | File | `/classes/Master.php?f=delete_category` | High
58 | File | `/classes/Master.php?f=log_employee` | High
59 | File | `/classes/Master.php?f=save_medicine` | High
60 | File | `/classes/Master.php?f=save_package` | High
61 | File | `/classes/SystemSettings.php?f=update_settings` | High
62 | ... | ... | ...

There are 540 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.bushidotoken.net/2024/06/tracking-adversaries-qilin-raas.html
* https://circleid.com/posts/a-look-back-at-the-top-10-ransomware-of-2025
* https://ctrlaltintel.com/research/Qilin/
* https://darktrace.com/blog/a-busy-agenda-darktraces-detection-of-qilin-ransomware-as-a-service-operator
* https://exchange.xforce.ibmcloud.com/report/details/guid:0c04ac691a4a4b1abab121043776b959
* https://github.com/Cisco-Talos/IOCs/blob/main/2025/10/uncovering-qilin-attack-methods-exposed-through-multiple-cases.txt
* https://op-c.net/blog/sap-cve-2025-31324-qilin-breach/
* https://trojan-killer.net/check-point-vpn-cve-2026-50751-qilin-ransomware/
* https://windowsir.blogspot.com/2025/09/ransomware-artifacts.html
* https://www.cybereason.com/blog/threat-alert-qilin-seizes-control
* https://www.huntress.com/blog/looking-at-qilin-ransomware-attack

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
