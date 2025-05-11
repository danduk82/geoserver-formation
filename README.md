
# Geoserver Ausbildung

To run the presentation:

```shell
docker run --rm -p 8090:8080 \
  -v $(pwd):/home/marp/app \
  -w /home/marp/app \
  marpteam/marp-cli \
  --server . --theme theme.css
```
