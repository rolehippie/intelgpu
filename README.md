# intelgpu

[![Source Code](https://img.shields.io/badge/github-source%20code-blue?logo=github&logoColor=white)](https://github.com/rolehippie/intelgpu)
[![General Workflow](https://github.com/rolehippie/intelgpu/actions/workflows/general.yml/badge.svg)](https://github.com/rolehippie/intelgpu/actions/workflows/general.yml)
[![Readme Workflow](https://github.com/rolehippie/intelgpu/actions/workflows/docs.yml/badge.svg)](https://github.com/rolehippie/intelgpu/actions/workflows/docs.yml)
[![Galaxy Workflow](https://github.com/rolehippie/intelgpu/actions/workflows/galaxy.yml/badge.svg)](https://github.com/rolehippie/intelgpu/actions/workflows/galaxy.yml)
[![License: Apache-2.0](https://img.shields.io/github/license/rolehippie/intelgpu)](https://github.com/rolehippie/intelgpu/blob/master/LICENSE)
[![Ansible Role](https://img.shields.io/badge/role-rolehippie.intelgpu-blue)](https://galaxy.ansible.com/rolehippie/intelgpu)

Ansible role to install intel graphics drivers.

## Sponsor

Building and improving this Ansible role have been sponsored by my current and previous employers like **[Cloudpunks GmbH](https://cloudpunks.de)** and **[Proact Deutschland GmbH](https://www.proact.eu)**.

## Table of content

- [Requirements](#requirements)
- [Default Variables](#default-variables)
  - [intelgpu_enable_i386](#intelgpu_enable_i386)
  - [intelgpu_packages](#intelgpu_packages)
- [Discovered Tags](#discovered-tags)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)

---

## Requirements

- Minimum Ansible version: `2.10`

## Default Variables

### intelgpu_enable_i386

Enable installation of i386 packages

#### Default value

```YAML
intelgpu_enable_i386: true
```

### intelgpu_packages

List of packages to install

#### Default value

```YAML
intelgpu_packages:
  - libgl1-mesa-dri:i386
  - mesa-vulkan-drivers
  - mesa-vulkan-drivers:i386
```

## Discovered Tags

**_intelgpu_**


## Dependencies

- None

## License

Apache-2.0

## Author

[Thomas Boerger](https://github.com/tboerger)
