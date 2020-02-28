# 非吳拼上海話輸入方案

配方：℞ **shinzoqchiuq/rime-shanghainese**

吳語上海話輸入方案，包含除吳語拼音外的多種拼音方案。如果需要以吳語拼音作爲輸入方案，請移步下方吳語學堂的倉庫。

本方案依賴於吳語學堂的 [上海吳語拼音輸入方案](https://github.com/NGLI/rime-wugniu_zaonhe) ℞ **NGLI/rime-wugniu_zaonhe**

安裝本方案前，需要先安裝吳語學堂的上海吳語拼音輸入方案。

本倉庫所有方案均基於中派上海話音系，包含的方案有：

- `shanghe_whuyik`：上海話拼音方案 正式（滬一）
- `zanghe_wrunri`：上海話拼音方案 副式（滬二）
- `zaonhe_faqwu`：吳語拉丁式注音法（法吳）

其中滬一常出現在錢乃榮教授近年出版的書籍中，有時也被人稱作錢拼。

## 拼音方案對比

### 聲母

| 例字 |  IPA   | 學堂式吳拼 | 滬一 | 滬二 | 法吳 |
| :--: | :----: | :--------: | :--: | :--: | :--: |
|  北  |   p    |     p      |  b   |  p   |  p   |
|  潑  |   pʰ   |     ph     |  p   |  ph  |  ph  |
|  蔔  |   b    |     b      |  bh  |  b   |  b   |
|  摸  |   m    |     m      |  mh  |  mr  |  m   |
|  咪  |   ʔm   |     mh     |  m   |  m   |  mh  |
|  夫  |   f    |     f      |  f   |  f   |  f   |
|  扶  |   v    |     v      |  fh  |  v   |  v   |
|  得  |   t    |     t      |  d   |  t   |  t   |
|  脫  |   tʰ   |     th     |  t   |  th  |  th  |
|  奪  |   d    |     d      |  dh  |  d   |  d   |
|  諾  |   n    |     n      |  nh  |  nr  |  n   |
|  拿  |   ʔn   |     nh     |  n   |  n   |  nh  |
|  勒  |   l    |     l      |  lh  |  lr  |  l   |
|  拎  |   ʔl   |     lh     |  l   |  l   |  lh  |
|  資  |   ts   |     ts     |  z   |  ts  |  tz  |
|  次  |  tsʰ   |    tsh     |  c   | tsh  |  ts  |
|  絲  |   s    |     s      |  s   |  s   |  s   |
|  字  |   z    |     z      |  sh  |  z   |  z   |
|  機  |   tɕ   |     c      |  j   |  c   |  c   |
|  期  |  tɕʰ   |     ch     |  q   |  ch  |  ch  |
|  其  |   dʑ   |     j      |  jh  |  j   |  j   |
|  擬  |   ȵ    |     gn     |  nh  |  nr  |  gn  |
|  粘  |   ʔȵ   |     kn     |  n   |  n   |  kn  |
|  希  |   ɕ    |     sh     |  x   |  sh  |  sh  |
|  齊  |   ʑ    |     zh     |  xh  |  zh  |  zh  |
|  葛  |   k    |     k      |  g   |  k   |  k   |
|  克  |   kʰ   |     kh     |  k   |  kh  |  kh  |
|  個  |   ɡ    |     g      |  gh  |  g   |  g   |
|  魚  |   ŋ    |     ng     | nhg  | ngr  |  ng  |
|  捱  |   ʔŋ   |     nk     |  ng  |  ng  |  nk  |
|  阿  | 零聲母 |    不標    | 不標 | 不標 | 不標 |
|  黑  |   h    |     h      |  h   |  h   |  h   |
|  合  |   ɦ    |     gh     |  hh  |  x   |  r   |

### 韻母

|      例字       | IPA  | 學堂式吳拼 | 滬一 | 滬二 | 法吳 |
| :-------------: | :--: | :--------: | :--: | :--: | :--: |
|       之        |  ɿ   |     y      |  y   |  z   |  y   |
|       衣        |  i   |     i      |  i   |  i   |  i   |
|       烏        |  u   |     u      |  u   |  u   |  u   |
|       淤        |  y   |     iu     |  yu  |  yu  |  iu  |
|       阿        |  ᴀ   |     a      |  a   |  a   |  a   |
|       鴉        |  iᴀ  |     ia     |  ia  |  ia  |  ia  |
|       怪        |  uᴀ  |     ua     |  ua  |  ua  |  ua  |
|       蛇        |  o   |     o      |  o   |  o   |  au  |
|       好        |  ɔ   |     au     |  ao  |  oa  |  o   |
|       要        |  iɔ  |    iau     | iao  | ioa  |  io  |
|       歐        |  ɤ   |     eu     |  ou  |  eu  |  oe  |
|       優        |  iɤ  |    ieu     | iou  | ieu  | ioe  |
|       哀        |  ᴇ   |     e      |  e   |  e   |  e   |
|       廿        |  iᴇ  |     ie     |  ie  |  ie  |  ie  |
|       彎        |  uᴇ  |     ue     |  ue  |  ue  |  ue  |
|       安        |  ø   |     oe     |  oe  |  oe  |  eu  |
|       碗        |  uø  |    uoe     | uoe  | uoe  | ueu  |
|       冤        |  yø  |    ioe     | yuoe | yuoe | ieu  |
|       硬        |  ã   |     an     |  an  |  an  |  an  |
|       央        |  iã  |    ian     | ian  | ian  | ian  |
|       橫        |  uã  |    uan     | uan  | uan  | uan  |
|       項        |  ɑ̃   |    aon     | ang  | ang  | aon  |
| 旺<sub>白</sub> |  iɑ̃  |    iaon    | iang | iang | iaon |
|       汪        |  uɑ̃  |    uaon    | uang | uang | uaon |
|       恩        |  ən  |     en     |  en  |  en  |  en  |
|       英        |  in  |     in     |  in  |  in  |  in  |
|       溫        | uən  |    uen     | uen  | uen  | uen  |
|       允        |  yn  |    iun     | yun  | yun  | iun  |
|       翁        |  oŋ  |     on     | ong  | ong  |  on  |
|       永        | ioŋ  |    ion     | iong | iong | ion  |
|       壓        |  ᴀʔ  |     aq     |  ak  |  ak  |  aq  |
|       約        | iᴀʔ  |    iaq     | iak  | iak  | iaq  |
|       挖        | uᴀʔ  |    uaq     | uak  | uak  | uaq  |
|       谷        |  oʔ  |     oq     |  ok  |  ok  |  oq  |
|       肉        | ioʔ  |    ioq     | iok  | iok  | ioq  |
|       合        |  əʔ  |     eq     |  ek  |  ek  |  eq  |
|       一        | iɪʔ  |     iq     |  ik  |  ik  |  iq  |
|       骨        | uəʔ  |    ueq     | uek  | uek  | ueq  |
|       血        | yɪʔ  |    iuq     | yuik | yuik | iuq  |
|       而        |  əl  |     er     |  er  |  el  |  el  |
|       嘸        |  m̩   |     m      |  m   |  m   |  m   |
|       嗯        |  n̩   |     n      |  n   |  n   |  n   |
|       五        |  ŋ̍   |     nɡ     |  ng  |  ng  |  nɡ  |

### 拼寫說明

- 零聲母的拼寫規則，滬一和滬二與普通話相同。即後接 \[i\] / \[y\] 韻母或 \[i\] / \[y\] 介音時拼爲 y，後接 \[u\] 韻母或 \[u\] 介音時拼爲 w。吳拼和法吳均無此規則。如「烏」字，滬一和滬二拼作 wu，吳拼和法吳拼作 u。

- \[ɦ\] 聲母後接 \[i\] / \[y\] / \[u\] 韻母或 \[i\] / \[y\] / \[u\] 介音時，吳拼和法吳拼爲 y / yu / w，滬一拼作 yh / yhu / wh，滬二拼作 yr / yru / wr。如「胡」字，滬一拼作 whu，滬二拼作 wru，吳拼和法吳拼作 wu。

- 滬一和滬二的拼寫中，\[tɕ\] 組聲母後接 yu 韻母或 yu 介音時，可省略 y。如「居」字，滬一和滬二分別拼寫爲 ju，cu。

## 方案介紹

1. 滬一、滬二分別爲《上海話拼音方案》的正式和副式，在 2006 年「首屆國際上海方言學術研討會」上集體審定通過。方案本身僅使用 26 個字母，同時也使用字母標調。本倉庫的輸入方案沒有聲調，故使用字母標調的特點在本倉庫中沒有體現。該方案的正式（滬一）常見於方言入門教學類出版物。該方案的特點是接近漢語拼音，易於入門。副式（滬二）的特點是接近國際音標，方便使用者區分清濁音。這兩種方案都針對上海話設計，設計之初就未考慮適配吳語區其他方言點，是這兩種方案的一個缺點。另外，滬一的聲母拼寫較爲怪異，常爲人詬病。
2. 法吳又稱吳語拉丁式注音法，由網友「上海閒話abc」創制。該方案在設計時借鑑了法語的正字法，故稱爲「法吳」。該方案的聲母與滬二類似，提示使用者區別清濁音。該方案可以兼容吳語區其他方言點，但未見有正式發佈，較爲可惜。Rime 官方倉庫中的「[Rime 吳語輸入方案](https://github.com/rime/rime-wugniu)」同樣採用法吳註音，只是音系與本倉庫有所不同。本倉庫的音系爲《上海市區方言志》中的中派上海話，大致指出生在 1940 年至 1965 間的上海人所使用的音系。而「Rime 吳語輸入方案」在中派的基礎上區分了一些聲母和韻母，然而卻與老派上海話不同，更像是一個人造音系。所以本倉庫重新基於中派的音系製作了法吳的輸入法。

