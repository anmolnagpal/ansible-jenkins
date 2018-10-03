<p align="center"><img src="https://user-images.githubusercontent.com/4303310/42187056-ce468908-7e5f-11e8-8abb-022262fb82e6.png" /></p>

> Ansible role to deploy/setup jenkins on ubuntu 
<p align="center">
    <a href="LICENSE.md">
      <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg?style=flat-square" alt="Software License">
    </a>
    <a href="https://www.paypal.me/anmolnagpal">
      <img src="https://img.shields.io/badge/paypal-donate-179BD7.svg?style=flat-squares" alt="Donate">
    </a>
  </p>
</p>
## Role Variables

```yamlex
jenkins_version: 2.138.1
jenkins_http_port: 8443
jenkins_hostname: jenkins.yourwebsite.com
```

## Example Playbook

```yaml
- hosts: jenkins
  roles:
    - role: ansible-jenkins
      become: true
```
## 👬 Contribution
- Open pull request with improvements
- Discuss ideas in issues

- Reach out with any feedback [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/anmol_nagpal.svg?style=social&label=Follow%20%40anmol_nagpal)](https://twitter.com/anmol_nagpal)
