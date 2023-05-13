## Deploy JSON Server to Vercel

A template to deploy [JSON Server](https://github.com/typicode/json-server) to [Vercel](https://vercel.com), allow you to run fake REST API online!

Demo from this repository: 

1. https://json-server-in.vercel.app
2. https://json-server-in.vercel.app/api/posts

### How to use

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign Up or login into [Vercel](https://vercel.com).
4. From the Vercel dashboard, click "**+ New Project**" then "**Import**" your repository.
5. In the "**Configure Project**" screen, leave everything default and click "**Deploy**".
6. Wait until deployment is done, and your own JSON server is ready to serve!

## Default `db.json`

```json
[
	{
		"id":1,
		"name": "Dark Chocolate",
		"Flavor": "Chocolate",
		"Description": "Rich, creamy chocolate ice cream.",
		"Price": 250,
		"Stock": 10
	},
	{
		"id":2,
		"name": "Classic Vanilla"
		"Flavor": "Vanilla",
		"Description": "Classic vanilla ice cream.",
		"Price": 200,
		"Stock": 15
	},
	{
		"id":3,
		"name": "Neapolitan",
		"Flavor": "Strawberry",
		"Description": "Fresh and fruity strawberry ice cream.",
		"Price": 300,
		"Stock": 8
	},
]
```

## Reference

1. https://github.com/typicode/json-server
2. https://vercel.com
3. https://shadowsmith.com/how-to-deploy-an-express-api-to-vercel
