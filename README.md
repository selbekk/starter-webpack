# Webpack Starter for Enonic XP

This starter gives you everything you need to get started with Enonic and
Webpack.

## Initialize

Use Enonic's `toolbox.sh init-project` script to initialize your project:

```bash
./path/to/toolbox.sh init-project -n com.example.MyApp -r https://github.com/selbekk/starter-webpack.git
```

In addition to the suggested folder structure for Enonic XP (v6.4.0 and above),
we create a `webpack.config.js` for you, with Babel transformations already set
up for you.

## Tasks

As a matter of convention, this starter interfaces all tasks through npm
scripts. The ones set up for you are:

```bash
npm run build       # Runs your gradle build, which in turn runs webpack
npm run deploy      # Deploys application to your local installation
npm run watch       # Continuously builds and deploys your application
```
