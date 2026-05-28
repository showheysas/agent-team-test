# 06. Web調査レポート: スバル トレイルシーカー納車遅延の背景

**調査日**: 2026年5月28日
**調査担当**: Web調査(自動車サプライチェーン)
**対象車種**: Subaru Trailseeker(EV, 2026年モデル)
**遅延状況**: 約1ヶ月遅延、ディーラー説明「部品調達不足」

---

## エグゼクティブ・サマリー

トレイルシーカー個別の「リコール起因」「特定部品起因」の遅延報道は **未確認** だが、調査の結果、複数のマクロ要因が重なり合い、2026年春時点でスバル(特に日本生産のEV)が**通常より長い納車リードタイムに陥る蓋然性は極めて高い**ことが分かった。

主な要因(複合):

1. **トランプ関税(15%)による米国向け輸入車のコスト/物流再配分** ― スバルは米国販売の約70%、うち半数を日本から輸入。
2. **スバル全社レベルの業績悪化と戦略転換**(2026/5/19発表、営業利益90%減)― 自社EV計画を無期限延期。資源は ICE/HEVへ振り替え。
3. **トレイルシーカー(=e-Outback)はGunma Yajima工場で2026年2月に量産開始したばかり**で立ち上げ初期。
4. **2026年のRoRo(自動車運搬船)船腹タイト化** + 新規EV火災規制で日本→米国の海上輸送リードタイムが伸長。
5. **中国の希土類輸出規制**(EVモーター用Sm/Gd等)、**車載半導体・DRAM/NAND不足**(AIデータセンター需要に押されて自動車向けが後回し)。
6. **紅海・パナマ運河の物流不安定**は継続中(2025年10月のガザ停戦後も「中程度脅威」、パナマ運河の喫水制限は2026〜27年継続見込み)。

---

## 1. 2026年のスバル生産トラブル・遅延ニュース

### 1.1 Gunma Yajima工場 ― トレイルシーカーEV量産開始(2026年2月)

- **2026年2月4日**、スバルは Gunma Yajima工場で **BEV(Trailseeker / e-Outback)の量産を開始**したと公式発表。
- 2025年8月から進めていた生産ライン改修が2026年1月に完了。**BEV・ガソリン・ハイブリッドを同一ラインで混流生産する方式**(mixed-model line)。
- Trailseekerはスバル/トヨタ共同開発BEVシリーズの**第2弾**、かつスバル**初の自社製BEV**(従来のSolterraはトヨタ製造)。
- Yajima工場ではTrailseekerの他、Outback(海外向け)、Forester、Crosstrek、Impreza、トヨタブランド姉妹車を生産。
- 出典: Subaru Corporation NewsRelease(2026/2/4), Automotive World, electrive.com(2026/2/5), autoevolution

**含意**: 量産開始が2026年2月なら、初期顧客向け納車は2026年春以降。立ち上げ初期は歩留まりや部品供給の安定化に時間を要するのが一般的で、計画から1ヶ月程度のスリップは「立ち上げ初期の典型的な現象」として説明可能。

### 1.2 米国SIA(Subaru of Indiana Automotive)の状況

- 2026年モデルの**Forester ガソリン車**を2025年10月7日に量産開始。
- **2026年から SIA で初めてハイブリッド(Forester Hybrid)生産**を開始。米国でのスバル初の量産HEV。
- 現在SIAはAscent / Crosstrek / Foresterを生産。**Trailseekerは生産していない**(=日本Yajimaのみ)。
- 出典: Subaru U.S. Media Center, Automotive World, fox59.com

### 1.3 スバル全社業績と戦略転換(2026年5月)

- **2026年5月15日〜19日報道**: スバル決算で**営業利益90%減**。
- 関税負担 ¥229億億円(≒$1.4B)+ EV関連減損 約$385M。
- CEO 大崎篤氏が**自社開発EVのローンチを「無期限延期」**と表明(従来は2028年予定)。
- Gunma 大泉工場で2027年から計画していた新EV専用ラインは、**ガソリン/ハイブリッド先行→将来EVを追加投入する混流方式**へ転換。
- 同様にマツダも同時期にEV計画延期。
- 出典: WardsAuto, Electrek(2026/5/19), Automotive News(2026/5/15), carsales.com.au, electrive.com

**含意**: 全社で資源配分を見直し中。EV関連のサプライチェーン(バッテリーセル、e-Axle、希土類モーター)の発注量・優先度が流動的。Trailseeker個別の生産トラブルというより、**全社的なリソース配分の優先順位変動が個別納期に影響**している可能性。

