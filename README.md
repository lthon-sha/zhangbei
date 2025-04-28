Excel 数据生成与转换工具
项目概述
这是一个 Python 脚本，用于生成一个简单的 Pandas DataFrame，导出为 Excel 文件（包含公式），并将 Excel 文件转换为 PDF。项目适用于 Linux 平台。
功能

创建一个简单的 3x3 DataFrame，包含列 A、B、C。
在列 Sum_A_B 中添加公式，计算 A 和 B 的和。
将 DataFrame 导出为格式优化的 Excel 文件。
使用 LibreOffice 将 Excel 文件转换为 PDF。

依赖
在运行脚本之前，请确保安装以下依赖：
Python 库
pip install pandas openpyxl

LibreOffice
在 Linux 系统上安装 LibreOffice，例如在 Ubuntu 上：
sudo apt-get install libreoffice

使用方法

确保已安装上述依赖。
将脚本保存为 excel_to_pdf.py。
在终端运行脚本：python excel_to_pdf.py


运行后，当前目录会生成以下文件：
simple_dataframe.xlsx：包含 DataFrame 和公式的 Excel 文件。
simple_dataframe.pdf：Excel 文件的 PDF 版本。



输出示例
生成的 Excel 文件将包含以下内容：

列 A、B、C：原始数据。
列 Sum_A_B：计算公式 =A + B 的结果。
列宽已自动调整以提高可读性。

注意事项

确保 LibreOffice 已正确安装且可在命令行中访问。
脚本运行需要 Linux 环境。


