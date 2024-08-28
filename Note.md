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

BOT_HELLO
```js
  context.push(copiedHello);
```

```js
<div className={styles["chat-message-avatar"]}>
  {isUser ? ( <Avatar avatar={config.avatar} />

<div className={styles["chat-input-panel"]}>
  <ChatActions
```

```js
export function Chat() {
    return <_Chat key={sessionIndex}></_Chat>;
}

function _Chat() {
  const chatStore = useChatStore();
  const session = chatStore.currentSession();

  
  useEffect(() => {
    chatStore.updateCurrentSession((session) => {
          session.messages.forEach((m) => {

   // preview messages
  const renderMessages = useMemo(() => {
    [session.messages,]);

  const messages = useMemo(() => {
 }, [msgRenderIndex, renderMessages]);

```

sidebar.tsx

```js
<div className={styles["sidebar-header-bar"]}>
```

## NPM 

react-markdown  
[nanoid](https://www.npmjs.com/package/nanoid)


## store

```js
useChatStore = createPersistStore(

  newSession(mask?: Mask) {
  const session = createEmptySession();

```