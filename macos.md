For scripts see `.macos`

## Applications

- Enpass
- Spark
- iTerm2
- Chrome
- Edge
- Firefox
- Spotify
- Todoist
- Alfred
- VS Code
- Kap
- GPG Suite

### Setup

- Edge & Chrome:
  - Install Enpass extension
  - Install React extension
- VSCode
  - Cmd + Shift + P to add code to `$PATH`
  - Install Aperture

## Terminal

- Install homebrew
- [generate ssh-keygen](https://docs.github.com/en/github/authenticating-to-github/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent), add to GitHub
- [generate gpg key](https://docs.github.com/en/github/authenticating-to-github/managing-commit-signature-verification/generating-a-new-gpg-key), add to GitHub 


### Setup

Run after all terminal setup

```sh
gh repo clone dev
./dev/.macos
cp ./dev/{.zshrc,.aliases,.gitconfig} ~/
```

## Apple Silicon notes

- [Duplicate terminal](https://dev.to/courier/tips-and-tricks-to-setup-your-apple-m1-for-development-547g), run via Rosetta
- Install nvm via cURL
- Install node v14 via `nvm install 14`. arch should be x64, not arm64
- Install yarn via `npm install -g yarn`
