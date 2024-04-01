## Content with the CLI

With the CLI installed, run:

```
jupyter lite build
```

Any contents found in:

{lite-dir}/files/
any content roots added via:
the CLI flag --contents
the #/LiteBuildConfig/contents in jupyter_lite_config.json
Will be:

copied to the built site under {output-dir}/files/
may have timestamps changed if --source-date-epoch is provided.
indexed to provide {output-dir}/api/contents/{subdir?}/all.json
