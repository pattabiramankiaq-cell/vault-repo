Objective

Install and configure HashiCorp Vault on Ubuntu Linux.
Tasks Completed

    Installed Vault and verified the version.
    Initialized and unsealed Vault.
    Enabled username/password authentication.
    Enabled the KV version 2 secrets engine.
    Stored and retrieved sample secrets.
    Created an access policy and verified permissions.

Verification

    Vault service status: active (running)
    Vault status: initialized and unsealed
    Authentication: userpass enabled
    Secrets engine: KV version 2
    Policy: training-read
    Access test: read allowed, write denied

Security Notes

This is a local training lab. The listener uses HTTP on localhost and must not be exposed to an untrusted network. No root tokens, unseal keys, or real passwords should be committed to GitHub.
