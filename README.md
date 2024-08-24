## Newly Launched ZPL Viewer Tool Website

Hello everyone!

In our work, we often need to design and preview ZPL (Zebra Programming Language) files. Previously, I used tools like ZPL Design, but I thought an online tool would be more convenient. So, I took some time to develop an online ZPL preview tool, hoping it can help those with similar needs.

### Website Features

The newly launched ZPL Viewer website (address: [https://zplpreview.com](https://zplpreview.com)) offers the following features:

- **Online ZPL File Preview**: Preview ZPL files directly in your browser to ensure labels and barcodes are correctly formatted before printing.
- **ZPL Conversion Tools**:
  - **HTML to ZPL**
  - **PDF to ZPL**
  - **Image to ZPL**
- **Download Features**:
  - Convert the previewed ZPL to an image or PDF file for download.

### How to Use

#### Online ZPL Preview

1. Open the website: [https://zplpreview.com](https://zplpreview.com)
2. Enter or paste the ZPL code into the text area.
3. Select print density: 6 dpmm (152 dpi), 8 dpmm (203 dpi), 12 dpmm (300 dpi), 24 dpmm (600 dpi).
4. Click the "Preview" button to view the result.

#### Sample Code

```zpl
^XA
^FO50,50
^A0N,50,50
^FDShipping Label^FS

^FO50,120
^A0N,35,35
^FDRandom Tracking #: 123456789^FS

^FO50,170
^A0N,35,35
^FDRecipient: John Doe^FS

^FO50,220
^A0N,35,35
^FDDelivery Address: 123 Main St, Anytown, USA^FS

^FO50,270
^A0N,35,35
^FDCity: Anytown^FS

^FO50,320
^A0N,35,35
^FDState: NY^FS

^FO50,370
^A0N,35,35
^FDZip Code: 12345^FS

^FO50,420
^GB500,3,3^FS

^FO100,440
^A0N,35,35
^FDItem Details:^FS

^FO100,480
^GB480,240,3^FS

^FO120,500
^A0N,30,30
^FD1. Item1^FS

^FO120,600
^A0N,30,30
^FDQty: 1^FS

^FO260,500
^A0N,30,30
^FD2. Item2^FS

^FO260,550
^A0N,30,30
^ Ut ^FS

^FO260,600
^A0N,30,30
^FDQty: 2^FS

^FO400,500
^A0N,30,30
^FD3. Item3 ^FS

^FO400,550
^A0N,30,30
^Duis.^FS

^FO400,600
^A0N,30,30
^FDQty: 3^FS

^XZ
```

I hope everyone can try it out and provide feedback to help us continuously improve this tool. If you have any questions or suggestions, please feel free to contact me.

Thank you all for your support!

---

Feel free to visit and try it out: [https://zplpreview.com](https://zplpreview.com)

© 2024 ZPL Viewer. All rights reserved.
