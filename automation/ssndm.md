# Simple Services Network Description Manifest

Software package/image managements does neither describe services dependencies requirements nor network requirements.
The goal here is to establish a common manifest 
* to define default specifications and optional services used by a package/image,
* to facilitate DevOps network security automation 
* and to declare contractual requirements (billing, legal liabilities per juridiction).

The manifest can also be used also to specify projects dependencies requirements.

Non-goals are creating a repository of these ssndm.yml, ssndm.json and ssndm.xml files.

# Problem resolution
* Get a fully define services dependencies definition with their requirements and configuration
  * Allow automatic detailed definition of network egress rules
* Define legal liabilities as a specification and document the ones linked to the use of the package
* Define fast accesses to tests and source code to enable detailed audit
* Standardize masked knowledge of package usages.

# Formats
In order to facilitate specification, implementation, flexibility and dissemination, formats supported are YAML, JSON and XML.

First examples will be defined in YAML.

# Specification

service_type data_used, external_service, internal_provided_service

application          level         - Description and requirements recap
application/package  string Package reference
application/license  string Package reference
application/required string constant yes/no
application/sensitive_data string constant yes/no
application/sensitive_type string constant hierarchy per country

services/mandatory optional/service - Network service definitiotenn

events
  event_type maintenance_window, end_of_life

costs_assessment
   creation_date
   

# Example
application:
  description:
  package:
  required: yes
  sensitive_data: no
  provider: AWS
  head_quarter_juridiction: USA
  top_juridiction: USA:CJS
  services:
    mandatory:
      service:
        type: frontend_to_backend
        enabled_by_default: yes
        fqdn_url:
        port:
        protocol:
        authentication:
        authorization:
        provider: AWS
        provider_service: EC2
        service_documentation_url:
        head_quarter_juridiction: USA
        top_juridiction: USA:SCJ
        test_code:
        source_code_call:
        alternative_services:
    service:
        type: backend_to_database
        enabled_by_default: yes
        fqdn_url:
        port:
        protocol:
        authentication:
        authorization:
        provider: AWS
        provider_service: RDS PostgreSQL
        service_documentation_url:
        head_quarter_juridiction: USA
        top_juridiction: USA:SCJ
        test_code:
        source_code_call:
        alternative_services:
      service:
        type: geoip database download
        enabled_by_default: yes
        service_documentation_url
        fqdn_url:
        port:
        protocol:
        authentication:
        authorization:
        failback_mode: log_warnings, retry_3
        head_quarter_juridiction: USA
        top_juridiction: USA:SCJ
        test_code:
        source_code_call:
        alternative_services:
    service:
        type: timezone database download
        enabled_by_default: yes
        service_documentation_url
        fqdn_url:
        port:
        protocol:
        authentication:
        authorization:
        head_quarter_juridiction: USA
        top_juridiction: USA:SCJ
        test_code:
        source_code_call:
        alternative_services:
    optional:
      service:
  

  
  
  
