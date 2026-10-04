# masterlabos-licences

Signed licence revocation list read by MasterLabOS.

`revoked.json` contains only one-way fingerprints, signed with the vendor's key. It reveals no licence numbers, customers or data, and cannot be changed by anyone else: MasterLabOS ignores any list that is not signed by the vendor or is older than the last one it saw.
