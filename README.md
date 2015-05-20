fail2ban addons
===============
This project contains additional filters and actions for fail2ban.

filters
-------
  - *apache-notexist.conf*
  
    Detect if someone is crawling your website and ban it for several minutes.
  
  - *sso-relay.conf*

actions
-------
  - *iptables-redirect.conf*
  
    Redirect user from original port(80) to destination port(1080) using iptables.
    The 80 port is the original website (heavyweight) and 1080 port is another website showing warning message (static page).

Author
------
  SHIE, Li-Yi <lyshie@mail.nsysu.edu.tw>
  
LICENSE
-------
  GNU General Public License (GPL)
