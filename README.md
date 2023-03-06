# Schemas

This repository contains a collection of [JSON Schema](http://json-schema.org/) specifications for the validation of Reviewpad configuration files.

## Usage

### VSCode

You can configure your VSCode to validate your Reviewpad configuration file against the schemas.

Open your `settings.json` file and add the following configuration:

```json
{
    "yaml.schemas": {
        // Validate reviewpad.yml against the latest schema
        "https://raw.githubusercontent.com/reviewpad/schemas/main/latest/schema.json": [
            "reviewpad.yml",
        ]
    },
}
```
