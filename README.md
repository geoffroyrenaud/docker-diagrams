# 

## build the container

```
docker build . -t mydiagrams
```

## create a diagrams

```
cat diagram-example.py | docker run -i --rm -v $(pwd)/out:/out mydiagrams
```

