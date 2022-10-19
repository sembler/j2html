# j2html.com source code

## Running

Run this as any maven project.
Website is available on http://localhost:8888/.

## Deploying

In order to "deploy" the website, the static files in the `j2html/docs` must be updated.
You can either download the files manually from your browser, or use curl:

```sh
curl "http://localhost:8888/" > index.html
curl "http://localhost:8888/download.html" > download.html
curl "http://localhost:8888/examples.html" > examples.html
curl "http://localhost:8888/news.html" > news.html
curl "http://localhost:8888/404.html" > 404.html
```

Changes will be deployed automatically once they have been merged.
