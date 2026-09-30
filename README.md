# redhat.rhel_hardening_roles

Ansible collection providing hardening roles for Red Hat Enterprise Linux,
generated from [ComplianceAsCode/content](https://github.com/ComplianceAsCode/content).

## Roles

- `redhat.rhel_hardening_roles.rhel10_anssi_bp28_enhanced`
- `redhat.rhel_hardening_roles.rhel10_anssi_bp28_high`
- `redhat.rhel_hardening_roles.rhel10_anssi_bp28_intermediary`
- `redhat.rhel_hardening_roles.rhel10_anssi_bp28_minimal`
- `redhat.rhel_hardening_roles.rhel10_bsi`
- `redhat.rhel_hardening_roles.rhel10_cis`
- `redhat.rhel_hardening_roles.rhel10_cis_server_l1`
- `redhat.rhel_hardening_roles.rhel10_cis_workstation_l1`
- `redhat.rhel_hardening_roles.rhel10_cis_workstation_l2`
- `redhat.rhel_hardening_roles.rhel10_e8`
- `redhat.rhel_hardening_roles.rhel10_hipaa`
- `redhat.rhel_hardening_roles.rhel10_ism_o`
- `redhat.rhel_hardening_roles.rhel10_ism_o_secret`
- `redhat.rhel_hardening_roles.rhel10_ism_o_top_secret`
- `redhat.rhel_hardening_roles.rhel10_pci_dss`
- `redhat.rhel_hardening_roles.rhel10_stig`
- `redhat.rhel_hardening_roles.rhel10_stig_gui`
- `redhat.rhel_hardening_roles.rhel8_anssi_bp28_enhanced`
- `redhat.rhel_hardening_roles.rhel8_anssi_bp28_high`
- `redhat.rhel_hardening_roles.rhel8_anssi_bp28_intermediary`
- `redhat.rhel_hardening_roles.rhel8_anssi_bp28_minimal`
- `redhat.rhel_hardening_roles.rhel8_cis`
- `redhat.rhel_hardening_roles.rhel8_cis_server_l1`
- `redhat.rhel_hardening_roles.rhel8_cis_workstation_l1`
- `redhat.rhel_hardening_roles.rhel8_cis_workstation_l2`
- `redhat.rhel_hardening_roles.rhel8_cui`
- `redhat.rhel_hardening_roles.rhel8_e8`
- `redhat.rhel_hardening_roles.rhel8_hipaa`
- `redhat.rhel_hardening_roles.rhel8_ism_o`
- `redhat.rhel_hardening_roles.rhel8_ospp`
- `redhat.rhel_hardening_roles.rhel8_pci_dss`
- `redhat.rhel_hardening_roles.rhel8_stig`
- `redhat.rhel_hardening_roles.rhel8_stig_gui`
- `redhat.rhel_hardening_roles.rhel9_anssi_bp28_enhanced`
- `redhat.rhel_hardening_roles.rhel9_anssi_bp28_high`
- `redhat.rhel_hardening_roles.rhel9_anssi_bp28_intermediary`
- `redhat.rhel_hardening_roles.rhel9_anssi_bp28_minimal`
- `redhat.rhel_hardening_roles.rhel9_bsi`
- `redhat.rhel_hardening_roles.rhel9_ccn_advanced`
- `redhat.rhel_hardening_roles.rhel9_ccn_basic`
- `redhat.rhel_hardening_roles.rhel9_ccn_intermediate`
- `redhat.rhel_hardening_roles.rhel9_cis`
- `redhat.rhel_hardening_roles.rhel9_cis_server_l1`
- `redhat.rhel_hardening_roles.rhel9_cis_workstation_l1`
- `redhat.rhel_hardening_roles.rhel9_cis_workstation_l2`
- `redhat.rhel_hardening_roles.rhel9_cui`
- `redhat.rhel_hardening_roles.rhel9_e8`
- `redhat.rhel_hardening_roles.rhel9_hipaa`
- `redhat.rhel_hardening_roles.rhel9_ism_o`
- `redhat.rhel_hardening_roles.rhel9_ospp`
- `redhat.rhel_hardening_roles.rhel9_pci_dss`
- `redhat.rhel_hardening_roles.rhel9_stig`
- `redhat.rhel_hardening_roles.rhel9_stig_gui`

## Usage

```yaml
- hosts: all
  roles:
    - redhat.rhel_hardening_roles.rhel9_stig
```

## Requirements

- `ansible-core >= 2.16`
- `Python >= 3.12`
- `ansible.posix >= 2.2.0`

## Installation

Install this collection from [Red Hat Ansible Automation Hub](https://console.redhat.com/ansible/automation-hub):

```console
ansible-galaxy collection install   --server https://console.redhat.com/api/automation-hub/   redhat.rhel_hardening_roles
```

For an offline installation, install the generated
`redhat-rhel_hardening_roles-1.1.82.tar.gz` artifact.

## Changelog

See the [ComplianceAsCode release notes](https://github.com/ComplianceAsCode/content/releases).

## Support

This collection is maintained by Red Hat RHEL Security Content.

As Red Hat Ansible Certified Content, this collection is entitled to support
through Ansible Automation Platform (AAP) using the Create issue button on the
top right corner of Automation Hub. If a support case cannot be opened with
Red Hat and the collection has been obtained either from Galaxy or GitHub,
there may be community help available on the Ansible Forum
(https://forum.ansible.com/).

For project issues, use the [collection issue tracker](https://redhat.atlassian.net/secure/CreateIssueDetails!init.jspa?pid=10390&issuetype=10016&components=18915).

## License

BSD-3-Clause

## Author

Red Hat
