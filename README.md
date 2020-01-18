https://help.github.com/ja/actions/automating-your-workflow-with-github-actions/creating-a-javascript-action
を参考にしている

# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```
uses: actions/hello-world-javascript-actions@v1
with:
  who-to-greet: 'Mona the Octocat'
```
