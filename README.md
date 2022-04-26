> This role is not meant to be shared. It is only used by myself.
> I use this role in my playbooks by adding the repo as a Git submodule.

# Ansible Role `awscli`

- <https://github.com/aws/aws-cli/blob/v2/CHANGELOG.rst>

## FAQ

## Bump version of asdf?

Get the version reference you want from the
[official changelog](https://github.com/aws/aws-cli/blob/v2/CHANGELOG.rst).

Go into [./tasks/main.yaml](./tasks/main.yaml) and bump the version in the
"Import role trallnag.awscli" task.
