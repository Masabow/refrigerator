# ユーザアカウントの追加

MeteorはログインのUIによる複数ユーザアカウントシステムを数分で取り入れることができます

アカウントシステムとUIを有効にするには
関連するパッケージを導入する必要があります
```Bash
meteor add accounts-ui accounts-password
```

HTML内で下記のようにしてログインボタンを設定します

```html imports/ui/body.html
Hide Completed Tasks
</label>
 
{{> loginButtons}}
 
<form class="new-task">
    <input type="text" name="text" placeholder="Type to add new tasks" />
</form>
```