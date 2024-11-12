# TODO

## 进行中
```dataviewjs
var pages = dv.pages('"成语"')
  .file.tasks.where(t => t.checked && t.text);
dv.taskList(pages)
```

## 待完成
```dataviewjs
var pages = dv.pages('"成语"')
  .file.tasks.where(t => !t.checked && t.text);
dv.taskList(pages)
```
