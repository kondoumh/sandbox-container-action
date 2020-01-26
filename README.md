# sandbox-container-action
Sandbox of Docker container action

# sandbox-action
Sandbox of GitHub Action 

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

```yaml
uses: kondoumh/sandbox-container-action@master
with:
  who-to-greet: 'Mona the Octocat'
```
