---
date: 2026-05-03
sewLastFrostDateDiff:
---
### Seedling Start Date

```javascript
date("2026-05-03") - 
((IF(sewLastFrostDateDiff>0,sewLastFrostDateDiff,weeksBeforeFrostDate)*7).toString()+" days")
```

### Plant Date

```javascript
date("2026-05-03")-((weeksBeforeFrostDate*7).toString()+" days")
```

