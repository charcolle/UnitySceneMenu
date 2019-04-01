# UnitySceneMenu
![](https://img.shields.io/badge/version-v2.0.0-brightgreen.svg)  
マルチシーンで作業するのに便利なツールです。  
[AssetStore](https://assetstore.unity.com/packages/tools/utilities/unityscenemenu-111222)

![gif](desc/unityscenemenu_v2.gif)

## サポートバージョン
Unity5.6以上

# Forum
どんな要望も大歓迎です :)    
[UnityConnect UnitySceneMenu](https://connect.unity.com/p/unityscenemenu)

# 使い方
[Youtube](https://youtu.be/TvXUYsBicRw)  

![img](desc/unityscenemenu_main.png)  

* [設定ウインドウ](##設定ウインドウ)
    * [シーンメニュー](###シーンメニュー)
    * [シーンの登録](###シーンの登録)
* [Sceneメニューウインドウ](##Sceneメニューウインドウ)
* [ビルドシーン自動登録](##ビルドシーン登録)

## 設定ウインドウ
Sceneを登録しないとUnitySceneMenuは使うことができないので先に設定を行います。  
[Window]->[SceneMenu]->[Config]を選択し、UnitySceneMenuの設定ウインドウを開きます。  

### シーンメニュー
#### シーンメニューの作成
一番左側のカラムエリアで右クリックし、[**Create**]を選択するとメニューが作成されます。*New Menu*が出現するので、名前を編集します。  
![img](desc/unityscenemenu_menu_create.png)　

#### シーンメニューの編集
対象のメニューを長く選択するか、右クリックメニューの[**Rename**]から名前を変更します。

#### シーンメニューの削除
対象のメニューで右クリックメニューを開き、[**Delete**]を選択することで削除します。

#### シーンメニューの並べ替え
メニューをドラッグすると任意の位置へ移動します。
  
### シーンの登録
作成したメニューへシーンを登録します。

#### シーンの登録
一番右のカラムには、Project内に存在するすべてのシーンが表示されています。その中から、自分がメニューに登録したいと思うシーンをクリックします。  
クリックすると、中央のカラムにクリックしたシーンが登録されます。  
![img](desc/unityscenemenu_scene_add.png)　

#### シーンの削除
登録したシーンは、中央のカラムのシーンを右クリックし[**Delete**]を選択することで削除します。  
また、右カラムにある該当シーンをもう一度クリックすることで削除します。

#### シーンの並べ替え
シーンをドラッグすると任意の位置へ移動します。  
シーンメニューを実際に利用する時の並び順になるので、変更したい場合はここで行います。

#### 基本シーンの設定
メニューを切り替えて最初にロード状態にするシーンを基本シーンといいます。  
基本シーンは、シーン一覧で青色に表示されます。  
基本シーンは、必ず先頭のシーンに設定されますが、数を変更することが可能です。シーン一覧の上にある**メニュー名**をクリックし、基本シーンの数を設定してください。先頭から設定された数だけ基本シーンとして設定されます。

![img](desc/unityscenemenu_basicscene_1.png)　
![img](desc/unityscenemenu_basicscene_2.png)

## Sceneメニューウインドウ
[Window]->[SceneMenu]->[Scenes]を選択し、UnitySceneMenuを開きます。  

### 操作方法
1. 右上のプルダウンに設定ウインドウで登録したメニューが表示されます。ここでメニューの切り替えを行います。  
![img](desc/unityscenemenu_scenemenu_1.png)  

1. シーンの名前をクリックすると、シーンがロードされます。

1. 左Ctrlキーを押したままシーンを選択すると、そのシーンのみをロードします。

1. **Refresh**ボタンで初期状態に戻します。

1. 登録したシーンがとても長いとき、マウスホイールでスクロールしてシーンを選択します。また、検索BOXでメニュー内のシーンを検索することが可能です。

1. **Current Loaded**をオンにすることで、現在ロード中のシーンのみを表示します。

1. ウインドウメニューから、設定画面を開くことができます。  
![img](desc/unityscenemenu_scenemenu_2.png)  

## ビルドシーン自動登録
メニューに登録したシーンを自動的にビルドシーンへと登録する機能があります。  

### ビルドシーンメニュー設定
該当メニューを右クリックし、[**Set as BuildTarget**]を選択することで、メニュー内のシーンがその順番通りにビルドシーンへと登録されます。この設定が行われたメニューには、シーンアイコンが付与されます。  
この設定が行われたメニューは、今後シーンを追加したときも自動的に登録が行われるようになります。

![img](desc/unityscenemenu_buildscene.png)  

### ビルドシーンメニュー設定解除
該当メニューを右クリックし、[**Remove from BuildTarget**]を選択することで、ビルド自動登録機能を解除します。