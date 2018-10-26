# JLinkster Registry

An instance of the JHipster Registry, which provides Eureka Service Discovery, Spring Cloud Config Server, and
Administration Server functionality, for the JLinkster application.

## Related Projects

* [JLinkster Config](https://github.com/jlinkster/config)
* [JLinkster Registry](https://github.com/jlinkster/registry)
* [JLinster Vault](https://github.com/jlinkster/vault)
* [JLinkster UAA](https://github.com/jlinkster/uaa)
* [JLinkster Gateway](https://github.com/jlinkster/gateway)
* [JLinkster Web](https://github.com/jlinkster/web)
* [JLinkster Profile Service](https://github.com/jlinkster/profile)
* [JLinkster Connections Service](https://github.com/jlinkster/connections)
* [JLinkster Recommendations Service](https://github.com/jlinkster/recommendations)

## Configuration

The only runtime configuration required is to provide the username and password that clients will use to access
the registry.

* JLINKSTER_REGISTRY_USERNAME: The username the clients will use to access the registry
* JLINKSTER_REGISTRY_PASSWORD: The password the clients will use to access the registry
