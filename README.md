# Authorized ACR Git-URL research fixture

This repository is a test fixture for the operator's own ACR Tasks registry. Its submodule contains a post-checkout hook that makes one GET request to the operator-owned listener path configured at build time. Do not run a recursive clone on an unpatched Git client outside the authorized test.
