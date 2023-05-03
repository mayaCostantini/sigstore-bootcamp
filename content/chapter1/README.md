# Chapter 1: General introduction to Sigstore, its history, philosophy and purpose

## Brief history

Project Sigstore is a new standard for signing, verifying and protecting software.

The project was started by Red Hat in 2020, and joined later by Google and Purdue University.
Sigstore was donated to the Linux Foundation in 2021 and made its public instances of Rekor and Fulcio Generaly Available in 2022.


_Resources:_

- https://docs.sigstore.dev/history/

## The Sigstore philosophy and purpose

Sigstore is a set of tools for signing all types of software artifacts, from files to container images and binaries.
As a free and open source project maintaining its own public good instance,
Sigstore aims to **"become to digital signatures what Let's Encrypt is to HTTPS"**.

Since the project creation, the Sigstore public instance has stored over 20 million artifact signatures,
with this number growing exponentially.

Sigstore is an open [Public Key Infrastructure (PKI)](https://en.wikipedia.org/wiki/Public_key_infrastructure) offers a simple interface to sign and verify artifacts that enable developers
to protect their software without needing expert knowledge in cryptography or security.
As opposed to most commonly used signing tools such as GPG, it eliminates complexity by abstracting cryptography primitives
and the tackles the issue of public key distribution.


_Resources:_

- [SigstoreCon 2022 Keynote: The Meteoric Rise of Sigstore - Luke Hinds](https://www.youtube.com/watch?v=WRDTpNWq6sE&t=606s&pp=ygUddGhlIG1ldGVvcmljIHJpc2Ugb2Ygc2lnc3RvcmU%3D)