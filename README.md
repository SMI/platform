⚀ Work in progress! ⚀

# SMI Platform

This repo contains the ansible playbooks for installing and configuring the components of the SMI platform.

## Services required

-   Configs
    -   [ ] Files from live system
    -   [ ] Logging config
-   Services / Languages
    -   [ ] SQL Server
    -   [ ] MySQL (MariaDB)
    -   [ ] Redis
    -   [x] MongoDB
    -   [x] RabbitMQ
    -   [ ] Java / maven
-   Software
    -   [x] SmiServices
    -   [ ] rdmp-cli
        -   [ ] Create data load pipeline mirroring the live system
    -   [ ] CTP
    -   [ ] ExtractorCL
    -   [ ] smi_nerd service (docker or install)
    -   [ ] Monitoring (Prometheus / Grafana)

## TODOs

-   [ ] Usage instructions
-   all_install_as_containers
-   molecule tests
-   smi bashrc
-   smi example user setup (as a script)
-   checks for duplicated uid/gids
-   Separate repo with
    -   Packer images for azure & virtualbox
    -   Tf scripts
-   Can we also replicate the RC/researcher environments for testing?
    -   file copy tool
    -   DicomRepopulator
