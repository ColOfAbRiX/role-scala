# scala

Ansible role to install Scala and SBT

## Role Variables

| Variable             | Default  | Description                      |
| :---                 | :---     | :---                             |
| `scala_jdk_version`  | `1.8.0`  | Version Java JDK to install.     |
| `scala_main_version` | `2.12.2` | Version of Scala to install.     |
| `scala_sbt_version`  | `0.13.5` | Version of Scala SBT to install. |

## Example Playbook

Simple example:

```Yaml
- hosts: servers
  roles:
   - role: scala
```

## License

MIT

## Author Information

[Fabrizio Colonna](colofabrix@tin.it)

## Contributors

Pull requests are also very welcome. Please create a topic branch for your proposed changes. If you don't, this will create conflicts in your fork after the merge.
