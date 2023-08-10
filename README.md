# Parcel plugin to compile @acryps/page

## Installation

To install the package run

`npm install parcel-transformer-page --save-dev`

Create or update the parcel config

```
{
    "extends": ["@parcel/config-default"],
    "transformers": {
        "*.js": ["...", "parcel-transformer-page"]
    }
}
```
