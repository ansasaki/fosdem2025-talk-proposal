# Expanding Keylime: Attestation for Trusted Execution Environments

Keylime, a remote attestation framework, has long enabled trusted computing by
leveraging measurements from Trusted Platform Modules (TPMs). However, with the
rise of modern processors supporting Trusted Execution Environments (TEEs), the
need for TEE attestation has become critical to ensure workloads truly operate
within secure enclaves.  In this talk, we’ll explore how Keylime can extend its
capabilities to perform remote attestation for TEEs, focusing on confidential
virtual machines (cVMs). We will focus on a practical use case: attesting cVMs
running on AMD SEV-SNP enabled processors. Using coconut-svsm to generate TEE
evidence and Keylime as the attestation server, we’ll showcase a complete
attestation workflow from boot to runtime.
