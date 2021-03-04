# Splunk AppInspect action

This action runs Splunk's AppInspect CLI against a provided a directory of a SPlunk App. It fails it the result contains any failures.

## Inputs

### `app-path`

**Required**: The path to directory of the app in the working directory.

## Outputs

### `status`:  

`pass|fail`

## Example usage

uses: actions/hello-world-docker-action@v1
with:
  who-to-greet: 'Mona the Octocat'

```yml
uses: dshomoye/splunk-appinspect@master
with:
  app-path: 'test'
```
