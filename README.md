[![Build Status](https://drone.anthonyrabbito.com/api/badges/anthr76/anthony-rabbito-web/status.svg)](https://drone.anthonyrabbito.com/anthr76/anthony-rabbito-web)

# anthony-rabbito-web


### Generating from Docker

```
git clone https://github.com/anthr76/anthony-rabbito-web.git
```

##### Building from scratch

```
docker run --rm --volume="$PWD:/srv/jekyll" -it jekyll/jekyll jekyll build
```

##### Serving local webserver with drafts

```
docker run --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll jekyll serve --watch --drafts
```

### Generating on bare-metal

[From Jekyll](https://jekyllrb.com/docs/installation/)
