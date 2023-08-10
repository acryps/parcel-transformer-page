# Parcel plugin to compile @acryps/page

## Installation

To install the package run<br>
> $ npm install --save-dev parcel-transformer-page

Create or update the parcel config

```
{
    "extends": ["@parcel/config-default"],
    "transformers": {
        "*.js": ["...", "parcel-transformer-page"]
    }
}
```
