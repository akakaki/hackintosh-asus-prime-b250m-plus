# ASUS-PRIME-B250M-PLUS-Hackintosh

> opencore version 0.7.0

## 硬體

| 配置 | 詳細 |
|--|--|
| 主板 | ASUS PRIME B250M-PLUS |
| 處理器 | Intel(R) Core(TM) i5-7500 |
| 記憶體 | Kingston 16G DDR4 2400MHz * 2 |
| 內顯 | Intel(R) HD Graphics 630 ( 0x59120000 ) |
| 音效卡 | Realtek ALC887 (id: 3)|
| 有線網卡 | Intel I219V |
| 無線網卡&藍芽 | CM94360CD FV-T919 |

## 更新至新系統問題
> 目前停留在 Mojave 再上去顯卡沒辦法正常顯示

```
AAPL,ig-platform-id

- mojave => 00001259 / AAASWQ==
- big sur => 07009B3E / BwCbPg==

<key>PciRoot(0x0)/Pci(0x2,0x0)</key>
<dict>
  <key>AAPL,ig-platform-id</key>
  <data>AAASWQ==</data>
  <key>AAPL,slot-name</key>
  <string>Internal@0,2,0</string>
  <key>device-id</key>
  <data>ElkAAA==</data>
  <key>model</key>
  <string>Intel HD Graphics 630</string>
</dict>
```

ProperTree預設開啟，但目前已先關閉此功能。
```
DisableIoMapper: false
```