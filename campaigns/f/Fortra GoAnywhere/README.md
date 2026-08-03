# Fortra GoAnywhere - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Fortra GoAnywhere_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Fortra GoAnywhere:

* [US](https://vuldb.com/country/us)
* [NL](https://vuldb.com/country/nl)
* [GB](https://vuldb.com/country/gb)
* ...

There are 2 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Fortra GoAnywhere or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [Clop](https://vuldb.com/actor/clop) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Fortra GoAnywhere.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [3.101.53.11](https://vuldb.com/ip/3.101.53.11) | ec2-3-101-53-11.us-west-1.compute.amazonaws.com | [Clop](https://vuldb.com/actor/clop) | Medium
2 | [5.34.178.28](https://vuldb.com/ip/5.34.178.28) | s41.friendhosting.net | [Clop](https://vuldb.com/actor/clop) | High
3 | [5.34.178.30](https://vuldb.com/ip/5.34.178.30) | dedic-hghdgsjhdgjhgdj67tyu687uy-1209043.hosted-by-itldc.com | [Clop](https://vuldb.com/actor/clop) | High
4 | [5.34.178.31](https://vuldb.com/ip/5.34.178.31) | free.ds | [Clop](https://vuldb.com/actor/clop) | High
5 | [5.34.180.48](https://vuldb.com/ip/5.34.180.48) | mail.tube-plant.com | [Clop](https://vuldb.com/actor/clop) | High
6 | [15.235.13.184](https://vuldb.com/ip/15.235.13.184) | gollum.utwb.net | [Clop](https://vuldb.com/actor/clop) | High
7 | [15.235.83.73](https://vuldb.com/ip/15.235.83.73) | web0.meritusedu.ca | [Clop](https://vuldb.com/actor/clop) | High
8 | [20.47.120.195](https://vuldb.com/ip/20.47.120.195) | - | [Clop](https://vuldb.com/actor/clop) | High
9 | [24.3.132.168](https://vuldb.com/ip/24.3.132.168) | c-24-3-132-168.hsd1.pa.comcast.net | [Clop](https://vuldb.com/actor/clop) | High
10 | ... | ... | ... | ...

There are 34 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Fortra GoAnywhere. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `.claude/skills/ui-styling/scripts/tailwind_config_gen.py` | High
2 | File | `.github/workflows/combine-prs.yml` | High
3 | File | `/?explorer/index/zip` | High
4 | File | `/?_route=settings/users-view/` | High
5 | File | `/accounts/chart-save` | High
6 | File | `/add.php` | Medium
7 | File | `/addnewfaculty` | High
8 | File | `/addprojectsale.php` | High
9 | File | `/add_personal_details.php` | High
10 | File | `/admi.php/admin/addon/add.html` | High
11 | File | `/admin-cp/theme/editor/default` | High
12 | File | `/admin/?page=patients/view_patient` | High
13 | File | `/admin/?page=room_types` | High
14 | File | `/admin/?page=user/manage_user` | High
15 | File | `/admin/add-services.php` | High
16 | File | `/admin/addgiving.php` | High
17 | File | `/admin/addproduct.php` | High
18 | File | `/admin/admin-add-employee.php` | High
19 | File | `/admin/admin_class_novo.php` | High
20 | File | `/admin/admin_user.php` | High
21 | File | `/admin/ajax.php?action=add_to_cart` | High
22 | File | `/admin/ajax.php?action=delete_cart` | High
23 | File | `/admin/ajax.php?action=delete_category` | High
24 | File | `/admin/ajax.php?action=delete_menu` | High
25 | File | `/admin/ajax.php?action=get_cart_count` | High
26 | File | `/admin/ajax.php?action=save_category` | High
27 | File | `/admin/ajax.php?action=save_order` | High
28 | File | `/admin/ajax.php?action=save_user` | High
29 | File | `/admin/applicants/controller.php` | High
30 | File | `/admin/categories/save` | High
31 | File | `/admin/category/add.do` | High
32 | File | `/admin/content/editor` | High
33 | File | `/admin/dcat-api/editor-md/upload` | High
34 | File | `/admin/delete_judge.php` | High
35 | File | `/admin/edit_judge.php` | High
36 | File | `/admin/edit_team.php` | High
37 | File | `/admin/get_balance.php` | High
38 | File | `/admin/index.php?page=save_settings` | High
39 | File | `/admin/jobs-admins/delete-jobs.php` | High
40 | File | `/admin/list_onlineuser.php` | High
41 | File | `/admin/login.php` | High
42 | File | `/admin/message.php` | High
43 | File | `/admin/modules/student/trans.php` | High
44 | File | `/admin/mod_amenities/controller.php?action=edit` | High
45 | File | `/admin/mod_room/controller.php?action=add` | High
46 | File | `/admin/mod_users/controller.php?action=add` | High
47 | File | `/admin/mod_users/controller.php?action=edit` | High
48 | File | `/admin/patients/manage_history.php` | High
49 | File | `/admin/patients/view_history.php` | High
50 | File | `/admin/plugin_antispam` | High
51 | File | `/admin/productedit.php` | High
52 | File | `/admin/report.php` | High
53 | File | `/admin/search_staff_to_assign_pc.php` | High
54 | File | `/admin/update/` | High
55 | File | `/admin/update_customer.php` | High
56 | File | `/admin/update_ss_img.php` | High
57 | File | `/admin/view_order.php` | High
58 | File | `/adminaccount.php` | High
59 | File | `/Administrator/PHP/AdminDeleteAlbum.php` | High
60 | File | `/Administrator/PHP/AdminEditAlbum.php` | High
61 | File | `/Administrator/PHP/AdminUpdateAlbum.php` | High
62 | File | `/adminPage/main/upload` | High
63 | File | `/adminpanel/admin/facebox_modal/updateExaminee.php` | High
64 | File | `/ajax.php` | Medium
65 | File | `/ajax.php?action=delete_category` | High
66 | File | `/ajax.php?action=delete_expired` | High
67 | File | `/ajax.php?action=delete_product` | High
68 | File | `/ajax.php?action=delete_supplier` | High
69 | File | `/ajax.php?action=save_category` | High
70 | File | `/ajax.php?action=save_expired` | High
71 | File | `/ajax.php?action=save_product` | High
72 | File | `/ajax.php?action=save_supplier` | High
73 | File | `/ajaxmedicine.php` | High
74 | File | `/apartment-visitor/report.php` | High
75 | File | `/apartment-visitor/visitor-entry.php` | High
76 | File | `/api/admin/store/product/save` | High
77 | File | `/api/Dinner/PayConfig` | High
78 | File | `/api/file/downloadfile` | High
79 | File | `/api/job/add/` | High
80 | File | `/api/mjkj-chat/chat/ai/delete/chat` | High
81 | File | `/api/skills/delete` | High
82 | File | `/api/users_handler.php` | High
83 | File | `/api/v1/provision` | High
84 | File | `/api/v1/toolbox/device/update/swap` | High
85 | File | `/api/wizard/getCapability` | High
86 | File | `/api/wizard/getCapabilityWeb` | High
87 | File | `/api/wizard/getLanguage` | High
88 | File | `/api/wizard/getsyncpppoecfg` | High
89 | File | `/app/controller/share.class.php` | High
90 | File | `/app/controller/systemRole.class.php` | High
91 | File | `/application/install/index.php` | High
92 | File | `/appointmentapproval.php` | High
93 | File | `/appointmentdetail.php` | High
94 | File | `/archive.php` | Medium
95 | File | `/archive1.php` | High
96 | File | `/archive2.php` | High
97 | File | `/archive3.php` | High
98 | File | `/askquery.php` | High
99 | File | `/attendance-php/Admin/createClass.php` | High
100 | File | `/attendance-php/Admin/createClassArms.php` | High
101 | File | `/auto_reboot.asp` | High
102 | File | `/backend/admin/his_admin_account.php` | High
103 | File | `/backend/register.php` | High
104 | File | `/base-boot/actuator` | High
105 | File | `/Base/BaseService.asmx/DataService` | High
106 | File | `/bin/gpio` | Medium
107 | File | `/bin/httpd` | Medium
108 | File | `/boaform/admin/formgponConf` | High
109 | File | `/boaform/formCountrystr` | High
110 | File | `/boaform/formTracert` | High
111 | File | `/boafrm/formDdns` | High
112 | File | `/boafrm/formSmsManage` | High
113 | File | `/boafrm/formUSSDSetup` | High
114 | File | `/boafrm/formVpnConfigSetup` | High
115 | File | `/boat-details.php` | High
116 | File | `/booking.php` | Medium
117 | File | `/BRS_top.html` | High
118 | File | `/C6/JHSoft.Web.ModuleCount/GetFormSn.aspx` | High
119 | File | `/cap.js` | Low
120 | File | `/cdemos/echs/api/v2/` | High
121 | File | `/cdemos/echs/priv/echs.js` | High
122 | File | `/cgi-bin/adm.cgi` | High
123 | File | `/cgi-bin/cstecgi.cgi` | High
124 | File | `/cgi-bin/glc` | Medium
125 | File | `/cgi-bin/login.cgi` | High
126 | File | `/cgi-bin/network_mgr.cgi` | High
127 | File | `/cgi-bin/ping.cgi` | High
128 | File | `/cgi-bin/widget_api.cgi` | High
129 | File | `/cgi-bin/wireless.cgi` | High
130 | File | `/cgi/advanced/misc_main.cgi` | High
131 | File | `/cgi/iux_set.cgi` | High
132 | File | `/checkout` | Medium
133 | File | `/cims/modules/admin/reply.php` | High
134 | File | `/classes/Master.php?f=save_patient_history` | High
135 | File | `/classes/SystemSettings.php?f=update_settings` | High
136 | ... | ... | ...

There are 1211 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.cisa.gov/news-events/cybersecurity-advisories/aa23-158a

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
