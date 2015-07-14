Unity5 Effects
============

Unity5 用に書いたエフェクト置き場。現在あるもの：  

### Temporal Screen Space Reflections
![alt text](doc/ScreenSpaceReflections.png)  
[パッケージ](Packages/ScreenSpaceReflections.unitypackage)  
スクリーンスペース反射です。  
kode80 氏が[似たようなもの](https://github.com/kode80/kode80SSR)を公開していますが、そちらとはアルゴリズムが違い、
若干残像が出てしまう欠点があるものの、圧倒的に高速でクオリティも引けを取りません。  
実装の詳細に興味があれば[こちらの記事](http://i-saint.hatenablog.com/entry/2014/12/05/174706)もどうぞ。
また、上記スクリーンショットの背景は[こちら](https://github.com/i-saint/RaymarchingOnUnity5)の Raymarcher によるものです。

#### モザイク
![alt text](doc/mosaic.gif)  
[パッケージ](Packages/Mosaic.unitypackage)  
指定オブジェクトをモザイク領域化するシェーダです。


<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
