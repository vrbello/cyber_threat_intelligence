# Payroll Pirate - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Payroll Pirate_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Payroll Pirate:

* [CA](https://vuldb.com/country/ca)
* [US](https://vuldb.com/country/us)
* [GB](https://vuldb.com/country/gb)

## Actors

These _actors_ are associated with Payroll Pirate or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Storm-2755](https://vuldb.com/actor/storm-2755) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Payroll Pirate.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [24.53.42.79](https://vuldb.com/ip/24.53.42.79) | modemcable079.42-53-24.mc.videotron.ca | [Storm-2755](https://vuldb.com/actor/storm-2755) | High
2 | [24.202.0.56](https://vuldb.com/ip/24.202.0.56) | modemcable056.0-202-24.mc.videotron.ca | [Storm-2755](https://vuldb.com/actor/storm-2755) | High
3 | [47.55.96.251](https://vuldb.com/ip/47.55.96.251) | drmons0561w-47-55-96-251.dhcp-dynamic.fibreop.ns.bellaliant.net | [Storm-2755](https://vuldb.com/actor/storm-2755) | High
4 | ... | ... | ... | ...

There are 14 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Payroll Pirate. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22 | Path Traversal | High
2 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
3 | T1068 | CWE-264, CWE-269 | Execution with Unnecessary Privileges | High
4 | ... | ... | ... | ...

There are 5 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Payroll Pirate. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/com/esafenet/servlet/client/DecryptApplicationService.java` | High
2 | File | `/etc/tomcat8/Catalina/attack` | High
3 | File | `index.php` | Medium
4 | ... | ... | ...

There are 13 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://sra.io/blog/payroll-pirate-campaign-aitm-session-hijacking-and-microsoft-graph-reconnaissance-across-multiple-client-environments/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
