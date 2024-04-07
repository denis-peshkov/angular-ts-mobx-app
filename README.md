# angular-ts-mobx-app
How to create a Angular + TypeScript + MobX


## initial work

### установить angular-cli
```
$ npm install -g npm@10.5.1
$ npm install -g @angular/cli
```

### создать проект
```
$ ng new angular-ts-mobx-app --routing=false --style=scss --ssr=false --strict=true --routing=true --package-manager=yarn
$ cd angular-ts-mobx-app/
```

### обновляем .gitignore
```diff
# Node
/node_modules
-npm-debug.log
-yarn-error.log
+
+# css
+*.css
+
+# yarn
+yarn.lock
+yarn-debug.log*
+yarn-error.log*
+
+# npm
+package-lock.json
+npm-debug.log*
```
