# Pubkey

##  GitHub
- [Managing commit signature verification](https://docs.github.com/cn/github/authenticating-to-github/managing-commit-signature-verification)
  - [Checking for existing GPG keys](https://docs.github.com/en/github/authenticating-to-github/checking-for-existing-gpg-keys)
  - [Generating a new GPG key](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-gpg-key)
  - [Adding a new GPG key to your GitHub account](https://docs.github.com/en/github/authenticating-to-github/adding-a-new-gpg-key-to-your-github-account)
  - [Telling Git about your signing key](https://docs.github.com/en/github/authenticating-to-github/telling-git-about-your-signing-key)
  - [Associating an email with your GPG key](https://docs.github.com/en/github/authenticating-to-github/associating-an-email-with-your-gpg-key)
  - [Signing commits](https://docs.github.com/en/github/authenticating-to-github/signing-commits)
  - [Signing tags](https://docs.github.com/en/github/authenticating-to-github/signing-tags)

## GPG
```
gpg ---full-generate-key
gpg --list-keys --with-keygrip --keyid-format LONG
gpg --list-secret-keys --with-keygrip --keyid-format LONG
gpg --armor --export [subfpr!]
```

