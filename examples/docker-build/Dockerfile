ARG runtime_image=registry.apps.ocp-csonprd.intra.absa.co.za/openshift/wildfly-runtime:latest
FROM ${runtime_image}
COPY --chown=jboss:root target/server $JBOSS_HOME
RUN chmod -R ug+rwX $JBOSS_HOME
