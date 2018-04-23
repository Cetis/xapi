This is the input file for an intervention-update-activity event.

Data should be supplied as a UTF-8 Tab Seperated File called intevention-update.tsv

# intervention-create-activity

* [ITEM_ID](#item_id) [1]
* [TUTOR_ID](#tutor_id) [1]
* [TIMESTAMP](#timestamp) [1]
* [NOTE](#note) [0..1]
* [WEIGHTING](#weighting) [0..1]
* [TYPE](#type) [1]


## ITEM_ID 
### Description

A unique identifier for the item being updated

### Valid Values
Any

### Format
String (255)

## TUTOR_ID
### Description

id of Tutor updating activity/intervention


### Valid Values
Any

### Format
String (255)

## TIMESTAMP
### Description

Timestamp representing time that intervention was updated on system


### Valid Values
Any

### Format
ISO 8601 timestamp

## NOTE
### Description

If the update is a note, the notes contents


### Valid Values
Any

### Format
String (255)

## WEIGHTING
### Description

If the update is a weighting change, 1-5 severity weighting

### Valid Values

1 - 5

### Format
int (1)

## TYPE
### Description

The type of input, weight change or note

### Valid Values

weight
note

### Format
string(255)