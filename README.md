# b2b-api-docs

Written in API Blueprint, based on Apiary.

## Static API docs
[Aglio](https://github.com/danielgtaylor/aglio) is used to compile the `apiary.apib` to a stand-alone HTML representation.

### Dependencies
* newest node/npm (with working [node-gyp](https://github.com/nodejs/node-gyp))

### Installation
* npm install -g aglio

##### Windows
* install newest node
* ``npm install -g npm-windows-upgrade``
* ``npm-windows-upgrade``
* follow the [node-gyp installation guide for windows](https://github.com/nodejs/node-gyp#installation)

### Usage
* ``aglio -i apiary.apib -o build/output.html``