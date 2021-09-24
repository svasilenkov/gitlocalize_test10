# Описание файла .gitlocalize.yml

| Поле  | Описание | Задача |
|-------|----------|--------|
| settings.ignore_escaped_strings | Отключает декодирование символов указанных в MD-файлах в виде кодов (например, "&#123;") | [409](https://trello.com/c/ciI8CQA2/409-%D0%BD%D0%B5-%D0%B4%D0%B5%D0%BA%D0%BE%D0%B4%D0%B8%D1%80%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-%D1%83%D0%BC%D1%8B%D1%88%D0%BB%D0%B5%D0%BD%D0%BD%D0%BE-%D1%83%D0%BA%D0%B0%D0%B7%D0%B0%D0%BD%D0%BD%D1%8B%D0%B5-%D0%B2-%D0%B2%D0%B8%D0%B4%D0%B5-%D0%BA%D0%BE%D0%B4%D0%BE%D0%B2-%D1%81%D0%B8%D0%BC%D0%B2%D0%BE%D0%BB%D1%8B) |
| settings.advise_cla_signing | При создании review request предлагается поставить галочку, подтверждающую, что подписано Google CLA | [431](https://trello.com/c/e3I2ha4t/431-%D1%81%D0%BE%D0%BE%D0%B1%D1%89%D0%B0%D1%82%D1%8C-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%B8%D0%B1%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%B0%D0%BC-%D0%BE-%D0%BD%D0%B5%D0%BE%D0%B1%D1%85%D0%BE%D0%B4%D0%B8%D0%BC%D0%BE%D1%81%D1%82%D0%B8-%D0%BF%D0%BE%D0%B4%D0%BF%D0%B8%D1%81%D0%B0%D1%82%D1%8C-cla) |
| settings.frontmatter_not_escaped | Включается поддержка MD-файлов, в которых frontmatter не отделен в начале и в конце "---" | [432](https://trello.com/c/9WX70Mdl/432-%D1%83%D0%B1%D1%80%D0%B0%D1%82%D1%8C-%D0%BA%D0%B0%D1%81%D1%82%D0%BE%D0%BC%D0%BD%D1%8B%D0%B9-%D0%BA%D0%BE%D0%B4-%D0%B4%D0%BB%D1%8F-google) |
| settings.popup_for_contributors.enabled | Включает показ контрибьюторам сообщения о прекращении поддержки коммьюнити-переводов | [483](https://trello.com/c/2BIOT8ei/483-wf-%D0%BF%D0%BE%D0%BA%D0%B0%D0%B7%D1%8B%D0%B2%D0%B0%D1%82%D1%8C-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%B8%D0%B1%D1%8C%D1%8E%D1%82%D0%BE%D1%80%D0%B0%D0%BC-%D1%81%D0%BE%D0%BE%D0%B1%D1%89%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BE-%D0%BF%D1%80%D0%B5%D0%BA%D1%80%D0%B0%D1%89%D0%B5%D0%BD%D0%B8%D0%B8-%D0%BF%D0%BE%D0%B4%D0%B4%D0%B5%D1%80%D0%B6%D0%BA%D0%B8-%D0%BA%D0%BE%D0%BC%D0%BC%D1%8C%D1%8E%D0%BD%D0%B8%D1%82%D0%B8-%D0%BF%D0%B5%D1%80%D0%B5%D0%B2%D0%BE%D0%B4%D0%BE%D0%B2) |
| settings.popup_for_contributors.message_text | Текст сообщения для контрибьютеров | [483](https://trello.com/c/2BIOT8ei/483-wf-%D0%BF%D0%BE%D0%BA%D0%B0%D0%B7%D1%8B%D0%B2%D0%B0%D1%82%D1%8C-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%B8%D0%B1%D1%8C%D1%8E%D1%82%D0%BE%D1%80%D0%B0%D0%BC-%D1%81%D0%BE%D0%BE%D0%B1%D1%89%D0%B5%D0%BD%D0%B8%D0%B5-%D0%BE-%D0%BF%D1%80%D0%B5%D0%BA%D1%80%D0%B0%D1%89%D0%B5%D0%BD%D0%B8%D0%B8-%D0%BF%D0%BE%D0%B4%D0%B4%D0%B5%D1%80%D0%B6%D0%BA%D0%B8-%D0%BA%D0%BE%D0%BC%D0%BC%D1%8C%D1%8E%D0%BD%D0%B8%D1%82%D0%B8-%D0%BF%D0%B5%D1%80%D0%B5%D0%B2%D0%BE%D0%B4%D0%BE%D0%B2) |
| settings.mention_contributors_in_pull_requests | При создании pull request в комментарии упоминаются все пользователи, которые участвовали в переводе ресурса | [408](https://trello.com/c/QJFNebxf/408-%D0%BE%D0%BF%D0%BE%D0%B2%D0%B5%D1%89%D0%B0%D1%82%D1%8C-%D0%B2%D1%81%D0%B5%D1%85-%D0%BA%D0%BE%D0%BD%D1%82%D1%80%D0%B8%D0%B1%D1%8C%D1%8E%D1%82%D0%B5%D1%80%D0%BE%D0%B2-%D0%BA%D0%BE%D0%B3%D0%B4%D0%B0-%D1%81%D0%BE%D0%B7%D0%B4%D0%B0%D0%B5%D1%82%D1%81%D1%8F-pull-request) |
| settings.postprocess_jupyter_notebooks_with_nbfmt_py | Включает постобработку файлов Jupyter Notebooks скриптом на Phyton перед отправкой pull request'ов | [628](https://trello.com/c/Vcw80nXu/628-%D1%81%D0%B4%D0%B5%D0%BB%D0%B0%D1%82%D1%8C-%D0%BE%D0%B1%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D1%83-%D1%81-%D0%BF%D0%BE%D0%BC%D0%BE%D1%89%D1%8C%D1%8E-nbfmtpy-%D0%BF%D0%B5%D1%80%D0%B5%D0%B4-%D0%BE%D1%82%D0%BF%D1%80%D0%B0%D0%B2%D0%BA%D0%BE%D0%B9-pull-request%D0%B0) |
| settings.json_files_type2 | Включает трактовку всех JSON-файлов репозитория как [файлов второго типа](https://github.com/gitlocalize/minikube/blob/master/translations/es.json) | [323](https://trello.com/c/dBK3LSRV/323-%D1%81%D0%B4%D0%B5%D0%BB%D0%B0%D1%82%D1%8C-%D0%BF%D0%BE%D0%B4%D0%B4%D0%B5%D1%80%D0%B6%D0%BA%D1%83-json-%D1%84%D0%B0%D0%B9%D0%BB%D0%BE%D0%B2-%D0%B2%D1%82%D0%BE%D1%80%D0%BE%D0%B3%D0%BE-%D1%82%D0%B8%D0%BF%D0%B0) |
| synchronize.paths[].source | Path Rule для которого будут применяться правила exclude | [193](https://trello.com/c/zKqN5ovh/193-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D1%83-black-%D0%B8-whitelist-%D0%B4%D0%BB%D1%8F-%D1%81%D0%B8%D0%BD%D1%85%D1%80%D0%BE%D0%BD%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8-%D0%B8-pre-translation) |
| synchronize.paths[].include | Список папок или файлов, которые **должны** показываться в интерфейсе GitLocalize (поддерживаются маски, в том числе RegEx) | [193](https://trello.com/c/zKqN5ovh/193-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D1%83-black-%D0%B8-whitelist-%D0%B4%D0%BB%D1%8F-%D1%81%D0%B8%D0%BD%D1%85%D1%80%D0%BE%D0%BD%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8-%D0%B8-pre-translation) |
| synchronize.paths[].exclude | Список папок или файлов, которые **не должны** показываться в интерфейсе GitLocalize (поддерживаются маски, в том числе RegEx) | [193](https://trello.com/c/zKqN5ovh/193-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D1%83-black-%D0%B8-whitelist-%D0%B4%D0%BB%D1%8F-%D1%81%D0%B8%D0%BD%D1%85%D1%80%D0%BE%D0%BD%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8-%D0%B8-pre-translation) |
| pretranslate.paths[].source | Path Rule для которого будут применяться правила include | [193](https://trello.com/c/zKqN5ovh/193-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D1%83-black-%D0%B8-whitelist-%D0%B4%D0%BB%D1%8F-%D1%81%D0%B8%D0%BD%D1%85%D1%80%D0%BE%D0%BD%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8-%D0%B8-pre-translation) |
| pretranslate.paths[].include | Список папок или файлов, для которых **будет** автоматически запускаться Machine Translate (поддерживаются маски, в том числе RegEx) | [193](https://trello.com/c/zKqN5ovh/193-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D1%83-black-%D0%B8-whitelist-%D0%B4%D0%BB%D1%8F-%D1%81%D0%B8%D0%BD%D1%85%D1%80%D0%BE%D0%BD%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8-%D0%B8-pre-translation) |
| pretranslate.paths[].exclude | Список папок или файлов, для которых **не будет** автоматически запускаться Machine Translate (поддерживаются маски, в том числе RegEx) | [193](https://trello.com/c/zKqN5ovh/193-%D1%80%D0%B5%D0%B0%D0%BB%D0%B8%D0%B7%D0%BE%D0%B2%D0%B0%D1%82%D1%8C-%D0%BD%D0%B0%D1%81%D1%82%D1%80%D0%BE%D0%B9%D0%BA%D1%83-black-%D0%B8-whitelist-%D0%B4%D0%BB%D1%8F-%D1%81%D0%B8%D0%BD%D1%85%D1%80%D0%BE%D0%BD%D0%B8%D0%B7%D0%B0%D1%86%D0%B8%D0%B8-%D0%B8-pre-translation) |
| pretranslate.segments.ignore_frontmatter_keys | Список ключей frontmatter, для которые не будут автоматически переводиться с помощью Machine Translate | [411](https://trello.com/c/frK6u1yR/411-%D0%BD%D0%B5-%D0%BF%D0%B5%D1%80%D0%B5%D0%B2%D0%BE%D0%B4%D0%B8%D1%82%D1%8C-%D0%B2-pretranslate-%D0%BD%D0%B5%D0%BA%D0%BE%D1%82%D0%BE%D1%80%D1%8B%D0%B5-%D0%BF%D0%BE%D0%BB%D1%8F-frontmatter) |
| pretranslate.segments.ignore_patterns | Список паттернов (RegEx) для кусков текстов в сегментах, для которые не должны переводиться с помощью Machine Translate | |
| exclusive_tags | Список кастомных тегов для маркдаун формата(Пример 10) | |
| segments.ignore_frontmatter_keys | Список ключей frontmatter, которые будут заблокированы для пользователя, не буду переводиться, учитываться в статистике | [995](https://trello.com/c/iixT6MW3/995)

## Примеры конфигурационных файлов

### Пример 1

```
settings:
  ignore_escaped_strings:
  - "true"
  advise_cla_signing:
  - "true"
  frontmatter_not_escaped:
  - "true"
  popup_for_contributors:
    enabled: true
    message_text: WebFundamentals is transitioning to web.dev, and for now, this project is no longer accepting translations from contributors. Your translations will no longer be reviewed and sent as Pull Requests. Please stay tuned for future updates on the <a href="https://web.dev">web.dev</a> project.

synchronize:
  paths:
  - source: .
    exclude:
    - "locales2/*"
    - "locales/*"
    - "_redirects.yaml"

pretranslate:
  segments:
    ignore_frontmatter_keys:
    - "layout"
    - "permalink"
    - "noindex"
    - "date"
    - "override"
    - "codelabs"
    - "tags"
    - "authors"

    ignore_patterns:
    - !ruby/regexp /{%\s?([a-zA-Z0-9\.\,\-\?\'\"\s]*)\s?%}/
    - "{# wf_(?!featured_snippet).*#}"
    - "^(Note|Caution|Warning|Success|Key Point|Key Term|Objective|Dogfood): "
    - "{:.*}"
    - "{%.*%}"

  paths:
  - source: .
    include:
    - "pretrans5/*.*"
```

### Пример 2: исключены html-файлы из главной и подпапок

```
synchronize:
  paths:
  - source: .
    exclude:
      - "*.html"
```

### Пример 3: в главной html-файлы видны, из подпапок исключены

```
synchronize:
  paths:
  - source: .
    exclude:
      - "**/*.html"
```

### Пример 4: из главной html-файлы исключены, а в подпапках видны

```
synchronize:
  paths:
  - source: .
    exclude:
      - "*.html"
    include:
      - "**/*.html"
```

### Пример 5: пропали json-файлы из папок из подпапок, но после include вернулся test1.json только в главной, см: пример 6

```
synchronize:
  paths:
  - source: .
    exclude:
      - "*.json"
      - "1/test2.json"
    include:
      - "test1.json"
```

### Пример 6: пропали json-файлы из папок из подпапок, после include вернулся test1.json в главой и подпапках

```
synchronize:
  paths:
  - source: .
    exclude:
      - "*.json"
      - "1/test2.json"
    include:
      - "test1.json"
      - "**/test1.json"
```

### Пример 7: пропали json-файлы только в подпапках папки 3, но в самой папке 3 видны

```
synchronize:
  paths:
  - source: .
    exclude:
      - "*.html"
      - "3/**/*.json"
```

### Пример 8: pretranslate всех папок и подпапок папки 3

```
pretranslate:
  paths:
  - source: .
    include:
      - "3/*.*"
```

### Пример 9: pretranslate всех папок и подпапок папки 3, кроме папок и подпапок папки 3/3

```
pretranslate:
  paths:
  - source: .
    include:
      - "3/*.*"
    exclude:
      - "3/3/*.*"
```

### Пример 10: opened - открывающий тег, change_opened - регексп с макрдаун тегом которым хотим обособить тег и аналогично с закрывающим

```
exclusive_tags:
  - opened: !ruby/regexp \[sourcecode:html\]
    change_opened: "```\n"
    closed: !ruby/regexp \[\/sourcecode\]
    change_closed: "\n```"
    remove_tag: !ruby/regexp \n
```
