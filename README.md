# beulogue docker action

This action allows to use [beulogue](https://github.com/SiegfriedEhret/beulogue) as a GitHub action.

## Example usage

Add a step to you workflow:

```yaml
# Runs beulogue action
- name: Run beulogue
  uses: nyrst/beulogue-action@main
  with:
    args: build
```
