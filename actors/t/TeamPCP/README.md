# TeamPCP - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [TeamPCP](https://vuldb.com/actor/teampcp). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/teampcp](https://vuldb.com/actor/teampcp)

## Campaigns

The following _campaigns_ are known and can be associated with TeamPCP:

* Aqua Security Trivy

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with TeamPCP:

* [US](https://vuldb.com/country/us)
* [DE](https://vuldb.com/country/de)
* [NL](https://vuldb.com/country/nl)
* ...

There are 2 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of TeamPCP.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [34.66.134.145](https://vuldb.com/ip/34.66.134.145) | 145.134.66.34.bc.googleusercontent.com | - | Medium
2 | [35.188.190.218](https://vuldb.com/ip/35.188.190.218) | 218.190.188.35.bc.googleusercontent.com | - | Medium
3 | [35.192.220.222](https://vuldb.com/ip/35.192.220.222) | 222.220.192.35.bc.googleusercontent.com | - | Medium
4 | ... | ... | ... | ...

There are 8 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _TeamPCP_. This data is unique as it uses our predictive model for actor profiling.

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

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by TeamPCP. This data is unique as it uses our predictive model for actor profiling.

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
22 | File | `/cgi-bin/hd_config.cgi` | High
23 | ... | ... | ...

There are 195 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://hunt.io/blog/teampcp-python-toolkit-firescale-github-c2-takedown
* https://research.jfrog.com/post/xinference-compromise/
* https://unit42.paloaltonetworks.com/monitoring-npm-supply-chain-attacks/
* https://www.mend.io/blog/compromised-bitwarden-cli-npm-worm-ai-poisoning/
* https://www.paloaltonetworks.com/blog/cloud-security/trivy-supply-chain-attack/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
