# Summary

* [Introduction](README.md)
* [Installation](install/README.md)
    * [Docker](install/docker.md)
* [Quick Start](quick_start/README.md)
    * [Authenticating](quick_start/authenticating.md)
    * [Add an endpoint](quick_start/add_endpoint.md)
    * [Add Plugins](quick_start/add_plugins.md)
    * [Authentication](quick_start/add_auth.md)
* [Proxy Reference](proxy/README.md)
    * [Terminology](proxy/terminology.md)
    * [Overview](proxy/overview.md)
    * [Routing capabilities](proxy/routing_capabilities.md)
    * [Request Host header](proxy/request_host_header.md)
        * [Using wildcard hostnames](proxy/wildcard_hostnames.md)
        * [The `preserve_host` property](proxy/preserve_host_property.md)
    * [Request URI](proxy/request_uri.md)
        * [The `strip_path` property](proxy/strip_uri_property.md)
        * [The `append_path` property](proxy/append_uri_property.md)
    * [Request HTTP method](proxy/request_http_method.md)
    * [Routing priorities](proxy/routing_priorities.md)
    * [Conclusion](proxy/conclusion.md)
* Plugins
    * [Compression](plugins/compression.md)
    * [OAuth](plugins/oauth.md)
    * [Rate Limit](plugins/rate_limit.md)
    * [CORS](plugins/cors.md)
    * [Request Transformer](plugins/request_transformer.md)
    * [Response Transformer](plugins/response_transformer.md)
    * [Body Limit](plugins/body_limit.md)
* Auth
    * [OAuth 2.0](auth/oauth.md)
* Misc
    * [Monitoring](misc/monitoring.md)
    * [Health Checks](misc/health_checks.md)
    * [Storage](misc/storage.md)
* Upgrade Notes
    * [2.x to 3.x](upgrade/3x.md)