# common_vars의 변수 별 deployment

K-PaaS >= v6.0.0

### BOSH INFO
|변수이름|deployment|
|------|---|
|bosh_url|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>service-deployment/web-ide|
|bosh_client_admin_id|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>service-deployment/web-ide|
|bosh_client_admin_secret|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>service-deployment/web-ide|
|bosh_director_port|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>service-deployment/web-ide|
|bosh_oauth_port|service-deployment/lifecycle-service<br>service-deployment/redis<br>service-deployment/gateway-service<br>service-deployment/web-ide|
|bosh_version|service-deployment/redis<br>service-deployment/web-ide|

### Application Platform INFO
|변수이름|deployment|
|------|---|
|system_domain|service-deployment/glusterfs<br>service-deployment/rabbitmq<br>service-deployment/mongodb<br>service-deployment/source-control-service<br>service-deployment/redis<br>service-deployment/pipeline-service<br>service-deployment/logging-service<br>service-deployment/web-ide<br>ap-deployment/ap<br>portal-deployment/portal-api<br>portal-deployment/portal-ui<br>portal-deployment/portal-container-infra|
|ap_admin_username|service-deployment/glusterfs<br>service-deployment/mongodb<br>service-deployment/redis<br>service-deployment/web-ide<br>ap-deployment/ap<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|ap_admin_password|service-deployment/glusterfs<br>service-deployment/rabbitmq<br>service-deployment/mongodb<br>service-deployment/redis<br>service-deployment/web-ide<br>ap-deployment/ap<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|ap_nats_ip|service-deployment/mongodb<br>service-deployment/rabbitmq|
|ap_nats_port|service-deployment/mongodb|
|ap_nats_user|service-deployment/mongodb|
|ap_nats_password|service-deployment/mongodb|
|ap_database_ips|portal-deployment/portal-api|
|ap_database_port|ap-deployment/ap<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|ap_database_type|portal-deployment/portal-api|
|ap_database_driver_class|portal-deployment/portal-api|
|ap_cc_db_id|portal-deployment/portal-api|
|ap_cc_db_password|ap-deployment/ap<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|ap_uaa_db_id|portal-deployment/portal-api|
|ap_uaa_db_password|ap-deployment/ap<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|ap_api_version|portal-deployment/portal-ui|


### UAAC INFO
|변수이름|deployment|
|------|---|
|uaa_client_admin_id|service-deployment/logging-service<br>portal-deployment/portal-api|
|uaa_client_admin_secret|service-deployment/logging-service<br>ap-deployment/ap<br>portal-deployment/portal-api<br>portal-deployment/portal-container-infra|
|uaa_client_portal_secret|ap-deployment/ap<br>portal-deployment/portal-ui<br>portal-deployment/portal-container-infra|


### Portal INFO
|변수이름|deployment|
|------|---|
|portal_web_user_url|portal-deployment/portal-api|
|portal_web_user_language|portal-deployment/portal-api<br>portal-deployment/portal-ui|
|portal_web_admin_language|portal-deployment/portal-ui|
