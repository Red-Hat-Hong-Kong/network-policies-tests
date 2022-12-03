# rhhk & hkex network policy demo env

## Deploy
```bash
oc new-project rhhk
oc apply -k johnny.rhhk
oc apply -k peter.rhhk
oc new-project hkex
oc apply -k marco.hkex
oc apply -k bill.hkex
```