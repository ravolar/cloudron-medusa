# cloudron-medusa — файл версий пакета Medusa (Mugav Auto) для Cloudron

Здесь только **файл версий** `CloudronVersions.json`, который читает Cloudron (кнопка Update), и иконка. Кода здесь нет:
пакет и сборка — в закрытом репозитории проекта (`medusa/app/deploy/cloudron/`), образ — в закрытом реестре
`ghcr.io/ravolar/mugavauto-medusa`. Установить пакет без доступа к этому реестру нельзя.

Адрес для Cloudron (App Store → Add custom app → Community app):

```
https://raw.githubusercontent.com/ravolar/cloudron-medusa/main/CloudronVersions.json
```

Версии добавляет скрипт выпуска `medusa/app/deploy/cloudron/release.sh` (на сервере сборки): образ → закрытый реестр →
`cloudron versions add` → коммит сюда. `CloudronManifest.json`, `CHANGELOG` и тексты рядом — копии последней выпущенной
версии. Руками этот репозиторий не правят.
