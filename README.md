# Excel 数据生成与转换工具

这是一个 Python 脚本，用于生成一个简单的 Pandas DataFrame，导出为 Excel 文件（包含公式），并将 Excel 文件转换为 PDF。项目适用于 Linux 平台。

## 依赖

在运行脚本之前，请确保安装以下依赖：

```shell
pip install pandas openpyxl
```

在 Linux 系统上安装 LibreOffice，例如在 Ubuntu 上：

```shell
sudo apt-get install libreoffice
```

## 使用方法

在终端运行脚本：

```shell
python excel_to_pdf.py
```

运行后，当前目录会生成以下文件：

- simple_dataframe.xlsx：包含 DataFrame 和公式的 Excel 文件。
- simple_dataframe.pdf：Excel 文件的 PDF 版本。

