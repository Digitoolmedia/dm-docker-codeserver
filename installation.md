# Installation for what?
This md is a temporary document to recap on the tools missing from the base code-server image. This steps will go into a future dockerfile that will enhance my CI/CD process for Node.js development.

---



### [Node.js v18.x](https://github.com/nodesource/distributions/blob/master/README.md#installation-instructions) install
```
# Using Ubuntu
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt-get install -y nodejs

# Using Debian, as root
curl -fsSL https://deb.nodesource.com/setup_18.x | bash -
apt-get install -y nodejs
```

### Useful VS Code extensions

- [Vue Language Features](https://open-vsx.org/extension/lukashass/volar)
- [Tailwind CSS IntelliSense](https://open-vsx.org/extension/bradlc/vscode-tailwindcss)
- [Prettier - Code formatter](https://open-vsx.org/extension/esbenp/prettier-vscode)
- [Markdown Preview Github Styling](https://open-vsx.org/extension/bierner/markdown-preview-github-styles)
- [GitHub Pull Requests and Issues](https://open-vsx.org/extension/GitHub/vscode-pull-request-github)