### 1.4 サプライヤー起因の問題

- 2026年内の**特定サプライヤー起因のスバル生産停止報道は未確認**。
- 過去事例として2024年2月にYajimaで25トン金型による死亡事故→8営業日停止があったが、これは2026年5月時点の遅延とは無関係(2年前の事案)。

---

## 2. 業界全体の2026年5月時点の部品調達状況

### 2.1 半導体(DRAM/NAND/eMMC が深刻)

- **2026年最大の供給制約はメモリ系(DRAM・NAND)**。原因は**AIデータセンター需要の急増**で、メモリメーカーが利益率の高いAI向けを優先し、車載向けが後回し。
- **SK hynix は2026年生産分が完売**、新規発注のリードタイムは**58週超**。
- **eMMC(車載制御モジュール)価格は200%上昇**、DDR4/LPDDR4(インフォテイメント・ADAS用)は2026年初頭比で**約70%上昇**。
- アナリストは「2026年下半期に供給戦略の問題から**実際の生産問題へ転化する可能性**」と警告。ただし広範な操業停止には至らないとの見方。
- 出典: S&P Global Automotive Insights, PYMNTS, Detroit News(2026/2/21), EE Times, Autobody News

**Trailseekerへの含意**: EVはインフォテイメント・ADAS・BMSで大量のメモリを消費。Trailseekerのような新規立ち上げ車種は既存車種よりメモリ手配の柔軟性が低く、供給制約の影響を受けやすい。

### 2.2 希土類・リチウム・ニッケル

- **2026年の最大焦点は中国の希土類輸出規制**(2025年10月発表、その後一部停止):
  - 対象に**サマリウム(Sm)・ガドリニウム(Gd)・ルテチウム(Lu)** 系化合物の輸出ライセンス拡大が含まれる。これらは**EVモーターと電力エレクトロニクスに必須**。
  - 規制の一時停止は**2026年11月10日に期限切れ**。再発動時には域外適用(中国産希土類を含む製品全般)。
  - IEA試算: 全面再発動なら中国外で**年間6.5兆ドルの経済影響**、自動車・電子分野が最も曝露。
- リチウム供給は2026年時点では「過剰供給寄り」だが、**2028年から不足に転じる**との予測(Electrek 2026/3/3)。
- ニッケルはインドネシアが世界50%、コバルトはコンゴ70%と地理的集中リスク継続。
- 出典: Certivo, IEA, Clark Hill PLC, Discovery Alert, Taylor Wessing(2026/4)

### 2.3 トランプ関税(2025-2026)の自動車業界への影響

- **2025年以降、米関税は自動車業界に累計$35.4Bの負担**。
- **トヨタは2026年度(2026/3末締め)で¥1.45兆($9.1B)の関税負担**見込み、業界最大級の被害。
- 輸入車は$5,000〜$8,900/台の値上げ、国内生産車も鉄・アルミ高騰で$1,600〜$2,000/台上昇。
- **スバルは米販売の70%超が米国、その半数を日本から輸入** ― 15%関税が直撃。
- スバルの対応: Forester生産をSIA(インディアナ)へ移管、Outbackは逆に**日本生産へ集約**(高価格帯が関税負担を吸収しやすいため)。
- 注: 一部関税は最高裁が差し止めたが、**自動車関税は維持**された。
- 出典: Autoblog, Automotive News, Digital Dealer, carsales.com.au

**Trailseekerへの含意**: Trailseekerは日本Yajima生産→米国輸出のため**15%関税の直接対象**。スバルは輸出フローの最適化を進めており、配船・通関スケジュールの再調整が個別納期に影響している可能性。

### 2.4 紅海・パナマ運河の物流状況

- **紅海**: Houthiによる商船攻撃は2025年10月のガザ停戦で**一旦停止**。ただし2026年4月時点でBab el-Mandeb海峡は**「中程度脅威」**レベル。停戦崩壊や2026年イラン情勢悪化時には再開警告あり。
- **パナマ運河**: 2026年4月時点でパナマ運河庁が**厳格な喫水制限・日次通航枠削減を継続中**。制限は**2026年いっぱい、場合により2027年まで継続見込み**。
- **影響**: ジャストインタイム製造ラインに数日の遅延でも影響。欧州の数工場が部品遅延で一時停止を発表。海運運賃・燃料サーチャージの引き上げが2026年4月に実施。
- 出典: Global Trade Magazine, J.P. Morgan, project44, Conqueror Network

