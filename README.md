# Scan Code Map

|   入力(変更前)   |   出力(変更後)   |   設定値   |   Byte 列   |
|:-----------------|:-----------------|-----------:|------------:|
|            ヘッダ|                  | 0x00000000 | 00 00 00 00 |
|            ヘッダ|                  | 0x00000000 | 00 00 00 00 |
|        エントリ数|                  | 0x00000006 | 06 00 00 00 |
|CapsLock    (  3A)|SysRq       (  54)| 0x003A0054 | 54 00 3A 00 |
|右 Windows  (E05C)|CapsLock    (  3A)| 0xE05C003A | 3A 00 5C E0 |
|SysRq       (  54)|右 Windows  (E05C)| 0x0054E05C | 5C E0 54 00 |
|Scroll Lock (  46)|Break       (E046)| 0x0046E046 | 46 E0 46 00 |
|Break       (E046)|Scroll Lock (  46)| 0xE0460046 | 46 00 E6 00 |
|   Null Terminate |                  | 0x00000000 | 00 00 00 00 |
