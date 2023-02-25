---
tags: artist
cssClasses: cards, cards-align-bottom, cards-cols-5, table-numbers, table-lines, row-alt
---
# 侯孝賢 Hsiao-hsien Hou

![|300]( https://img1.doubanio.com/view/personage/raw/public/5f4123d0fd32dcd29f5c5ea71dad284c.jpg )

- 姓名:: 侯孝賢
- 照片:: https://img1.doubanio.com/view/personage/raw/public/5f4123d0fd32dcd29f5c5ea71dad284c.jpg 
- 性別:: 男 
- 星座:: 白羊座 
- 出生日期:: 1947年04月08日
- 出生地:: 中國,廣東,梅縣
- 職業:: 製片人 / 編劇 / 導演 / 演員 / 副導演
- 更多外文名:: Xiao Xian Hou / Xiao-Xian Hou / Hou Hao Yin
- 家庭成員:: 曹寶鳳(妻) / 侯蘊華(女) / 蔡君飛(女婿)
- imdb編號:: [nm0396284](https://www.imdb.com/name/nm0396284)

## 電影 `$=dv.pages('#movie').filter(movie=>movie.導演=="侯孝賢").length`

```dataviewjs
let movies = dv.pages("#movie").filter(movie => movie.導演=="侯孝賢")
  .sort(movie=> movie.上映日期);
let aTitles = new Array()
for (let movie of movies) {
  let title = `[${movie.title}](${movie.IMDb})`;
  aTitles.push(title);
}
dv.paragraph(aTitles.join(" | "));
```

```dataview
table 上映日期, IMDb, "![](" + 照片 + ")" as 照片
from #movie
where 導演="侯孝賢"
sort 上映日期
```

