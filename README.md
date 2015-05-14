# nagios-plugins
Nagios plugins to monitor additional services.

# check_mysql_ssl_certificate
"Check MySQL SSL Certificate" is a passive check used to check the expiration date of x509 certificates.
Usage:
check_ssl_certificate.py [-h] [-c CRITICAL] [-w WARNING] [-p PATH]

optional arguments:
-h, --help show this help message and exit
-c CRITICAL Set Critical Threshold
-w WARNING Set Warning Threshold
-p PATH Set Cert Path
