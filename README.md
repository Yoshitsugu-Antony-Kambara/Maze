# Maze
### これだけは抑えておくポイント  <br>

### Swiftの⾔語特性  <br>
加速度センサーを使用するために、まずはCoreMotionというライブラリを宣言しないといけない  <br>

加速度の取得(※イマイチ掴めなかった...)
```swift

        let handler: CMAccelerometerHandler = {(CMAccelerometerData: CMAccelerometerData?, error: Error?) -> Void in
            self.speedX += CMAccelerometerData!.acceleration.x
            self.speedY += CMAccelerometerData!.acceleration.y
```
### エラーが起きたところ・起きそうなところ <br>

### 原因  <br>


### 解決⽅法
