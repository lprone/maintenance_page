# maintenance page docker

## Default Running 
### Run

English Version
```
docker run --rm -p 80:80 -d lprone/maintenance:eng
```

Spanish Version
```
docker run --rm -p 80:80 -d lprone/maintenance:spa
```

## Customize Page

You can customize your maintenance page modifying [index.html](https://github.com/lprone/maintenance_page/blob/master/index.html) file.

### Build
```docker build -t <image-name> .```

### Run
```docker run --rm -p 80:80 -d <image-name>```
