# kcc-docker
Dockerfile for running the Kindle Comic Converter (KCC) - https://kcc.iosphe.re.

## Usages

```
docker run -it -v /data:/data --privileged tomasen/kcc-docker \
kcc-c2e.py -m -o /data/mobi/ --title=comic -f MOBI --batchsplit=1 \
/data/comic/images/
```

More: [https://github.com/ciromattia/kcc/]
