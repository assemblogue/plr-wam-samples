# plr-wam-samples

**plrDart の推論エンジン（`plr_wam`）の例題**です。オントロジー（クラスと属性の定義）と、
それを使う知識グラフ・ホーン節プログラムが入っています。

`wam_test` の GUI はここから最新のものを読みます（読めなければ同梱のものを使います）。

```
sample/quote_graph_*      見積書（空から作る）
sample/quote_shared_*     見積書（共有データ版）
sample/quote_pattern_*    見積書（パターンで集計）
sample/ontology.jsonld    調達申請ワークフロー
sample/golden_*           調達申請（golden シナリオ）
sample/shipment_*         分納・返品を繰り返す出荷
sample/master*            購買検討（マスターDB）
sample/pricing_*          価格決定（CLI の例題）
```

**中身はすべて架空です。** えんぴつ・消しゴム・ノート・印刷用紙といった品目と、
「購買担当」「承認者」のような役割名だけで、実在の個人・組織のデータは含みません。

正典は private リポジトリ `assemblogue/plrDart` の
`plr_console/tool/wam_test/sample/` で、ここはその公開の写しです。
