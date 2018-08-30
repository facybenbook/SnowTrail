# Snow Trail

スクリプトを使用せず、シェーダーとレンダーテクスチャーを用いて作成したSnow Trailです。オブジェクトが雪（用意したplane）のなかを通過するとその部分がかき分けられていきます。  
    
カメラのデプスをレンダーテクスチャーに焼き付け、それをシェーダーで読み込むことで頂点の押し下げを行っています。シェーダーでテッセレーションを行えるようにしてあるので、ポリゴンの少ないplaneでもあるていどそれっぽく見えます。(Unity5.6.3p1で作成しました)      

詳しくはコチラの[動画](https://streamable.com/yourv "RSnow Trail")を見てください。
