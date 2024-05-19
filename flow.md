# package.jsonの　 "react-scripts"が古いので書き換える
"react-scripts": "^5.0.1"













## Export ボタンが見つからない場合でも、以下の手順でプロジェクトを GitHub に手動でフォークすることができます。

プロジェクトをダウンロードする

CodeSandbox でプロジェクトを開き、左側のサイドバーにある「ファイルアイコン」（Explorer）をクリックします。
上部の「ファイルツリー」（例: src フォルダーなど）が表示されるエリアの上に、ダウンロードボタン（↓アイコン）がある場合があります。それをクリックしてプロジェクトを ZIP ファイルとしてダウンロードします。
プロジェクトを解凍する

ダウンロードした ZIP ファイルを解凍します。
GitHub に新しいリポジトリを作成する

GitHub にログインし、右上の「+」ボタンをクリックして「New repository」を選択します。
リポジトリ名や説明を入力し、「Create repository」をクリックします。
ローカルでリポジトリを設定する

ターミナルを開き、解凍したプロジェクトフォルダに移動します。以下のコマンドを実行します：
sh
コードをコピーする
cd path/to/unzipped/project
git init
git remote add origin https://github.com/username/repository.git
git add .
git commit -m "Initial commit"
git push -u origin master
ここで、path/to/unzipped/project は解凍したプロジェクトのパス、username は GitHub のユーザー名、repository は新しく作成したリポジトリ名です。
これで、CodeSandbox で作成したプロジェクトが GitHub にフォークされます。

