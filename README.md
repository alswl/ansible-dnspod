# Ansible-dnspod

Simple dnspod module for ansible.
Use DNSPod API to control domain.

## Require

*   DNSPod token: get it from [https://www.dnspod.cn/console/user/security](https://www.dnspod.cn/console/user/security)

## Usage


-   action: `./library/dnspod.py -a 'token=12345,00000000000000000000000000000000 sub_domain=test base_domain=example.cn state=present record_type=A value=10.1.1.1'`
-   action: `./library/dnspod.py -a 'token=12345,00000000000000000000000000000000 sub_domain=test base_domain=example.cn state=absent'`

## Ref

*   [DNSPod API Document](https://www.dnspod.cn/docs/index.html)
