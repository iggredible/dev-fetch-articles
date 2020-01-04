# dev.to fetch ✌️

We can agree that [dev.to](https://dev.to/) is the best dev spot in the world. What if you want to cross-post your dev articles into your own personal blog site, but too lazy to copy-paste each post? 😴

Now you can fetch all your DEV posts in markdown easily! 😱

# Getting started

Clone the repo, install all dependencies, and create `content/` directory in project root. The files will go in there

```
git clone https://github.com/iggredible/dev-fetch-articles.git
cd dev-fetch-articles
npm install
mkdir content
mkdir .env
// create a key called DEV_KEY and give it your dev key values from dev.to site
```

This script uses [dotenv](https://github.com/motdotla/dotenv) to store your DEV_KEY info. Create a `.env` file in project root and add `DEV_KEY=YOUR_DEV_KEY_HERE` (you can find your `DEV_KEY` inside *Settings -> Account* on [dev.to](https://dev.to/) site).

# Usage

Easy! Just run `npm run fetch-dev`. You will find all your articles inside `content/` folder you just created. You can use this script into your app or use this script to generate content that you can copy to your app.

# Contributions

Any PR for improvements/ suggestions are more than welcome! ✌️

# LICENSE

MIT © Igor Irianto
