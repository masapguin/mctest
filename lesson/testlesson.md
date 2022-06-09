# Test Tutorial

## Step 1

まず、``||player:on chat||``ブロックを置き、<br>
チャットコマンドの指定を<br>
**run** に書き換えましょう。

#### ~ tutorialhint 
```blocks
player.onChat("run", function () {
})
```

## Step 2

次に、``||agent:move||``ブロックをドラッグして、<br>
``||player:on chat||``ブロックの中にドロップしましょう。

#### ~ tutorialhint 
```blocks
player.onChat("run", function () {
    agent.move(FORWARD, 1)
})
``` 

## Step 3

**エージェント** を2歩前進させたいので、
``||agent:move||``の中の歩数を **2** に変更します。 

#### ~ tutorialhint 
```blocks
player.onChat("run", function () {
    agent.move(FORWARD, 2)
})
``` 

## Finish!

右下の緑の実行ボタンを押してMinecraft に戻ったら<br>
**t** でチャットウィンドウを開き、チャットコマンド **run** と入力して <br>
Enterキーを押すことでプログラムを実行してみましょう。

#### ~ tutorialhint 
![Agent run](/static/minecraft_chat_run.png)
