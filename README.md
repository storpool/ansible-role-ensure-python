ensure_python
=========

Install a Python interpreter on the remote hosts so that subsequent Ansible playbooks can be executed against it.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - name: Ensure Python is installed
      hosts: all
      connection: ssh
      gather_facts: false
      roles:
        - ensure_python

License
-------

Apache-2.0

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
