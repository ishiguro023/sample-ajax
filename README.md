# samplr-ajax
授業中のソースのリソース

## jQuery 側の json オブジェクトの準備
```javascript
formData = {};
```
{} は 空の json オブジェクト
```javascript
formData = {"param1"} = "テスト";
```
formData のプロパティは formData["プロパティ文字列"]に値をセットして作成される
formData のプロパティは formData.プロパティ文字列 と書くこともできます
```javascript
formData.param1 = "テスト";
```
