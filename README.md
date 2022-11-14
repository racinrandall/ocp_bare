# bare-metal
The following files are required to be placed in appropriate locations after downloading this project

- filename: mirror-registry.tar.gz
  location: roles/ocp-mirror/files/
- filename: oc-4.11.13-linux.tar.gz ( or current version )
  location: roles/sync_registry/files/
  variable: oc_cli_tar
- filename: oc-mirror.tar.gz
  location: roles/sync_registry/files/
  variable: oc_mirror_tar
- filename: mirror_content.tar ( tar of mirror content )
  location: roles/sync_registry/files/
  variable: mirror_tarball
- filename: openshift-baremetal-install
  location: roles/pre-ocp/files
  variable: ipi_installer
- filename: rhcos-411.86.202210041459-0-qemu.x86_64.qcow2.gz
  location: roles/pre-ocp/files
  variable: rhcos_image
  variable: rhcos_image # This is the sha256 sum of the uncompressed rhcos_image
  