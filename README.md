# zhunusovgroup-site

Статический сайт zhunusovgroup.kz. Хостинг — GitHub Pages, домен подключён через файл `CNAME`.

## Структура

- `index.html` — вся страница (HTML + CSS + JS в одном файле)
- `CNAME` — домен для GitHub Pages (`zhunusovgroup.kz`)
- `robots.txt`, `sitemap.xml` — индексация
- `.nojekyll` — отключает обработку Jekyll на Pages

## Как вносить правки

```bash
cd ~/dev/zhunusovgroup-site
# правки в index.html
git add -A && git commit -m "описание правки" && git push
```

Через 30–60 секунд изменения будут на https://zhunusovgroup.kz

## Локальный просмотр

```bash
cd ~/dev/zhunusovgroup-site && python3 -m http.server 8080
# открыть http://localhost:8080
```
