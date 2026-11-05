# UpToDate Expert AI · 診療科・領域別の活用例

[英語版](https://icannotcodejusthci.github.io/EAI-Prompts-Eng/)をもとにした日本語版です。19の診療科・領域、71症例、119の質問を収録しています。[韓国語版](https://icannotcodejusthci.github.io/EAI-Prompts/)および英語版とは別のリポジトリで管理します。

## ページ

- 活用例：https://icannotcodejusthci.github.io/EAI-Prompts-JP/
- モバイルアプリの案内：https://icannotcodejusthci.github.io/EAI-Prompts-JP/mobile/
- App Store（日本）：https://apps.apple.com/jp/app/uptodate-expert-ai/id6756627759
- Google Play（日本語・日本）：https://play.google.com/store/apps/details?id=com.uptodate.expertai&hl=ja&gl=JP

ストアのリンク先は公式の日本向けWebページです。ストアアプリを開いた場合の表示言語や地域は、端末やアカウントの設定に従うことがあります。配信元が掲載する説明文や画像には英語が含まれる場合があります。

## 翻訳について

日本の臨床現場で用いられる診療科名、疾患名、薬剤名を使用しています。必要に応じて略語・英語を併記しています。

- Neurology：脳神経内科
- Family Medicine：総合診療・家庭医療
- Preeclampsia：妊娠高血圧腎症
- TACO：輸血関連循環過負荷
- TRALI：輸血関連急性肺障害
- Trodelvy / Enhertu：トロデルビ / エンハーツ

症例の数値、単位、時間経過、診断の確実性、質問の意図は原文に沿っています。NAFLDなど原文の診断名を、診断基準が異なる新分類に無断で置き換えてはいません。原文に含まれる不整合や意図的な誤りも、翻訳時に医学的事実として修正してはいません。

これは臨床上の問いを検討するためのプロンプト例であり、診療指針や患者個別の治療推奨ではありません。日本の承認適応・用量・診療体制への変更を行ったものでもありません。実際の診療では最新の添付文書、ガイドライン、施設の手順を確認してください。

### 用語の確認に使用した資料

- [日本神経学会：標榜診療科名の変更](https://www.neurology-jp.org/news/about_change_name.html)
- [日本プライマリ・ケア連合学会](https://www.primarycare-japan.com/)
- [日本産婦人科医会：妊娠高血圧症候群](https://www.jaog.or.jp/note/no115_2_14_3/)
- [日本赤十字社：TRALI / TACO](https://www.jrc.or.jp/mr/reaction/non_hemolytic/trali_taco/)
- [PMDA：トロデルビ](https://www.pmda.go.jp/PmdaSearch/rdDetail/iyaku/4291472D1026_1?user=1)
- [PMDA：エンハーツ](https://www.pmda.go.jp/PmdaSearch/rdDetail/iyaku/4291452D1029_1?user=1)
- [日本消化器病学会：脂肪性肝疾患の日本語病名](https://www.jsge.or.jp/news/20240820-3/)

## ファイルと公開設定

`index.html` が症例一覧、`cases.json` が症例データ、`mobile/index.html` がアプリ案内ページです。画像、ロゴ、ファビコンは元のデザインを引き継いでいます。英語が埋め込まれたストアバッジの代わりに、日本語のダウンロードボタンを表示します。

GitHub Pages は **Settings → Pages → Deploy from a branch → main → / (root)** で公開できます。管理者メニューの保存先は `EAI-Prompts-JP` です。元の韓国語・英語リポジトリには書き込みません。

## 管理者メニュー

ページ下部の「管理者メニュー」から、症例・診療科の追加や症例の削除ができます。`EAI-Prompts-JP` に限定し、**Contents: Read and write** 権限を持つ GitHub fine-grained personal access token が必要です。「保存（コミット）」を押すと `cases.json` に反映されます。トークンは保存されず、画面を閉じると入力欄から消去されます。

GitHub上で `cases.json` を直接編集することもできます。既存の `specialties` と `cases` の構造、および `specialtyId` の対応を維持してください。

## プロンプトの共有・ご意見

「プロンプトを共有」「意見を送る」は、利用者のメールアプリで下書きを開きます。自動送信は行いません。宛先は `index.html` の `CONTACT_MAIL` で設定しています。患者を特定できる情報は記載しないでください。
