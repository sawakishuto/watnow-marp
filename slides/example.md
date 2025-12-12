---
marp: true
theme: default
paginate: true
header: "watnow Presentation"
footer: "© 2025 watnow"
---

# Welcome to Marp! 🎉

**マークダウンでプレゼンテーションを作ろう**

---

## Marp とは？

- マークダウンでスライドを作成できるツール
- `---` で新しいスライドを区切る
- シンプルで使いやすい

---

## 基本的な書き方

### テキストの装飾

- **太字** は `**太字**`
- _斜体_ は `*斜体*`
- ~~取り消し線~~ は `~~取り消し線~~`

---

## コードの表示

```javascript
const hello = () => {
  console.log("Hello, Marp!");
};
```

シンタックスハイライトも対応！

---

## リストの表示

### 順序なしリスト

- アイテム 1
- アイテム 2
- アイテム 3

### 順序付きリスト

1. 最初のステップ
2. 次のステップ
3. 最後のステップ

---

## 画像の挿入

```markdown
![width:300px](./images/sample.png)
```

サイズ指定も簡単！

---

## 2 カラムレイアウト

<div class="columns">
<div>

### 左カラム

- 項目 A
- 項目 B

</div>
<div>

### 右カラム

- 項目 C
- 項目 D

</div>
</div>

<style scoped>
.columns { display: flex; gap: 2rem; }
.columns > div { flex: 1; }
</style>

---

<!-- _class: lead -->

# Thank you! 🙌

質問はありますか？

---

## 参考リンク

- [Marp 公式サイト](https://marp.app/)
- [Marp CLI](https://github.com/marp-team/marp-cli)
- [Marpit Framework](https://marpit.marp.app/)
