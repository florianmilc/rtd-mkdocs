# Adding Configuration Requirements

The `python.install.requirements` parameter allows you to indicate a file containing additional configuration file.
By using this file, you can include in the project specified packages and installation requirements.

For more details, see the [Requirements File](https://docs.readthedocs.io/en/stable/config-file/v2.html#requirements-file) section in the Read the Docs documentation.

**Procedure:**

1. In the `config/` directory, create a `requirements.txt` file.
2. Edit the file, paste the following configuration, and save the changes.
``` txt title="requirements.txt"
mkdocs-material==9.5.47
Pygments==2.18.0
pymdown-extensions==10.12
Markdown==3.7
```
1. Ensure the `requirements.txt` is added to the project. See [Creating Read the Docs Configuration File](creating_rdt.md).