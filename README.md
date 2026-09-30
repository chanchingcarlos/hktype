# HKType 粵拼打字遊戲

單頁靜態網站，學廣東話拼音打字。開 `index.html` 即玩，亦可經 GitHub Pages 上網玩。

## 玩法

- **01 打字**：睇住個中文字，打出粵拼（唔使聲調，如 `luk` = 綠）
- **02 詞語**：打成個詞嘅拼音，用空格分開（如 `hoeng gong`）
- **03 四選一**：見拼音揀啱字，亦可撳表頭排序（Excel 式）
- **04 錯題庫**：錯咗自動記低，可重練，撳表頭轉排序
- **05 識字庫**：答啱自動記低，連「試咗幾多次先啱」都記低

## 規則

- 難度：初級 / 中級 / 高級 / 地獄 / 混合 / 海量（MEGA）
- 海量庫：約 2.7 萬單字 + 9.9 萬詞語（CanCLID rime-cantonese 詞庫，CC-BY 4.0）
- 答啱唔會再出（識字庫排除），答錯隔幾題再出直到啱為止
- 答啱 1 秒後自動下一題，答錯停低慢慢睇
- 所有記錄存瀏覽器 localStorage，唔使 login

## 開網站（GitHub Pages）

Settings → Pages → Deploy from a branch → main / root → Save，
之後用 `https://<username>.github.io/hktype/` 開，手機電腦都得。
