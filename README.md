## WC3 Build Order App

A simple app to create and share WC3 build orders.

## Build Node

* `npm install`
* `npm install -g ts-node`

Local:
* `npm run start:dev`

Prod:
* `npm run build`
* `npm run start`

## Build Client

* `cd /src/client`
* `npm install`

Local:
* `npm start`

Prod:
* `npm run build`
* `npm install -g serve`
* `serve -s build`

You need to be running a mongodb instance locally.

## Contributing
I will host this repository but I will not spend a lot of time on the development of this small application.

If you want to contribute to this project, please create a pull request.

Adding more "actions" (clickable Icons) can be accomplished by adding the 
ActionCode enum in `src/client/src/store/common/types.ts` and adding ActionCodeDetails for this
code in `src/client/src/store/common/actionCodes.ts - actionCodesToDetailsMap`.
