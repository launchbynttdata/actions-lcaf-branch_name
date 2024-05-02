# Github Action to Validate a Branch Name

## About

This action is designed to examine the name of a branch and determine whether or not it is suitable for use for predicting the next Semantic Version of a repository.

## Usage

```workflow
...
  steps:
  - name: Validate Branch Name
    uses: launchbynttdata/actions-lcaf-branch_name@v0
...
```

## Compatibility

This action has only been tested on GitHub.com.
