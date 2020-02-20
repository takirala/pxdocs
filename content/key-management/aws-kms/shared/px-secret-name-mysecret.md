---
hidden: true
---

Take a note of the annotation `px/secret-name: mysecret`. This specific annotation indicates _Portworx_ to use the the secret called `mysecret` to encrypt the volume. In this case, it will **NOT**  create a new passphrase for this volume and NOT use per volume encryption. If the annotation is not provided then _Portworx_ will use the per volume encryption workflow as described in the previous section