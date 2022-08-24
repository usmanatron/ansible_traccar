# Ansible Role: traccar

Installs the Traccar application

## Requirements

This role assumes the following:

* Docker is installed

## Role Variables

### Main Variables

| Name | Details |
| --- | --- |
| `traccar_version` | TODO |
| `traccar_database_password` | TODO |
| `traccar_smtp_host` | Email host to use |
| `traccar_smtp_port` | Post of the above Email host to use |
| `traccar_smtp_from` | From address |
| `traccar_smtp_username` | SMTP Authentication username |
| `traccar_smtp_password` | SMTP Authentication password (Note: stored in plaintext in the config) |

### Default Variables

| Name | Default Value | Details |
| --- | --- | --- |
| `app_name` | `traccar` | Used to name things |
| `app_folder` | `/apps/traccar` | The base directory for deployment |
| `freshrss_database_username` | `traccar` | Database username |
| `freshrss_database_version` | `12.5` | Version of the PostgreSQL container to use |

## Dependencies

None

## License

MIT
