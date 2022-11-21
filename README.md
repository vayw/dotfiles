# Create config  before init

`~/.config/chezmoi/chezmoi.toml`

```
[data]
  email = <my email address>
  gpgkey = <my gpg keygrip>
[data.git] # optional
  Instead = [
  {"Of"="https://private.host.org", "Use"="ssh://git@private.host.org:22"}
]
```
