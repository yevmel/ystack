# ystack
collection of configuration used to setup a web development project.

## frontend

```bash
curl https://raw.githubusercontent.com/yevmel/ystack/refs/heads/main/frontend.patch | git apply
```

`frontend.patch` adds the following configuration to the project:
* `javascript` folder under `src/main`
* esbuild for javascript, results are written to `src/main/resources/statis/script.js`
* `css` folder under `src/main`
* [tailwindcss v4](https://tailwindcss.com) and the form plugin, results are written to `src/main/resources/static/style.css`
* http-server serving `src/main/resources/static` on port 9001 for local development
