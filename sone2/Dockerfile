FROM odoo:8

COPY ./openerp-server.conf /etc/odoo/openerp-server.conf

RUN mkdir -p /var/lib/odoo
VOLUME /var/lib/odoo

CMD ["python", "/usr/bin/openerp-server", "--config=/etc/odoo/openerp-server.conf"]

