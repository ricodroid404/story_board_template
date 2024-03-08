# story_board_template
### Xcode14くらいから、新規プロジェクトを立ち上げた時に、ストーリーボードを選択できなくなったみたい。
### このリポジトリをクローンすると、Xcode15とか、最近のXcodeを使用していてもストーリーボードのプロジェクトを開くことができる😉

## 手順
- 本リポジトリをクローンする
```
git clone git@github.com:ricodroid404/story_board_template.git
```

- プロジェクトフォルダへ移動
```
cd story_board_template
```

- 任意のプロジェクト名に変更するためのシェルスクリプト(changeName.sh)を変更する
```
vim changeName.sh
```
**new_project_name="NewProjectName"** の　**NewProjectName** を、設定したいプロジェクト名に変更する
```
# 新しいプロジェクト名
# !!!!ここを変更したいプロジェクト名に変更してください!!!
new_project_name="NewProjectName"
```

- プロジェクト名を任意のプロジェクト名にするためにシェルを実行　（ **story_board_template** のままでOKなら、実行しなくて良い）
  ```
  chmod +x changeName.sh
  ```

- Xcodeでプロジェクトを開く

- ストーリーボードが使用できる新規プロジェクトが立ち上がっている 🚀🚀🚀🚀


