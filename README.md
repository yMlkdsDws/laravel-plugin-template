# laravel-plugin-template

## Usage

### Composer を設定する

以下のプロパティを適切に設定する。

-   `name`

### 名前空間の変更

各ファイルの `Entap\ExamplePackage` を適切な名前空間に置き換える。

置換用の正規表現

```
Entap(\\{1,2})ExamplePackage
```

### 最新の依存パッケージをインストールする

```
composer require laravel/framework
composer require --dev phpunit/phpunit orchestra/testbench
```
