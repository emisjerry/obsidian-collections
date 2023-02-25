## 劇情片
```dataview
table "![|200](" + 照片 + ")" as 照片
from #movie and -"Templates"
where contains(型別, "劇情")
```
## 愛情片
```dataview
table "![|200](" + 照片 + ")" as 照片
from #movie and -"Templates"
where contains(型別, "愛情")
```