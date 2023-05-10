
# README
## Nextcloud Hub
This package parses and visualises Nextcloud Hub logs

## Package Contents
* Parser
* Dashboards
## Use Case
* SecOps
* ITOps
## Technology Vendor
[Nextcloud](https://nextcloud.com/)

## Support
Best effort support for this package is in the [GitHub repository discussions](https://github.com/bgraabek/LogScale-Package-for-Nextcloud/discussions). You can also raise issues is in the [GitHub repository issues](https://github.com/bgraabek/LogScale-Package-for-Nextcloud/issues) section.

## Dependencies
This package has been developed and tested with logs from Nextcloud v20.
It uses logs from the Nextcloud audit log file. This file must be ingested for the package to work.

## Installation
For the dashboards in this package to light up, the audit log from a Nextcloud server must be ingested. Nextcloud must first be configured to write an audit log. For more information on this see the [Nextcloud logging](https://docs.nextcloud.com/server/latest/admin_manual/configuration_server/logging_configuration.html) section in the Nextcloud documentation.
Then install and configure the Falcon LogScale collector to send entries from the audit log file to a Falcon LogScale system. The Falcon LogScale collector must specify that the nextcloud parser (included in this package) be used.  
For more detailed installation information, see the [Nextcloud package wiki](https://github.com/bgraabek/LogScale-Package-for-Nextcloud/wiki).
      
