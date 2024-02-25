> [!tip] Node Version Manager
Nvm [Official docs](https://github.com/nvm-sh/nvm#installing-and-updating)

## Dental Admin UI Config

* Inside project run

```shell
nvm use
nvm install
npm i
```

* Add host `dentaladmin.com.mx`

```shell
sudo nano /etc/hosts
# Add domain
127.0.0.1 dev.dentaladmin.com.mx
```

* Finally up the project.

```shell
npm run start
```
