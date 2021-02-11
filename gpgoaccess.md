### GOACCESS SITE LOG
---

1. Replace the **DOMAIN-NAME** with your domain

  * zcat /var/log/nginx/**DOMAIN-NAME**.access.log* | goaccess --log-format='[%d:%t %^] %h %^ - %v "%r" %s %b "%R" "%u"' --date-format='%d/%b/%Y' --time-format='%H:%M:%S %Z'
