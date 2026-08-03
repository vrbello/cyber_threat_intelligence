# Salesforce Experience Cloud Site - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the campaign known as _Salesforce Experience Cloud Site_. The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor](https://vuldb.com/actor)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Salesforce Experience Cloud Site:

* [VN](https://vuldb.com/country/vn)
* [SG](https://vuldb.com/country/sg)

## Actors

These _actors_ are associated with Salesforce Experience Cloud Site or other actors linked to the campaign.

ID | Actor | Confidence
-- | ----- | ----------
1 | [ShinyHunters](https://vuldb.com/actor/shinyhunters) | High

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Salesforce Experience Cloud Site.

ID | IP address | Hostname | Actor | Confidence
-- | ---------- | -------- | ----- | ----------
1 | [54.251.184.9](https://vuldb.com/ip/54.251.184.9) | ec2-54-251-184-9.ap-southeast-1.compute.amazonaws.com | [ShinyHunters](https://vuldb.com/actor/shinyhunters) | Medium
2 | [88.216.68.137](https://vuldb.com/ip/88.216.68.137) | ip-88-216-68-137.010.ptr.cherryservers.net | [ShinyHunters](https://vuldb.com/actor/shinyhunters) | High
3 | [138.199.60.10](https://vuldb.com/ip/138.199.60.10) | - | [ShinyHunters](https://vuldb.com/actor/shinyhunters) | High
4 | ... | ... | ... | ...

There are 1 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used within Salesforce Experience Cloud Site. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-80 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 21 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration during Salesforce Experience Cloud Site. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/?page=reports` | High
2 | File | `/add-computer.php` | High
3 | File | `/add-customer.php` | High
4 | File | `/addcompany.php` | High
5 | File | `/admin-api/infra/file/upload` | High
6 | File | `/admin.php` | Medium
7 | File | `/admin/about_edit.php?action=modify` | High
8 | File | `/admin/add-customer.php` | High
9 | File | `/admin/add-services.php` | High
10 | File | `/admin/addmanagerclinic.php` | High
11 | File | `/admin/add_account.php` | High
12 | File | `/admin/add_candidate_modal.php.` | High
13 | File | `/admin/add_sundaysch.php` | High
14 | File | `/admin/admin-profile.php` | High
15 | File | `/admin/adminHome.php` | High
16 | File | `/admin/admin_feature.php` | High
17 | File | `/admin/ajax.php?action=login2` | High
18 | File | `/admin/approve.php` | High
19 | File | `/admin/category.php` | High
20 | File | `/admin/category_save.php` | High
21 | File | `/Admin/changepassword.php` | High
22 | File | `/admin/check_availability.php` | High
23 | File | `/admin/class.php` | High
24 | File | `/admin/delete_account.php` | High
25 | File | `/admin/del_service.php` | High
26 | File | `/admin/doctors.php` | High
27 | File | `/admin/edit-art-medium-detail.php` | High
28 | File | `/admin/edit-art-product-detail.php?editid=2` | High
29 | File | `/admin/edit-pass-detail.php` | High
30 | File | `/admin/edit-user-profile.php` | High
31 | File | `/admin/edit_room.php` | High
32 | File | `/admin/forgot-password.php` | High
33 | File | `/admin/forms/option_lists/edit.php` | High
34 | File | `/admin/general-setting` | High
35 | File | `/admin/group/list/` | High
36 | File | `/admin/index.php` | High
37 | File | `/admin/login.php` | High
38 | File | `/admin/manage-users.php` | High
39 | File | `/admin/orders/update_status.php` | High
40 | File | `/admin/pages_account.php` | High
41 | File | `/admin/print1.php` | High
42 | File | `/admin/search-appointment.php` | High
43 | File | `/admin/search-booking-request.php` | High
44 | File | `/admin/sn_package/sn_https` | High
45 | File | `/admin/sou.php` | High
46 | File | `/admin/subcategory.php` | High
47 | File | `/admin/update-image1.php` | High
48 | File | `/admin/update_s3.php` | High
49 | File | `/admin/update_student.php` | High
50 | File | `/admin/view-appointment.php` | High
51 | File | `/admin/view_reserved.php` | High
52 | File | `/adminpanel/admin/query/deleteCourseExe.php` | High
53 | File | `/admin_class.php` | High
54 | File | `/admin_system/api.php` | High
55 | File | `/ajax.php?action=delete_deductions` | High
56 | File | `/ajax.php?action=delete_loan` | High
57 | File | `/ajax.php?action=delete_sales` | High
58 | File | `/ajax.php?action=delete_trainer` | High
59 | File | `/ajax.php?action=save_customer` | High
60 | File | `/ajax/action.php` | High
61 | File | `/ajx.php` | Medium
62 | File | `/aloneReport/index.do/../../aloneReport/download.do;othersusrlogout.do` | High
63 | File | `/api/controllers/admin/app/ComboController.php` | High
64 | File | `/api/sys/ng-alain/getDictItemsByTable/` | High
65 | File | `/api/users_handler.php` | High
66 | File | `/app/sms.php` | Medium
67 | File | `/App/Tpl/Admin/Default/Channel/index.html.Attackers` | High
68 | File | `/apply_settings` | High
69 | File | `/apps/system/services/role_menu.go` | High
70 | File | `/assets/uploadSllyabus.php` | High
71 | File | `/att_add.php` | Medium
72 | File | `/b2c/package-information` | High
73 | File | `/bank/statements.php` | High
74 | File | `/bin/httpd` | Medium
75 | File | `/boafrm/formDosCfg` | High
76 | File | `/boafrm/formIpv6Setup` | High
77 | File | `/boafrm/formPortFw` | High
78 | File | `/boafrm/formSysCmd` | High
79 | File | `/boafrm/formTracerouteDiagnosticRun` | High
80 | File | `/brand/queryAll` | High
81 | File | `/bwdates-report-result.php` | High
82 | File | `/bwdates-reports-details.php` | High
83 | File | `/C6/JHSoft.Web.AcceptAip/AcceptShow.aspx/` | High
84 | File | `/calculate` | Medium
85 | File | `/categorywise-products.php` | High
86 | File | `/CDGServer3/workflowE/useractivate/updateorg.jsp` | High
87 | File | `/cgi-bin/cstecgi.cgi` | High
88 | File | `/cgi-bin/cstecgi.cgi?action=save&setting` | High
89 | File | `/cgi-bin/JSONAPI` | High
90 | File | `/cgi-bin/login.cgi` | High
91 | File | `/cgi-bin/luci/api/auth` | High
92 | File | `/cgi-bin/mbox-config?method=SET&section=ping_config` | High
93 | File | `/cgi-bin/sessions/get-temp-file` | High
94 | File | `/cgi-bin/user/Config.cgi` | High
95 | ... | ... | ...

There are 839 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the campaign and the associated activities:

* https://www.reco.ai/blog/inside-the-shinyhunters-experience-cloud-campaign-iocs-detection-logic-and-whats-at-risk

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
