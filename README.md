# Ansible Role: Elasticsearch

An Ansible Role that installs Elasticsearch on Debian/Ubuntu.

## Requirements

- Requires at least Java 8+.
- **1024 mb ram minimum**

```
config.vm.provider "virtualbox" do |v|
  v.memory = 1024
  v.cpus = 2
end
```

## Role Variables

    elasticsearch_network_host: localhost
    elasticsearch_http_port: 9200

## Dependencies

  - java

## Example Playbook

    role: - MarioDevment.elasticsearch

## License

MIT / BSD