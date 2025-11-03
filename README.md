# LLM2Grove

<img src="https://github.com/akita11/LLM2Grove/blob/main/LLM2Grove1.jpg" width="240px">

<img src="https://github.com/akita11/LLM2Grove/blob/main/LLM2Grove2.jpg" width="240px">

M5Stack社の[LLM Module](https://www.switch-science.com/products/10334)を、Groveコネクタ経由で使用できるようにするためのボードです。LLM Moduleにとりつけ、GroveケーブルでM5StackシリーズのPortCに接続して使用します。（オプションでI2C通信を行うためのPortA用コネクタを実装できるパターンを用意してあります）（※LLM Moduleのファームウエア書き換えやLAN接続を行うことはできません）


## 使い方（接続方法）

M5Stack社の[LLM Module](https://www.switch-science.com/products/10334)に本ボードをとりつけます（両者のどちらが上側でも構いません）

Groveコネクタ（PortC用）をM5Stackシリーズ等のマイコンのGroveポートに接続して、UIFlowやその他のLLM Module用のソフトウエアで使用します。

M5Stackシリーズの場合はPortCに接続すると、直接LLM Moduleをスタック接続した場合と同等に扱うことができます。その他のPortに接続する場合は、それに応じた通信(UARTのTXとRX)用のピンを使用してください。


## Author

Junichi Akita (@akita11) / akita@ifdl.jp
