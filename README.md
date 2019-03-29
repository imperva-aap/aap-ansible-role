# Tomcat Ansible role

This ansible role installs Prevoty in to a Tomcat instance.

- [Getting Started](#getting-started)
    - [Prerequisities](#prerequisities)
    - [Installing](#installing)

## Getting Started

These instructions will get you a copy of the role for your ansible playbook. Once launched, it will install [Prevoty](https://prevoty.com/) in a Tomcat installation

### Prerequisites
1. Tomcat installed via tarball
2. Copy the prevoty jar files in to the files directory. Be sure to use the versioned jars.
3. Copy the prevoty configuration files to the files directory. Be sure to set your logging path in the prevoty_logging.json file (in the future, this will be done automatically)

### Installing
1. Check out this repository in to your ansible playbook as a role.
2. Add the role to your main playbook
