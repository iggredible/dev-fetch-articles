# dev.to fetch

We can agree that [dev.to](https://dev.to/) is the best dev spot in the world. What if you want to cross posts your dev articles into your own personal [jamstack](https://jamstack.org/) blog site but too lazy to copy-paste each post?

Now you can fetch all your dev.to posts and put them in your personal blog easily.

Here is how:

# Getting started

Clone the repo, install all dependencies, and create `content` directory

```
git clone https://github.com/iggredible/dev-fetch-articles.git
cd dev-fetch-articles
mkdir content
npm install
```

This script uses [dotenv](https://github.com/motdotla/dotenv) to store your DEV_KEY info. Create a `.env` file in project root and add `DEV_KEY=YOUR_DEV_KEY_HERE` (you can find your `DEV_KEY` inside *Settings -> Account*)

# Usage

Easy! Just run `npm run fetch-dev`. You will find all your articles inside `content/` folder you just created.
