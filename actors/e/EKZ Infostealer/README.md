# EKZ Infostealer - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [EKZ Infostealer](https://vuldb.com/actor/ekz_infostealer). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/ekz_infostealer](https://vuldb.com/actor/ekz_infostealer)

## Campaigns

The following _campaigns_ are known and can be associated with EKZ Infostealer:

* CVE-2026-35616

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with EKZ Infostealer:

* [US](https://vuldb.com/country/us)
* [ES](https://vuldb.com/country/es)
* [IO](https://vuldb.com/country/io)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of EKZ Infostealer.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [83.138.53.110](https://vuldb.com/ip/83.138.53.110) | - | CVE-2026-35616 | High
2 | [185.220.101.15](https://vuldb.com/ip/185.220.101.15) | berlin01.tor-exit.artikel10.org | CVE-2026-35616 | High
3 | [192.42.116.14](https://vuldb.com/ip/192.42.116.14) | this-is-a-tor-exit-node-hviv114.hviv.nl | CVE-2026-35616 | High

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _EKZ Infostealer_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | ... | ... | ... | ...

There are 15 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by EKZ Infostealer. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.claude/skills/design-system/scripts/generate-slide.py` | High
2 | File | `.claude/skills/ui-styling/scripts/tailwind_config_gen.py` | High
3 | File | `/?explorer/index/zip` | High
4 | File | `/accounts/chart-save` | High
5 | File | `/accounts/mr-save` | High
6 | File | `/addnewfaculty` | High
7 | File | `/admi.php/admin/addon/add.html` | High
8 | File | `/admin/?page=patients/view_patient` | High
9 | File | `/admin/?page=room_types` | High
10 | File | `/admin/addproduct.php` | High
11 | File | `/admin/add_sub_topic.php` | High
12 | File | `/admin/admin_class_novo.php` | High
13 | File | `/admin/ajax.php?action=add_to_cart` | High
14 | File | `/admin/ajax.php?action=delete_cart` | High
15 | File | `/admin/ajax.php?action=delete_category` | High
16 | File | `/admin/ajax.php?action=delete_menu` | High
17 | File | `/admin/ajax.php?action=get_cart_count` | High
18 | File | `/admin/ajax.php?action=login` | High
19 | File | `/admin/ajax.php?action=save_category` | High
20 | File | `/admin/ajax.php?action=save_menu` | High
21 | File | `/admin/ajax.php?action=save_order` | High
22 | File | `/admin/ajax.php?action=save_user` | High
23 | File | `/admin/block_status.php` | High
24 | File | `/admin/campsdetails.php` | High
25 | File | `/admin/checklogin.php` | High
26 | File | `/admin/dcat-api/editor-md/upload` | High
27 | File | `/admin/delete_judge.php` | High
28 | File | `/admin/edit_exercises.php` | High
29 | File | `/admin/edit_judge.php` | High
30 | File | `/admin/edit_team.php` | High
31 | File | `/admin/index.php?page=save_settings` | High
32 | File | `/admin/jobs-admins/delete-jobs.php` | High
33 | File | `/admin/message.php` | High
34 | File | `/admin/modules/student/index.php?view=view` | High
35 | File | `/admin/modules/student/trans.php` | High
36 | File | `/admin/patients/manage_history.php` | High
37 | File | `/admin/patients/view_history.php` | High
38 | File | `/admin/plugin_antispam` | High
39 | File | `/admin/productedit.php` | High
40 | File | `/admin/search_staff_to_assign_pc.php` | High
41 | File | `/admin/update/` | High
42 | File | `/admin/update_customer.php` | High
43 | File | `/admin/update_ss_img.php` | High
44 | File | `/admin/view_order.php` | High
45 | File | `/adminaccount.php` | High
46 | File | `/Administrator/PHP/AdminDeleteAlbum.php` | High
47 | File | `/Administrator/PHP/AdminEditAlbum.php` | High
48 | File | `/Administrator/PHP/AdminUpdateAlbum.php` | High
49 | File | `/airag/app/debug` | High
50 | File | `/ajax.php` | Medium
51 | File | `/ajax.php?action=delete_category` | High
52 | File | `/ajax.php?action=delete_expired` | High
53 | File | `/ajax.php?action=delete_product` | High
54 | File | `/ajax.php?action=delete_supplier` | High
55 | File | `/ajax.php?action=login` | High
56 | File | `/ajax.php?action=save_category` | High
57 | File | `/ajax.php?action=save_expired` | High
58 | File | `/ajax.php?action=save_product` | High
59 | File | `/ajax.php?action=save_receiving` | High
60 | File | `/ajax.php?action=save_supplier` | High
61 | File | `/ajax.php?action=save_type` | High
62 | File | `/ajax.php?action=save_user` | High
63 | File | `/api/Dinner/PayConfig` | High
64 | File | `/api/health` | Medium
65 | File | `/api/skills/delete` | High
66 | File | `/api/v1/provision` | High
67 | File | `/app/controller/systemRole.class.php` | High
68 | File | `/apply.cgi` | Medium
69 | File | `/archive3.php` | High
70 | File | `/askquery.php` | High
71 | File | `/attendance-php/Admin/createClass.php` | High
72 | File | `/auto_reboot.asp` | High
73 | File | `/backend/admin/his_admin_account.php` | High
74 | File | `/Base/BaseService.asmx/DataService` | High
75 | File | `/bin/httpd` | Medium
76 | File | `/Blog/BlogSearch.aspx` | High
77 | File | `/boaform/admin/formgponConf` | High
78 | File | `/boaform/formCountrystr` | High
79 | File | `/boaform/formTracert` | High
80 | File | `/boafrm/formDdns` | High
81 | File | `/boafrm/formSmsManage` | High
82 | File | `/boafrm/formVpnConfigSetup` | High
83 | File | `/boafrm/formWsc` | High
84 | File | `/booking.php` | Medium
85 | File | `/C6/JHSoft.Web.ModuleCount/GetFormSn.aspx` | High
86 | File | `/cdemos/echs/api/v2/` | High
87 | File | `/cdemos/echs/api/v2/patient-records` | High
88 | File | `/cdemos/echs/priv/echs.js` | High
89 | File | `/cgi-bin/adm.cgi` | High
90 | File | `/cgi-bin/cstecgi.cgi` | High
91 | File | `/cgi-bin/login.cgi` | High
92 | File | `/cgi-bin/network_mgr.cgi` | High
93 | File | `/cgi-bin/webfile_mgr.cgi` | High
94 | File | `/cgi/advanced/misc_main.cgi` | High
95 | File | `/cgi/iux_set.cgi` | High
96 | File | `/cims/modules/admin/reply.php` | High
97 | File | `/classes/Master.php?f=save_patient_history` | High
98 | File | `/classes/Users.php?f=delete` | High
99 | File | `/classes/Users.php?f=save` | High
100 | File | `/common/jsp/upload3.jsp` | High
101 | File | `/common/upload` | High
102 | File | `/company` | Medium
103 | File | `/dashboard_page/forms/fetch.php` | High
104 | File | `/download.php` | High
105 | File | `/edithousepic.php` | High
106 | File | `/edit_branch.php` | High
107 | File | `/edit_staff.php` | High
108 | File | `/eloginwel.php` | High
109 | File | `/etc/boa.conf` | High
110 | File | `/etc/init.d/run_central2.sh` | High
111 | File | `/Export_csv/export` | High
112 | File | `/feed/UploadImage.do` | High
113 | File | `/Frontend/Search.php` | High
114 | File | `/goform/addressNat` | High
115 | File | `/goform/aspForm` | High
116 | File | `/goform/DelFil` | High
117 | File | `/goform/DhcpListClient` | High
118 | File | `/goform/formAccep` | High
119 | File | `/goform/formAccept` | High
120 | File | `/goform/formConnectionSetting` | High
121 | ... | ... | ...

There are 1075 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://arcticwolf.com/resources/blog/forticlient-ems-exploited-via-cve-2026-35616-to-deliver-ekz-infostealer-disguised-as-a-fortinet-patch/

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
