# Maze - Cyber Threat Intelligence

These _indicators_ were reported, collected, and generated during the [VulDB CTI analysis](https://vuldb.com/kb/cti) of the actor known as [Maze](https://vuldb.com/actor/maze). The _activity monitoring_ correlates data from social media, forums, chat rooms, and darknet markets. It helps to determine associated actors, specific activities, expected intentions, emerging research, and ongoing attacks. Our unique _predictive model_ uses _big data_ to forecast activities and their characteristics.

_Live data_ and more _analysis capabilities_ are available at [https://vuldb.com/actor/maze](https://vuldb.com/actor/maze)

## Countries

These _countries_ are directly (e.g. origin of attacks) or indirectly (e.g. access by proxy) associated with Maze:

* [MY](https://vuldb.com/country/my)

## IOC - Indicator of Compromise

These _indicators of compromise_ (IOC) indicate associated network resources which are known to be part of research and attack activities of Maze.

ID | IP address | Hostname | Campaign | Confidence
-- | ---------- | -------- | -------- | ----------
1 | [5.199.167.188](https://vuldb.com/ip/5.199.167.188) | - | - | High
2 | [37.1.213.9](https://vuldb.com/ip/37.1.213.9) | - | - | High
3 | [37.252.7.142](https://vuldb.com/ip/37.252.7.142) | - | - | High
4 | [91.218.114.4](https://vuldb.com/ip/91.218.114.4) | - | - | High
5 | [91.218.114.11](https://vuldb.com/ip/91.218.114.11) | - | - | High
6 | [91.218.114.25](https://vuldb.com/ip/91.218.114.25) | mail.autozetconsignment.com | - | High
7 | [91.218.114.26](https://vuldb.com/ip/91.218.114.26) | - | - | High
8 | ... | ... | ... | ...

There are 26 more IOC items available. Please use our online service to access the data.

## TTP - Tactics, Techniques, Procedures

_Tactics, techniques, and procedures_ (TTP) summarize the suspected MITRE ATT&CK techniques used by _Maze_. This data is unique as it uses our predictive model for actor profiling.

ID | Technique | Weakness | Description | Confidence
-- | --------- | -------- | ----------- | ----------
1 | T1006 | CWE-22, CWE-35, CWE-36, CWE-41 | Path Traversal | High
2 | T1040 | CWE-294, CWE-319 | Authentication Bypass by Capture-replay | High
3 | T1055 | CWE-74 | Improper Neutralization of Data within XPath Expressions | High
4 | T1059 | CWE-94, CWE-1321 | Argument Injection | High
5 | T1059.007 | CWE-79, CWE-87 | Basic Cross Site Scripting | High
6 | ... | ... | ... | ...

There are 18 more TTP items available. Please use our online service to access the data.

## IOA - Indicator of Attack

These _indicators of attack_ (IOA) list the potential fragments used for technical activities like reconnaissance, exploitation, privilege escalation, and exfiltration by Maze. This data is unique as it uses our predictive model for actor profiling.

ID | Type | Indicator | Confidence
-- | ---- | --------- | ----------
1 | File | `/activity.php` | High
2 | File | `/activity/index/get-memberall` | High
3 | File | `/addnewfaculty` | High
4 | File | `/admin-api/system/mail-log/page` | High
5 | File | `/admin-api/system/tenant/get-by-website` | High
6 | File | `/admin/ajax.php?action=delete_cart` | High
7 | File | `/admin/ajax.php?action=delete_category` | High
8 | File | `/admin/ajax.php?action=delete_menu` | High
9 | File | `/admin/ajax.php?action=get_cart_count` | High
10 | File | `/admin/ajax.php?action=get_cart_items` | High
11 | File | `/admin/ajax.php?action=login` | High
12 | File | `/admin/ajax.php?action=login2` | High
13 | File | `/admin/ajax.php?action=save_category` | High
14 | File | `/admin/ajax.php?action=save_menu` | High
15 | File | `/admin/ajax.php?action=save_order` | High
16 | File | `/admin/ajax.php?action=save_user` | High
17 | File | `/admin/block_status.php` | High
18 | File | `/admin/index.php?page=save_settings` | High
19 | File | `/admin/jobs-admins/delete-jobs.php` | High
20 | File | `/admin/plugin_antispam` | High
21 | File | `/admin/send_message.php` | High
22 | File | `/admin/tools.php` | High
23 | File | `/Administrator/PHP/AdminUpdateAlbum.php` | High
24 | File | `/ajax.php?action=delete_category` | High
25 | File | `/ajax.php?action=delete_expired` | High
26 | File | `/ajax.php?action=delete_receiving` | High
27 | File | `/ajax.php?action=delete_user` | High
28 | File | `/ajax.php?action=save_category` | High
29 | File | `/ajax.php?action=save_expired` | High
30 | File | `/ajax.php?action=save_receiving` | High
31 | File | `/ajax.php?action=save_sales` | High
32 | File | `/ajax.php?action=save_type` | High
33 | File | `/api/access-tokens` | High
34 | File | `/api/ai-scanner/status-webhook` | High
35 | File | `/api/file/readDir` | High
36 | File | `/api/gateway/restart` | High
37 | File | `/api/global/users/search?x=/api/system/status` | High
38 | File | `/api/google/authorize` | High
39 | File | `/api/notification/pushMsg` | High
40 | File | `/api/v1/account/reset-password` | High
41 | File | `/api/v1/public-chatbotConfig/:id` | High
42 | File | `/api/v1/public-chatflows/:id` | High
43 | File | `/api/v1/text-to-speech/generate` | High
44 | File | `/boaform/admin/formgponConf` | High
45 | File | `/boaform/formCountrystr` | High
46 | File | `/boaform/formIPv6Routing` | High
47 | File | `/boaform/formRouting` | High
48 | File | `/boaform/formTracert` | High
49 | File | `/boafrm/formIpQoS` | High
50 | File | `/boafrm/formVpnConfigSetup` | High
51 | File | `/boafrm/formWanConfigSetup` | High
52 | File | `/boafrm/formWsc` | High
53 | File | `/booking.php` | Medium
54 | File | `/bot/v1/chat` | Medium
55 | File | `/cgi-bin/cstecgi.cgi` | High
56 | File | `/cims/modules/admin/reply.php` | High
57 | File | `/cims/modules/student/complaint.php` | High
58 | File | `/company` | Medium
59 | File | `/console` | Medium
60 | File | `/core/link/preview` | High
61 | ... | ... | ...

There are 533 more IOA items available (file, library, argument, input value, pattern, network port). Please use our online service to access the data.

## References

The following list contains _external sources_ which discuss the actor and the associated activities:

* https://blog.talosintelligence.com/2019/12/IR-Lessons-Maze.html
* https://blog.talosintelligence.com/2022/03/threat-roundup-0304-0311.html
* https://ddanchev.blogspot.com/2024/06/exposing-sonatrach-data-leak-and-data.html
* https://github.com/sophoslabs/IoCs/blob/master/Ransomware-Maze.csv

## Literature

The following _articles_ explain our unique predictive cyber threat intelligence:

* [VulDB Cyber Threat Intelligence Documentation](https://vuldb.com/kb/cti)
* [Cyber Threat Intelligence - Early Anticipation of Attacks](https://www.scip.ch/en/?labs.20201022)

## License

(c) [1997-2026](https://vuldb.com/kb/changelog) by [vuldb.com](https://vuldb.com/kb/about). All data on this page is shared under the license [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Questions? Check the [FAQ](https://vuldb.com/kb/faq), read the [documentation](https://vuldb.com/kb) or [contact us](https://vuldb.com/contact)!
