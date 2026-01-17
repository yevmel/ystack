# ystack
collection of configuration used to setup a web development project.

## frontend

```bash
curl https://raw.githubusercontent.com/yevmel/ystack/refs/heads/main/frontend.patch | git apply
```

`frontend.patch` adds the following configuration to the project:
* esbuild for javascript, results are written to `src/main/resources/statis/script.js`
* http-server serving `src/main/resources/static` on port 9001 for local development
* `css` folder under `src/main`
  * [sass](https://sass-lang.com/) and [dashvar](https://dashvar.com)
* `javascript` folder under `src/main`
  * [htmx](https://htmx.org/) and [lit-html](https://lit.dev/docs/libraries/standalone-templates/)
