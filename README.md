![example workflow](https://github.com/n-sassa/training-adviser-rest/actions/workflows/django.yml/badge.svg)
[![codecov](https://codecov.io/gh/n-sassa/training-adviser-rest/branch/main/graph/badge.svg?token=NQYCGYNCDI)](https://codecov.io/gh/n-sassa/training-adviser-rest)
# training_adviser API
「筋トレ初心者でジムに通い始めるけど何から始めればいいか分からない」  
そんな方におすすめの**StrongLifts 5×5メソッド**を実践するためのAPIです。  
 
# StrongLifts 5×5メソッドとは
 
StrongLifts 5×5は、名前にある5×5の通り5回5セットの筋トレを繰り返すだけのシンプルなトレーニング手法です。  

## 基本のやり方
StrongLiftsはたったの5種目のトレーニングを行うだけです。
> ・スクワット  
> ・ベンチプレス  
> ・バーベルロウ  
> ・ショルダープレス  
> ・デッドリフト
  
■ 種目の分割  
これらの種目をセットAとセットBに分け、それぞれを交互に繰り返します。
> セットA：スクワット、ベンチプレス、バーベルロウ  
> セットB：スクワット、ショルダープレス、デッドリフト
セットAを行ったら1日以上休みを挟んでセットBを行い、また1日以上休みを挟んでセットAを行うというように繰り返します。
  
■ 重量の増やし方  
最初は各種目20kgでトレーニングを開始します。  
※20kgで重たい場合はバーベルシャフトのみ（約10kg)  
その後は前回のトレーニング重量から2.5kg増やして行きます。  
※デッドリフトのみ5kgずつ増やします。  
トレーニング中に重量の変更は行わず5セット(1セットあたり5回)上げることを目標にします。  
※デッドリフトのみ1セットあたり1回  

## 回数と頻度
トレーニングは週3回行い、間に必ず1日の休みを入れます（例：月、水、金）。12週間続けましょう。  

### 目標は12周間続けること
推奨されているトレーニング頻度は週3回になります。  
これを12週間続けて下さい。  
軽い重量から始めるためトレーニングのフォーム等を意識しながら行うことでその後の筋トレをより良いものにすることができます。  

# 言語
- python 3.9.13

# ライブラリ
- Django 4.0.4
- DjangoRESTframework 3.13.1
- djangorestframework-simplejwt 4.8.0
- django-cors-headers 3.11.0
- djoser 2.1.0
- pytest
- pytest-cov
- pytest-django
- pytest-factoryboy

# 仮想環境
- docker

# CI
- GitHub Actions

# 機能
- ログインユーザー登録
- プロフィール登録
- トレーニング登録、変更、削除
- 次回のトレーニング内容の出力
- 次回のトレーニング重量の出力
