# Windows-to-Front
RISC OS Desktop Modernisation Global Control to push Windows to the front by a single click

## Source Tree

```
./
├── doc
├── Models
│   ├── bas
│   │   ├── attic
│   │   └── doc
│   ├── c
│   │   ├── c
│   │   ├── doc
│   │   ├── h
│   │   └── o
│   └── s
├── Resources
└── src
```

* Doc contains documentation for the final approved code
* Models contains test and research code to model the final approved code
** bas for BBC BASIC code
** c for C code
** s for ASM (however I am trying NOT to use ASM)
* Resources contains all the code required resources as on ROOL regular source-tree
* src contains the final approved code

## Status
At this time I am doign some reserch to find best way to handle all RISC OS usual edge-cases (many) while general windows-to-front seems already to be working fine (look into Models.bas for the actual code I am testing)

Althought if BBC BASIC code seems to be performing well, I still think C might be better for the final code 

 
