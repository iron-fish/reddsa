Implementation of the [RedDSA][reddsa] signature scheme and the [FROST][frost]
threshold signature scheme.

This is a fork of the original [`reddsa`][reddsa-crate] crate from Zcash. The
fork was created by the Iron Fish project to support its own implementation of
RedDSA and FROST.

## Delta from upstream

These are the differences between this crate and the upstream
[`reddsa`][reddsa-crate] crate:

* This contains code from upstream that has not been published yet.

[reddsa]: https://zips.z.cash/protocol/protocol.pdf#concretereddsa
[frost]: https://zfnd.org/frost/
[reddsa-crate]: https://crates.io/crates/reddsa
