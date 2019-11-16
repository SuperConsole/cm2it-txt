**$git config user.name**  
 - userのnameを表示
 - user.email: email表示

**$git log**  
 -  過去のコミットを確認したいときに使おう

**$git git reset --hard HEAD^**  
 - --hard：ワークディレクトリの内容も書き換え
 - --soft：ワークディレクトリの内容はそのまま
 - HEAD^：直前のコミット
 - HEAD~{n} ：n個前のコミット
 - HEAD^やHEAD~{n}の代わりにコミットのハッシュ値OK
 
**$git revert \[commit_hash]**  
 - コミットの取り消し(逆向きコミット)
 
**$git commit --amend**
 - 直前のコミットに上書きできる
 - コミットメッセージの編集やケアレスミス修正にどうぞ
