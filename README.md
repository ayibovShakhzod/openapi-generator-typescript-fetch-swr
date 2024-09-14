## Overview
This project uses the OpenAPI Generator to create TypeScript client code with [`fetch`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FUsers%2Fshakhzod%2FDesktop%2Fmy%2Fopenapi-generator-typescript-fetch-swr%2FREADME.md%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A21%2C%22character%22%3A86%7D%7D%2C%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FUsers%2Fshakhzod%2FDesktop%2Fmy%2Fopenapi-generator-typescript-fetch-swr%2FREADME.md%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A0%2C%22character%22%3A31%7D%7D%5D%2C%228def593b-1430-405e-b08d-791f3a023683%22%5D "Go to definition") and [`swr`](command:_github.copilot.openSymbolFromReferences?%5B%22%22%2C%5B%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FUsers%2Fshakhzod%2FDesktop%2Fmy%2Fopenapi-generator-typescript-fetch-swr%2FREADME.md%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A21%2C%22character%22%3A145%7D%7D%2C%7B%22uri%22%3A%7B%22scheme%22%3A%22file%22%2C%22authority%22%3A%22%22%2C%22path%22%3A%22%2FUsers%2Fshakhzod%2FDesktop%2Fmy%2Fopenapi-generator-typescript-fetch-swr%2FREADME.md%22%2C%22query%22%3A%22%22%2C%22fragment%22%3A%22%22%7D%2C%22pos%22%3A%7B%22line%22%3A0%2C%22character%22%3A37%7D%7D%5D%2C%228def593b-1430-405e-b08d-791f3a023683%22%5D "Go to definition") for API interactions.

## Configuration for Your Project

### Add to Dependencies
Add the following to your dependencies:
```json
"openapi-generator-typescript-fetch-swr": "github:ayibovShakhzod/openapi-generator-typescript-fetch-swr"
```

### Install OpenAPI Generator CLI
Install the OpenAPI Generator CLI using npm or yarn:
```sh
npm install @openapitools/openapi-generator-cli
# or
yarn add @openapitools/openapi-generator-cli
```

### Add Command Script
Add the following command script to your project:
```json
"<name-command>": "openapi-generator-cli generate -i <openapi-file> -g typescript-fetch -t ./node-modules/openapi-generator-typescript-fetch-swr/template -o <output-path> --additional-properties useSingleRequestParameter=true --additional-properties enumPropertyNaming=original --additional-properties=typescriptThreePlus=true"
```

#### Parameters:
- `<name-command>`: Replace with the desired name for your command.
- `-i <openapi-file>`: Specifies the input OpenAPI specification file.
- `-o <output-path>`: Specifies the output directory where the generated code will be placed.
- `--additional-properties <key1=value1,key2=value2,...>`: Allows you to pass additional properties to the generator. These properties can be used to customize the generated code.