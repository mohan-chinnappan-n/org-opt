# Apex Triggers

## List triggers

```
cat  ~/.ea/apexTrigger.soql
```
```sql
SELECT ID , Body
 FROM ApexTrigger
```
```
$ sfdx mohanc:tooling:query -u mohan.chinnappan.n_ea2@gmail.com -q ~/.ea/apexTrigger.soql 

"attributes","Id","Body"
"{""type"":""ApexTrigger"",""url"":""/services/data/v49.0/tooling/sobjects/ApexTrigger/01q3h000000aVZAAA2""}","01q3h000000aVZAAA2","trigger TestTooling on Account (before insert) {
```
