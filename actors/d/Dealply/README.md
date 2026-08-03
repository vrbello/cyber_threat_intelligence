# Dealply - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [Dealply](https://vuldb.com/actor/dealply). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/dealply](https://vuldb.com/actor/dealply)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Dealply:

* [IT](https://vuldb.com/country/it)
* [US](https://vuldb.com/country/us)
* [ES](https://vuldb.com/country/es)
* ...

There are 1 more country items available. Please use our online service to access the data.

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Dealply.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.9.9.18](https://vuldb.com/ip/5.9.9.18) | static.18.9.9.5.clients.your-server.de | - | High
2 | [13.248.196.204](https://vuldb.com/ip/13.248.196.204) | a64c2b794233c60a6.awsglobalaccelerator.com | - | High
3 | [23.0.52.194](https://vuldb.com/ip/23.0.52.194) | a23-0-52-194.deploy.static.akamaitechnologies.com | - | High
4 | [23.3.126.219](https://vuldb.com/ip/23.3.126.219) | a23-3-126-219.deploy.static.akamaitechnologies.com | - | High
5 | [23.54.219.51](https://vuldb.com/ip/23.54.219.51) | a23-54-219-51.deploy.static.akamaitechnologies.com | - | High
6 | [23.221.50.122](https://vuldb.com/ip/23.221.50.122) | a23-221-50-122.deploy.static.akamaitechnologies.com | - | High
7 | [34.231.131.84](https://vuldb.com/ip/34.231.131.84) | ec2-34-231-131-84.compute-1.amazonaws.com | - | Medium
8 | ... | ... | ... | ...

There are 29 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Dealply_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-23, CWE-24, CWE-36 | Path Traversal | High
2 | T1040 | CWE-294 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-88, CWE-94 | Argument Injection | High
5 | T1059.007 | CWE-79 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 20 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Dealply. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `$SPLUNK_HOME/var/run/splunk/apptemp` | High
2 | File | `../mtd/Config/Sha1Account1` | High
3 | File | `/admin/add_category.php` | High
4 | File | `/admin/ajax_products_list.php` | High
5 | File | `/admin/blog/comment/create` | High
6 | File | `/admin/bookList?page=1&limit=10` | High
7 | File | `/admin/bwdates-passreports-details.php` | High
8 | File | `/admin/bwdates-reports-details.php` | High
9 | File | `/admin/course_action.php` | High
10 | File | `/admin/delete_user.php` | High
11 | File | `/admin/edit-subcategory.php` | High
12 | File | `/admin/login_query.php` | High
13 | File | `/admin/manage-art-medium.php` | High
14 | File | `/admin/sales-reports-detail.php` | High
15 | File | `/admin/search-invoices.php` | High
16 | File | `/admin/search-pass.php` | High
17 | File | `/admin/testimonials/manage.php` | High
18 | File | `/admin/view-appointment.php` | High
19 | File | `/admin_single_student.php` | High
20 | File | `/agents/deploy/initiate.c` | High
21 | File | `/api/file/upload` | High
22 | File | `/api/GylOperator/UpdatePasswordBatch` | High
23 | File | `/api/v1/serve/awel/flow/import` | High
24 | File | `/api/wizard/getLanguage` | High
25 | File | `/api/wizard/getWifiNeighbour` | High
26 | File | `/appy.cgi` | Medium
27 | File | `/auth.asp` | Medium
28 | File | `/auth/register` | High
29 | File | `/bin/boa` | Medium
30 | File | `/bin/httpd` | Medium
31 | File | `/bin/main` | Medium
32 | File | `/biurl_grou` | Medium
33 | File | `/boaform/formPing6` | High
34 | File | `/boafrm/formDateReboot` | High
35 | File | `/boafrm/formDdns` | High
36 | File | `/boafrm/formDhcpv6s` | High
37 | File | `/boafrm/formDMZ` | High
38 | File | `/boafrm/formFirewallAdv` | High
39 | File | `/boafrm/formIpv6Setup` | High
40 | File | `/boafrm/formMultiAP` | High
41 | File | `/boafrm/formParentControl` | High
42 | File | `/boafrm/formPortFw` | High
43 | File | `/boafrm/formSaveConfig` | High
44 | File | `/boafrm/formStaticDHCP` | High
45 | File | `/boafrm/formTmultiAP` | High
46 | File | `/boafrm/formWanConfigSetup` | High
47 | File | `/boafrm/formWlAc` | High
48 | File | `/boafrm/formWsc` | High
49 | File | `/cgi-bin/account_mgr.cgi` | High
50 | File | `/cgi-bin/account_mgr.cgi?cmd=cgi_user_add` | High
51 | File | `/cgi-bin/app_mgr.cgi` | High
52 | File | `/cgi-bin/cstecgi.cgi` | High
53 | File | `/cgi-bin/firewall.cgi` | High
54 | File | `/cgi-bin/hedwig.cgi` | High
55 | File | `/cgi-bin/login.cgi` | High
56 | File | `/cgi-bin/UploadCfg` | High
57 | File | `/cgi/timepro.cgi` | High
58 | File | `/collect/PortV4/downLoad.html` | High
59 | File | `/contact.php` | Medium
60 | File | `/contact_us.php` | High
61 | File | `/controller/api/hotelList.php` | High
62 | File | `/customer_details.php` | High
63 | File | `/dbsrv.asp` | Medium
64 | File | `/dev/ttyACM*` | Medium
65 | File | `/discuss/uploadMdPic` | High
66 | File | `/Easy7/apps/WebService/ImportSystemConfiguration.jsp` | High
67 | File | `/editedcampaign.php` | High
68 | ... | ... | ...

There are 599 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2020/01/threat-roundup-0124-0131.html
* https://blog.talosintelligence.com/2020/05/threat-roundup-0522-0529.html
* https://blog.talosintelligence.com/2020/08/threat-roundup-0821-0827.html

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
