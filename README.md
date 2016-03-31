# pdf2excel

### 批量将pdf转换成excel

转换服务由 https://smallpdf.com/cn/pdf-to-excel 提供。增加批量转换功能。

### 如何运行？

在 Unix 上执行，前提是已经安装好 npm 和 nodejs

```bash
git clone https://github.com/hanxi/pdf2excel.git
cd pdf2excel
npm install
chmod a+x pdf2excel
./pdf2excel -i pdfdir -o exceldir
```

其中 pdfdir 用于存放将要转换的 pdf 文件， 转换后的 excel 文件存放在 exceldir 中
