# create-pull-request-action

Create a pull request.

<!-- actdocs start -->

## Description

This action creates a new pull request.

## Usage

```yaml
  steps:
    - name: Create Pull Request
      uses: tmknom/create-pull-request-action@v0
      with:
        head-branch: feat/new-branch
```

## Inputs

| Name | Description | Default | Required |
| :--- | :---------- | :------ | :------: |
| head-branch | The branch that contains commits for the pull request. | n/a | yes |
| base-branch | The branch into which you want your code merged. | n/a | no |
| body | The body for the pull request. | n/a | no |
| title | The title for the pull request. | n/a | no |

## Outputs

N/A

<!-- actdocs end -->

## Permissions

| Scope         | Access |
| :------------ | :----- |
| pull-requests | write  |

## FAQ

N/A

## Related projects

N/A

## Release notes

See [GitHub Releases][releases].

[releases]: https://github.com/tmknom/create-pull-request-action/releases
