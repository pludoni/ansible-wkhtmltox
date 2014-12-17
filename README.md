Role Name
=========

Installs wkhtmltopdf as .deb for Ubuntu.


Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: zealot128.wkthmltox
           wkhtmltox_install_fonts: true
           wkhtmltox_main_version: 0.12.2-dev
           wkhtmltox_minor_version: 0.12.2-dev-5dea253
           wkhtmltox_download_url: 'http://downloads.sourceforge.net/project/wkhtmltopdf/{{wkhtmltopdf_main_version}}/wkhtmltox-{{wkhtmltopdf_minor_v

License
-------

BSD

