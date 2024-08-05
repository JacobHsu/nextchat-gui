# Note

home.tsx

```js
function Screen() {
  //     TightBorder: "緊湊邊框",
  const shouldTightBorder = true; // getClientConfig()?.isApp || (config.tightBorder && !isMobileScreen); // 強制緊湊邊框 全螢幕
```

chat.tsx

```js
 <div className="window-header"
```

sidebar.tsx

```js
<div className={styles["sidebar-header-bar"]}>
```