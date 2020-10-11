# GitHub Pages入門

## GitHubとは
GitHubとは、ソフトウェア開発プロジェクトのための**ソースコード管理**サービスです。
公開されているソースコードの閲覧や簡単なバグ管理機能、SNSの機能を備えており、開発者にとって無くてはならないサービスです。

## GitHub Pagesとは
GitHubに保存したソースコードを実行し、**静的webサイトを公開できる無料サービス**です。
webサイトとして公開すると、URLを知っている人なら誰でもアクセスできます。
（普段のJavaScript講座では、自分のパソコンに保存してあるソースコードをブラウザで表示しているだけ）

# GitHub公開手順
## 1.GitHubのアカウント作成
下記ページを参考に、GitHubのアカウントを作成しましょう。
**ブラウザがchromeだと上手く作れない場合があるので、別ブラウザで作りましょう。**
<a href="https://note.com/snmal_jp/n/n3ef510a8181e">https://note.com/snmal_jp/n/n3ef510a8181e</a>

## 2.リポジトリ作成
**2.1 自分のリポジトリ（=ソースコードの貯蔵庫）を開く**

<img width="340" alt="your repositories" src="https://user-images.githubusercontent.com/41470674/95670895-17796e00-0bcc-11eb-9049-df08ea1906e9.png">

**2.2 NEWをクリックし、新たなリポジトリを作る**
<img width="1326" alt="new" src="https://user-images.githubusercontent.com/41470674/95670987-d2a20700-0bcc-11eb-86a2-5fe17f2fe599.png">
**2.3 リポジトリの名前（例 bmi）をつけて作成**
<img width="860" alt="create" src="https://user-images.githubusercontent.com/41470674/95670958-9b335a80-0bcc-11eb-8346-5b88a2b50c2c.png">

## 3.ファイルのアップロード
**3.1 自分のパソコンからファイル（html）をアップロードする**
<img width="948" alt="upload files" src="https://user-images.githubusercontent.com/41470674/95670972-b7cf9280-0bcc-11eb-982c-8d7b75f88006.png">

**3.2 「choose your files」をクリックし、アップロードするファイルを選択**
<img width="1309" alt="choose your files" src="https://user-images.githubusercontent.com/41470674/95670995-eb122180-0bcc-11eb-8c57-0efe7b4d3048.png">

**3.3 「Commit changes」をクリックし、アップロード完了**
<img width="605" alt="commit" src="https://user-images.githubusercontent.com/41470674/95671023-33314400-0bcd-11eb-9b8a-a7d6d78d65e2.png">

## 4.設定からGitHubPagesとして公開
**4.1 「Settings」をクリック**
<img width="1191" alt="settings" src="https://user-images.githubusercontent.com/41470674/95671035-50fea900-0bcd-11eb-8ea3-e354fa6f150e.png">

**4.2 「GitHub Pages」の「Source」をnoneから「main」に変更**
<img width="998" alt="main" src="https://user-images.githubusercontent.com/41470674/95671041-61168880-0bcd-11eb-905e-88862e646c32.png">

**4.3 「Save」をクリック**
<img width="900" alt="save" src="https://user-images.githubusercontent.com/41470674/95671044-6e337780-0bcd-11eb-806b-30766e092c2d.png">

**4.4 自動でサイトのURLが発行される**
<img width="867" alt="url" src="https://user-images.githubusercontent.com/41470674/95671050-83a8a180-0bcd-11eb-8078-6edf2150b5f7.png">

**これでサイトの公開は完了です！**
サイトが反映されるには20秒ほど時間がかかります。
404のエラーコードが返ってくる場合や、READMEがサイトに反映されてしまう（htmlが反映されない）場合は、5の手順に進みましょう。

## 5.htmlのファイル名を変更
**5.1 htmlファイルを選択**
<img width="1200" alt="select" src="https://user-images.githubusercontent.com/41470674/95671069-9de27f80-0bcd-11eb-8dcd-d6a4932d9e3d.png">

**5.2 「Edit」をクリックし、htmlファイルの編集画面にいく**
<img width="1309" alt="edit" src="https://user-images.githubusercontent.com/41470674/95671076-ab980500-0bcd-11eb-95cf-6ec1e5c665dd.png">

**5.3 ファイル名を「index.html」に変更（htmlのファイル名は基本indexにしておきましょう）**
<img width="508" alt="name" src="https://user-images.githubusercontent.com/41470674/95671081-b783c700-0bcd-11eb-91bc-8c52712852d2.png">

**5.4 「Commit changes」をクリックし、編集完了**

<img width="605" alt="commit" src="https://user-images.githubusercontent.com/41470674/95671085-c10d2f00-0bcd-11eb-9daa-b1ca7ebed8eb.png">

20秒ほど待って、サイトのURLにアクセスしてみましょう。
htmlファイルが表示されれば成功です！

## 補足
GitHub内でもコーディングできますが、Commitしてからサイトに反映されるのに20秒ほど時間がかかります。
JavaScript講座のようにVScodeでコーディングし、完成したものをGitHubにアップロードすることをお勧めします。
（自分のパソコンに保存しブラウザで開けば、すぐ反映されるので、手直しがしやすいため）

自分でhtmlファイルを公開すれば、自作サイトを作り放題！！
サイトのURLはメモしておくか、**READMEに記述しておきましょう！**

＜READMEに記述する方法＞
<img width="1116" alt="readme" src="https://user-images.githubusercontent.com/41470674/95671487-c28d2600-0bd2-11eb-8cfd-046d281b59e4.png">
