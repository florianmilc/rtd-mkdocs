# Creating Read the Docs Configuration File

The Read the Docs service requires a configuration file to set for instance Python version or add additional configuration files to the project.

**Procedure:**

1. In the root location of your project, create a `.readthedocs.yaml` file.
1. Edit the file, paste the configuration provided below, and save the changes.

``` yaml title=".readthedocs.yaml"
version: 2

build:
  os: ubuntu-24.04
  tools:
    python: "3.13"

python:
  install:
    - requirements: config/requirements.txt

mkdocs:
  configuration: mkdocs.yml
  fail_on_warning: false
```

1. This parameter adds additional requirements to the configuration.
2. This parameter adds the configuration file for the MkDocs.

For more details on configuring Read the Docs, see the [Configuration File](https://docs.readthedocs.io/en/stable/config-file/index.html) section in the Read the Docs documentation.
