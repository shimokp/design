# TemplateMethodパターン

## 概要
スーパークラスで処理の枠組みのみを定めて、サブクラスで具体的な内容を実装する。

## メリット
処理の流れが複雑になっても、スーパークラスで定義されたメソッドを呼ぶだけで、
適切な順番で呼ぶことができるため誤りが少なくなる。