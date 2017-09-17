# Adapterパターン
二つのインターフェース間に違いがある場合にその違いを吸収するためのAdapterをおくやり方である。
Adapterパターンは継承を利用するパターンと、移譲を利用するパターンの２つのアプローチがある。

### メモ
interfaceはimplements, abstractはextends

## 継承するパターン
ターゲットがinterfaceの場合に利用

## 移譲するパターン
ターゲットが抽象クラスとして宣言されている場合に利用
抽象クラスはextendsして利用するため、Javaにおいては二重継承の制約に引っかかってしまう。