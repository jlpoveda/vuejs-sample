
init
===

```
alias docker-vue-dev='docker run --rm -v $(pwd):/src -w /src -p 8080:8080 node:6 bash -c "npm install && npm run dev"'
alias docker-vue-build='docker run --rm -v $(pwd):/src -w /src node:6 bash -c "npm install && npm run build"'
```
