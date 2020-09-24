# Test to run tic-tac-toe game on Air for Android.

**DEMO**  
[https://evofan.github.io/as_test_tictactoe/index.html](https://evofan.github.io/as_test_tictactoe/index.html)  

Android 8.0.0(use .apk file)  
![https://raw.githubusercontent.com/evofan/as_test_tictactoe/master/screenshot/pic_on_android.png](https://raw.githubusercontent.com/evofan/as_test_tictactoe/master/screenshot/pic_on_android.png "image")  

PC(use .swf file)  
![https://raw.githubusercontent.com/evofan/as_test_tictactoe/master/screenshot/pic_on_pc.png](https://raw.githubusercontent.com/evofan/as_test_tictactoe/master/screenshot/pic_on_pc.png "image")  

10年位前にAir for Android書き出しで作った三目並べのゲーム。
当時のver.は、Androidは2.3.x、Airは3.2ぐらいだったと思う。

昔のファイルを整理してたら出てきて、手元のスマホで試したらそのまま動いてビックリ。  
（スマホにAirが入ってないのでインストール促されるのと、アプリに署名の証明書が無いのでセキュリティの警告が出る）  

AS3.0なので外部化した記憶があるが、これは内部にスクリプトが書いてある。  
状態遷移（State Pattern）でゲームの進行しているが、中の記述は綺麗とは言えない。  
折角なので時間見てTypeScript(JavaScript) + WebGL(Canvas)で書き直すかしてみたい。  
PC版も今年でChromeのflash playerサポートが終わるので、見れなくなるだろうし。  
