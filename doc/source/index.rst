=================================
Glance role for OpenStack-Ansible
=================================

.. toctree::
   :maxdepth: 2

   configure-glance.rst

:tags: openstack, glance, cloud, ansible
:category: \*nix

This role will install the following Upstart services:
    * glance-api
    * glance-registry

Example playbook
~~~~~~~~~~~~~~~~

.. literalinclude:: ../../examples/playbook.yml
   :language: yaml

Tags
~~~~

This role supports two tags: ``glance-install`` and ``glance-config``

The ``glance-install`` tag can be used to install and upgrade.

The ``glance-config`` tag can be used to manage configuration.
