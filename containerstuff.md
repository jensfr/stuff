skopeo copy docker://quay.io/isolatedcontainers/kata-operator-payload:4.5.11 oci:/tmp/kata-operator-payload:4.5.11
oci-image-tool unpack --ref name=4.5.11  kata-operator-payload kata-operator-bundle-4.5.11


