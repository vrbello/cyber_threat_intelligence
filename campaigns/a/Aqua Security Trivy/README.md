# Aqua Security Trivy - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Aqua Security Trivy_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Aqua Security Trivy:

* [US](https://vuldb.com/country/us)
* [DE](https://vuldb.com/country/de)
* [NL](https://vuldb.com/country/nl)

## Actors

These _actors_ are associated with Aqua Security Trivy or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [TeamPCP](https://vuldb.com/actor/teampcp) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Aqua Security Trivy.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [45.148.10.212](https://vuldb.com/ip/45.148.10.212) | - | [TeamPCP](https://vuldb.com/actor/teampcp) | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Aqua Security Trivy. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-35 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Aqua Security Trivy. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `%PROGRAMDATA%\checkmk\agent\local` | High
2 | File | `/admin/?/layout/add` | High
3 | File | `/admin/admin/save` | High
4 | File | `/admin/assets/plugins/DataTables/media/unit_testing/templates/deferred_table.php` | High
5 | File | `/admin/class-result.php` | High
6 | File | `/admin/dialog/select_images_post.php` | High
7 | File | `/admin/manage_register.php` | High
8 | File | `/admin/overtime_add.php` | High
9 | File | `/admin/pass-bwdates-reports-details.php` | High
10 | File | `/admin/property-details.php` | High
11 | File | `/Admin/Proses_Edit_Akun.php` | High
12 | File | `/admin/search-medicalcard.php` | High
13 | File | `/admin/tag/save` | High
14 | File | `/ajax.php` | Medium
15 | File | `/api/admin/common/download/templates` | High
16 | File | `/ASDKAPI/api/v8.6/item/addfile` | High
17 | File | `/att_single_view.php` | High
18 | File | `/boafrm/formNtp` | High
19 | File | `/boafrm/formVpnConfigSetup` | High
20 | File | `/boafrm/formWsc` | High
21 | File | `/cgi-bin/cstecgi.cgi` | High
22 | ... | ... | ...

There are 178 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.paloaltonetworks.com/blog/cloud-security/trivy-supply-chain-attack/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
