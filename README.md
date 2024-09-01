# mnml

mnml is a under development minimalistic theme for [Hugo](https://gohugo.io/).

## Features

Under construction.

## Installation

> mnml does not support Git Submodule. You can use Hugo Modules to install mnml.

1. Install [Hugo >= v0.133.0](https://gohugo.io/getting-started/installing/).
2. Install [Go Programming Language](https://go.dev/doc/install).
3. Create a new Hugo site.

    ```bash
    hugo new site <site_name> --format toml
    ```

4. Initialize your Hugo site.

   ```bash
    hugo mod init <repo_url>
    ```

5. Add mnml in your config.

    ```toml
    # hugo.toml
    [module]
        [[module.imports]]
        path = "github.com/2b3d4f/mnml"
    ```

### Update mnml

```bash
hugo mod get -u
```

## Configuration

Under construction.

## Demo

[mnml-demo](https://2b3d4f.github.io/mnml-demo)

<!-- or

```bash
hugo server --buildDrafts --cleanDestinationDir --disableFastRender --logLevel info -N --contentDir example/content --config example/hugo.toml
``` -->

<!-- ## Develop this theme in local

```bash
git clone https://github.com/2b3d4f/mnml
cd mnml
hugo server --buildDrafts --cleanDestinationDir --disableFastRender --logLevel info -N --contentDir example/content --config example/hugo.toml
``` -->
