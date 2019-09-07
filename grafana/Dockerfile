FROM grafana/grafana:6.3.5
MAINTAINER alexey.i.egorov@megafon.ru
VOLUME /var/lib/grafana
COPY ldap.toml /etc/grafana/ldap.toml
ENV GF_AUTH_LDAP_ENABLED true
EXPOSE 3000