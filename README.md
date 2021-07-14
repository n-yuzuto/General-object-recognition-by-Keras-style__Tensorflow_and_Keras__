# General-object-recognition-by-Keras-style__Tensorflow_and_Keras__

Kerasを用いて、一般物体認識を行いました。  
今回はデータに一般物体認識のデータセット[CIFAR-10]を利用しました。  
CNNで一般物体認識を行いました。構造をディープにしましたが、あまり良い結果は得られませんでした。  

ネットワークの構築は、モデルの構築の実行結果を見てください。 

今回はepoch数を30とし、早期終了を行うEarlyStoppingを生成しましたが、実行する際に、ストップすることはありませんでした。  

【考察】  
精度、損失とも、訓練データは学習回数と共に改善されていますが、検証データの精度は、30回付近からほとんど変化していません。一方、損失も30回
付近からほぼ横ばいです。いずれにしても、訓練データのグラフから徐々に離されているので、オーバーフィッティングが起きてしまっていることが分かります。

***
.ipynbファイルが開かれない時は、こちらのリンクにURLを貼ってご覧になってください。  
[nbviewer](https://nbviewer.jupyter.org/)
