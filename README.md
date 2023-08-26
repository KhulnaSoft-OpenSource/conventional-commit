# @khulnasoft-opensource/conventional-commit

> Never miss a conventional commit with [**commitizen**](https://www.npmjs.com/package/npm-install-checks) running on [**npx**](https://www.npmjs.com/package/commitizen).

[![Commits](https://img.shields.io/github/commit-activity/w/khulnasoft-opensource/conventional-commit?style=flat)](https://github.com/khulnasoft-opensource/conventional-commit/pulse)
[![Issues](https://img.shields.io/github/issues/khulnasoft-opensource/conventional-commit.svg?style=flat)](https://github.com/khulnasoft-opensource/conventional-commit/issues)
[![Releases](https://img.shields.io/github/v/release/khulnasoft-opensource/conventional-commit.svg?style=flat)](https://github.com/khulnasoft-opensource/conventional-commit/releases)
[![Discord](https://img.shields.io/discord/714698561081704529.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/U2peSNf23P)
[![Twitter](https://img.shields.io/twitter/follow/saucedopen?label=Follow&style=social)](https://twitter.com/saucedopen)

</div>

## 📦 Install

This package is binary and doesn't require installation however you can add it to your repository as a `devDependency`:

```shell
npm install --save-dev @khulnasoft-opensource/conventional-commit
```

## 🚀 Usage

All you have to do is run the script next to your `package.json`:

```shell
npx @khulnasoft-opensource/conventional-commit
# or
npx conventional-commit
```

## 🔧 Configuration

The most common use case for this package is to run it instead of the `git commit` command inside your `npm` scripts:

```json
{
  "scripts": {
    "push": "npx @khulnasoft-opensource/conventional-commit"
  }
}
```

or

```json
{
  "scripts": {
    "push": "npx conventional-commit"
  }
}
```

If you want to ensure local-only usage:

```json
{
  "scripts": {
    "push": "conventional-commit"
  }
}
```


## 🤝 Contributing

We encourage you to contribute to Open Sauced! Please check out the [Contributing guide](https://docs.khulnasoft.com/) for guidelines about how to proceed.

If you decide to fix a bug, make sure to use the conventional commit available at:

```shell
npm run push
```

## ⚖️ LICENSE

MIT © [KhulnaSoft OpenSource](LICENSE)
