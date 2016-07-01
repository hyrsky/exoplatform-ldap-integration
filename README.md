# eXo LDAP Integration
LDAP Integration for https://www.exoplatform.com/

I was struggling to get exo to work with ldap so here is my configuration files to make your life easier

## Installation
 * Edit `./WEB-INF/conf/organization/picketlink-idm-ldap-config.xml` to your liking
 * Compress, `jar cvf ./* ldap-integration.war`
 * Copy .war to `$PLATFORM_TOMCAT_HOME/webapps`

## My LDAP tree: 
 * https://gist.github.com/hyrsky/024794d0cc3fa227285ae347087d486f

## References

https://www.exoplatform.com/docs/PLF43/PLFAdminGuide.LDAP.PicketLink.QuickStart.html
