## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_google"></a> [google](#requirement\_google) | 3.5.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_google-beta"></a> [google-beta](#provider\_google-beta) | 6.15.0 |
| <a name="provider_random"></a> [random](#provider\_random) | 3.6.3 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [google-beta_google_composer_environment.composer_environment](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_composer_environment) | resource |
| [google-beta_google_project_iam_member.custom_service_account_bigquery_editor](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_iam_member) | resource |
| [google-beta_google_project_iam_member.custom_service_account_cloudfunctions_invoker](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_iam_member) | resource |
| [google-beta_google_project_iam_member.custom_service_account_composer_admin](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_iam_member) | resource |
| [google-beta_google_project_iam_member.custom_service_account_composer_worker](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_iam_member) | resource |
| [google-beta_google_project_iam_member.custom_service_account_dataform_editor](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_iam_member) | resource |
| [google-beta_google_project_service.composer_api](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_service) | resource |
| [google-beta_google_service_account.custom_service_account](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_service_account) | resource |
| [random_integer.random_number](https://registry.terraform.io/providers/hashicorp/random/latest/docs/resources/integer) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_BUCKET_OBJECT_DAGS_PREFIX"></a> [BUCKET\_OBJECT\_DAGS\_PREFIX](#input\_BUCKET\_OBJECT\_DAGS\_PREFIX) | Nome do bucket para o Cloud Composer (DAGs e consultas) | `string` | `"cc"` | no |
| <a name="input_COMPOSER_NAME"></a> [COMPOSER\_NAME](#input\_COMPOSER\_NAME) | O nome do ambiente do composer | `string` | `"cc-example-environment"` | no |
| <a name="input_COMPOSER_SA_ID"></a> [COMPOSER\_SA\_ID](#input\_COMPOSER\_SA\_ID) | Nome do service account do Composer | `string` | `"44823525"` | no |
| <a name="input_ENVIRONMENT_SIZE"></a> [ENVIRONMENT\_SIZE](#input\_ENVIRONMENT\_SIZE) | n/a | `string` | `"ENVIRONMENT_SIZE_SMALL"` | no |
| <a name="input_PROJECT"></a> [PROJECT](#input\_PROJECT) | O projeto onde os recursos serão criados | `string` | `"dataplex-experience-6133"` | no |
| <a name="input_REGION"></a> [REGION](#input\_REGION) | A região onde os recursos serão criados | `string` | `"us-east1"` | no |
| <a name="input_SCHEDULER_COUNT"></a> [SCHEDULER\_COUNT](#input\_SCHEDULER\_COUNT) | Número de instâncias do programador | `number` | `1` | no |
| <a name="input_SCHEDULER_CPU"></a> [SCHEDULER\_CPU](#input\_SCHEDULER\_CPU) | Número de vCPUs para o programador | `number` | `0.5` | no |
| <a name="input_SCHEDULER_MEMORY"></a> [SCHEDULER\_MEMORY](#input\_SCHEDULER\_MEMORY) | Quantidade de memória (em GB) para o programador | `number` | `2` | no |
| <a name="input_SCHEDULER_STORAGE"></a> [SCHEDULER\_STORAGE](#input\_SCHEDULER\_STORAGE) | Espaço de armazenamento (em GB) para o programador | `number` | `1` | no |
| <a name="input_TRIGGERER_COUNT"></a> [TRIGGERER\_COUNT](#input\_TRIGGERER\_COUNT) | Número de instâncias do acionador | `number` | `1` | no |
| <a name="input_TRIGGERER_CPU"></a> [TRIGGERER\_CPU](#input\_TRIGGERER\_CPU) | Número de vCPUs para o acionador | `number` | `0.5` | no |
| <a name="input_TRIGGERER_MEMORY"></a> [TRIGGERER\_MEMORY](#input\_TRIGGERER\_MEMORY) | Quantidade de memória (em GB) para o acionador | `number` | `1` | no |
| <a name="input_TRIGGERER_STORAGE"></a> [TRIGGERER\_STORAGE](#input\_TRIGGERER\_STORAGE) | Espaço de armazenamento (em GB) para o acionador | `number` | `1` | no |
| <a name="input_WEB_SERVER_CPU"></a> [WEB\_SERVER\_CPU](#input\_WEB\_SERVER\_CPU) | Número de vCPUs para o servidor web | `number` | `0.5` | no |
| <a name="input## Requirements

| Name | Version |
|------|---------|
| <a name="requirement_google"></a> [google](#requirement\_google) | 3.5.0 |

## Providers

| Name | Version |
|------|---------|
| <a name="provider_google-beta"></a> [google-beta](#provider\_google-beta) | 6.15.0 |
| <a name="provider_random"></a> [random](#provider\_random) | 3.6.3 |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [google-beta_google_composer_environment.composer_environment](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_composer_environment) | resource |
| [google-beta_google_project_iam_member.custom_service_account_bigquery_editor](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_iam_member) | resource |
| [google-beta_google_project_iam_member.custom_service_account_cloudfunctions_invoker](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_iam_member) | resource |
| [google-beta_google_project_iam_member.custom_service_account_composer_admin](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_iam_member) | resource |
| [google-beta_google_project_iam_member.custom_service_account_composer_worker](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_iam_member) | resource |
| [google-beta_google_project_iam_member.custom_service_account_dataform_editor](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_iam_member) | resource |
| [google-beta_google_project_service.composer_api](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_project_service) | resource |
| [google-beta_google_service_account.custom_service_account](https://registry.terraform.io/providers/hashicorp/google-beta/latest/docs/resources/google_service_account) | resource |
| [random_integer.random_number](https://registry.terraform.io/providers/hashicorp/random/latest/docs/resources/integer) | resource |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_BUCKET_OBJECT_DAGS_PREFIX"></a> [BUCKET\_OBJECT\_DAGS\_PREFIX](#input\_BUCKET\_OBJECT\_DAGS\_PREFIX) | Nome do bucket para o Cloud Composer (DAGs e consultas) | `string` | `"cc"` | no |
| <a name="input_COMPOSER_NAME"></a> [COMPOSER\_NAME](#input\_COMPOSER\_NAME) | O nome do ambiente do composer | `string` | `"cc-example-environment"` | no |
| <a name="input_COMPOSER_SA_ID"></a> [COMPOSER\_SA\_ID](#input\_COMPOSER\_SA\_ID) | Nome do service account do Composer | `string` | `"44823525"` | no |
| <a name="input_ENVIRONMENT_SIZE"></a> [ENVIRONMENT\_SIZE](#input\_ENVIRONMENT\_SIZE) | n/a | `string` | `"ENVIRONMENT_SIZE_SMALL"` | no |
| <a name="input_PROJECT"></a> [PROJECT](#input\_PROJECT) | O projeto onde os recursos serão criados | `string` | `"dataplex-experience-6133"` | no |
| <a name="input_REGION"></a> [REGION](#input\_REGION) | A região onde os recursos serão criados | `string` | `"us-east1"` | no |
| <a name="input_SCHEDULER_COUNT"></a> [SCHEDULER\_COUNT](#input\_SCHEDULER\_COUNT) | Número de instâncias do programador | `number` | `1` | no |
| <a name="input_SCHEDULER_CPU"></a> [SCHEDULER\_CPU](#input\_SCHEDULER\_CPU) | Número de vCPUs para o programador | `number` | `0.5` | no |
| <a name="input_SCHEDULER_MEMORY"></a> [SCHEDULER\_MEMORY](#input\_SCHEDULER\_MEMORY) | Quantidade de memória (em GB) para o programador | `number` | `2` | no |
| <a name="input_SCHEDULER_STORAGE"></a> [SCHEDULER\_STORAGE](#input\_SCHEDULER\_STORAGE) | Espaço de armazenamento (em GB) para o programador | `number` | `1` | no |
| <a name="input_TRIGGERER_COUNT"></a> [TRIGGERER\_COUNT](#input\_TRIGGERER\_COUNT) | Número de instâncias do acionador | `number` | `1` | no |
| <a name="input_TRIGGERER_CPU"></a> [TRIGGERER\_CPU](#input\_TRIGGERER\_CPU) | Número de vCPUs para o acionador | `number` | `0.5` | no |
| <a name="input_TRIGGERER_MEMORY"></a> [TRIGGERER\_MEMORY](#input\_TRIGGERER\_MEMORY) | Quantidade de memória (em GB) para o acionador | `number` | `1` | no |
| <a name="input_TRIGGERER_STORAGE"></a> [TRIGGERER\_STORAGE](#input\_TRIGGERER\_STORAGE) | Espaço de armazenamento (em GB) para o acionador | `number` | `1` | no |
| <a name="input_WEB_SERVER_CPU"></a> [WEB\_SERVER\_CPU](#input\_WEB\_SERVER\_CPU) | Número de vCPUs para o servidor web | `number` | `0.5` | no |
| <a name="input_WEB_SERVER_MEMORY"></a> [WEB\_SERVER\_MEMORY](#input\_WEB\_SERVER\_MEMORY) | Quantidade de memória (em GB) para o servidor web | `number` | `2` | no |
| <a name="input_WEB_SERVER_STORAGE"></a> [WEB\_SERVER\_STORAGE](#input\_WEB\_SERVER\_STORAGE) | Espaço de armazenamento (em GB) para o servidor web | `number` | `1` | no |
| <a name="input_WORKERS_MAX"></a> [WORKERS\_MAX](#input\_WORKERS\_MAX) | Número máximo de workers | `number` | `3` | no |
| <a name="input_WORKERS_MIN"></a> [WORKERS\_MIN](#input\_WORKERS\_MIN) | Número mínimo de workers | `number` | `1` | no |
| <a name="input_WORKER_CPU"></a> [WORKER\_CPU](#input\_WORKER\_CPU) | Número de vCPUs para os workers | `number` | `0.5` | no |
| <a name="input_WORKER_MEMORY"></a> [WORKER\_MEMORY](#input\_WORKER\_MEMORY) | Quantidade de memória (em GB) para os workers | `number` | `2` | no |
| <a name="input_WORKER_STORAGE"></a> [WORKER\_STORAGE](#input\_WORKER\_STORAGE) | Espaço de armazenamento (em GB) para os workers | `number` | `10` | no |
| <a name="input_ZONE"></a> [ZONE](#input\_ZONE) | A zona específica para os recursos | `string` | `"us-east1-a"` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_composer_service_account_name"></a> [composer\_service\_account\_name](#output\_composer\_service\_account\_name) | n/a |
_WEB_SERVER_MEMORY"></a> [WEB\_SERVER\_MEMORY](#input\_WEB\_SERVER\_MEMORY) | Quantidade de memória (em GB) para o servidor web | `number` | `2` | no |
| <a name="input_WEB_SERVER_STORAGE"></a> [WEB\_SERVER\_STORAGE](#input\_WEB\_SERVER\_STORAGE) | Espaço de armazenamento (em GB) para o servidor web | `number` | `1` | no |
| <a name="input_WORKERS_MAX"></a> [WORKERS\_MAX](#input\_WORKERS\_MAX) | Número máximo de workers | `number` | `3` | no |
| <a name="input_WORKERS_MIN"></a> [WORKERS\_MIN](#input\_WORKERS\_MIN) | Número mínimo de workers | `number` | `1` | no |
| <a name="input_WORKER_CPU"></a> [WORKER\_CPU](#input\_WORKER\_CPU) | Número de vCPUs para os workers | `number` | `0.5` | no |
| <a name="input_WORKER_MEMORY"></a> [WORKER\_MEMORY](#input\_WORKER\_MEMORY) | Quantidade de memória (em GB) para os workers | `number` | `2` | no |
| <a name="input_WORKER_STORAGE"></a> [WORKER\_STORAGE](#input\_WORKER\_STORAGE) | Espaço de armazenamento (em GB) para os workers | `number` | `10` | no |
| <a name="input_ZONE"></a> [ZONE](#input\_ZONE) | A zona específica para os recursos | `string` | `"us-east1-a"` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_composer_service_account_name"></a> [composer\_service\_account\_name](#output\_composer\_service\_account\_name) | n/a |
