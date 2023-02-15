# readme_amitani
# 開発環境
Python(3.8.10)  
Google Colaboratory  
jupyter notebook  
Twitter API v1  
Twitter API v2 academic research
# 概要
いいね1000以上の画像付きツイートをバズ，いいね1000未満の画像付きツイートを非バズとし収集している．  
randomforest，XGBoostを用いて二値分類予測を行う．  
テキストと画像の特徴量を組み合わせモデル，テキスト特徴量のみのモデル，画像特徴量のみのモデルで精度比較を行う．  
テキストと画像の，偏りや特徴から精度向上のための分析を行う．
# ファイルの説明
###  `./newbuzz` 
randomforest，XGBoostで使用したバズツイート．
###  `./newnonbuzz` 
randomforest，XGBoostで使用した非バズツイート．
###  `./text_image_vec`
テキストと画像の特徴量抽出するプログラム．日本語話し言葉BERTモデルを含む．
###  `./旧buzz`
収集したバズツイート．randomforest，XGBoostでは使用していない．
###  `./旧nonbuzz`
収集した非バズツイート．randomforest，XGBoostでは使用していない．
###  `./predict_model`
##### `output`
実際の予測結果をまとめたフォルダ．特徴量単体，特徴量組み合わせとrandomforest，XGBoostで4種類のディレクトリがある．
##### `output_accuracy`
モデルの予測精度をまとめたフォルダ．特徴量単体，特徴量組み合わせとrandomforest，XGBoostで4種類のディレクトリがある．
##### `outputvec_merge`
画像特徴量をまとめたフォルダ．
##### `tw_bert`
テキスト特徴量をまとめたフォルダ．
##### `category`
画像のオブジェクト検出を行った結果をまとめたフォルダ．
##### `text_image_vec`
テキストと画像から特徴量を抽出するプログラム．
##### `model_program`
randomforest，XGBoostの予測モデルを作成するプログラム．
##### `multitask_model`
マルチタスク学習を行うプログラム
###  `./tweet_reply`
ツイートのリプライ情報をまとめたフォルダ．
###  `./tweet_research`
ツイートの収集や分析のプログラムをまとめたフォルダ．
###  `./学会資料`
学会の論文などをまとめたフォルダ．
