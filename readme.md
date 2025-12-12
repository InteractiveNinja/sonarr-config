Adds Custom my Repo as resource_provider

`settings.yaml`
```yaml
resource_providers:
  - name: ninjas-cf
    type: trash-guides
    clone_url: https://github.com/InteractiveNinja/sonarr-config
    reference: main
  - name: ninjas-templates
    type: config-templates
    clone_url: https://github.com/InteractiveNinja/sonarr-config
    reference: main
```