Format: YAML
Company: IBM/Red Hat
License: GPL
Language: Python

https://www.ansible.com/

https://github.com/ansible-collections/overview

https://pypi.org/project/ansible-base/#history

https://pypi.org/project/ansible/#history

# Tasks for playbooks and taskslist files

> [shell](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/shell_module.html),
[command](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/command_module.html),
[raw](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/raw_module.html)

## Native
> [file stat](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/stat_module.html),
[copy](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/copy_module.htm),
[get_url](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/get_url_module.html)
[/!\ use_proxy: no](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/get_url_module.html#parameter-use_proxy),
[unarchive](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/unarchive_module.html),
[template](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/template_module.html)

> [blockinfile](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/blockinfile_module.html),
[lineinfile](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/lineinfile_module.html),
[replace](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/replace_module.html),
[script](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/script_module.html),
[assemble](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/assemble_module.html),
[tempfile](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/tempfile_module.html)

> [uri](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/uri_module.html),
[pause](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/pause_module.html),
[wait_for](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/wait_for_module.html),
[wait_for_connection](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/wait_for_connection_module.html),
[async_status](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/async_status_module.html) [2](https://docs.ansible.com/ansible/latest/user_guide/playbooks_async.html)

> [user](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/user_module.html),
[group](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/group_module.html),
[cron](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/cron_module.html),
[fail](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/fail_module.html),
[blocks](https://docs.ansible.com/ansible/latest/user_guide/playbooks_blocks.html),
[getent](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/getent_module.html),
[fetch](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/fetch_module.html),
[known_host](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/known_hosts_module.html),
[service_facts](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/service_facts_module.html),
[service](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/service_module.html),
[systemd](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/systemd_module.html)

> [items](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/items_lookup.html),
[together](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/together_lookup.html)
[first_found](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/first_found_lookup.html),
[assert](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/assert_module.html)
[list](https://github.com/ansible/ansible/tree/devel/lib/ansible/modules)

> [pip](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/pip_module.html)

https://www.jeffgeerling.com/blog/2021/allowing-ansible-playbooks-work-new-user-groups-on-first-run
> https://lobste.rs/s/j9amxd/allowing_ansible_playbooks_work_with_new

http://blog.vmsplice.net/2021/06/my-performance-benchmarking-workflow.html

https://www.redhat.com/sysadmin/troubleshoot-ansible-playbooks

https://zwischenzugs.com/2021/08/27/five-ansible-techniques-i-wish-id-known-earlier/
> https://news.ycombinator.com/item?id=28327694

# Ansible Vault

# Notes

https://fr.slideshare.net/GeorgeShuklin1/best-practices-for-ansible Best practices for ansible

https://docs.ansible.com/ansible/latest/user_guide/playbooks_variables.html#accessing-information-about-other-hosts-with-magic-variables

https://stackoverflow.com/questions/58002354/how-can-i-resolve-an-inventory-member-who-has-a-certain-attribute/58004236#58004236

https://alta3.com/blog/throttling-ansibles-localaction-module Throttling Ansible's Local_Action Module

https://www.edureka.co/blog/interview-questions/ansible-interview-questions/

https://www.unixarena.com/2019/05/passing-variable-from-one-playbook-to-another-playbook-ansible.html/

https://blog.quarkslab.com/ansible-security-assessment.html

# News
https://linuxfr.org/news/presentation-de-monkeyble-framework-de-test-bout-en-bout-pour-ansible

https://github.com/omerbsezer/Fast-Ansible

https://news.ycombinator.com/item?id=33122409

https://www.ansible.com/blog/ansible-vs.-terraform-demystified

https://www.jeffgeerling.com/blog/2022/aptkey-deprecated-debianubuntu-how-fix-ansible

https://developers.redhat.com/articles/2022/05/26/whats-new-ansible-automation-platform-22

https://github.com/ansible-community/community-topics/issues/82 Future of the "ansible" package

https://github.com/afroisalreadyinu/practical-ansible-intro
> https://news.ycombinator.com/item?id=30559033

https://frederic-hemberger.de/notes/ansible/determine-latest-software-release-from-github/

https://jurrevriesen.nl/ansible-boilerplate-for-webapps/

https://blog.stephane-robert.info/post/ansible-task-asynchrones/

https://linuxfr.org/news/sortie-de-squest-le-portail-de-service-pour-tower-awx-en-version-1-0

https://blog.stephane-robert.info/post/ansible-4.0/

https://steampunk.si/blog/ansible-role-argument-specification/

https://groups.google.com/g/ansible-devel/c/AeF2En1RGI8 Ansible 4
> https://news.ycombinator.com/item?id=27215477
> > https://docs.ansible.com/ansible/devel/porting_guides/porting_guide_4.html Python 3.8