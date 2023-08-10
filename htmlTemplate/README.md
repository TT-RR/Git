# メタ情報の記述
Visual Studio Code で`!`と入力して候補が表示されたら`Enter`を押すと、HTMLの雛形（スニペットの機能※）が入力されます。

```
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8" />
	<meta http-equiv="X-UA-Compatible" content="IE=edge" />
	<meta name="viewport" content="width=device-width, initial-scale=1.0" />
	<title>Document</title>
</head>
<body>
    
</body>
</html>
```
1.<html lang="en">を削除

2.<meta name="robots" content="noindex" /> を追加

 => 公開時に検索エンジンに表示されないようにする設定
 
3.<title>の内容を変更
