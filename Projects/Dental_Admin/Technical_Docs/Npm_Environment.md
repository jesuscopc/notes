# Npm ENvironment ELementary OS

> [!NOTE]
NVM ( NODE VERSION MANAGER) Installation [Official docs](https://github.com/nvm-sh/nvm#installing-and-updating)

## Dental Admin UI Config

* Inside project run

```sh
nvm use
nvm install
npm i
```

* Add host `dentaladmin.com.mx`

```sh
sudo nano /etc/hosts
# Add domain
127.0.0.1 dev.dentaladmin.com.mx
```

* Finally up the project.

```sh
npm run start
```
