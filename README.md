# Portch beta: withdrawn keys

Portch is in private testing. Each tester gets a key signed for their own Mac, good for a short while.
This file lists the keys that have been withdrawn before they ran out.

`revocations.json` holds nothing but twelve-character key ids, the day it was published, and a signature.
It says nothing about who holds a key, which Mac it was issued for, or what anyone does with Portch.

The signature is what matters: Portch checks it against the public key built into the app, so a list that
didn't come from me is thrown away. If Portch can't reach this file at all, it honours the key the tester
already holds, so nobody is locked out by a dropped connection.
