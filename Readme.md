### Build your site locally
1. Create 

```sh
hugo new site mysite
```


### Run Server
```
hugo server
```

or 

```
docker run --rm -it  -p 1313:1313   -v $(pwd):/src   klakegg/hugo server
```

### Publish  Code
```
hugo -d docs/
```

or

```
docker run --rm -it  -p 1313:1313   -v $(pwd):/src   klakegg/hugo -d docs/
```


### Useful Links:

[1] https://levelup.gitconnected.com/build-a-personal-website-with-github-pages-and-hugo-6c68592204c7

