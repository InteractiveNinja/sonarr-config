Adds Custom my Repo as resource_provider

`settings.yaml`

```yaml
resource_providers:
  - name: ninjas-cf
    type: trash-guides
    clone_url: https://github.com/InteractiveNinja/sonarr-config.git
    reference: main
  - name: ninjas-templates
    type: config-templates
    clone_url: https://github.com/InteractiveNinja/sonarr-config.git
    reference: main
```

`recyclarr.yml`

```yaml
include:
  - template: ninja-sonarr-v4-1080p-anime
```