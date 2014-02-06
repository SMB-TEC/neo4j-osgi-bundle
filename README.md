## Neo4j OSGI Bundle


### Neo4j Version: 2.0.1 Community

Creates a "super bundle" containing the Neo4j Community Edition. It is just a library bundle. We did not add any additional OSGi service nor removed any stuff. It's up to you to start the database.

### Missing Dependencies? ###

We decided not to include several libraries from the "org.apache" namespace. Goto Eclipse Orbit and download/install them from this updatesite:

[http://download.eclipse.org/tools/orbit/downloads/drops/R20130827064939/repository/](http://download.eclipse.org/tools/orbit/downloads/drops/R20130827064939/repository/ "http://download.eclipse.org/tools/orbit/downloads/drops/R20130827064939/repository/")
