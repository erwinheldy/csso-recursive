# csso-recursive
Run terser on a folder recursively, auto minify the results into .min.css file.

## Installation
`npm i csso-recursive -g`

## Example
`csso-recursive --input=dist/css --verbose`

## Options
- `--input=[dir]`             Input directory
- `--config=[config.json]`    CSSO configuration file. Using `csso-recursive.config.js` if exist
- `--verbose`                 Enable verbose
