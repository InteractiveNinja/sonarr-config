Adds Custom my Repo as resource_provider

`settings.yaml`
```yaml
resource_providers:
  - name: ninjas-cf
    type: custom-formats
    clone_url: https://github.com/InteractiveNinja/sonarr-config
    reference: main
```