# ZMK Studio キーマップ バックアップ (2026-06-30)

ZMK Studio (GUI) で本体フラッシュに保存されている現在のキーマップの記録。
スクショからの読み取りのため、一部不確実な箇所あり（※印）。

レイヤー数: 4 (0〜3) — `.keymap` ファイルと構造一致。
**重要: `settings_reset` を焼かない限り、この Studio 設定は再書き込みしても保持される。**

物理レイアウト（キー位置番号）:
```
 0  1  2  3  4  5      6  7  8  9 10 11
12 13 14 15 16 17     18 19 20 21 22 23
24 25 26 27 28 29     30 31 32 33 34 35
36 37       38 39     40 41       42 43
```

---

## Layer 0 (default)
```
左:  Tab  Q   W   E   R   T        右:  Y   U   I   O   P   GUI
     Ctrl A   S   D   F   G             H   J   K   L  (空) Ctrl
     Shft Z   X   C   V   B             N   M   ,   .   -   Shft
     Esc  Alt    (空) F11             F12 (空)      (空) Alt
```
※ ファイルのデフォルトとの主な差分: 右上 P 隣が BSPC→GUI、右Ctrl(元 ENTER) など。

## Layer 1
```
左:  (空) Tab  W  [International?]  [Keypad/Left?]  ...   右:  -   7   8   9   *   Del
     (空) Esc  S   F5   ?    ...                          {   4   5   6   0  (空)
     (空) (空) F1  F2   F3   (空)                         ;   1   2   3   /  (空)
     (空)(空)      (空)(空)                              (空) Space   (空)(空)
```
※ 左手側はラベルが重なって読み取り不確実。右手はテンキー＋記号で確実。

## Layer 2
```
左:  (空) Q    W   End  R   PgUp     右:  Home Del  ↑   O  (空)(空)
     (空) A    S   Tab  F   PgDn          BkSp  ←   ↓   →  (空)(空)
     (空) Z    X   C    V   B             N    M   Tab Tab  /   \
     (空)(空)      (空)(空)              (空)(空)       (空)(空)
```

## Layer 3
全キー空白 = `&trans`（透過レイヤー）。