**Trailseekerへの含意**: 日本→米国(太平洋航路)はパナマ運河を経由しないため**直接影響は限定的**だが、**RoRo船の世界的な再配置**で太平洋航路の船腹もタイト化している(下記2.5)。

### 2.5 RoRo(自動車運搬船)の船腹タイト化 ← 重要

- 2026年は**自動車運搬船の船腹が極めてタイト**:
  - メーカー自社チャーター船が増え、市場利用可能枠が減少。
  - 世界RoRo船隊の高齢化、造船ヤードのバックログが3〜5年。
  - **2026年から EV運搬船に対する新規消防規制が適用**(リチウムイオン電池火災対応)― 既存船の改修・運用制限。
- 結果として、**従来30日前で取れた予約が60〜90日前必要**に。EV専用船の供給はさらに厳しい。
- 出典: TransGlobal, KMC JAPAN, WCShipping

**Trailseekerへの含意**: 「日本のYajimaから出荷準備完了」→「米国到着・通関・ディーラー納車」までのリードタイムが**2025年比で2〜4週間延びている可能性が高い**。ディーラー説明の「部品調達不足」よりも、実態は**船腹確保の遅れ**である可能性も視野に入れるべき。

---

## 3. スバルの最新リコール・サービスキャンペーン情報

### 3.1 2026 Trailseeker のリコール

- **2026年5月時点でNHTSA登録のTrailseekerリコールは無し**(調査範囲内では未確認)。
- 出典: cars.com, mikeshawsubaru.com, cardog.app

### 3.2 関連:Solterra(姉妹車)のリコール

- **2022-2026 Solterra**: Panoramic View Monitor(パノラミック・ビュー・モニター)のソフトウェア不具合で、バック時にリアカメラがフリーズまたはブランクになる現象。**所有者通知発送日 2026年1月2日**。販売店でパーキングアシストSWアップデート、無償。
- **2023-2025 Solterra**: HVAC障害時にデフロスタ/デフォガが作動不能になる可能性。HVAC制御ECUのSWアップデート+電動コンプレッサの点検・必要に応じて交換、無償。
- Toyota/Subaru は Solterra / bZ4X のバッテリー関連で訴訟係争中(NHTSAリコールとは別件)。
- 出典: Recharged, Cars.com, Subaru.com, Autoblog

**Trailseekerへの含意**: Trailseekerは Solterra と同じ e-TNGAプラットフォーム(およびその発展型)を共有。Solterraのリコール対応で**ソフトウェアエンジニアリングや特定ECU部品の社内優先度がTrailseeker新規生産分から取られる可能性**は理論的にあり得るが、**証拠は未確認**。

### 3.3 米国販売動向(2026年4月)

- 2026年4月の米国スバル販売: **52,733台、前年同月比 -5.9%**。
- Foresterが4ヶ月連続のボリュームリーダー。
- **EVファミリー(Solterra + Uncharted + Trailseeker)が合計2,053台 ― 過去最高月**。
- スバル自身が「**悪天候と継続的な在庫不足**(lingering inventory shortages)」を不振の理由として説明。
- 出典: Subaru U.S. Media Center(2026/5発表), The Drive, autoevolution, PR Newswire

**Trailseekerへの含意**: スバル米国が**公式に「在庫不足」を認めている**。Trailseekerは立ち上げ初期なので、ディーラー側の「部品調達不足」説明は、実態として「**スバル本体の供給(=量産立ち上げ+海上輸送)が需要に追いついていない**」状況を伝えている可能性が高い。

---

## 4. Trailseekerは EV ― 関連サプライチェーン詳細

### 4.1 スバル/トヨタ共同開発EVプラットフォームの生産動向

- **Trailseeker(e-Outback)**: 2026年2月から Gunma Yajima(スバル自社)で生産開始。
- **トヨタ姉妹車**: 同じくYajimaで生産(Subaru Corporationが委託生産)。
- **次世代 共同開発コンパクトEV SUV**: 2026年1月にYajimaで生産開始予定との報道あり(Carscoops 2024/10, 2025/3)。
- スバルは2028年予定だった自社開発EVを無期限延期したが、**トヨタ共同のEV(Solterra / Trailseeker / Uncharted)は継続**。
- 出典: TopSpeed, Carscoops, Autoblog, Subaru NewsRelease, electrive.com

