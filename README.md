<a href="https://github.com/moddyz/HelloWorldCompositeRunStepsAction/actions?query=workflow%3A%22Main%22"><img src="https://github.com/moddyz/HelloWorldCompositeRunStepsAction/workflows/Main/badge.svg"/></a>

# HelloWorldCompositeRunStepsAction

This action prints "Hello world"  or "Hello" + name of a specified person to the log, produces a random
number output, then says goodbye.

## Inputs

### `who`

**Required** The name of the person to greet.  Defaults to `"World"`.

## Outputs

### `random-number`

The random generated number.

## Example usage

```
uses: moddyz/HelloWorldCompositeRunStepsAction@v1
with:
  who: 'Cobra Kai'
```
