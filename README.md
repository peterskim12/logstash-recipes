# logstash-recipes
Collection of Logstash parsing recipes

* winlog-security.conf: Security messages from Windows Event Logs contain nested key/value pairs that would be useful as distinct fields that can be filtered and aggregated on. This provides an example of how to parse out those nested fields using the grok, mutate and kv filters.
