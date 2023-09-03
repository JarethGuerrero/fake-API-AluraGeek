## Deploy JSON Server to Vercel

A template for deploying [JSON Server](https://github.com/typicode/json-server) on [Vercel](https://vercel.com), allowing you to run a fake REST API online 🐣!

Demo from this repository: 
https://alurageek-api.vercel.app/
### How to use (resume)

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign up or log in to [Vercel](https://vercel.com).
4. From the Vercel dashboard, click "**+ New Project**" and then "**Import**" your repository.
5. On the "**Configure Project**" screen, leave everything as default and click "**Deploy**".
6. Wait until deployment is complete, and your custom JSON server will be ready to serve!

## Default `db.json`

```json
{
 "product": [
        {
            "img": "https://m.media-amazon.com/images/I/31KuQdOmcXL._AC_.jpg",
            "name": "Trooper mug",
            "price": "$60.00",
            "description": "Trooper helmet mug",
            "category": "starwars",
            "id": 1
        },
        {
            "img": "https://m.media-amazon.com/images/I/61ijsSt+JwL._AC_SL1500_.jpg",
            "name": "Vader Funko",
            "price": "$60.00",
            "description": "Collectible Funko of Darth Vader",
            "category": "starwars",
            "id": 2
        }
 ]
}