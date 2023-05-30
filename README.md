# uSheet

基于 LuckySheet 二次开发

## 更新

### 2023-05-30

- 新增: 插入/删除行或列的校验钩子函数
  1、insertCheck: (fn) => fn(true/false)
  2、deleteCheck: (fn) => fn(true/false)

### 2023-05-26

- 解决从 WPS 复制粘贴样式/错位 Bug;

### 2023-05-09

- 解决从 WPS 复制粘贴报错;
- 解决从 WPS 复制行/列宽高失效;
