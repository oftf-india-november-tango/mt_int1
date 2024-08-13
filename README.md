# Quick Start

```bash
$ npm ci
$ npm start
```

# Feature

There's an endpoint at `https://productcatalog.onefourtwentyfour.com/products` that has a list of products for sale. I would like to be able
to display these products in a list.

Example curl request:
```bash
$ curl -H "Authorization: Bearer dc896e1f" https://productcatalog.onefourtwentyfour.com/products | python -m json.tool

{
    "page": 1,
    "products": [
        {
            "id": "36407912",
            "image": "https://images.vestiairecollective.com/cdn-cgi/image/f=auto/produit/36407912-1_2.jpg",
            "price": "140.62",
            "name": "Versace Patent leather vanity case",
            "brand": "Versace",
            "num": "1"
        },
...
    ],
    "has_more": true
}
```
