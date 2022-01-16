# Adding Configuration Requirements

The `python.install.requirements` parameter allows you to indicate additional configuration requirements.
By using this parameter, you specify a file that requires to feature in the project a specific layout or extension.

**Procedure:**

1. In the `config/` directory, create a `requirements.txt` file.
1. Edit the file and paste the following configuration example:

``` txt title="requirements.txt"
mkdocs-material==8.0
Pygments==2.10.0
pymdown-extensions==9.1
Markdown==3.2.1
```
Ensure the `requirements.txt` is added to the project. See [Creating Read the Docs Configuration File](creating_rdt.md).