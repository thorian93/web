# Thorian93 Web Collection

## Here be dragons!
Everything within this repository is subject to possibly heavy change
and I cannot guarantee any stability at this point. You have been warned!

---

## Getting help

If you need help, take a look at the [issues](https://github.com/thorian93/web/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc)
and create one, if you cannot find a solution to your problem.
I will try help to the best of my abilities.

## Included content

### Roles
Name | Description | Tests
--- | --- | ---
[thorian93.web.webserver](https://github.com/thorian93/web/blob/web/roles/webserver/README.md)|Detects webserver in use and provides variables.|[![Molecule Tests for Common Role](https://github.com/thorian93/web/actions/workflows/molecule-role-common.yaml/badge.svg)](https://github.com/thorian93/web/actions/workflows/molecule-role-webserver.yaml)


## Installing this collection
Please refer to the [official Ansible documentation](https://docs.ansible.com/ansible/latest/collections_guide/collections_installing.html) on how to install this collection. The most basic way is this:

    ansible-galaxy collection install thorian93.web

## Using this collection

You can either call roles by their Fully Qualified Collection Namespace (FQCN),
such as `thorian93.web.webserver`, or you can call modules by their short name
if you list the `thorian93.web` collection in the playbook's [`collections`](https://docs.ansible.com/ansible/devel/user_guide/collections_using.html#using-collections-in-playbooks) keyword:

```yaml
---
- hosts: all

  collections:
    - thorian93.web

  tasks:
    - name: "Run webserver role."
      ansible.builtin.include_role:
        name: webserver
```

## Contributing to this collection

I welcome and appreciate contributions to this collection.
If you find problems, please open an issue or create a PR against the [thorian93.web collection repository](https://github.com/thorian93/web).
See [Contributing to Ansible-maintained collections](https://docs.ansible.com/ansible/devel/community/contributing_maintained_collections.html#contributing-maintained-collections) for more details on how to contribute.

## Release notes
<!--Add a link to a changelog.rst file or an external docsite to cover this information. -->
See [CHANGELOG.rst](CHANGELOG.rst).

## More information

- [Ansible Collection overview](https://github.com/ansible-collections/overview)
- [Ansible User guide](https://docs.ansible.com/ansible/latest/user_guide/index.html)
- [Ansible Developer guide](https://docs.ansible.com/ansible/latest/dev_guide/index.html)
- [Ansible Community code of conduct](https://docs.ansible.com/ansible/latest/community/code_of_conduct.html)

## Licensing
See [LICENSE](LICENSE).
