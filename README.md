# Create `~/.config/chezmoi/chezmoi.toml before init`
```
[data]
  email = <my email address>
  gpgkey = <my gpg keygrip>
[data.git] # optional
  Instead = [
  {"Of"="https://private.host.org", "Use"="ssh://git@private.host.org:22"}
]
```
