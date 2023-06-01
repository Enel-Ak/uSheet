# uSheet

基于 LuckySheet 二次开发

## 更新

### 2023-06-01

- feat: initCompleted 初始化完成钩子

### 2023-05-30

- feat: 插入/删除行或列的校验钩子
- feat: insertCheck: (type, index, value, direction, sheetIndex, fn) => fn(true/false)
- feat: deleteCheck: (type, index, value, direction, sheetIndex, fn) => fn(true/false)

### 2023-05-26

- fix: 从 WPS 复制粘贴样式/错位 Bug;

### 2023-05-09

- fix: 从 WPS 复制粘贴报错;
- fix: 从 WPS 复制行/列宽高失效;
