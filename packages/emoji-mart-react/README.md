# `@katherineheadshall/emoji-mart-react`

A React wrapper for [EmojiMart](https://missiveapp.com/open/emoji-mart).

## 🧑‍💻 Usage
```sh
npm install --save emoji-mart @katherineheadshall/emoji-mart-data @katherineheadshall/emoji-mart-react
```

```js
import data from '@katherineheadshall/emoji-mart-data'
import Picker from '@katherineheadshall/emoji-mart-react'

function App() {
  return (
    <Picker data={data} onEmojiSelect={console.log} />
  )
}
```

## 📚 Documentation
Original documentation by Missive: https://github.com/missive/emoji-mart#react
