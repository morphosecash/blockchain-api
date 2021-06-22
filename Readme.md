

# Blockchain API

API Morphose uses to fetch data from Binance Smart Chain, Ethereum and Moonbeam 


## Development workflow

* npm test  - runs tests
  * npm run posttest - starts the linter
* npm run lint - preconfigured linter
* npm run docs - generates the apidocs
* npm run bundle - builds a new bundle
* npm run preversion - Steps before we create a new Tag
  * lint
  * changelog
* npm run pages - pushes generated apidocs to the server
* postversion - after generating a new version, push the tag to the server
* npm run changelog - generates a changelog and pushes it
