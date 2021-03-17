# Setup

## SSH

```
cat ~/.ssh/<key>.pub | ssh dolina_admin@mikrotik_byt 'mkdir -p ~/.ssh && cat >> ~/.ssh/authorized_keys'

or

scp ~/.ssh/id_rsa_mikrotic.pub dolina_admin@mikrotik_byt
ssh -i ~/.ssh/id_rsa_mikrotic dolina_admin@mikrotik_byt
ssh -i ~/.ssh/id_rsa_mikrotic byt_admin@mikrotik_byt
```
