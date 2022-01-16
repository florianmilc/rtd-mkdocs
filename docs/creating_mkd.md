# Creating MkDocs Configuration File

MkDocs allows you to quickly create a website and run it locally on your computer.
The source files for a project that uses MkDocs consists of Markdown content files and YAML configuration files.

!!! tip

    Running a website locally requires MkDocs installed on your computer. See [Installing MkDocs](install_mkd.md).

**Procedure:**

1. In the root location of your project, create a `mkdocs.yml` file.
2. Edit the file and paste the configuration provided below.

``` yaml title="mkdocs.yml"
site_name: My Website
nav: # (1)
    - Home: index.md
theme: readthedocs # (2)
```

1. The `nav` parameter allows you to build table of contents by providing `<name of the section>: filename.md`.
2. This parameter specifies the theme to be used for your website.

Ensure the `mkdocs.yml` is added to the project. See [Creating Read the Docs Configuration File](creating_rdt.md).