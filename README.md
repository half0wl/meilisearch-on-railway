# Meilisearch on Railway

One-click deploy for [Meilisearch](https://github.com/meilisearch/meilisearch) on Railway.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/template/EVzqfe?referralCode=EPXG5z) ![](https://avatars.githubusercontent.com/u/43250847?s=48&v=4)

---
> ⚠️  This template depends on Railway's Volumes feature. You must be a part
> of the [Priority Boarding](https://docs.railway.app/reference/priority-boarding)
> program to use it. Follow the instructions in the link to enroll in the program.
---

## Template Configuration

| Name | Description |
| ----------- | ----------- |
| `MEILI_MASTER_KEY` | **Required**. Master key of the Meilisearch instance. Keep this secure! Refer to [Meilisearch Docs -> Security -> Master API Key](https://www.meilisearch.com/docs/learn/security/master_api_keys#protecting-a-meilisearch-instance). |
| `MEILI_ENV` | Optional; defaults to `development`. Environment to run Meilisearch in (`development` or `production`). Refer to [Meilisearch Docs -> Configure -> Environment](https://www.meilisearch.com/docs/learn/configuration/instance_options#environment). |
| `MEILI_LOG_LEVEL` | Optional; defaults to `INFO`. Log level of the Meilisearch instance. Refer to [Meilisearch Docs -> Configure -> Log Level](https://www.meilisearch.com/docs/learn/configuration/instance_options#log-level). |
| `MEILI_HTTP_ADDR` | Optional; defaults to `0.0.0.0:3331`. HTTP address and port Meilisearch will use. Refer to [Meilisearch Docs -> Configure -> HTTP address & port binding](https://www.meilisearch.com/docs/learn/configuration/instance_options#http-address--port-binding). |
| `PORT` | Optional; defaults to `3331`. Listening port of the Meilisearch instance. |

For further configuration, please refer to https://www.meilisearch.com/docs.

## License

[MIT](LICENSE)



