# kiforks/max-nesting-depth
Limit the depth of nesting.

## Installation

```bash
npm install kiforks/max-nesting-depth
```

## Usage

If your project does not already have stylelint, then in the root of the project create the file `.stylelintrc`, or with the extension `.stylelintrc.js` so that the code editor can highlight the syntax.

Then add `kiforks/max-nesting-depth` to the `.stylelintrc` config file.

_.stylelintrc_
```json
{
    "plugins": [
      "kiforks/max-nesting-depth"
    ],
    "rules": {
	    "kiforks/max-nesting-depth": [3]
    }
}
```

## Description
This is a custom broken order with the ability to ignore not only pseudo classes, but also pseudo elements. All information about this rule you can find here - https://stylelint.io/user-guide/rules/list/max-nesting-depth/#optional-secondary-options
