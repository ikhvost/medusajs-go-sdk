# Go SDK for MedusaJS Admin API
This repository contains the go sdk for the MedusaJS Admin API.

## Compatibility
Please note that this SDK is specifically designed to be compatible with MedusaJS **v2.0.0** and is not intended for use with MedusaJS v1.x.

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