**Base setup**

```bash
$ heroku create wdc-class-7-django-heroku
$ heroku config:set PYTHONPATH=cryptos_alert
$ heroku config:set DJANGO_SETTINGS_MODULE=cryptos_alert.settings.prod
```

**Starting and stopping clock**

```bash
$ heroku ps:scale clock=1
$ heroku ps
$ heroku ps:stop clock.1
```

**Realtime logs**

```bash
$ heroku logs --tail
```
