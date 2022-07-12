# Z3 web demo

This repo has a working example of Z3 running on the web. You can run it online https://bakkot.github.io/z3-web-demo/.

## Building

```
npm install # install dependencies
npm run build # build
```

## Running

Serve this directory somehow (e.g. `npx http-server`), then navigate to `index.html`. You should see something like

```
### running the low-level API
sat
(
  (define-fun a () Int
    0)
  (define-fun f ((x!0 Int) (x!1 Bool)) Int
    0)
)

### running the high-level API
sat
x is 4
```
in the console.
