# Creating Read the Docs Configuration File

Read the Docs require a configuration file that indicates for instance Python version or additional configuration files.
The following example shows the contents of `.readthedocs.yaml` for generating a website that uses Mkdocs.

**Procedure:**

1. In the root location of your project, create a `.readthedocs.yaml` file.
2. Edit the file and paste the configuration provided below.

``` yaml title=".readthedocs.yaml"
version: 2

python:
  version: 3.7
  install:
    - requirements: config/requirements.txt # (1)
mkdocs:
  configuration: mkdocs.yml # (2)
  fail_on_warning: false
```

1. This parameter adds additional requirements to the configuration. See [Adding Configuration Requirements](adding_reqs.md).
2. This parameter adds the configuration file for the MkDocs. See [Creating MkDocs Configuration File](creating_mkd.md).

For more details on configuring Read the Docs, see [Configuration File](https://docs.readthedocs.io/en/stable/config-file/index.html) section in the Read the Docs documentation.