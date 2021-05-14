# ClusTimesViewer
ClusTimes を設置してくれてありがとうございます

ClusTimesは、clusterのユーザー有志による草の根新聞メディアです。 このClusTimes Viewerをワールドに設置すると、自動的にClusTimesの最新版を読み込み、ワールドで記事を表示します。 

ファイルは以下からダウンロードしてください。

https://github.com/Dolphiiiin/ClusTimesViewer/releases

#ClusTimes-Viewerの設置方法

 - [project foloder] Asset/prefabs/にある、ClusTimes Controllerを設置

 - [Hierarchy] UI->PlayerLocalUIを追加

![](https://cdn.discordapp.com/attachments/681123942676561950/842660099209953280/putPlayerLocalUI.png)

（すごく大きいobjectができますがサイズも場所もそのままで大丈夫、あとで調整します）

 - PlayerLocalUIを開きsafeareaに、ClusTimes - local UIのprefabを設置

![](https://cdn.discordapp.com/attachments/681123942676561950/842660099037855744/SelectLocaPlayerPrefab.png)

 - 記事を出したい位置に空のGameObjectを設置

このobjectでモニタの位置を指定します。あとで調整可能です。設置したらとりあえず進んでください。

 - LocalUIのインスペクタのScale/Position/Rotation Constraintのそれぞれに、さっきつくった空のGameObjectを指定し、Zeroのボタンを押す

![](https://cdn.discordapp.com/attachments/681123942676561950/842660098677538857/settransformobject.png)

 - GameObjectで設置場所を調整

ここで場所を調整します。モニタには表と裏があります、裏からは透過してみえるます。

モニタは、コントローラのボタンを押した後に表示されます。モニタは、個々のユーザーにしか見えないように設定されています。（背景に重複しても、ボタンをおしたユーザーが一時的に重複するだけになっています。）
