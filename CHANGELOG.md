# Ansible Role for OpenJDK

## 7.5.0 - TBC

### Major Changes

-   Support Fedora 38

## 7.4.0 - 2023-03-29

### Major Changes

-   Support Ansible community package 7.4.0
-   Support Ubuntu 23.04

## 7.3.0 - 2023-03-01

-   Support Ansible community package 7.3.0

### Major Changes

## 7.2.0 - 2023-02-01

-   Support Ansible community package 7.2.0

### Major Changes

## 7.1.0 - 2022-12-09

### Major Changes

-   Support Ansible community package 7.1.0

## 7.0.0 - 2022-11-26

### Major Changes

-   Support Ansible community package 7.0.0

## 6.6.0 - 2022-11-10

### Major Changes

-   Support Ansible community package 6.6.0
-   Remove Fedora 35 support
-   Remove openSUSE Leap 15.3 support

## 6.5.0 - 2022-10-14

-   Support Ansible community package 6.5.0

### Major Changes

-   Support Ubuntu 22.10
-   Support Fedora 37

## 6.4.0 - 2022-09-15

### Major Changes

-   Support Ansible community package 6.4.0

## 6.3.0 - 2022-08-24

### Major Changes

-   Support Ansible community package 6.3.0

## 6.2.0 - 2022-08-03

### Major Changes

-   Support Ansible community package 6.2.0

## 6.1.0 - 2022-07-14

### Major Changes

-   Support Ansible community package 6.1.0
-   Revamp jdbc related with OBS repo
-   Revamp maven related with OBS repo
-   Remove Ubuntu 21.10 support

## 6.0.0 - 2022-06-22

### Major Changes

-   Support Ansible community package 6.0.0

## 5.9.0 - 2022-06-08

### Major Changes

-   Support Ansible community package 5.9.0

## 5.8.0 - 2022-05-20

### Major Changes

-   Support Ansible community package 5.8.0
-   Remove Fedora 34 support

## 5.7.0 - 2022-04-27

### Major Changes

-   Rename Ansible Role with FQCN
-   Support Ansible community package 5.7.0
-   Support RHEL 9
-   Support CentOS 9 Stream
-   Support openSUSE Leap 15.4

## 5.6.0 - 2022-04-07

### Major Changes

-   Support Ansible community package 5.6.0
-   Support Fedora 36
-   Support Ubuntu 22.04
-   Support Ansible community package 5.5.0
-   Support Ansible community package 5.4.0

## 5.5.0 - 2022-02-11

### Major Changes

-   Remove Ubuntu 21.04 support
-   Replace AdoptOpenJDK with Eclipse Temurin
-   Skip package upgrade before running molecule
-   Support Fedora Rawhide
-   Support Debian Testing

## 5.4.0 - 2021-12-31

### Major Changes

-   Remove openSUSE Leap 15.2 support
-   Upgrade minimal Ansible community package support to 4.10

## 5.3.0 - 2021-10-20

### Major Changes

-   Remove Fedora 33 support
-   Remove Ubuntu 20.10 support
-   Support Fedora 35
-   Support Ubuntu 21.10
-   Upgrade minimal Ansible community package support to 4.7.0

## 5.2.0 - 2021-09-19

### Major Changes

-   Install dependencies with package manager
-   Upgrade minimal Ansible community package support to 4.5.0

## 5.1.0 - 2021-07-18

### Major Changes

-   Upgrade minimal Ansible community package support to 4.2.0
-   Support Debian 11
-   Support openSUSE Leap 15.3
-   Improve download archive logic

## 5.0.0 - 2021-06-02

### Major Changes

-   Upgrade minimal Ansible support to 4.0.0
-   Support Fedora 34
-   Support Ubuntu 21.04
-   Simplify download archive logic

## 4.7.0 - 2021-03-13

### Major Changes

