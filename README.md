# GraphQL CMR
A graphQL interfacing CMR. Used to search granules and collections

# How TO

```code
$npm install
$npm start
```

Visit localhost:9001/graphql

## Collection search
```
{
    collections(short_name: "xxxx") {
        id
    }
}

```


## Granules search
```
{
    granules(short_name: "xxxx") {
        download_link
    }
}


```
