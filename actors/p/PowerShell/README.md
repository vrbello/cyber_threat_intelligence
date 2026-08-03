# PowerShell - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [PowerShell](https://vuldb.com/actor/powershell). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/powershell](https://vuldb.com/actor/powershell)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with PowerShell:

* [US](https://vuldb.com/country/us)
* [CN](https://vuldb.com/country/cn)
* [GB](https://vuldb.com/country/gb)
* ...

There are 16 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of PowerShell.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.8.18.46](https://vuldb.com/ip/5.8.18.46) | vm19313.hyper.hosting | - | High
2 | [5.8.19.43](https://vuldb.com/ip/5.8.19.43) | vm19315.hyper.hosting | - | High
3 | [5.101.85.24](https://vuldb.com/ip/5.101.85.24) | vm19311.hyper.hosting | - | High
4 | [18.194.67.137](https://vuldb.com/ip/18.194.67.137) | ec2-18-194-67-137.eu-central-1.compute.amazonaws.com | - | Medium
5 | [23.105.182.6](https://vuldb.com/ip/23.105.182.6) | - | - | High
6 | [38.240.55.52](https://vuldb.com/ip/38.240.55.52) | - | - | High
7 | [43.153.201.105](https://vuldb.com/ip/43.153.201.105) | - | - | High
8 | [43.156.137.45](https://vuldb.com/ip/43.156.137.45) | - | - | High
9 | [45.74.10.38](https://vuldb.com/ip/45.74.10.38) | - | - | High
10 | [45.76.53.253](https://vuldb.com/ip/45.76.53.253) | 45.76.53.253.vultrusercontent.com | - | Medium
11 | [45.144.212.54](https://vuldb.com/ip/45.144.212.54) | - | - | High
12 | [45.153.34.90](https://vuldb.com/ip/45.153.34.90) | - | - | High
13 | [45.156.87.17](https://vuldb.com/ip/45.156.87.17) | - | - | High
14 | [45.221.99.101](https://vuldb.com/ip/45.221.99.101) | spk.laws.ms | - | High
15 | ... | ... | ... | ...

There are 56 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _PowerShell_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22 | Path Traversal | High
2 | T1040 | CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by PowerShell. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/admin-api/system/tenant/get-by-website` | High
2 | File | `/admin-cp/file-manager/upload` | High
3 | File | `/admin/` | Low
4 | File | `/admin/?action=home&do=shop:index&keyword=&kind=all` | High
5 | File | `/admin/admin-area.php` | High
6 | File | `/admin/blog/comment/create` | High
7 | File | `/admin/bwdates-reports-details.php` | High
8 | File | `/admin/category/controller.php` | High
9 | File | `/admin/create_product.php` | High
10 | File | `/admin/delete_pending.php` | High
11 | File | `/admin/general.cgi` | High
12 | File | `/admin/login-back.php` | High
13 | File | `/admin/login.php` | High
14 | File | `/admin/member_save.php` | High
15 | File | `/admin/quesadd.php` | High
16 | File | `/admin/reminders/manage_reminder.php` | High
17 | File | `/admin/return_add.php` | High
18 | File | `/admin/suppliers/view_details.php` | High
19 | File | `/admin/twitter.php` | High
20 | File | `/admin/view-enquiry.php` | High
21 | File | `/admin/view-progress-report.php` | High
22 | File | `/admin_area/index.php` | High
23 | File | `/ajax/getBasicInfo.php` | High
24 | File | `/ajax/php/leaf_search.php` | High
25 | File | `/API/info` | Medium
26 | File | `/apply/index.php` | High
27 | File | `/att_add.php` | Medium
28 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
29 | File | `/backend/admin/his_admin_register_patient.php` | High
30 | File | `/be/erpc.php` | Medium
31 | File | `/be/rpc.php` | Medium
32 | File | `/Bloodgroop_process.php` | High
33 | File | `/borrow.php` | Medium
34 | File | `/cancelbookingpatient.php` | High
35 | File | `/CCMAdmin/serverlist.asp` | High
36 | File | `/cgi-bin/cstecgi.cgi` | High
37 | File | `/cgi-bin/jumpto.php?class=user&page=config_save&isphp=1` | High
38 | File | `/cgi-bin/luci/admin/network/wireless/config/` | High
39 | File | `/cgi-bin/nas_sharing.cgi` | High
40 | File | `/cgi-bin/system_mgr.cgi` | High
41 | File | `/cgi/get_param.cgi` | High
42 | File | `/classes/Master.php?f=delete_record` | High
43 | File | `/clearance/clearance.php` | High
44 | File | `/complainer_page.php` | High
45 | File | `/csms/admin/inquiries/view_details.php` | High
46 | File | `/cstecgi.cgi` | Medium
47 | File | `/database?action=GetDatabaseAccess` | High
48 | File | `/Digital-Infrastructure-9.6.7/y9-digitalbase-webapp/y9-module-filemanager/risenet-y9boot-webapp-filemanager/src/main/java/net/risesoft/y9public/controller/Y9FileController.java` | High
49 | File | `/download.php` | High
50 | File | `/ecommerce/admin/login.php` | High
51 | File | `/ecommerce/popup_Item.php` | High
52 | File | `/ecommerce/support_ticket` | High
53 | File | `/emap/devicePoint_addImgIco?hasSubsystem=true` | High
54 | File | `/forum/away.php` | High
55 | File | `/function/login.php` | High
56 | File | `/goform/AdvSetWrlsafeset` | High
57 | File | `/goform/execCommand` | High
58 | ... | ... | ...

There are 505 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.cyble.com/2022/06/03/cve-2022-30190-actively-exploited-in-the-wild/
* https://blog.talosintelligence.com/2019/01/threat-roundup-0111-0118.html
* https://community.blueliv.com/#!/s/6192412f82df413eb2354f9a
* https://urlhaus.abuse.ch/url/3524502/
* https://urlhaus.abuse.ch/url/3567832/
* https://urlhaus.abuse.ch/url/3569952/
* https://urlhaus.abuse.ch/url/3599447/
* https://urlhaus.abuse.ch/url/3599644/
* https://urlhaus.abuse.ch/url/3609961/
* https://urlhaus.abuse.ch/url/3610665/
* https://urlhaus.abuse.ch/url/3611366/
* https://urlhaus.abuse.ch/url/3611800/
* https://urlhaus.abuse.ch/url/3615937/
* https://urlhaus.abuse.ch/url/3616524/
* https://urlhaus.abuse.ch/url/3616526/
* https://urlhaus.abuse.ch/url/3626882/
* https://urlhaus.abuse.ch/url/3631737/
* https://urlhaus.abuse.ch/url/3634931/
* https://urlhaus.abuse.ch/url/3646386/
* https://urlhaus.abuse.ch/url/3662661/
* https://urlhaus.abuse.ch/url/3667202/
* https://urlhaus.abuse.ch/url/3682323/
* https://urlhaus.abuse.ch/url/3682727/
* https://urlhaus.abuse.ch/url/3683249/
* https://urlhaus.abuse.ch/url/3684667/
* https://urlhaus.abuse.ch/url/3684822/
* https://urlhaus.abuse.ch/url/3695595/
* https://urlhaus.abuse.ch/url/3710980/
* https://urlhaus.abuse.ch/url/3713982/
* https://urlhaus.abuse.ch/url/3724206/
* https://urlhaus.abuse.ch/url/3729323/
* https://urlhaus.abuse.ch/url/3729354/
* https://urlhaus.abuse.ch/url/3730390/
* https://urlhaus.abuse.ch/url/3730914/
* https://urlhaus.abuse.ch/url/3733972/
* https://urlhaus.abuse.ch/url/3734653/
* https://urlhaus.abuse.ch/url/3736690/
* https://urlhaus.abuse.ch/url/3740904/
* https://urlhaus.abuse.ch/url/3741045/
* https://urlhaus.abuse.ch/url/3741406/
* https://urlhaus.abuse.ch/url/3747726/
* https://urlhaus.abuse.ch/url/3749517/
* https://urlhaus.abuse.ch/url/3757522/
* https://urlhaus.abuse.ch/url/3758276/
* https://urlhaus.abuse.ch/url/3759043/
* https://urlhaus.abuse.ch/url/3764550/
* https://urlhaus.abuse.ch/url/3765965/
* https://urlhaus.abuse.ch/url/3766139/
* https://urlhaus.abuse.ch/url/3766234/
* https://urlhaus.abuse.ch/url/3772041/
* https://urlhaus.abuse.ch/url/3775068/
* https://urlhaus.abuse.ch/url/3776359/
* https://urlhaus.abuse.ch/url/3776553/
* https://urlhaus.abuse.ch/url/3779400/
* https://urlhaus.abuse.ch/url/3780288/
* https://urlhaus.abuse.ch/url/3784159/
* https://urlhaus.abuse.ch/url/3784261/
* https://urlhaus.abuse.ch/url/3787613/
* https://urlhaus.abuse.ch/url/3794058/
* https://urlhaus.abuse.ch/url/3794062/
* https://urlhaus.abuse.ch/url/3794733/
* https://urlhaus.abuse.ch/url/3802587/
* https://urlhaus.abuse.ch/url/3806858/
* https://urlhaus.abuse.ch/url/3824458/
* https://urlhaus.abuse.ch/url/3828510/
* https://urlhaus.abuse.ch/url/3842131/
* https://urlhaus.abuse.ch/url/3844941/
* https://urlhaus.abuse.ch/url/3850504/
* https://urlhaus.abuse.ch/url/3854909/
* https://urlhaus.abuse.ch/url/3861696/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
