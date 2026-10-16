# aws-support-calc

月額 AWS 利用料を入力すると、各 AWS Support プラン（Business Support+ / Enterprise / Unified Operations、旧 Developer / Business）の請求額を自動計算する静的 Web アプリ。

各プランは「月額の最低料金」と「利用料に対する累進の従量料率」の高い方が請求される。定額プランは無い。

- 公開 URL: https://striderkein.github.io/aws-support-calc/
- 出典: [AWS Support Plan Pricing](https://aws.amazon.com/premiumsupport/pricing/)、[終了告知](https://docs.aws.amazon.com/awssupport/latest/user/support-plans-eos.html)（2026-10-16 時点、商用リージョン）

依存なし。`index.html` 1 ファイルを GitHub Pages で配信している。
