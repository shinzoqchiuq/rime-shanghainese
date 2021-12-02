# 上海話輸入方案（錢拼、滬二、法吳、NRSS）

配方：℞ **shinzoqchiuq/rime-shanghainese**

吳語上海話輸入方案，包含除吳語拼音（吳拼）外的四種拼音方案。

本方案依賴於吳語學堂的 [上海吳語拼音輸入方案](https://github.com/NGLI/rime-wugniu_zaonhe) ℞ **NGLI/rime-wugniu_zaonhe**

安裝本方案前，需要先安裝吳語學堂的上海吳語拼音輸入方案。

本倉庫所有方案均基於中派上海話音系，包含的方案有：

- `shanghe_xhipin`：上海話拼音方案 正式（錢拼）
- `zanghe_wrunri`：上海話拼音方案 副式（滬二）
- `zaonhe_faqwu`：吳語拉丁式注音法（法吳）
- `zonhe_nrss`：新版上海話羅馬字方案（NRSS）

本倉庫的四種拼音方案均只適用於上海市區話。若僅使用上海話，可以在這四種方案中任選一種順手的方案。但若想瞭解各地的吳語方言，如蘇州話、上海本地話等，請點擊上方鏈接，使用能兼容各地吳語的上海話吳語拼音輸入方案。

## 拼音方案對比

### 聲母

|  例字  |  IPA   | 學堂式吳拼 | 錢拼 | 滬二 | 法吳 | NRSS |
| :----: | :----: | :--------: | :--: | :--: | :--: | :--: |
|   北   |   p    |     p      |  b   |  p   |  p   |  p   |
|   潑   |   pʰ   |     ph     |  p   |  ph  |  ph  |  ph  |
|   蔔   |   b    |     b      |  bh  |  b   |  b   |  b   |
|   摸   |   m    |     m      |  mh  |  mr  |  m   |  m   |
|   咪   |   ʔm   |     mh     |  m   |  m   |  mh  |  m   |
|   夫   |   f    |     f      |  f   |  f   |  f   |  f   |
|   扶   |   v    |     v      |  fh  |  v   |  v   |  v   |
|   得   |   t    |     t      |  d   |  t   |  t   |  t   |
|   脫   |   tʰ   |     th     |  t   |  th  |  th  |  th  |
|   奪   |   d    |     d      |  dh  |  d   |  d   |  d   |
|   諾   |   n    |     n      |  nh  |  nr  |  n   |  n   |
|   拿   |   ʔn   |     nh     |  n   |  n   |  nh  |  n   |
|   勒   |   l    |     l      |  lh  |  lr  |  l   |  l   |
|   拎   |   ʔl   |     lh     |  l   |  l   |  lh  |  l   |
|   資   |   ts   |     ts     |  z   |  ts  |  tz  |  ts  |
|   次   |  tsʰ   |    tsh     |  c   | tsh  |  ts  |  c   |
|   絲   |   s    |     s      |  s   |  s   |  s   |  s   |
|   字   |   z    |     z      |  sh  |  z   |  z   |  z   |
|   機   |   tɕ   |     c      |  j   |  c   |  c   |  ky  |
|   欺   |  tɕʰ   |     ch     |  q   |  ch  |  ch  |  q   |
|   其   |   dʑ   |     j      |  jh  |  j   |  j   |  j   |
|   擬   |   ȵ    |     gn     |  nh  |  nr  |  gn  |  n   |
|   粘   |   ʔȵ   |     kn     |  n   |  n   |  kn  |  n   |
|   希   |   ɕ    |     sh     |  x   |  sh  |  sh  |  x   |
| （齊） |   ʑ    |     zh     |  xh  |  zh  |  zh  |  zh  |
|   葛   |   k    |     k      |  g   |  k   |  k   |  k   |
|   克   |   kʰ   |     kh     |  k   |  kh  |  kh  |  kh  |
|   個   |   ɡ    |     g      |  gh  |  g   |  g   |  g   |
|   魚   |   ŋ    |     ng     | nhg  | ngr  |  ng  |  ng  |
|   捱   |   ʔŋ   |     nk     |  ng  |  ng  |  nk  |  ng  |
|   阿   | 零聲母 |    不標    | 不標 | 不標 | 不標 | 不標 |
|   黑   |   h    |     h      |  h   |  h   |  h   |  h   |
|   合   |   ɦ    |     gh     |  hh  |  x   |  r   |  gh  |

### 韻母

|      例字       | IPA  | 學堂式吳拼 | 錢拼 | 滬二 | 法吳 | NRSS  |
| :-------------: | :--: | :--------: | :--: | :--: | :--: | :---: |
|       之        |  ɿ   |     y      |  y   |  z   |  y   |   y   |
|       衣        |  i   |     i      |  i   |  i   |  i   |   i   |
|       烏        |  u   |     u      |  u   |  u   |  u   |   u   |
|       淤        |  y   |     iu     |  yu  |  yu  |  iu  | ü(iu) |
|       阿        |  ᴀ   |     a      |  a   |  a   |  a   |   a   |
|       鴉        |  iᴀ  |     ia     |  ia  |  ia  |  ia  |  ia   |
|       怪        |  uᴀ  |     ua     |  ua  |  ua  |  ua  |  ua   |
|       蛇        |  o   |     o      |  o   |  o   |  au  |   o   |
|       好        |  ɔ   |     au     |  ao  |  oa  |  o   |  au   |
|       要        |  iɔ  |    iau     | iao  | ioa  |  io  |  iau  |
|       歐        |  ɤ   |     eu     |  ou  |  eu  |  oe  |  eu   |
|       優        |  iɤ  |    ieu     | iou  | ieu  | ioe  |  ieu  |
|       哀        |  ᴇ   |     e      |  e   |  e   |  e   |   e   |
|       廿        |  iᴇ  |     ie     |  ie  |  ie  |  ie  |  ie   |
|       彎        |  uᴇ  |     ue     |  ue  |  ue  |  ue  |  ue   |
|       安        |  ø   |     oe     |  oe  |  oe  |  eu  |  oe   |
|       碗        |  uø  |    uoe     | uoe  | uoe  | ueu  |  uoe  |
|       冤        |  yø  |    ioe     | yuoe | yuoe | ieu  |  ioe  |
|       硬        |  ã   |     an     |  an  |  an  |  an  |  ang  |
|       央        |  iã  |    ian     | ian  | ian  | ian  | iang  |
|       橫        |  uã  |    uan     | uan  | uan  | uan  | uang  |
|       項        |  ɑ̃   |    aon     | ang  | ang  | aon  |  on   |
| 旺<sub>白</sub> |  iɑ̃  |    iaon    | iang | iang | iaon |  ion  |
|       汪        |  uɑ̃  |    uaon    | uang | uang | uaon |  uon  |
|       恩        |  ən  |     en     |  en  |  en  |  en  |  en   |
|       英        |  in  |     in     |  in  |  in  |  in  |  in   |
|       溫        | uən  |    uen     | uen  | uen  | uen  |  uen  |
|       允        |  yn  |    iun     | yun  | yun  | iun  |  iun  |
|       翁        |  oŋ  |     on     | ong  | ong  |  on  |  ung  |
|       永        | ioŋ  |    ion     | iong | iong | ion  | iung  |
|       壓        |  ᴀʔ  |     aq     |  ak  |  ak  |  aq  |  ah   |
|       約        | iᴀʔ  |    iaq     | iak  | iak  | iaq  |  iah  |
|       挖        | uᴀʔ  |    uaq     | uak  | uak  | uaq  |  uah  |
|       谷        |  oʔ  |     oq     |  ok  |  ok  |  oq  |  oh   |
|       肉        | ioʔ  |    ioq     | iok  | iok  | ioq  |  ioh  |
|       合        |  əʔ  |     eq     |  ek  |  ek  |  eq  |  eh   |
|       一        | iɪʔ  |     iq     |  ik  |  ik  |  iq  |  ih   |
|       骨        | uəʔ  |    ueq     | uek  | uek  | ueq  |  ueh  |
|       血        | yɪʔ  |    iuq     | yuik | yuik | iuq  |  iuh  |
|       而        |  əl  |     er     |  er  |  el  |  el  |  er   |
|       嘸        |  m̩   |     m      |  m   |  m   |  m   |   m   |
|       嗯        |  n̩   |     n      |  n   |  n   |  n   |   n   |
|       五        |  ŋ̍   |     nɡ     |  ng  |  ng  |  nɡ  |  nɡ   |

### 拼寫說明

- 曲藝演員及部分年紀較大的中派分尖團，分尖團的音系比尖團不分的音系少一個聲母 zh。
- 零聲母的拼寫規則，錢拼和滬二與普通話相同。即後接 \[i\] / \[y\] 韻母或 \[i\] / \[y\] 介音時拼爲 y，後接 \[u\] 韻母或 \[u\] 介音時拼爲 w。吳拼、法吳和 NRSS 均無此規則。如「烏」字，錢拼和滬二拼作 wu，吳拼、法吳和 NRSS 拼作 u。
- \[ɦ\] 聲母後接 \[i\] / \[y\] / \[u\] 韻母或 \[i\] / \[y\] / \[u\] 介音時，吳拼、法吳和 NRSS 拼爲 y / yu / w，錢拼拼作 yh / yhu / wh，滬二拼作 yr / yru / wr。如「胡」字，錢拼拼作 whu，滬二拼作 wru，吳拼、法吳和 NRSS 拼作 wu。
- 錢拼和滬二的拼寫中，\[tɕ\] 組聲母後接 yu 韻母或 yu 介音時，可省略 y。如「居」字，錢拼和滬二分別拼寫爲 ju，cu。
- NRSS 的拼寫中，聲母 ky 後接 i 且 i 後有元音時可省去 i。如「君」、「囧」、「菊」、「叫」分別拼作 kyun，kyung，kyuh，kyau。
- NRSS 在輸入時，ü 使用 iu 代替，但不參與簡拼。如「居」拼作 kyiu 而非 kyu。

## 方案介紹

1. 錢拼、滬二分別爲《上海話拼音方案》的正式和副式，在 2006 年「首屆國際上海方言學術研討會」上集體審定通過。方案本身僅使用 26 個字母，同時也使用字母標調。本倉庫的輸入方案沒有聲調，故使用字母標調的特點在本倉庫中沒有體現。該方案的正式（錢拼）常見於方言入門教學類出版物。該方案的特點是接近漢語拼音，易於入門。副式（滬二）的特點是接近國際音標，方便使用者區分清濁音。這兩種方案都針對上海話設計，設計之初就未考慮適配吳語區其他方言點，是這兩種方案的一個缺點。另外，錢拼的聲母拼寫較爲怪異，常爲人詬病。
2. 法吳又稱吳語拉丁式注音法，由網友「上海閒話abc」創制。該方案在設計時借鑑了法語的正字法，故稱爲「法吳」。該方案的聲母與滬二類似，提示使用者區別清濁音。該方案可以兼容吳語區其他方言點，但未見有正式發佈，較爲可惜。Rime 官方倉庫中的「[Rime 吳語輸入方案](https://github.com/rime/rime-wugniu)」同樣採用法吳註音，只是音系與本倉庫有所不同。本倉庫的音系爲《上海市區方言志》中的中派上海話，大致指出生在 1940 年至 1965 間的上海人所使用的音系。所以本倉庫基於中派的音系重新製作了法吳的輸入法。
3. NRSS 全稱「新版上海話羅馬字方案（The New Romanization System of Shanghainese）」，由微信公衆號「沪语角」設計。方案參考了吳拼、錢拼以及傳教士羅馬字。方案包含一個特殊字符 ü，在輸入時需使用 iu 代替。該方案使用符號標記聲調，在本輸入方案中無法體現。具體方案可查看微信公衆號文章：[声母](https://mp.weixin.qq.com/s/Eg1YO5eul6Gd08C8GtELEQ)，[韵母](https://mp.weixin.qq.com/s/Ob6sbyflELoKSkljk3nR9A)，[声调](https://mp.weixin.qq.com/s/RGax0Ii7W19I7BqaNbkaTA)。

## 聯繫

- 郵箱：shinzoqchiuq@outlook.com
- QQ：1613023143
