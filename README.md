# Kolvins .dotfiles
managed with [`chezmoi`](https://www.chezmoi.io/)

## How to use
```
chezmoi init Kolvin
```

## Secret managment
Personal & Work secrets are stored in [1Password](https://1password.com/), and you'll need
the [1Password
CLI](https://support.1password.com/command-line-getting-started/) installed.
Login to 1Password for the first time with:
```
eval $(op signin <subdomain>.1password.com <email>)
```

Then, to login afterwards, run:
```
eval $(op signin)
```