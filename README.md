# マンション販売計画シミュレーター

広告開始から完売目標までの反響・来場・契約・広告費を月次で試算するブラウザツールです。

- 公開URL: https://yusukea-svg.github.io/mansion-schedule/
- 入力したデータは利用者のブラウザ内（localStorage）にだけ保存され、外部には送信されません。ページの Content-Security-Policy で外部への通信（fetch / XHR など）を遮断しています。
- PowerPoint（全体計画）と Excel（月次計画表）はブラウザ内で生成して保存します。
- 外部から読み込むのは表示用フォント（Google Fonts）と出力用ライブラリ（SheetJS、PptxGenJS／jsDelivr）のみです。

今後、用地取得・設計・施工・竣工引渡しの工程を追加していく予定です。
