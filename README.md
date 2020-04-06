# O2MCHTestScripts
## tests of raw decoder
* decoding of UserLogic pedestal data
```
o2-mchraw-dump -i data-de819-ul-ped-20200331.raw -j > out.json
```
Then compare `out.json` with `data-de819-ul-ped-20200331.json`
