# my-game-archive
今までUnityで作成したゲームについてまとめました。

## AIエアーホッケーゲーム
<img width="2400" height="1080" alt="AI対戦ホッケーゲーム" src="https://github.com/user-attachments/assets/37242b19-0755-434c-9920-298d5002f6b1" />

Unityの拡張機能ml-agentを使用して、自己対戦 (Self-Play)でエアーホッケーの対戦相手を作成しました
agent同士だと実力は拮抗していましたが、片方を人間が操作するには難易度が高すぎたので、agent側の動きを遅くすることで難易度を下げました
他にも以下の自然環境と融合したギミックを追加しました
一定の点数に達したことで降りてきた球体に触ると、動物が登場し、ギミックが作動するようになっています。
パッドが倍増したり、サイズが変わったり、ゴールの幅を狭めたりします。

## Fishusse
<img width="1173" height="702" alt="image" src="https://github.com/user-attachments/assets/469aa738-b14d-4d7c-9435-db765c8a247c" />

学部のC言語授業の延長線上で2048ゲームを作成してたのが原型です。その後、サークル内のゲームジャムをきっかけに本作を考案しました。
魚の出世と2048の数字の増加を対応させるというコンセプトです。
海の中という環境を生かし、ランダムに発生するサメが魚を食べるギミックを追加しました。
UnityのUIについてや、動かし方、他基礎的なことを学習することの一環で作成したものです。

参考：
https://youtu.be/mSO1a-KjSs8?si=uIhQ-KddbUvljQ-i

## ヘカちゃんの大冒険
<img width="2400" height="1080" alt="ヘカちゃんの大冒険" src="https://github.com/user-attachments/assets/aaf472f1-55f0-49be-b4fe-edc87ed57b46" />

Unityの2Dアクション向けフリーアセット
現実世界と闇の世界を行き来することにより、コースの謎を解いていくというコンセプトのもと作成しました。
動く床やプレイヤーの重力を変えるなどのギミックを導入しました。
このゲームはUnityの基礎講習で講師をした延長上で作成したもので、大学祭に合わせて動画の公開を行いました。

大学祭では小さい子供に多く遊んでもらいました。しかし、ギミックの理解が困難であったことや、地面に埋まるバグ、操作性などの課題が判明しました。
翌年の大学祭では難易度を下げたり、バグの修正をしたことで、ゴールまで行くプレイヤーが多くなりました。

参考：
・南山公認サークル「Multi Creaters Club」のYouTubeより
https://youtube.com/shorts/gMWRm1k_7Zo?si=4oaGhUtfsjBY_ywl

・アセット
https://assetstore.unity.com/packages/2d/environments/free-platform-game-assets-85838

## 石臼のシミュレーション
<img width="1177" height="532" alt="image" src="https://github.com/user-attachments/assets/3c480b05-4014-44fc-934c-4b8047422e8e" />

石臼でそば粉を砕く様子を見かけて、物理シミュレーションで実装してみたいと思い、作成しました。
穴の開いたオブジェクトの当たり判定の実装方法を調べることで実現できました。
物理シミュレーションの実装経験を積む良い機会になりました。

参考：
https://youtu.be/6j4CeQ7zFw0?si=TcgCdN40L8xaJYDq
