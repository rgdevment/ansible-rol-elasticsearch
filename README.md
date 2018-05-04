# Ansible Role: Elasticsearch

An Ansible Role that installs Elasticsearch on Debian/Ubuntu.

## Requirements

- Requires at least Java 8+.
- **Memory: 2048mb minimum**

```
config.vm.provider "virtualbox" do |v|
  v.memory = 2048
  v.cpus = 2
end
```

## Role Variables

    network_host: localhost
    http_port: 9200

## Dependencies

  - java

## Example Playbook

    role: - MarioDevment.elasticsearch

## License

MIT