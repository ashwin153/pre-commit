A collection of [pre-commit] hooks for [Vagrant].

## vagrant-validate

Automatically runs `vagrant validate` on commit. Requires [Vagrant] and [VirtualBox] to be installed.

```yaml
  - repo: https://github.com/ashwin153/pre-commit-vagrant
    rev: v1.1.0
    hooks:
      - id: vagrant-validate
```

[pre-commit]:
  https://pre-commit.com/
[Vagrant]:
  https://www.vagrantup.com
[VirtualBox]:
  https://www.virtualbox.org
