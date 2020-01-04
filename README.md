# dev.to fetch

We can agree that [dev.to](https://dev.to/) is the best dev spot in the world. What if you want to cross posts your dev articles into your own personal [jamstack](https://jamstack.org/) blog site but too lazy to copy-paste each post?

Now you can fetch all your dev.to posts and put them in your personal blog easily.

Here is how:

# Getting started

Clone the repo and install all dependencies

```
npm install
```

This app uses [dotenv](https://github.com/motdotla/dotenv) to store your DEV_KEY info. Create a `.env` file in project root and add `DEV_KEY=YOUR_DEV_KEY_HERE` (you can find your `DEV_KEY` inside *Settings -> Account*)

Before running the app, fetch your posts by running:

``
npm run fetch-dev
```

You can find your dev data (named `DevTo.json`) inside `/src/data/dev/DevTo.json`

To run:

```
npm run serve
```

When you are ready to publish, run:

```
npm run build
```

To lint:

```
npm run lint
```


Made with 💪 using [vue-cli](https://cli.vuejs.org/).

# Resources:
- [dev.to API](https://docs.dev.to/api/)
- [vue-cli](https://cli.vuejs.org/)
`
