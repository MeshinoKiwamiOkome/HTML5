# 📝 HTML5 / CSS 学習ノート

> HTML5プロフェッショナル認定試験 レベル1 合格を目指して作成した、  
> 要素別・テーマ別の学習用サンプル集です。

---

## 🎯 目的

- **HTML5プロフェッショナル認定試験 レベル1** の合格を目標とした自習用教材
- 各ページは「要素の意味・使い方・注意点」を実際に動くサンプルと  
  **入力できる回答解説付き演習問題**で学べる構成
- HTML編 全10ページ完了 🎉 → CSS編 順次追加中

---

## 📁 ファイル構成

/
├── index.html # トップページ（学習ノート一覧）
│
├── 【HTML編】
├── basics.html # 基本構文・文書構造
├── semantic.html # セマンティック・インタラクティブ要素
├── meta_structure.html # 全体構造・メタ情報
├── section_structure.html # セクション・基本構造
├── media.html # 画像・動画・音声
├── global_attributes.html # グローバル属性
├── text_elements.html # テキスト要素
├── list_elements.html # リスト要素
├── form_elements.html # フォーム要素
├── table_elements.html # テーブル要素
│
└── 【CSS編】
├── css_basics.html # CSS基礎知識
├── css_selectors.html # セレクタ
├── css_priority.html # 適用の優先順位
└── css_colors.html # 色


---

## 📚 学習コンテンツ一覧

### ✅ HTML編（全10ページ・完了）

| ファイル | 内容 | 主な学習要素 |
|---|---|---|
| `basics.html` | 基本構文・文書構造 | DOCTYPE / 文字参照 / コメント / タグ省略 / 空要素 |
| `semantic.html` | セマンティック・インタラクティブ要素 | figure / details / dialog / canvas / template / iframe |
| `meta_structure.html` | 全体構造・メタ情報 | html / head / meta / link / base / title |
| `section_structure.html` | セクション・基本構造 | article / section / aside / nav / hgroup / main |
| `media.html` | 画像・動画・音声 | img / picture / video / audio / track / map |
| `global_attributes.html` | グローバル属性 | class / id / lang / tabindex / data-* / dir |
| `text_elements.html` | テキスト要素 | mark / data / time / code / ins / del など |
| `list_elements.html` | リスト要素 | ul / ol / li / dl / dt / dd |
| `form_elements.html` | フォーム要素 | input / datalist / meter / progress / output / fieldset |
| `table_elements.html` | テーブル要素 | table / thead / tfoot / caption / colgroup / col |

### 🟪 CSS編（順次追加中）

| ファイル | 内容 | 主な学習要素 |
|---|---|---|
| `css_basics.html` | CSS基礎知識 | ルールセット / @import / box-sizing / rem / em / vw |
| `css_selectors.html` | セレクタ | 属性セレクタ / nth-child / 擬似要素 / 結合子 |
| `css_priority.html` | 適用の優先順位 | 詳細度 / !important / 指定元 / カスケード |
| `css_colors.html` | 色 | 16進数 / rgb() / hsl() / opacity / transparent |

---

## ✨ 各ページの構成

各学習ページは以下の構成で統一されています。

1. **概要・ポイント説明**  
   試験頻出の重要ポイントをハイライト表示

2. **コードサンプル**  
   シンタックスハイライト付きのコードブロック

3. **ライブデモ**  
   実際にブラウザで動作を確認できるデモ

4. **参照テーブル**  
   属性・値・使い分けの一覧表

5. **演習問題（インタラクティブ）**  
   - 正誤問題（○×入力）
   - 穴埋め問題（テキスト入力）
   - 選択問題（セレクトボックス）
   - チェックボックス問題
   - コード穴埋め問題
   - 記述問題（模範解答表示）

6. **まとめ一覧表**  
   学習内容の総まとめ

---

## 🔑 試験頻出ポイント（抜粋）

### HTML編

- `ul` / `ol` / `dl` の内容は**空でもOK**
- `ol` 要素は `reversed` 属性で**逆順**にできる（論理属性）
- `dl` で用語の定義をする場合は **`dfn` 要素も必要**
- `tfoot` 要素は `tbody` / `tr` よりも**後に1つだけ**配置できる
- `table` 要素の `border` 属性は **HTML Living Standard で削除**済み
- `datalist` 要素は `input` 要素に関連付けて**サジェスト機能**を追加する
- `time` 要素は `data` 要素を**日時に特化**させた要素

### CSS編

- CSSの書式には自由に空白を入れられるが、**セレクタだけは例外**
- `link` 要素・`style` 要素の **`type="text/css"` は省略可**（HTML5以降）
- `!important` 付きの優先順位は**逆転**する（UA > ユーザー > 製作者）
- 詳細度が最も高いのは **`style` 属性**（インラインスタイル）
- 詳細度は **A（ID）- B（属性系）- C（要素系）** の3桁で示す
- `hsl()` は **Hue（色相）/ Saturation（彩度）/ Lightness（明度）**
- `transparent` は CSS3 以降、**色の値が指定可能なすべての箇所**で使用可
- 不透明度は **0.0〜1.0 の単位なし数値**で指定する

---

## 🛠️ 使い方

### ローカルで開く

```bash
# リポジトリをクローン
git clone https://github.com/MeshinoKiwamiOkome/main.git

# index.html をブラウザで開く
open index.html        # macOS
start index.html       # Windows
xdg-open index.html    # Linux
