sa-graylog
===========

[![Build Status](https://travis-ci.org/softasap/sa-graylog.svg?branch=master)](https://travis-ci.org/softasap/sa-graylog)

```
  roles:
    - {
        role: "sa-graylog",
        graylog_api_domain: "graylog.example.com",
        graylog_secret: Srq1IiuBwXrTwiw78dJBeLvWd4CbHYCOoO0NL4i74QWOImZqvbUzaD5PisTcP2aJ,
        graylog_admin_password_sha256: daa35e4f1a0e43def76e13a948cbda05be2569901fa0c6d5d6342fb2bdc85028 #admin!
      }
```

Advanced:

```
  roles:
    - {
        role: "sa-graylog",
        graylog_api_domain: "graylog.example.com",
        option_install_java: false,
        option_install_elastic_search: false,
        option_nginx_frontend: false,
        java_version: 8,
        graylog_api_domain: "graylog.example.com",
        graylog_secret: Srq1IiuBwXrTwiw78dJBeLvWd4CbHYCOoO0NL4i74QWOImZqvbUzaD5PisTcP2aJ,
        graylog_admin_password_sha256: daa35e4f1a0e43def76e13a948cbda05be2569901fa0c6d5d6342fb2bdc85028 #admin!
      }
```
