# item_modifier-set_custom_model_data
item_modifierの1項目であるset_custom_model_dataのサンプルになります。

詳しくはブログ記事『[【マイクラ】set_custom_model_dataでテクスチャを変更【item_modifier】](https://natsumake.com/item_modifier-set_custom_model_data/)』を参考にしてください。

<h3>概要</h3>
CustomModelDataの値をアイテムに対して指示することが出来ます

<h3>使い方</h3>

データパック導入後、ワールドに入り```/reload```と入力し実行してください。

ダイヤモンドやネザライトの剣、タラのスポーンエッグが付与されます。

タラを倒すことでset_custom_model_dataによってCustomModelDataの値が決められたエメラルドがドロップします。<br>
また、itemコマンドを使うことでCustomModelDataを適用させることも可能です。

そのコマンドがこちら。

```copy
/item modify entity @s weapon.mainhand sample:set_custom_model_data
```

リソースパックはないため、テクスチャの変更が起きません。<br>
dataコマンドでCustomModelDataの値を確認してください。

以下は手に持っているアイテムのデータを確認するコマンドになります。

```copy
/data get entity @s SelectedItem
```
