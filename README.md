# b2b-api-docs

This repository hosts the source files for the PaperC B2B API documentation.

## Reading the latest documentation

Documentation is served in two ways:

1. Visit (https://paperc.com/docs/)[https://paperc.com/docs/].  
_Hint:_ You can also save this page to your local computer as it's just a single HTML document. Good for doing offline work.
2. Visit (http://docs.paperc.apiary.io)[http://docs.paperc.apiary.io].  
Our (Apiary.io)[https://apiary.io]-hosted documentation has the same content as our self-hosted documentation, but also brings some handy functionality for live-testing endpoint. 

## Writing documentation

Documentation is written in the (API Blueprint)[https://apiblueprint.org/] API description language.

The description file `apiary.apib` can be edited by using either the (Apiary Online Editor)[https://app.apiary.io/paperc/editor] or a plain text editor.  
_Note:_ The Apiary editor will automatically push an updated `.apib` file into this repository upon saving.

## Building documentation

HTML representation of the documentation is compiled by [Aglio](https://github.com/danielgtaylor/aglio).

PaperC.com automatically re-compiles it on every deployment.

However, you may also manually compile the documentation (e.g. for testing).  
Run `build-apidocs` inside your paperc-com environment to do so. It will be output to `/apidocs/build/latest.html`.
