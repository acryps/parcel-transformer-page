# Parcel transformer page
Parcel plugin to compile @acryps/page

## Installation

To install the package run

`npm install @acryps/parcel-transformer-page --save-dev`

Create or update the parcel config

```
{
    "extends": ["@parcel/config-default"],
    "transformers": {
        "*.js": ["...", "@acryps/parcel-transformer-page"]
    }
}
```
