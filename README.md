# caz-templates

CAZ official templates

## Getting Started

Clone all template repositories

```shell
# clone all templates

# touch a vscode workspace config file
vi templates.code-workspace
```

The `templates.code-workspace` contents

```json
{
  "folders": [
    {
      "path": "minima"
    },
    {
      "path": "starter"
    },
    {
      "path": "nm"
    },
    {
      "path": "vercel"
    },
    {
      "path": "vue"
    },
    {
      "path": "vite"
    },
    {
      "path": "x-pages"
    }
  ],
  "settings": {
    "files.associations": {
      "**/template/**/*.*": "html"
    }
  },
  "extensions": {
    "recommendations": [
      "digitalbrainstem.javascript-ejs-support"
    ]
  }
}
```

Open `templates.code-workspace` in VSCode

## Contributing

1. **Fork** it on GitHub!
2. **Clone** the fork to your own machine.
3. **Checkout** your feature branch: `git checkout -b my-awesome-feature`
4. **Commit** your changes to your own branch: `git commit -am 'Add some feature'`
5. **Push** your work back up to your fork: `git push -u origin my-awesome-feature`
6. Submit a **Pull Request** so that we can review your changes.

> **NOTE**: Be sure to merge the latest from "upstream" before making a pull request!

## License

[MIT](LICENSE) &copy; [zce](https://zce.me)
