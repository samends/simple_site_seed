![Simple Seed](http://www.tosbase.com/content/img/icons/items/icon_item_seed_brown.png "Seed")

## Simple Site Seed

Too many seed projects have grown up into full blown trees, they are not seeds anymore.  This simple project aims to scale back all the bells and whistles and gives you what you'd expect from a seed, the basics for growth.

Upon cloning the application will have the following ready to go:

* Babel ES6 Complier
* Sass to Css Complier
* Bootstrap
* Basic express server
* Basic project structure

That's it!

### Setup

Once the project is cloned run the following to install node dependencies:

```
yarn
```

Next next:
```
yarn build
```
This will compile all es6 into es5.

In another terminal window run:

```
yarn watch-css
```
This will compile all sass into css.

Leave the previous two commands running as they will watch for code changes.

### Startup

To start the server run:
```
yarn start
```

### Other Info

* All compiled code is found in the dist folder, this is also where the site is being hosted.
* Server config info is located in server/main.js

