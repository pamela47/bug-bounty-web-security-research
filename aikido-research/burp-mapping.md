## Initial Platform Identification
# Burp Mapping – Aikido Security Research
During initial reconnaissance and dashboard review, the platform appeared to operate as a centralised security management system.

Observed asset categories included:

- Repositories
- Containers
- Clouds
- Virtual Machines
- Domains
- Pentests
- Code Audit
- Devices
- Firewall

Initial assessment suggested that Aikido aggregates and manages security findings across multiple technology assets and environments.

This early business-context understanding helped guide further mapping and API observation.
## Cloud Integration Mapping

Observed API endpoints included:

- /api/cloud/getScanInfo
- /api/cloud_integration/countClouds
- /api/cloud_integration/list
- /api/cloud_integration/registries

Initial observations:

- Platform uses JSON API responses
- Cloud integrations appear dynamically loaded
- Backend functionality appears API-driven
- Mapping performed through passive reconnaissance and observation
