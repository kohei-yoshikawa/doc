Juju GUI 2.0を既存環境への適用してみた。

```
$ juju version
1.24.6-trusty-amd64
$ juju upgrade-charm juju-gui
$ juju remove-unit juju-gui/0
$ juju add-unit juju-gui
```

で特に問題なく使えてるっぽい。

Juju GUI2.0、洗練されていい感じではある。
注文としては、、、

- Serviceのアイコンにサービス名はでてほしいなぁ。
- 拡大縮小がCtr++-やホイール上下になったけど左クリックでもできてほしい。
- アイコンの自動再整列ボタンがほしいなぁ。
- GUIベースのCharm Buildeがあればなぁ（それはいわない約束よ、おとっつぁん・・・)

## 参考

[Juju GUI 2.0のプレスリリース](https://insights.ubuntu.com/2016/01/25/released-juju-gui-2-0/)


