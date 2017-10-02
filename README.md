# ansible-role-newrelic-java-agent

Default Vars (tune/override these to your liking)
--------

```
newrelic_java_agent_path: "/opt/newrelic-java-agent"
newrelic_java_agent_url: "https://download.newrelic.com/newrelic/java-agent/newrelic-agent/current/newrelic-java.zip"
newrelic_java_agent_user: "newrelic"
newrelic_java_agent_group: "newrelic"
```


Required Vars (no default - you need to define these)
--------

```
newrelic_java_agent_license_key
newrelic_java_agent_app_name
```


Optional Var (set this to the relative or absolute path of a custom jinja2 template to use for newrelic.yml)
--------

```
newrelic_java_agent_custom_config
```
