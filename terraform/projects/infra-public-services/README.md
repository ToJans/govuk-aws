## Project: infra-public-services

This project adds global resources for app components:
  - public facing LBs and DNS entries
  - internal DNS entries



## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-----:|:-----:|
| apt_internal_service_names |  | list | `<list>` | no |
| apt_public_service_cnames |  | list | `<list>` | no |
| apt_public_service_names |  | list | `<list>` | no |
| asset_master_internal_service_names |  | list | `<list>` | no |
| aws_environment | AWS Environment | string | - | yes |
| aws_region | AWS region | string | `eu-west-1` | no |
| backend_internal_service_cnames |  | list | `<list>` | no |
| backend_internal_service_names |  | list | `<list>` | no |
| backend_public_service_cnames |  | list | `<list>` | no |
| backend_public_service_names |  | list | `<list>` | no |
| backend_redis_internal_service_names |  | list | `<list>` | no |
| bouncer_internal_service_names |  | list | `<list>` | no |
| bouncer_public_service_names |  | list | `<list>` | no |
| cache_internal_service_cnames |  | list | `<list>` | no |
| cache_internal_service_names |  | list | `<list>` | no |
| cache_public_service_cnames |  | list | `<list>` | no |
| cache_public_service_names |  | list | `<list>` | no |
| calculators_frontend_internal_service_cnames |  | list | `<list>` | no |
| calculators_frontend_internal_service_names |  | list | `<list>` | no |
| content_store_internal_service_names |  | list | `<list>` | no |
| db_admin_internal_service_names |  | list | `<list>` | no |
| deploy_internal_service_names |  | list | `<list>` | no |
| deploy_public_service_names |  | list | `<list>` | no |
| docker_management_internal_service_names |  | list | `<list>` | no |
| draft_cache_internal_service_cnames |  | list | `<list>` | no |
| draft_cache_internal_service_names |  | list | `<list>` | no |
| draft_cache_public_service_cnames |  | list | `<list>` | no |
| draft_cache_public_service_names |  | list | `<list>` | no |
| draft_content_store_internal_service_names |  | list | `<list>` | no |
| draft_frontend_internal_service_cnames |  | list | `<list>` | no |
| draft_frontend_internal_service_names |  | list | `<list>` | no |
| elb_public_certname | The ACM cert domain name to find the ARN of | string | - | yes |
| frontend_internal_service_cnames |  | list | `<list>` | no |
| frontend_internal_service_names |  | list | `<list>` | no |
| graphite_internal_service_names |  | list | `<list>` | no |
| graphite_public_service_names |  | list | `<list>` | no |
| jumpbox_public_service_names |  | list | `<list>` | no |
| logs_cdn_public_service_names |  | list | `<list>` | no |
| mapit_internal_service_names |  | list | `<list>` | no |
| mongo_internal_service_names |  | list | `<list>` | no |
| monitoring_internal_service_names |  | list | `<list>` | no |
| monitoring_public_service_names |  | list | `<list>` | no |
| mysql_internal_service_names |  | list | `<list>` | no |
| postgresql_internal_service_names |  | list | `<list>` | no |
| publishing_api_internal_service_names |  | list | `<list>` | no |
| puppetmaster_internal_service_names |  | list | `<list>` | no |
| rabbitmq_internal_service_names |  | list | `<list>` | no |
| remote_state_bucket | S3 bucket we store our terraform state in | string | - | yes |
| remote_state_infra_monitoring_key_stack | Override stackname path to infra_monitoring remote state | string | `` | no |
| remote_state_infra_networking_key_stack | Override infra_networking remote state path | string | `` | no |
| remote_state_infra_root_dns_zones_key_stack | Override stackname path to infra_root_dns_zones remote state | string | `` | no |
| remote_state_infra_security_groups_key_stack | Override infra_security_groups stackname path to infra_vpc remote state | string | `` | no |
| remote_state_infra_stack_dns_zones_key_stack | Override stackname path to infra_stack_dns_zones remote state | string | `` | no |
| remote_state_infra_vpc_key_stack | Override infra_vpc remote state path | string | `` | no |
| router_backend_internal_service_names |  | list | `<list>` | no |
| rummager_elasticsearch_internal_service_names |  | list | `<list>` | no |
| search_internal_service_cnames |  | list | `<list>` | no |
| search_internal_service_names |  | list | `<list>` | no |
| stackname | Stackname | string | - | yes |
| transition_db_admin_internal_service_names |  | list | `<list>` | no |
| transition_postgresql_internal_service_names |  | list | `<list>` | no |
| whitehall_backend_internal_service_cnames |  | list | `<list>` | no |
| whitehall_backend_internal_service_names |  | list | `<list>` | no |
| whitehall_backend_public_service_cnames |  | list | `<list>` | no |
| whitehall_backend_public_service_names |  | list | `<list>` | no |
| whitehall_frontend_internal_service_names |  | list | `<list>` | no |

