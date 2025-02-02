# AI可読性のある命名規則

{% hint style="info" %}
このドキュメントはまだ検証中です。検証結果
{% endhint %}

## Description

この文書は、コードを書く際に役立つ名前付けルールのパターンについて説明します。このパターンを利用することで、より読みやすく、理解しやすく、メンテナンスしやすいコードを書くことができます。

## Problem

コードを書く際に、変数や関数の名前をどうするか悩むことがあります。また、コメントアウトだけでコンテキストを提供しようとすると、読み手にとって理解しづらいコードになることがあります。この読みにくさは GitHub Copilot の精度にも影響してしまいます。最終的に GitHub Copilot から正確な提案を受けることができなくなってしまいます。

## Context

GitHub Copilot は Codex というエンジンを使用しており、このエンジンは GPT3 ベースのモデルを利用しています。GPT3 ベースのモデルは自然言語を理解することができるため、自然言語に似た変数の表現をすることで、より読みやすく理解しやすいコードを書くことができます。

## Solution

コードを書く際に、変数や関数の名前について悩んでいる場合は、チームであらかじめ共通の命名規則を GitHub Copilot を前提につくることで、AI にもより読みやすく理解しやすいコードを書くことができます。
コメントアウトだけでコンテキストを提供するのではなく、自然言語に似た変数の表現をすることで、GitHub Copilot がより正確な提案を行うことができるようになります。

以下は、名前付けルールのパターンの例です。

* ローワーケースを使用する
* キャメルケースを使用する
* 自然言語に似た変数の表現をする
* 短い名前を使用する
* 説明的な名前を使用する

## Resulting Context

この名前付けルールのパターンを利用することで、より読みやすく理解しやすいコードを書くことができます。また、GitHub Copilot がより正確な提案を行うことができるようになります。
