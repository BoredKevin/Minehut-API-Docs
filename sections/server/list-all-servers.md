---
description: List ALL currently online servers.
---

# List All Servers

{% swagger baseUrl="https://api.minehut.com" path="/servers_all" method="get" summary="List All Servers" %}
{% swagger-description %}
List ALL currently online servers.
{% endswagger-description %}

{% swagger-parameter in="header" name="authorization" type="string" %} Your Minehut token. {% endswagger-parameter %}

{% swagger-parameter in="header" name="x-session-id" type="string" %} Your Minehut session id. {% endswagger-parameter %}

{% swagger-response status="200" description="" %}
```
[{...}]
```
{% endswagger-response %}
{% endswagger %}
