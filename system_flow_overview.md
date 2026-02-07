## System Flow Overview

```mermaid
flowchart TD
    P[PRINCIPLES<br/>(mental models)]
    R[ROUTINES<br/>(daily structure)]

    ST[SOUND TRAINING<br/>(controlled sessions)]
    RW[REAL WORLD EVENTS<br/>(walks · yard · door)]

    IR[IMPROVED REFLEX PATHS<br/>(faster recovery)]
    INT[INTERVENTIONS<br/>(ladder · movement)]
    REC[RECOVERY<br/>(reset baseline)]

    P --> R

    R --> ST
    ST --> IR

    R --> RW
    IR --> INT
    RW --> INT

    INT --> REC
