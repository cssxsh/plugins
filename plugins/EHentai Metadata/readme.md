EHentai Metadata
----------------------------

> This plugin fetches metadata from E-Hentai & ExHentai

**IMPORTANT:** This plugin requires the [EHentai Login](https://github.com/happypandax/plugins/tree/master/plugins/EHentai%20Login) plugin to be present

## Configuration

Configure this plugin by adding `ehentai-metadata` to the `plugin.config` namespace in your `config.yaml`:
```yaml
plugin:
    config:
        ehentai-metadata:
            option1: True
            option2:
                - item 1
                - item 2
```

#### Available options

Name | Default | Description
--- | --- | ---
`filename_search` | `true` | use the filename/folder-name for searching instead of gallery title
`expunged_galleries` | `false` | enable expunged galleries in results
`remove_namespaces` | `true` | remove superfluous namespaces like 'artist', 'language' and 'group' because they are handled specially in HPX
`gallery_results_limit` | `10` | maximum amount of galleries to return
`blacklist_tags` | `[]` | tags to ignore when updating tags
`add_gallery_url` | `true` | add ehentai url to gallery

# Changelog

- `0.1.0b`
    - first version