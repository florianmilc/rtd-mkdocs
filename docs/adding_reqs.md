# Adding Configuration Requirements

The `python.install.requirements` parameter allows you to indicate a file containing additional configuration file.
By using this file, you can include in the project specified packages and installation requirements.

For more details, see the [Requirements File](https://docs.readthedocs.io/en/stable/config-file/v2.html#requirements-file) section in the Read the Docs documentation.

**Procedure:**

1. In the `config/` directory, create a `requirements.txt` file.
2. Edit the file, paste the following configuration, and save the changes.
``` txt title="requirements.txt"
mkdocs-material==8.0
Pygments==2.10.0
pymdown-extensions==9.1
Markdown==3.2.1
```
3. Ensure the `requirements.txt` is added to the project. See [Creating Read the Docs Configuration File](creating_rdt.md).