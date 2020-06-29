# Pgbouncer (ansible role)

This role will install pgbouncer on target hosts


### Tasks

[tasks/main.yml](tasks/main.yml)

```yaml
tasks:

```

### Default variables

[defaults/main.yml](defaults/main.yml)

```yaml
pg_version: 12                  # default postgresql version
pg_postgis_version: 30          # install postgis extension?
pg_pgdg_repo: false               # use official pgdg yum repo (disable if you have local mirror)
pg_dbsu:  postgres               # postgresql dbsu (currently setup during node provision)
pg_home:  /usr/pgsql             # postgresql binary
pg_postgis_install: true        # install postgis extension?
pg_extension_install: true      # install postgis extension?
```