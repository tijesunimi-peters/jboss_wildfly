FROM jboss/wildfly
ADD modules /opt/jboss/wildfly/modules/system/layers/base/com
ADD configuration/mgmt-groups.properties /opt/jboss/wildfly/standalone/configuration/
ADD configuration/mgmt-users.properties /opt/jboss/wildfly/standalone/configuration/
ADD configuration/standalone.xml /opt/jboss/wildfly/standalone/configuration/
COPY web/web.war /opt/jboss/wildfly/standalone/deployments/
