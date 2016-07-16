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
