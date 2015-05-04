Lessc wrapped in docker container.

# Usage

## Directly

```sh
docker run -it --rm -v $(pwd):$(pwd) -w $(pwd) ewoutp/lessc [lessc arguments]
```

## Alias

```sh
# Execute
alias lessc='docker run -it –rm -v $(pwd):$(pwd) -w $(pwd) ewoutp/lessc '
# Then use like this:
lessc -x style.less style.css
```
