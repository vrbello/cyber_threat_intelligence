# ModeloRAT - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _ModeloRAT_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with ModeloRAT:

* [US](https://vuldb.com/country/us)
* [SG](https://vuldb.com/country/sg)
* [CN](https://vuldb.com/country/cn)
* ...

There are 7 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with ModeloRAT or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [KongTuke](https://vuldb.com/actor/kongtuke) | High
2 | [ModeloRAT](https://vuldb.com/actor/modelorat) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of ModeloRAT.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.59.122.231](https://vuldb.com/ip/45.59.122.231) | 231.122.59.45.static.cloudzy.com | [ModeloRAT](https://vuldb.com/actor/modelorat) | High
2 | [45.76.241.51](https://vuldb.com/ip/45.76.241.51) | 45.76.241.51.vultrusercontent.com | [ModeloRAT](https://vuldb.com/actor/modelorat) | Medium
3 | [46.225.231.170](https://vuldb.com/ip/46.225.231.170) | static.170.231.225.46.clients.your-server.de | [ModeloRAT](https://vuldb.com/actor/modelorat) | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within ModeloRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1059 | CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | ... | ... | ... | ...

There are 14 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during ModeloRAT. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin.php/addon/index` | High
2 | File | `/admin/bookList?page=1&limit=10` | High
3 | File | `/admin/create_product.php` | High
4 | File | `/admin/maintenance/view_designation.php` | High
5 | File | `/adminui/history_log.php` | High
6 | File | `/analysisProject/pagingQueryData` | High
7 | File | `/api/GylOperator/UpdatePasswordBatch` | High
8 | File | `/api /v3/auth` | High
9 | File | `/Applications/Endurance.app/Contents/Library/LaunchServices/com.MagnetismStudios.endurance.helper` | High
10 | File | `/att_add.php` | Medium
11 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
12 | File | `/backend/admin/his_admin_register_patient.php` | High
13 | File | `/bin/httpd` | Medium
14 | File | `/com/tiandy/easy7/core/bo/CLSBODownLoad.java` | High
15 | File | `/department.php` | High
16 | File | `/extensions/realestate/index.php/agents/agent-register/addagent` | High
17 | ... | ... | ...

There are 139 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.huntress.com/blog/malicious-browser-extention-crashfix-kongtuke
* https://www.rapid7.com/blog/post/tr-it-support-dissecting-modelorat-campaign-microsoft-teams-compromise/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
