#Git
- マージする  

```sh
git checkout -b [new_branchname]
git add [filename]
git commit -m "[commit message]"
git checkout [マージ先のブランチ]
git merge [マージ元のブランチ]
```

- 一かたまりずつaddする  

 ```sh
 git add -p [filename]
 ```
 sを選択するとスプリット選択できる

- push

 ```sh
 git remote add origin git@github.com:hogehoge
 git push origin master
 ```

- tig  
 コミットがグラフィカルに見える

 ```sh
 tig
 ```
