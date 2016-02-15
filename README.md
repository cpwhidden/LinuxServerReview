# LinuxServerReview
Review repo for submission to Udacity

*  IP Address: 52.35.185.51
*  SSH port: 2200
*  URL: http://ec2-52-35-185-51.us-west-2.compute.amazonaws.com/


# Summary

1.  User named grader with sudo permissions created
2.  All packages updated and upgraded through apt-get
3.  Timezone configured to UTC
4.  SSH configured to serve on port 2200
5.  UFW only allows SSH, HTTP, and NTP connections
6.  Apache and mod_wsgi installed. Apache configured and WSGI script created.
7.  PostgreSQL installed
8.  catalog user in PostgreSQL created
9.  git installed
10.  Catalog project reprogrammed to use PostgreSQL
11.  Various fixes for getting Catalog project working on Ubuntu.  Apache configuration file set to run application as user named catalog.
12.  fail2ban installed to block IP address that repeatedly fail login
13.  cron-apt installed to automatically update packages and configured to run weekly
14.  glances installed to monitor server activity
15.  Disabled root access

# Third-party software
virtualenv was used to create a virtual Python environment for the application.
