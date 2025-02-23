# Cooking Simulator Re:make - ブラウザで楽しむ料理シミュレーションゲーム！

## 概要
**Cooking Simulator Re:make** は、自由に料理を楽しむ **「サンドボックスモード」** と、お客さんの注文を満たしてお金を稼ぐ **「営業モード」** を備えた3D調理シミュレーションゲームです。Three.js と Cannon.js を活用し、ブラウザでリアルなキッチン体験を提供します。

- **開発者:** [Hayato040404]
- **バージョン:** 1.0.0
- **ライセンス:** MIT

---

## 特徴
- **豊富なメニュー:** 14種類以上のレシピ（例: Fried Rice, Chicken Curry, Creamy Pasta）
- **リアルな調理:** 切る、焼く、洗うなどのプロセスを時間とともに再現
- **キッチンアップグレード:** 稼いだお金で調理速度や器具を強化
- **モード選択:**
  - **Sandbox:** 自由に創作料理を楽しむ
  - **Business:** 注文を3分以内に達成し報酬を獲得
- **軽量化対応:**
  - **Normal:** エフェクト＆サウンドあり
  - **Lite:** 軽量モード

> **動作方法:** `index.html` をブラウザで開くだけで動作しますが、外部サウンドが読み込まれない場合があります。サーバー環境を推奨します。

---

## 使い方
### **サンドボックスモード**
1. 「Sandbox (Normal)」または「Sandbox (Lite)」を選択
2. 「Order」ボタンで食材を選び、キッチンに配置
3. 「Pick」でナイフや食材を持ち、調理（切る、焼くなど）
4. 「Place」で皿に盛り付け
5. 「Serve」で料理を評価

### **営業モード**
1. 「Business (Normal)」または「Business (Lite)」を選択
2. 「Start」で開始し、壁の注文ボードを確認（例: "Spaghetti"）
3. 「Order」で必要な食材を注文
4. 調理後、皿に盛り付け、「Serve」で注文を達成（**制限時間: 3分**）
5. 報酬（50円）を獲得し、「Shop」でキッチンをアップグレード

---

## ショップ（アップグレード）
| アップグレード | 価格 | 効果 |
|---|---|---|
| **Faster Cooking** | 100円 | 調理時間を1.5秒 → 1秒に短縮 |
| **Extra Plate** | 150円 | 皿を追加 |
| **Oven** | 200円 | オーブンを追加 |

---

## 動作環境
- **対応ブラウザ:** Chrome, Firefox, Edge（最新版推奨）
- **依存ライブラリ:**
  - [Three.js (r134)](https://cdnjs.cloudflare.com/ajax/libs/three.js/r134/three.min.js)
  - [Cannon.js (0.6.2)](https://cdnjs.cloudflare.com/ajax/libs/cannon.js/0.6.2/cannon.min.js)

---

## スクリーンショット
- **キッチン:** サンドボックスモードでのキッチン
- **注文ボード:** 営業モードの注文ボード

---

## コントリビューション
1. **このリポジトリをフォーク**
2. **ブランチを作成:**
   ```bash
   git checkout -b feature/あなたの機能
   ```
3. **変更をコミット:**
   ```bash
   git commit -m "あなたの変更"
   ```
4. **プッシュ:**
   ```bash
   git push origin feature/あなたの機能
   ```
5. **プルリクエストを作成**

> バグ報告や新機能提案は [Issues](../../issues) へお願いします。

---

## ライセンス
このプロジェクトは **MIT License** ([LICENSE](./LICENSE)) の下で公開されています。

---

## 謝辞
- **Three.js** と **Cannon.js** の開発者に感謝
- 「Cooking Simulator」にインスパイアされたプロジェクト
