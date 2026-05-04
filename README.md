## FT2232HL JTAG Adapter

### Function

Can be used as Xilinx JTAG downloader & USB-to-UART bridge simultaneously following [this](https://gist.github.com/rikka0w0/24b58b54473227502fa0334bbe75c3c1).

Partly pin-to-pin compatible with the CJMCU FT232HL(the purple PCB one) and has a standard 2x7 JTAG connector.

Main chips: FT2232HL(QFP64), ASM1117(3.3V, SOT89), 93LC56(SOP8).

Type-C(tested later so not shown on pic) connection.

Made with Kicad 10.0.

---

[こちら](https://gist.github.com/rikka0w0/24b58b54473227502fa0334bbe75c3c1)の手順に従い、Xilinx JTAG ダウンローダーと USB-UART ブリッジとして同時に使用できます。

CJMCU FT232HL（紫色の PCB）とほぼピン互換で、標準的な 2x7 JTAG コネクタを搭載しています。

主要チップ: FT2232HL(QFP64)、ASM1117(3.3V, SOT89)、93LC56(SOP8)。

Type-C 接続対応（後で検証済み、写真には未反映）。

KiCad 10.0 で設計。

#### Gallery

![](pic/1.png)

![](pic/sch.png)

![](pic/pcb.png)

![](pic/3d.png)

#### License

GPL-v3
