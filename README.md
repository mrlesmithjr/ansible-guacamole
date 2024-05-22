# ansible-guacamole

Ansible role to install/configure Guacamole

## Build Status

### GitHub Actions

![Molecule Test](https://github.com/mrlesmithjr/ansible-guacamole/workflows/Molecule%20Test/badge.svg)

## Requirements

For any required Ansible roles, review:
[requirements.yml](requirements.yml)

## Role Variables

[defaults/main.yml](defaults/main.yml)

### TOTP Configuration

To enable Two factor authentification, create a variable `guacamole_totp`:
```
guacamole_totp:
  issuer: 'guacamole.exemple.com'
  period: 60
```

### OpenID Configuration

To enable OpenID authentification, create :
```
guacamole_openid_auth: true
guacamole_openid:
  authorization-endpoint: https://idp.xxx.xx/realms/yyy/protocol/openid-connect/auth
  jwks-endpoint: https://idp.xxx.xx/realms/yyy/protocol/openid-connect/certs
  issuer: https://idp.xxx.xx/realms/yyy
  client-id: remote
  redirect-uri: https://remote.xxx.xx/guacamole
```

### guacd Configuration

guacd is the native server-side proxy used by the Apache Guacamole web application. If you wish to deploy Guacamole, or an application using the Guacamole core APIs, you will need a copy of guacd running.

guacd is installed by default. To disable it, set `guacd_config.install` to `false`:

```
guacd_config:
  install: false
```

## Dependencies

## Example Playbook

[playbook.yml](playbook.yml)

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://twitter.com/mrlesmithjr)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
- [https://everythingshouldbevirtual.com](https://everythingshouldbevirtual.com)

<a href="https://www.buymeacoffee.com/mrlesmithjr" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

> NOTE: Repo has been created/updated using [https://github.com/mrlesmithjr/cookiecutter-ansible-role](https://github.com/mrlesmithjr/cookiecutter-ansible-role) as a template.
