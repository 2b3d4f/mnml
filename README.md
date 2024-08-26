# mnml

mnml is a minimalistic theme for [Hugo](https://gohugo.io/).

## Features

## Installation

1. [Install Hugo >= v0.133.0](https://gohugo.io/getting-started/installing/).
2. Create a new Hugo site.

    ```bash
    hugo new site <your-site-name> --format toml
    ```

3. Install mnml.

### Method 1: Hugo Modules (recommended)

1. Install [Go Programming Language](https://go.dev/doc/install).
2. Initialize your Hugo site.

   ```bash
    hugo mod init <your-site-git-repo>
    ```

3. Add mnml in your config.

    ```toml
    [module]
        [[module.imports]]
        path = "github.com/2b3d4f/mnml"
    ```

#### Update module

```bash
hugo mod get -u
```

### Method 2: Git Submodule

1. Add mnml as a submodule.

    ```bash
    git submodule add --depth 1 https://github.com/2b3d4f/mnml themes/mnml
    git submodule update --init --recursive
    ```

#### Update submodule

```bash
git submodule update --remote --recursive
```

## Configuration

## Demo

[mnml](https://2b3d4f.github.io/mnml)

or

```bash
hugo server --buildDrafts --cleanDestinationDir --disableFastRender --logLevel info -N --contentDir ./example/content --config ./example/hugo.toml
```
