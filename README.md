# OS Patching

Playbook for patching the OS for nodes hosting OpenShift v3.9 followed by a reboot.

Separate playbooks included for only applying patches and only rebooting to allow for
pre-staging patches followed by rolling reboots at a later time. This should help shorten
patching windows.
