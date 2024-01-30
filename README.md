## Hi 👋 I'm <a href=https://github.com/tapih>@tapih</a>

<!--
**tapih/tapih** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

-->

![github stats](https://github-readme-stats.vercel.app/api?username=tapih&show_icons=true&theme=tokyonight)

- 🔭 I’m currently working on Cloud Native technology, forcusing on Kubernetes, at @10xinc.
- 💬 Ask me about Kubernetes and GitHub Actions.
- 🌏 Fun fact: I love travelling. My wife and I went on a round-the-world trip for over a year!!
- 🌼 Tech Stack
  - Kubernetes
  - Docker
  - GitHub Actions
  - Google Cloud Platform
  - Terraform
  - Monitoring
    - Datadog
    - Cloud Monitoring
    - Grafana Stack
  - Go
  - GNU Make
  - Bash
  - Site Reliability Engineering
  - Machine Learning
- 📫 How to find me:
  - [Mail](h.muraoka714@gmail.com)
  - [Twitter](https://twitter.com/_tapih)
  - [Findy](https://findy-code.io/share_profiles/IbONI32qsRxqX)
  - [LinkedIn](https://jp.linkedin.com/in/hiroshi-muraoka-a4357770/en-us)
  - [Blog](https://blog.tapih.dev) (under construction)
  - [Kaggle](https://www.kaggle.com/pseprop) (inactive)

## 業務委託

2024/01 現在、業務委託先を募集しています。業務委託にご興味がある方は Mail or Twitter DM でご連絡いただけると数日以内に返信します。
経歴や得意な技術に関してはこのページ上部をご参照ください。以下、特に詳しい技術について補足します。

### Kubernetes

一番得意としているのは Kubernetes を利用した Platform 開発/運用です。 Kubernetes の内部に関する深い知識があり、 Kubernetes へのミドルウェアの開発・導入・メンテナンス、モニタリングの整備、 Kubernetes を利用したアプリケーション構築など下のレイヤから上のレイヤまで一通りこなせます。一方で、マイクロサービスの経験はありません。以下のような実績があります。

- GCP リソースの最適化により GCE インスタンスコスト 50% 削減
- GKE 上でのブランチデプロイの実装 (参考: https://times.hrbrain.co.jp/entry/kubernetes-branch-deploy)
- Helmfile を利用した各種 Kubernetes ミドルウェアのアップグレードの省力化及びバージョンアップ対応
- k6-operator を利用した負荷試験基盤の整備
- 各種モニタリング及びインシデントレスポンス体制の整備
- 各種 Kubernetes Controller の開発
- 各種 Kubernettes Controller の技術検証・導入
- 各種 OSS のバグ調査・修正
- LVM(Logical Volume Manager) を利用した CSI(Container Storage Interface) プラグインの開発

以下のような OSS コミット実績があり、 OSS のデバッグが比較的得意です。現職では、アプリケーションコード外の原因の分かりづらいバグの相談を受けることが多いのですが、大抵の相談は解決に至ることができ、かつかかる時間も比較的短いと自負しています。
- [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes/issues/91615)
- [external-secrets/external-secrets](https://github.com/external-secrets/external-secrets/pull/1902)

### GitHub Actions

次に得意としているのは、 GitHub Actions です。 GitHub Actions の仕様を知悉しています。以下のような実績があります。

- CircleCI -> GitHub Actions 移行に伴う CI/CD 刷新
  - 所要時間 50% 削減
  - 不安定系の大幅な削減
- Kubernetes 上で動く Self Hosted Runner コントローラの開発

### Site Reliability Engineering

SRE のプラクティスに関する深い理解があり、スタートアップの現場で実践してきました。 SRE に関わることであれば一通りこなすことができます。
また、証券会社で財務分析をしていたバックグラウンドから、会社の現在/未来を適切に分析して SRE として次に何をすべきかを判断することが得意と自負しています。

以下のような実績がありますが、本質的に体系化しづらい抽象度のトピックと捉えています。スタートアップの現場での成功/失敗を活かしたディスカッション・壁打ち相手くらいの温度感でご活用いただければ幸いです。

- スタートアップ組織における SRE チームの立ち上げ
  - チーム内コミュニケーションラインの整備
- SRE 採用面接・評価制度の初期設計

## 業務委託内容

時給ベースでの稼働となるため、基本的なスタンスとしては "事前のインプットがそこまでなくともバリューを出せる領域" つまり今までやったこと (特に Kubernetes) に近しいところでまずはお手伝いができればと考えています。その上で新しい技術に触れる機会をいただいた際には、積極的に挑戦したいと考えています。特に興味がある技術は以下の通りです。

- Backstage
- Nx
- Istio
- Arroy DB
- Meilisearch
- MLOps 全般

一方で、業務委託で扱わない技術は以下の通りです。念のためですが、好き嫌いや特定の技術を貶めるような意図ではなく、あくまで将来のキャリア形成のためにスコープを絞っているためである点を補足しておきます。

- AWS
- Go/TypeScript/Rust 以外のプログラミング言語を書くこと(必要なコードを読むのはもちろん OK)

## 条件

以下の条件でスタートの上、ご評価いただけた場合には 3 ヶ月\~半年程度経過後に 500\~1,000 円程度の時給アップを提案させていただく可能性があります。

- 時給: 6,000 円~
- 稼働時間: 20~30h/月
