# cloudwatchlogs-to-excel
CloudWatch ロググループの一覧をExcelに記入するJupyter Notebookです。  

# 事前準備
- Excelファイルは事前に用意してください。
- excel_file_pass にExcelファイルのパスを指定してください。
- シート名は手動で作成してください。

# 補足
- 以下の属性をExcelに記入します。  
  - ロググループ名
  - 保持期間
  - メトリクスフィルター名
  - メトリクスフィルターパターン
  - サブスクリプションフィルター名
  - サブスクリプションフィルターパターン