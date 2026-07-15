---
date: 2026-05-03
whenToStartInside:
---
### Seedling Start Date

```javascript
date("2026-05-03") - 
((IF(whenToStartInside>0,whenToStartInside,whenToStartOutside)*7).toString()+" days")
```

### Plant Date

```javascript
date("2026-05-03")-((whenToStartOutside*7).toString()+" days")
```

