> This role is not meant to be shared. It is only used by myself.
> I use this role in my playbooks by adding the repo as a Git submodule.

# Ansible Role `awscli`

- <https://github.com/aws/aws-cli>
- <https://github.com/aws/aws-cli/blob/v2/CHANGELOG.rst>

## FAQ

## Change version of the AWS CLI?

Go to [`tasks/main.yaml`](tasks/main.yaml) and bump the version in the
"Import role trallnag.awscli" task.
