# ClusTimesViewer

# お知らせ
近日中に記事の保管サーバーの移行が検討されているため、ギミックのアップデートが今後必要になる可能性があります

ClusTimes を設置してくれてありがとうございます

ClusTimesは、clusterのユーザー有志による草の根新聞メディアです。 このClusTimes Viewerをワールドに設置すると、自動的にClusTimesの最新版を読み込み、ワールドで記事を表示します。 

ファイルは以下からダウンロードしてください。

https://github.com/Dolphiiiin/ClusTimesViewer/releases

# ClusTimes-Viewerの設置方法

 - [project foloder] `Asset/prefabs/`にある、ClusTimes Viewerを設置  
 
![](https://cdn.discordapp.com/attachments/681123942676561950/842705078535585852/unknown.png)

 - 設置したClusTimes Viewer内のClusTimes Positionによって、モニターの位置を変更できます
> 裏面は透明になっています

もしもモニターの位置がおかしい、表示されない時には、
`PlayerLocalUI/SafeArea`内にある`ClusTimes - LocalUI`のインスペクターから、
各ConstraintのZeroボタンを押してください  
![](https://cdn.discordapp.com/attachments/681123942676561950/842660098677538857/settransformobject.png)

モニタは、コントローラのボタンを押した後に表示されます。モニタは、個々のユーザーにしか見えないように設定されています。（背景に重複しても、ボタンをおしたユーザーが一時的に重複するだけになっています。）
