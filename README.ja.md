# UnitySceneMenu v1.1
マルチシーンで作業するのに便利なツールです。  
AssetStore: https://assetstore.unity.com/packages/tools/utilities/unityscenemenu-111222

![unityscenemenu_screenshot](https://github.com/charcolle/UnitySceneMenu/blob/master/DescFiles/unityscenemenu.png)

## サポートバージョン
Unity5.4 or higher  

# 使い方
UnitySceneMenuにシーンを登録することで、ボタンを押すだけでシーンのロード・アンロードができます。
また、ビルドシーンを自動で登録する機能もあります。

UnitySceneMenuを利用する前に、Configウインドウでシーンを登録する必要があります。

1. UnitySceneMenuのConfigウインドウを開きます。[Window]-[SceneMenu]-[Config]
2. 左カラムにある[+] ボタンを押してメニューを作成します。作成したメニューの名前は[Edit]ボタンを押すことで自由に変更することが可能です。 メニューを選択した状態で[-] ボタンを押すとメニューの削除ができます.
3.  作成したメニューを選択すると、プロジェクトにあるすべてのシーンが右カラムに表示されます。メニューに登録したいシーンをそこから選んでください。シーンが多い場合はシーンの名前で検索することができます。中央カラムの[-]ボタンを押すことで登録したシーンの削除ができます。
*NOTE : Unityアイコンが付いてるものはビルド設定に登録されているシーンです*  

![unityscenemenu_config](https://github.com/charcolle/UnitySceneMenu/blob/master/DescFiles/unityscenemenu_1.gif)

### ◆SceneMenu
1. UnitySceneMenuを開きます。 [Window]-[SceneMenu]-[Scenes].
2. さっき登録したシーン群が表示されます。これらを押すことで簡単にシーンのロード・アンロードができます。
3. ドロップダウンメニューにはConfigウインドウで作成したメニューのすべてが表示されます。別のメニューを選択することで、メニューを切り替えることができます。
  
*NOTE:*  
*1. メニューに最初に登録されたシーンは、必ず最初に読み込まれます。ほかのシーンはnot loadedの状態で一緒に読み込まれます。*  
*2. メニューを切り替えると、前のメニューのシーンはすべてアンロードされ、新しいメニューのシーンが同様に読み込まれます。*  
*3. プレイモードの状態でシーンをロード・アンロードしたり、メニューを切り替えることはできません*    

![unityscenemenu_config](https://github.com/charcolle/UnitySceneMenu/blob/master/DescFiles/unityscenemenu_2.gif)
  
4. 左のCtrlキーを押しながらシーンを選択すると、単一シーンのみをロードすることができます。
  
![unityscenemenu_config](https://github.com/charcolle/UnitySceneMenu/blob/master/DescFiles/unityscenemenu_3.gif)
  
### ◆Auto SetUp BuildSetting
1. *Build Menu*から自動でビルド設定にシーンを登録する設定をします。この設定は、ディレクトリ単位で行われます。
2. *Use Auto BuildSetting*をオンにして、*BuildScene RootPath*にビルドするシーンが入ったディレクトリをドラッグ＆ドロップをしてパスを設定してください。
3. ビルド設定で一番最初に登録したいシーンを設定することができます。*FirstScenePath*に該当シーンをドラッグ&ドロップして設定を行ってください。
4. [Configure]ボタンを押すことで設定を反映することができますが、設定後は該当パスにシーンを追加・削除するごとに自動的にビルド設定は更新されます。
    
![unityscenemenu_config](https://github.com/charcolle/UnitySceneMenu/blob/master/DescFiles/unityscenemenu_4.gif)
