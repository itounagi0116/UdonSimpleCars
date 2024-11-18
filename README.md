# UdonSimpleCars  
WheelCollider を使用したシンプルなドライバーシステムです。同期可能でコード不要な設定が可能です。

![image](https://user-images.githubusercontent.com/2088693/137936901-bdcb12c5-6d77-4162-a128-6690c99b9884.png)

使用方法は `Assets/UdonSimpleCars/SampleAssets/UdonSimpleCar.prefab` をご確認ください。

---

## はじめに  

1. **VRChat Creator Companion** を使用して、UdonSharpを含むVRChatワールド用Unityプロジェクトを作成します。  
2. Unityプロジェクトを開きます。  
3. メニューの「Window」→「Package Manager」を開きます。  
4. 「+」ボタンをクリックし、`Add package from git URL` を選択します。  
5. 以下のURLを入力して「Add」ボタンをクリックしてください：  
   - 通常版: `git+https://github.com/esnya/UdonSimpleCars.git?path=/Packages/com.nekometer.esnya.udon-simple-cars`  
   - ベータ版: `git+https://github.com/esnya/UdonSimpleCars.git?path=/Packages/com.nekometer.esnya.udon-simple-cars#beta`  

---

## サンプルアセットのライセンス  
### [Engine-loop heavy vehicle/tank](https://opengameart.org/content/engine-loop-heavy-vehicletank)  
- ライセンス: [CC-BY 3.0](https://creativecommons.org/licenses/by/3.0/)  
- 作者: Nayckron

---

### 追加資料(整備中)
以下に、 **このスクリプトの機能** の簡単な説明を追加しています(LLMを用いて作成している為その点はご留意下さい)

| **スクリプト名**               | **説明**                                                                                                                                  |
|--------------------------------|------------------------------------------------------------------------------------------------------------------------------------------|
| **Editor**                     |                                                                                                                                          |
| USC_CarEditor.cs               | 車両設定を行うためのUnityエディタ拡張。                                                                                                   |
| USC_EditorUtilities.cs         | エディタユーティリティ関数を提供。                                                                                                       |
| USC_Layers.cs                  | レイヤー設定を簡略化するスクリプト。                                                                                                     |
| **Scripts - Accesories**       |                                                                                                                                          |
| SpeedIndicator.cs              | 車両の速度を表示するインジケーターを制御。                                                                                               |
| **Scripts - Core**             |                                                                                                                                          |
| USC_BoardingCollider.cs        | 車両への搭乗を制御するコライダー設定。                                                                                                   |
| USC_Car.cs                     | 車両の物理動作やインタラクション全般を管理するメインスクリプト。                                                                         |
| USC_CenterOfMass.cs            | 車両の重心位置を設定するためのスクリプト。                                                                                               |
| USC_RecoveryStation.cs         | リカバリーステーション（復帰ポイント）を制御。                                                                                           |
| USC_Respawner.cs               | 車両をリスポーンさせる機能を提供。                                                                                                       |
| USC_Seat.cs                    | 車両内の座席の機能や調整を行うスクリプト。                                                                                               |
| **Scripts - Towing**           |                                                                                                                                          |
| USC_HandPusher.cs              | 車両を手で押すための機能を提供するスクリプト。                                                                                           |
| USC_RemotePusher.cs            | 遠隔で車両を押す機能を提供。                                                                                                            |
| USC_TowingAnchor.cs            | トーイング（牽引）の起点となるアンカーを設定するスクリプト。                                                                             |
| USC_TowingJoint.cs             | トーイングジョイントの動作を制御。                                                                                                       |
| **Scripts - Utilities**        |                                                                                                                                          |
| USC_RigidbodyEventDispatcher.cs | Rigidbodyのイベントを管理するためのユーティリティスクリプト。                                                                           |

