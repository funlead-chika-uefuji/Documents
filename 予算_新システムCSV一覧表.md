# 予算\_新システムCSV一覧表

すべてのCSVは、ファイル名に画面で選択した会計年度（西暦4桁）を入れて出力する。
ファイル名は、下表のサンプルCSVファイル名の拡張子の前に「\_yyyy」を付けた形とする。

- 例：当初財源充当\_yyyy.csv
- 例：消費税額集計表\_yyyy.csv

| 新システム画面URL                                 | サンプルCSVファイル名           | 出力CSV名称                 | 実装   |
|------------------------------------------|----------------------|-----------------------|----|
| /financial_forecast-settlement-input       | 予算集計表（当初）.csv          | 予算集計表_当初(CSV)           | 8月以降 |
| /financial_forecast-settlement-input       | 予算集計表（補正）.csv          | 予算集計表_補正(CSV)           | 8月以降 |
| /financial_forecast-settlement-input       | 予算集計表（決算）.csv          | 予算集計表_決算(CSV)           | 8月以降 |
| /financial_forecast-settlement-input       | 予算集計表（暫定）.csv          | 予算集計表_暫定(CSV)           | 8月以降 |
| /budget_sorting_profit-and-loss            | 予算自動仕訳エラーリスト.csv       | 予算自動仕訳エラーリスト(CSV)       | 8月中  |
| /budget-document-creation                  | 予算仕訳リスト（予算科目別）.csv     | 予算仕訳リスト_予算科目別(CSV)      | 8月以降 |
| /budget_sorting_loan                       | 予算仕訳リスト（仕訳科目別）.csv     | 予算仕訳リスト_仕訳科目別(CSV)      | 8月以降 |
| /consumption-tax-summary                   | 消費税額集計表.csv            | 消費税額集計表(CSV)            | 8月以降 |
| /consumption-tax-calculation               | 消費税額計算書.csv            | 消費税額計算書(CSV)            | 8月以降 |
| /budget_copy-new                           | 当初予算データCSV取込エラーリスト.csv | 当初予算データCSV取込エラーリスト(CSV) | 8月中  |
| /budget_copy-new                           | 新年度予算科目CSV.csv         | 新年度予算科目(CSV)            | 8月中  |
| /estimate_unit_price_table_revision_update | 新年度単価一覧表（単価コード別）.csv   | 新年度単価一覧表_単価コード別(CSV)    | 8月以降 |
| /estimate_unit_price_table_revision_update | 新年度単価一覧表（所属別）.csv      | 新年度単価一覧表_所属別(CSV)       | 8月以降 |
| /budget-request-audit                      | 事業別見積要求書（当初）.csv       | 事業別見積要求書_当初(CSV)        | 8月以降 |
| /budget-request-audit                      | 事業別見積要求書（補正）.csv       | 事業別見積要求書_補正(CSV)        | 8月以降 |
| /budget-request-audit                      | 事業別見積要求書（暫定）.csv       | 事業別見積要求書_暫定(CSV)        | 8月以降 |
| /budget-request-audit                      | 事業別見積予算集計表（当初）.csv     | 事業別見積予算集計表_当初(CSV)      | 8月以降 |
| /budget-request-audit                      | 事業別見積予算集計表（補正）.csv     | 事業別見積予算集計表_補正(CSV)      | 8月以降 |
| /budget-request-audit                      | 事業別見積予算集計表（決算）.csv     | 事業別見積予算集計表_決算(CSV)      | 8月以降 |
| /budget-request-audit                      | 事業別見積予算集計表（暫定）.csv     | 事業別見積予算集計表_暫定(CSV)      | 8月以降 |
| /budget-request-audit                      | 予算見積要求書（当初）.csv        | 予算見積要求書_当初(CSV)         | 8月以降 |
| /budget-request-audit                      | 予算見積要求書（補正）.csv        | 予算見積要求書_補正(CSV)         | 8月以降 |
| /budget-request-audit                      | 予算見積要求書（暫定）.csv        | 予算見積要求書_暫定(CSV)         | 8月以降 |
| /budget-request-audit                      | 対前年度比較表.csv            | 対前年度比較表(CSV)            | 8月以降 |
| /budget-request-audit                      | 事業別予算査定一覧表（当初）.csv     | 事業別予算査定一覧表_当初(CSV)      | 8月以降 |
| /budget-request-audit                      | 事業別予算査定一覧表（補正）.csv     | 事業別予算査定一覧表_補正(CSV)      | 8月以降 |
| /budget-request-audit                      | 予算査定一覧表（科目別・当初）.csv    | 予算査定一覧表_科目別_当初(CSV)     | 8月以降 |
| /budget-request-audit                      | 予算査定一覧表（科目別・補正）.csv    | 予算査定一覧表_科目別_補正(CSV)     | 8月以降 |
| /budget-request-audit                      | 予算査定一覧表（科目別・暫定）.csv    | 予算査定一覧表_科目別_暫定(CSV)     | 8月以降 |
| /budget-request-audit                      | 予算査定一覧表（所属別・当初）.csv    | 予算査定一覧表_所属別_当初(CSV)     | 8月以降 |
| /budget-request-audit                      | 予算査定一覧表（所属別・補正）.csv    | 予算査定一覧表_所属別_補正(CSV)     | 8月以降 |
| /budget-request-audit                      | 予算査定一覧表（所属別・暫定）.csv    | 予算査定一覧表_所属別_暫定(CSV)     | 8月以降 |
| /initial_funding                           | 当初財源充当.csv             | 当初財源充当(CSV)             | 8月以降 |
| /fund-allocation                           | 補正財源充当.csv             | 補正財源充当(CSV)             | 8月以降 |
| /execution-plan-table                      | 執行計画表（科目）.csv          | 執行計画表_科目(CSV)           | 8月以降 |
| /execution-plan-table                      | 執行計画表（事業）.csv          | 執行計画表_事業(CSV)           | 8月以降 |
| /budget-allocation-table                   | 予算配当表（科目）.csv          | 予算配当表_科目(CSV)           | 8月以降 |
| /budget-allocation-table                   | 予算配当表（事業）.csv          | 予算配当表_事業(CSV)           | 8月以降 |
| /budget-allocation-summary-table           | 予算配当総括表.csv            | 予算配当総括表(CSV)            | 8月以降 |
| /budget_sorting_consumption_tax            | 予算税区分集計・調整額一覧表CSV.csv  | 予算税区分集計・調整額一覧表(CSV)     | 8月中  |
| /budget_sorting_consumption_tax            | 予算特定収入科目設定一覧表CSV.csv   | 予算特定収入科目設定一覧表(CSV)      | 8月中  |
