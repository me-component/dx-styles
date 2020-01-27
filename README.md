# Установка
Стили для приложения 

старый вариант
```

$ npm install "git+ssh://cl-tfs2018.monitel.local:22/tfs/CK-11/WebDev/_git/WebStyles"

```
новый вариант с версионностью

```
npm install @me-component/dx-styles
```



---
## Добавить стили в приложения

для (scss, sass, less)

```
Меняем старый вариант
```scss
@import "~monitel-web-styles/devextreme/datagrid/index";
@import "~monitel-web-styles/default/scroll";
```
На новый
```scss
@import "~@me-component/dx-styles/devextreme/datagrid/index";
@import "~@me-component/dx-styles/default/scroll";
```