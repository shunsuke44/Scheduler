# 工場のスケジューラアプリケーション
 工場の生産スケジューリングアプリケーションをCLIで作成しました。
 使用した言語はC++です。
## Development Environment
- Microsoft Visual Studio 2019
## Usage
```
./Scheduler.exe
```
プロンプトの例
```
*****    起動しました   *****
コマンドを入力してください
コマンドの使用法を見るには、"help"コマンドを入力してください
>>> help
< 各コマンドの動作 >
"print" : 登録した予定をカレンダー形式で表示    
"list" : 登録した予定を確認する
"delete" : listコマンドで表示した予定に対して、 
                指定した番号の予定を削除する    
"add" : 予定を追加する
"make template" : 予定を複数同時に登録するための
                テンプレートファイルを作成する  
"set" : テンプレートファイルから予定を登録する  
"clear" : 登録した予定をすべて削除する
"quit" : このプログラムを終了する
>>> quit
プログラムを終了します
```
## Commands
- `add`             : 予定を一つ追加する
- `make template`   : 予定を複数同時に登録するためのテンプレートファイルを作成する
- `set`             : テンプレートファイルの予定を追加
- `help`            : ヘルプを表示
- `list`            : 追加した予定のリストを表示
- `delete`          : listで表示した番号の予定を指定して削除
- `clear`           : 登録した予定をすべて削除する
- `quit`            : プログラムを終了する
