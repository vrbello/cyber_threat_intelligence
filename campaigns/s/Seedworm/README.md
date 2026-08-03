# Seedworm - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Seedworm_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Seedworm:

* [US](https://vuldb.com/country/us)
* [CH](https://vuldb.com/country/ch)
* [RU](https://vuldb.com/country/ru)
* ...

There are 21 more country items available. Please use our online service to access the data.

## Actors

These _actors_ are associated with Seedworm or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [MuddyWater](https://vuldb.com/actor/muddywater) | High
2 | [Seedworm](https://vuldb.com/actor/seedworm) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Seedworm.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [31.171.154.67](https://vuldb.com/ip/31.171.154.67) | - | [MuddyWater](https://vuldb.com/actor/muddywater) | High
2 | [34.117.59.81](https://vuldb.com/ip/34.117.59.81) | 81.59.117.34.bc.googleusercontent.com | [Seedworm](https://vuldb.com/actor/seedworm) | Medium
3 | [37.187.78.41](https://vuldb.com/ip/37.187.78.41) | ns3366607.ip-37-187-78.eu | [Seedworm](https://vuldb.com/actor/seedworm) | High
4 | ... | ... | ... | ...

There are 10 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Seedworm. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-21, CWE-22, CWE-24, CWE-29, CWE-35, CWE-36, CWE-425 | Path Traversal | High
2 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
3 | T1059 | CWE-88, CWE-94 | Argument Injection | High
4 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
5 | T1068 | CWE-250, CWE-264, CWE-266, CWE-269, CWE-274, CWE-284 | Execution with Unnecessary Privileges | High
6 | ... | ... | ... | ...

There are 19 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Seedworm. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?explorer/index/zip` | High
2 | File | `/add-subadmin.php` | High
3 | File | `/add_new_invoice.php` | High
4 | File | `/add_reference_to_local_model` | High
5 | File | `/add_user.php` | High
6 | File | `/admin.php?c=upload&f=zip&_noCache=0.1683794968` | High
7 | File | `/admin/?page=zone` | High
8 | File | `/admin/aboutus.php` | High
9 | File | `/admin/action/delete-vaccine.php` | High
10 | File | `/admin/actions/check-attendance.php` | High
11 | File | `/admin/add-table.php` | High
12 | File | `/admin/admin_running.php` | High
13 | File | `/Admin/akun_edit.php` | High
14 | File | `/admin/apply.php` | High
15 | File | `/admin/changeimage.php` | High
16 | File | `/Admin/changepassword.php` | High
17 | File | `/admin/completed-requests.php` | High
18 | File | `/admin/content/editor` | High
19 | File | `/admin/create-package.php` | High
20 | File | `/admin/delete_s6.php` | High
21 | File | `/admin/delete_user.php` | High
22 | File | `/admin/doAdminAction.php?act=addCate` | High
23 | File | `/admin/edit-art-product-detail.php?editid=2` | High
24 | File | `/admin/edit-brand.php` | High
25 | File | `/admin/edit-post.php` | High
26 | File | `/admin/edit-user.php` | High
27 | File | `/admin/edit_room.php` | High
28 | File | `/admin/emp-profile-avatar.php` | High
29 | File | `/admin/includes/edit_post.php` | High
30 | File | `/admin/index.php?page=user-profile` | High
31 | File | `/Admin/login.php` | High
32 | File | `/admin/login.php` | High
33 | File | `/admin/maintenance/manage_brand.php` | High
34 | File | `/admin/mechanics/manage_mechanic.php` | High
35 | File | `/admin/modules/room/index.php` | High
36 | File | `/admin/profile.php` | High
37 | File | `/Admin/Proses_Edit_Akun.php` | High
38 | File | `/admin/robot.php` | High
39 | File | `/admin/search-invoices.php` | High
40 | File | `/admin/SysModule/upload/ajaxmodel/upload/uploadfilepath/sysmodule_1` | High
41 | File | `/admin/tags/save` | High
42 | File | `/admin/twitter.php` | High
43 | File | `/admin/user-bookings.php` | High
44 | File | `/admin/user/index.php?view=edit` | High
45 | File | `/admin/yesterday-reg-users.php` | High
46 | File | `/adminapi/system/file/openfile` | High
47 | File | `/administrator/addcategory.php` | High
48 | File | `/Administrator/PHP/AdminUpdateUser.php` | High
49 | File | `/ajax.php?action=save_payroll` | High
50 | File | `/ajax.php?Ajax=GetModal_Sensor_Graph` | High
51 | File | `/alphaware/summary.php` | High
52 | File | `/api/admin` | Medium
53 | File | `/api/File/downloadFile` | High
54 | File | `/api/settings` | High
55 | File | `/api/store_integral/order/detail/:uni` | High
56 | File | `/api/sys/login` | High
57 | File | `/api/wizard/getCapability` | High
58 | File | `/api/wizard/setLanguage` | High
59 | File | `/app/api/controller/collect.php` | High
60 | File | `/app/api/v1/openvpn.py` | High
61 | File | `/app/controller/Api.php` | High
62 | File | `/app/index/controller/Common.php` | High
63 | File | `/app/register.php?action=reg` | High
64 | File | `/app/sys1.php` | High
65 | File | `/applications/core/modules/admin/editor/toolbar.php` | High
66 | File | `/Applications/Google\ Drive.app/Contents/MacOS` | High
67 | File | `/applications/nexus/modules/front/store/store.php` | High
68 | File | `/assetsGroupReport/assetsService.j%73p` | High
69 | File | `/auth.asp` | Medium
70 | File | `/backend/admin/his_admin_add_lab_equipment.php` | High
71 | File | `/backend/doc/his_doc_update-account.php` | High
72 | File | `/bin/httpd` | Medium
73 | File | `/biurl_grou` | Medium
74 | File | `/boaform/formSysCmd` | High
75 | File | `/boafrm/formDMZ` | High
76 | File | `/boafrm/formTmultiAP` | High
77 | File | `/borrow.php` | Medium
78 | File | `/browse.php` | Medium
79 | ... | ... | ...

There are 696 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://symantec-enterprise-blogs.security.com/blogs/threat-intelligence/seedworm-espionage-group
* https://www.security.com/threat-intelligence/iran-seedworm-electronics

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