### 4.2 バッテリーセル供給状況

- **Panasonic**:
  - 米国の遅延していたEVバッテリー工場が2025年7月生産開始へ。中国の原材料管理と米国関税を回避する狙い。
  - 2026年初頭から Zoox(ロボタクシー)向けに最新2170セル供給開始。
  - 出典: TrendForce
- **LG Energy Solution**:
  - **Fordとの$6.5B長期EV電池供給契約が解除**(米EV政策変更+需要鈍化が理由)。対象は2027-2032年分。
  - 出典: KED Global(2025/12)
- **SK On / Samsung SDI**:
  - 2026年に米国でESS(定置用)バッテリー生産開始予定。
  - 米国は2026年に**FEOC準拠セル容量で約10%の供給過剰**になる見通し(韓国系が80%超を占有)。
  - 出典: S&P Global, Solar Power World
- **市場全体**:
  - EV税控除廃止+関税でセルコストが$95/kWhへ上昇。
  - 完成車側の需要鈍化により、**バッテリーセル不足というよりはむしろ過剰側に振れている**。
- 出典: S&P Global Ratings

**Trailseekerへの含意**: Solterra/Trailseekerに採用されているバッテリー(従来 CATL / プライムプラネットエナジー&ソリューションズ等とされる)については**最新の個別契約情報は本調査範囲では未確認**。ただし、業界全体ではセル供給そのものは**逼迫していない**ため、Trailseekerの遅延がバッテリーセル不足に直接起因している蓋然性は低い。むしろ**バッテリー周辺の半導体・希土類モーター・パワーエレキ部品**の方が制約要因として現実的。

---

## 5. 個別フォーラム・顧客報告

- **Trailseeker Forum**(trailseekerforum.com)に「**8〜10週間待ち**と説明された」投稿(2026年3月、ディーラー談)。
- 公式リリース: 米国納車は**2026年春開始**。
- 実車試乗レビューは2026年5月時点で複数公開済み(MotorWeek, Charged EVs)。
- 出典: Trailseeker Forum, subaru.com, motorweek.org, chargedevs.com

**注**: Trailseeker Forum本体のWebFetchは403エラーで失敗。検索結果のスニペットを引用。

---

## 6. 「約1ヶ月遅延」の蓋然性が高い要因(優先度順)

| # | 要因 | 蓋然性 | 根拠の強さ |
|---|------|-------|----------|
| 1 | **量産立ち上げ初期(2026/2開始)の歩留まり・部品供給安定化** | 高 | 強(公式発表) |
| 2 | **RoRo船腹タイト化 + EV火災規制でリードタイム延長** | 高 | 強(業界横断的事実) |
| 3 | **トランプ関税対応で物流フロー再構築中** | 中〜高 | 強(スバル決算で言及) |
| 4 | **車載DRAM/NAND不足によるECU/インフォテイメント手配遅延** | 中 | 強(業界横断、Trailseeker個別証拠は未確認) |
| 5 | **米国販売側の在庫不足(スバル自身が認知)** | 高 | 強(2026/4 sales reportで言及) |
| 6 | **希土類モーター部材の手配リスク** | 中 | 中(規制再発動は2026/11、現時点で影響限定的) |
| 7 | **Trailseeker個別のリコール起因の生産停止** | 低 | 弱(NHTSA未登録) |
| 8 | **特定サプライヤーの倒産・火災等の単発イベント** | 低 | 弱(報道未確認) |

---

## 7. 未確認事項(さらなる調査が望ましい)

- Trailseekerに使用される**具体的なバッテリーセルサプライヤーと供給状況**(Panasonic / CATL / プライムプラネット?)
- Trailseeker個別の**ECUサプライヤー**(Denso, Aptiv等)の供給状況
- **2026年4-5月のYajima工場の稼働状況**(具体的な減産日数、シフト調整等)
- **Trailseeker向けの船積み実績**(船社、配船頻度)
- **ディーラー個別の「部品調達不足」説明の真偽**(本社からの公式ガイダンスかディーラー独自の説明か)

---

## 8. 推奨される顧客への説明スタンス(調査担当としての見解)

