os_nova role
############
:tags: openstack, cloud, ansible, os_nova
:category: \*nix

os_nova Role

.. code-block:: yaml

    - name: os_nova role
      hosts: "hosts"
      user: root
      roles:
        - { role: "os_nova" }
