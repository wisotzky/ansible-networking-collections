![NOKIA](Logo_Nokia.png)
# ansible-networking-collections

[Nokia](https://www.nokia.com/networks/) supports the [Ansible](https://www.ansible.com/) community to manage networking devices such as the Nokia [IP Networks portfolio](https://www.nokia.com/networks/ip-networks/) running [SR OS](https://www.nokia.com/networks/services/service-router-operating-system/).

This GitHub repository is about the development of [Ansible Collections](https://docs.ansible.com/ansible/latest/dev_guide/developing_collections.html) to work with Nokia devices.

## About Ansible Collections
*Collections are a distribution format for Ansible content that includes playbooks, roles, modules, and plugins. You can install and use collections through [Ansible Galaxy](https://galaxy.ansible.com).*

## Nokia Collections
Ansible collections contributed by Nokia are available from: https://galaxy.ansible.com/nokia 

#### Available
* [SR OS collection](sros) for CLI and NETCONF
* [gRPC collection](grpc) for OpenConfig gNMI

#### Planned
* [Nuage collection](nuage)
* [NetAct collection](netact)

## Controller requirements

The collections in this repository target **ansible-core 2.13** and newer. Ensure your automation host provides a supported Python 3 runtime (Python 3.8 or later is recommended).

## License

This project is licensed under the BSD-3-Clause license - see the [LICENSE](LICENSE).
