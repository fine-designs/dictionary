# Fine Designs dictionary
Custom cspell dictionaries used at Fine Designs.

## Usage
Add the desired dictionary definition files to a cspell config:

```json
"dictionaryDefinitions": [
    {
        "name": "fd_allowed",
        "path": "https://raw.githubusercontent.com/fine-designs/dictionary/main/allowed.txt",
        "description": "Allowed Fine Designs Spellings"
    },
    {
        "name": "fd_forbidden",
        "path": "https://raw.githubusercontent.com/fine-designs/dictionary/main/forbidden.txt",
        "description": "Custom Fine Designs Dictionary"
    }
]
```