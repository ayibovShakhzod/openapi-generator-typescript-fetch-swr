## Overview
This project uses the OpenAPI Generator to create TypeScript client code with `fetch` and `swr` for API interactions.

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
"<name-command>": "openapi-generator-cli generate -c ./node_modules/openapi-generator-typescript-fetch-swr/config.yaml -i <openapi-file> -g typescript-fetch -t ./node_modules/openapi-generator-typescript-fetch-swr/template -o <output-path> --additional-properties useSingleRequestParameter=false --additional-properties enumPropertyNaming=original --additional-properties typescriptThreePlus=true"
```

#### Parameters:
- `<name-command>`: Replace with the desired name for your command.
- `-i <openapi-file>`: Specifies the input OpenAPI specification file.
- `-o <output-path>`: Specifies the output directory where the generated code will be placed.
- `--additional-properties <key1=value1,key2=value2,...>`: Allows you to pass additional properties to the generator. These properties can be used to customize the generated code.