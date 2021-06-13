# ASUS-PRIME-B250M-PLUS-Hackintosh

> opencore version 0.7.0

## 硬體

| 配置 | 詳細 |
|--|--|
| 主板 | ASUS PRIME B250M-PLUS |
| 處理器 | Intel(R) Core(TM) i5-7500 |
| 記憶體 | Kingston 16G DDR4 2400MHz * 2 |
| 內顯 | Intel(R) HD Graphics 630 ( 0x59120000 ) |
| 音效卡 | Realtek ALC887 ( 1 ) |
| 有線網卡 | Intel I219V |

## 狀態

mojave => 00001259 / AAASWQ==
big sur => 07009B3E / BwCbPg==
目前版本最多只能到 Mojave 主要原因是因為顯卡沒辦法正常運行，真的不型可能也要買一張AMD顯卡了

`AAPL,ig-platform-id`
https://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1880677
```
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

https://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1855270
0x591B0000 => 00001B59 => AAAbWQ== => 查詢後發現是mobile