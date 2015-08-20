# saml2-setup

Creates a JBoss instance with an SAML2 Identity Provider (using jboss picketlink) and a test application as well.

An arquillian checks this setup and shows how SAML2 post binding works (with output of SAMLRequest and SAMLResponse).


Don't forget to install jboss-eap6.4.0.zip in your local maven repository to run this setup :
        
        mvn install:install-file -Dfile=jboss-eap-6.4.0.zip -DgroupId=org.jboss.as -DartifactId=jboss-eap -Dversion=6.4 -Dpackaging=zip





