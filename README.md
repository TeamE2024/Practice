<h1>Git Bashを使って初期設定をしよう</h1> 
　<ul>
   <li>Git for windowsをインストールしたら cmdを起動してgit --version を打つ。　git version 2.46.0.windows.1のように表示されたらOK</li>
   <li>Git Bashを開いて、すべてのリポジトリにかかるグローバル設定でユーザIDを設定をします。本来はメールアドレスも入れるけど今回は名前だけ。<br>
   git config --global user.name "Mariko"<br>
   git config --listで確認。</li>
 </ul>

 <br>
 <h1>Git Bashでディレクトリを作って、git リポジトリを初期化しよう</h1>
 <ul>
    <li>このリポジトリをクローンして、ローカルリポジトリを作成しよう</li>
   <li>「mkdir フォルダ名」でディレクトリを作成する。(mkdirはLinuxコマンドでmake directory)　今後ここを作業場として使用し、ローカルリポジトリに繋ぎます</li>
  <li>「cd フォルダ名」でディレクトリに移動</li>
     <li>「touch index.html」で先ほど作成したディレクトリの中にindex.htmlファイルを作成する</li>
        <li>「git init」でリポジトリ初期化。ブランチが作成されます</li>
           <li>「git status」で状態を確認しよう。詳細はぱわぽ見てね</li>
 </ul>
 <br>

 <h1>Gitで操作してみよう</h1>
 ぱわぽを見ながらgit addやgit statusを試してみよう<br>
 git addでstagingしたファイルはgit rm --cached ファイル名でステージングツリーから削除しよう<br>
 commit してローカルリポジトリに変更を反映しよう。詳細はぱわぽ参照！コミットする際は必ず-mオプションでメッセージをつけること<br>
メッセージを付けずにcommitだけするとどうなるかも見てみよう　ついでにnano editorも調べてみよう<br>
<br>

<h1>branchを作ってみよう</h1>
ぱわぽを見ながらブランチの作成し、自分が作成したブランチに移動してみよう<br>
<br>

<h1>プルリクエストとマージをやってみよう</h1>
パワポ見ながらやってみよー<br>
同じファイルの同じ部分を複数人で編集したらどうなるか確認してみよう<br>
git pullでリモートリポジトリの最新状態を取ってきて、人のコードを自分のローカルリポジトリに反映してみよう
