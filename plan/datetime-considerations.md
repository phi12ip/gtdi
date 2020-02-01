# datetime considerations

## Datetime standard: ISO 8601

### Dates:
- valid formats 
    - YYYY-MM-DD or YYYYMMDD
    - YYYY-MM
    - --MM-DD or --MMDD

### Times:
- valid formats
    - hh:mm:ss.sss or hhmmss.sss
    - hh:mm:ss or hhmmss
    - hh:mm or hhmm
    - hh
- 24:00 is not a valid representation of midnight
- time zones
    - UTC+0 offset is represented by a <time>Z
    - "-5:00" for New York
    - these two refer to the same moment:
        - 18:30Z and 22:30+04


### combined date and time representations

- the separator for the date time format is the 'T' character
- this can not besubstituted in the standard for a space
- D and T can use either basic or extended formats, but must use the same ones 

### durations

- 'P' is the designating character for a period or certain durations of time
- the formats are:
    - PnYnMnDTnHnMnS
    - PnW
- P1M is one month
- PT1M is one minute because of time designator 




