# 1tn.pw
Super simple URL shortner

Very simple API


## Create
```
curl --request POST \
  --url http://api.1tn.pw/create \
  --header 'Content-Type: application/json' \
  --data '{
	"url": "https://keloran.dev"
}'
```
Returns
```
{
	"short": "yJjWqM",
	"url": "https://keloran.dev"
}
```

## Get
```
curl --request GET \
  --url https://api.1tn.pw/yJjWqM \
```
Returns
```
{
	"long": "https://keloran.dev"
}
```