-   Bugfix [ansible-lint `namespace`](https://github.com/ansible-community/ansible-lint/pull/1451)
-   Bugfix [ansible-lint `no-handler`](https://github.com/ansible-community/ansible-lint/pull/1402)
-   Bugfix [ansible-lint `unnamed-task`](https://github.com/ansible-community/ansible-lint/pull/1413)
-   Simplify Python dependency with system packages
-   Support RHEL 8 with Molecule
-   Support RHEL 7 with Molecule
-   Remove CentOS 8 support
-   Improve HTTP transparent proxy support
-   Improve download archive logic
-   Support CentOS 8 Stream
-   Support openSUSE Tumbleweed
-   Migrate base Vagrant box from `generic/*` to `alvistack/*`

## 4.6.0 - 2020-12-28

### Major Changes

-   Simplify Molecule scenario for vagrant-libvirt
-   Migrate from Travis CI to GitLab CI
-   Support Fedora 33
-   Remove Fedora 32 support
-   Support Ubuntu 20.10
-   Remove redundant tags from tasks
-   Replace AdoptOpenJDK 14 with 15

## 4.5.0 - 2020-08-26

### Major Changes

-   Upgrade minimal Ansible Lint support to 4.3.2
-   Upgrade Travis CI test as Ubuntu Focal based
-   Upgrade minimal Ansible support to 2.10.0
-   Support openSUSE Leap 15.2
-   Remove Ubuntu 19.10 support

## 4.4.0 - 2020-06-04

### Major Changes

-   Support Fedora 32
-   Replace AdoptOpenJDK 13 with 14 for Ubuntu 20.04
-   Install from AdoptOpenJDK repo
-   Support Debian 10
-   `molecule -s default` with delegated to localhost

## 4.3.0 - 2020-04-22

### Major Changes

-   Template `molecule -s default` with dummy docker driver
-   Support CentOS/RHEL 8
-   Support Ubuntu 20.04
-   Remove Ubuntu 16.04 support
-   Upgrade minimal Molecule support to 3.0.2
-   Migrate role name to lowercase or underline
-   Migrate group name to lowercase or underline
-   Migrate molecule `group_vars` to file
-   Add Maven support

## 4.2.0 - 2020-02-13

### Major Changes

-   Migrate molecule driver to Libvirt
-   Migrate molecule verifier to Ansible
-   Support Ubuntu 19.10

## 4.1.0 - 2020-01-16

### Major Changes

-   Default `interpreter_python` with `python3`
-   Bugfix `python3-xml` not exists for openSUSE Leap 15.1
-   Rename role as `openjdk`
-   Add OpenJDK 13 support
-   Add `jshell` for Docker image

## 4.0.0 - 2019-11-05

### Major Changes

-   Upgrade minimal Ansible support to 2.9.0
-   Upgrade Travis CI test as Ubuntu Bionic based

## 3.5.0 - 2019-10-06

### Major Changes

-   Support openSUSE Leap 15.1
-   Default with Python 3
-   Revamp molecule test with vagrant

## 3.4.0 - 2019-09-18

### Major Changes

-   Run molecule test manually on Travis CI
-   Abstract package parameters with multiple version support
-   Support openjdk-11-jdk on Ubuntu 16.04 with PPA

## 3.3.0 - 2019-08-27

### Major Changes

-   Update for RHEL 7
-   Add Vagrant test for RHEL 7

## 3.2.0 - 2019-07-08

### Major Changes

-   Update LXD test profile for Kubernetes v1.15.0 support
-   Fix molecule `group_vars` with links
-   Replace `with_items` with `loop`
-   Replace `with_dict` with `var`
-   Replace `with_first_found` with `lookup('first_found')`

## 3.1.0 - 2019-06-13

### Major Changes

-   Always include default variables from `vars/main.yml`
-   Always use `become: true` with molecule, especially for vagrant

## 3.0.0 - 2019-05-20

### Major Changes

-   Upgrade minimal Ansible support to 2.8.0

## 2.6.0 - 2019-05-04

### Major Changes

-   Refine Travis CI Molecue test cases

## 2.5.0 - 2019-04-17

### Major Changes

-   Run test with `travis_wait 120`

## 2.4.0 - 2019-03-03

### Major Changes

-   Unify variable name as `package`
-   Add openSUSE Leap 15 support
-   Remove CentOS 6 support

## 2.3.0 - 2019-01-30

### Major Changes

-   Porting test to Molecule based

## 2.2.0 - 2019-01-25

### Major Changes

-   Default install OpenJDK 8 on Ubuntu 16.04 and CentOS 6
-   Default install OpenJDK 11 on Ubuntu 18.04 and CentOS 7
-   Bugfix hardcoded JAVA_HOME from /etc/profile.d/java.sh

## 2.1.0 - 2018-12-06

### Major Changes

-   CI with yamllint, ansible-lint and ansible-playbook --syntax-check
-   CI with LXD, improve systemd support
-   Use shell only when shell functionality is required
-   Template `/etc/profile.d/java.sh` for environment variables
-   Source environment variables with `su -l -s /bin/bash -c`
-   Default install Oracle Java JRE 8u191-b12
-   Support override with defaults/main.yml

## 2.0.0 - 2018-10-25

### Major Changes

-   Upgrade Ansible support to 2.6 or higher
-   Support both Ubuntu 16.04/18.04 and RHEL/CentOS 6/7
-   Upgrde Jave to 8u191-b12
-   Handle $JAVA_HOME with /etc/profile.d/java.sh
-   Keep APT/YUM cache as-is
-   Update Travis CI test plan

## 1.1.0 - 2017-11-23

### Major Changes

-   Install Java on Ubuntu 16.04/14.04 from official RPM with alien
-   Install Java on CentOS 7/6 from official RPM
-   Update test cases

## 1.0.0 - 2017-09-25

-   Ininitial release for Ansible 2.4
-   Support both Ubuntu 16.04/14.04 or RHEL/CentOS 7/6