1. ディーラー説明の「部品調達不足」は**部分的には正しい**(業界全体のメモリ・希土類・半導体逼迫は事実)が、**Trailseeker個別の特定部品トラブルの公開証拠は無い**。
2. より実態に近い説明は「**新規EV車種の量産立ち上げ初期(2026年2月開始)+RoRo船腹タイト化+関税対応の物流フロー調整**」の複合。
3. スバル米国自身が4月時点で「inventory shortages」を公式に認知しており、**個別ディーラーの責任ではない構造的問題**。
4. 「**1ヶ月遅延は当該車種・当該時期において業界平均的な範囲**」と位置づけられる。3ヶ月以上の遅延に発展する場合は別途精査が必要。

---

## 出典一覧(主要URL)

### スバル公式・業績
- [Subaru begins BEV production at Gunma Yajima Plant (Subaru Corporation, 2026/2/4)](https://www.subaru.co.jp/news-en/2026_02_04_173507/)
- [Subaru Begins BEV Production at Gunma Yajima Plant - Automotive World](https://www.automotiveworld.com/news/subaru-begins-bev-production-at-gunma-yajima-plant/)
- [Subaru Kicks Off Trailseeker EV Production at Gunma Yajima Plant - autoevolution](https://www.autoevolution.com/news/subaru-kicks-off-trailseeker-ev-production-at-gunma-yajima-plant-in-japan-265346.html)
- [Subaru begins series production of Trailseeker EV / e-Outback - electrive.com (2026/2/5)](https://www.electrive.com/2026/02/05/subaru-begins-series-production-of-trailseeker-ev-e-outback/)
- [Subaru is now building EVs in-house - Electrek (2026/2/5)](https://electrek.co/2026/02/05/subaru-builds-first-in-house-ev-new-electric-suv/)
- [Subaru postpones in-house EV development after profits fall 90% - WardsAuto](https://www.wardsauto.com/news/subaru-postpones-in-house-ev-development-after-profits-fall-90/820412/)
- [Subaru indefinitely postpones in-house EVs after profits plunge 90% - Electrek (2026/5/19)](https://electrek.co/2026/05/19/subaru-postpones-in-house-ev-launch-2028-profits-plunge-90/)
- [Mazda and Subaru postpone EV launches - electrive.com (2026/5/19)](https://www.electrive.com/2026/05/19/mazda-and-subaru-postpone-ev-launches/)
- [Subaru delays in-house EV production after $362 million charge - Automotive News (2026/5/15)](https://www.autonews.com/subaru/an-subaru-delays-ev-electric-vehicle-4q-earnings-financial-results-atsushi-osaki-0515/)
- [Subaru's EV rethink reveals the harsh new reality - carsales.com.au](https://www.carsales.com.au/editorial/details/subarus-ev-rethink-reveals-the-harsh-new-reality-facing-car-makers-152072/)
- [Subaru Begins Hybrid Production - Subaru U.S. Media Center](https://media.subaru.com/pressrelease/2419/1/subaru-indiana-automotive-begins-hybrid-production)
- [Subaru of America Reports April 2026 Sales - Subaru U.S. Media Center](https://media.subaru.com/pressrelease/2445/subaru-america-reports-april-2026-sales-results)
- [Subaru Sales Are Still Lagging - The Drive](https://www.thedrive.com/news/subaru-sales-are-still-lagging-but-numbers-dont-tell-the-whole-story)

### 半導体・部品調達
- [2026 Trends shaping the automotive semiconductor market - S&P Global](https://www.spglobal.com/automotive-insights/en/blogs/2026/04/automotive-semiconductor-market-trends)
- [2025-2026 DRAM Shortage: What auto marketers need to know - S&P Global (2026/2)](https://www.spglobal.com/automotive-insights/en/blogs/2026/02/what-auto-marketers-and-dealers-need-to-know-about-the-dram-shortage)
- [Automakers Face Chip Shortage Due to Demand From AI Data Centers - PYMNTS](https://www.pymnts.com/news/artificial-intelligence/2026/automakers-face-chip-shortage-demand-from-ai-data-centers/)
- [Another Chip Shortage Is Coming - Autobody News](https://www.autobodynews.com/news/another-chip-shortage-is-coming-this-one-will-hit-adas-parts)
- [Automakers Face Memory Crunch as AI Strains Chip Supply - EE Times](https://www.eetimes.com/automakers-face-memory-shock-as-ai-uses-up-semiconductor-supply/)
- [A new microchip shortage is looming - Detroit News (2026/2/21)](https://www.detroitnews.com/story/business/autos/2026/02/21/microchip-shortage-auto-dram-ai-data-centers-prices-increase/88740139007/)

### 希土類・バッテリー材料
- [China Rare Earth Export Controls 2026 - Certivo](https://www.certivo.com/blog-details/china-rare-earth-export-controls-2026-what-new-licensing-rules-mean-for-manufacturers)
- [With new export controls on critical minerals - IEA](https://www.iea.org/commentaries/with-new-export-controls-on-critical-minerals-supply-concentration-risks-become-reality)
- [China Hits Pause on Rare-Earth Export Controls - Clark Hill PLC](https://www.clarkhill.com/news-events/news/china-hits-pause-on-rare-earth-export-controls-and-what-it-means-for-supply-chains/)
- [Key Changes in China's Export Control Landscape for Rare Earths - Taylor Wessing (2026/4)](https://www.taylorwessing.com/en/insights-and-events/insights/2026/04/key-changes-in-china-s-export-control-landscape-for-rare-earths)
- [Lithium shortages could hit by 2028 - Electrek (2026/3/3)](https://electrek.co/2026/03/03/lithium-shortages-could-hit-by-2028-as-ev-demand-surges/)

### 関税
- [Trump Tariffs Have Cost Automakers Over $35 Billion - Autoblog](https://www.autoblog.com/news/trump-tariffs-have-cost-automakers-over-35-billion-since-2025)
- [Trump Threatens to Raise EU Auto Tariffs - Digital Dealer](https://digitaldealer.com/news/us-tariff-tracker-impact-automaker-response/164521/)
- [US Deliveries April 2026: Tariff-Impacted Sales - autoevolution](https://www.autoevolution.com/news/us-deliveries-april-2026-tariff-impacted-sales-didn-t-look-too-rosy-for-some-asian-automakers-269439.html)

### 物流・海運
- [Red Sea Disruptions, Panama Canal Constraints - Global Trade Magazine](https://www.globaltrademag.com/red-sea-disruptions-panama-canal-constraints-and-their-long-term-effects-on-global-trade-routes/)
- [The Impacts of the Red Sea Shipping Crisis - J.P. Morgan](https://www.jpmorgan.com/insights/global-research/supply-chain/red-sea-shipping)
- [The Red Sea crisis: Renewed attacks - project44](https://www.project44.com/supply-chain-insights/the-red-sea-crisis-ceasefire-collapse-leaves-red-sea-in-tumultuous-state/)
- [RoRo Shipping in 2026: Why Vehicle Shipping Capacity Is Tight - TransGlobal](https://tgal.us/roro-shipping-2026-vehicle-shipping-capacity/)
- [Updated RoRo Shipping Schedule from Japan - KMC JAPAN](https://kmcjapan.co.jp/blog/updated-roro-shipping-schedule-from-japan-feb-mar-2026-kmc-japan)

### リコール
- [Subaru Solterra Recalls List 2022-2026 - Recharged](https://recharged.com/articles/subaru-solterra-recalls-list)
- [2026 Subaru Solterra Recalls - Cars.com](https://www.cars.com/research/subaru-solterra-2026/recalls/)
- [2026 Subaru Trailseeker Recall - Mike Shaw Subaru](https://www.mikeshawsubaru.com/2026-subaru-trailseeker-recall.htm)
- [Vehicle Recalls - Subaru](https://www.subaru.com/recalls.html)

### バッテリーセル
- [LG Energy's $6.5 bn EV battery supply deal with Ford terminated - KED Global](https://www.kedglobal.com/batteries/newsView/ked202512170012)
- [Credit FAQ: U.S. Changes Policies, Korean Battery Firms Change Strategy - S&P Global Ratings](https://www.spglobal.com/ratings/en/regulatory/article/credit-faq-the-us-changes-policies-the-korean-battery-firms-change-strategy-s101653182)
- [Panasonic's Delayed U.S. EV Battery Plant - TrendForce](https://www.trendforce.com/news/2025/05/23/news-panasonics-delayed-u-s-ev-battery-plant-targets-july-launch-fighting-chinas-material-stranglehold-and-u-s-tariffs/)

### 顧客フォーラム
- [Order is in - Trailseeker Forum](https://www.trailseekerforum.com/threads/order-is-in-now-the-hardest-part-the-waiting.124/)

---

**調査担当注記**: 本レポートはWeb公開情報のみに基づく。スバル社内・サプライヤー社内の非公開情報、ディーラー個別の事情は含まれない。最終的な遅延原因の特定にはディーラーまたはスバルカスタマーサポートからのVIN単位の追跡情報が必要。
