# Bundle OPEN API Swagger

Instead of putting all of your api documentation code inside one `yaml` file, try bundling it from multiple files and have a nice folder structure so you don't end up with hundreds of lines of code which is hard to debug and modify later on.

This project uses [swagger-cli](https://github.com/APIDevTools/swagger-cli) tool to merge all `yaml` files into one inside `_build` folder.

## Instructions

To bundle and merge all files, run `npm run build`. You can preview the built file inside `_build` directory in [Swagger live editor](https://editor.swagger.io/).
