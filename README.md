# Go SDK for MedusaJS Admin API
This repository contains the go sdk for the MedusaJS Admin API.

## Compatibility
Please note that this SDK is specifically designed to be compatible with MedusaJS **v1.20.6** and is not intended for use with MedusaJS v2 or any later versions.

## Installation

This repository depends on oapi-codegen to generate the Go SDK.

```bash
go install github.com/deepmap/oapi-codegen/cmd/oapi-codegen@latest
```

## Generate the SDK

Once you have oapi-codegen installed, you can use it to generate the Go SDK from the OpenAPI specification file for MedusaJS.

```bash
go run github.com/deepmap/oapi-codegen/cmd/oapi-codegen --config oapi-config.yaml ./openapi.yaml
```