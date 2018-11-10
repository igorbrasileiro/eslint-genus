# eslint-plugin-sort-import-length

This plugin sort detect import length to be sorted

## Installation

You'll first need to install [ESLint](http://eslint.org):

```
$ npm i eslint --save-dev
```

Next, install `eslint-plugin-genus`:

```
$ npm install eslint-plugin-genus --save-dev
```

**Note:** If you installed ESLint globally (using the `-g` flag) then you must also install `eslint-plugin-genus` globally.

## Usage

Add `eslint-plugin-genus` to the plugins section of your `.eslintrc` configuration file. You can omit the `eslint-plugin-` prefix:

```json
{
    "plugins": [
        "eslint-plugin-genus"
    ]
}
```


Then configure the rules you want to use under the rules section.

```json
{
    "rules": {
        "genus/import-sort": "error"
    }
}
```

## Supported Rules

* Fill in provided rules here

**OBS**: this plugin isn't yet at npm
