echo "# HelloWord" >> README.md <br/>
git init <br/>
git add README.md <br/>
git commit -m "first commit" <br/>
git remote add origin https://github.com/YellowBull/HelloWord.git <br/>
git push -u origin master <br/>

每次都要输入密码很麻烦可以这样修改 <br/>
git remote remove origin <br/>
git remote add origin http://yourname:password@github.com/name/project.git <br/>
git push -u origin master <br/>
