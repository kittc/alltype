# alltype

当前已经支持 13 类查看器、49 个扩展名

**图纸查看器 · 支持的格式**
从一张 DXF 图纸到整块 PCB 的制造文件，从三维实体到扫描网格，都在同一个窗口里打开，不需要安装对应的 CAD 或 EDA 软件。

**二维工程图纸**
DXF、DWG。保留图层、线型与文字，中文与 GBK 编码自动识别；可开关图层、测量距离、角度与面积。

**三维 CAD 实体**
STEP（.step / .stp）、IGES（.igs / .iges）、BREP、Rhino 3DM。实体按原有颜色显示，支持装配结构、线框、剖切与视角旋转，可测量。

**通用三维网格**
STL、OBJ、glTF / GLB、PLY。适合快速查看扫描件、打印件与交换模型。

**建筑信息模型**
IFC。按项目—场地—建筑—楼层—构件展开结构树，点选查看构件属性，按楼层显隐与隔离。

**电子设计与 PCB 制造**

光绘与钻孔：Gerber（.gbr / .bgr / .ger / .pho / .art 及 gtl、gbl、gto、gbo、gts、gbs、gm1 各层后缀）、Excellon（.drl / .xln）
板级设计：KiCad .kicad_pcb、Altium .PcbDoc / .SchDoc、EAGLE .sch / .brd
工程与元件库：Altium .PrjPcb / .OutJob 文档清单，.PcbLib / .SchLib / .IntLib 类型识别
制造数据：ODB++（.odb / .tgz）
逐层显隐、网络高亮、元件清单与导出、板级距离测量；同目录或 ZIP 内的多层文件可作为一块板一次加载。

**文档与图像**
PDF（含 PDF 兼容的 Illustrator .ai）、PNG、JPG / JPEG、WebP、BMP、GIF、SVG。PDF 支持连续滚动、页面旋转、文本选择与全文查找；位图与矢量 SVG 支持缩放、拖拽平移与适配。

所有解析都在本机完成，内核随包内置，打开文件时既不联网，也不依赖原设计软件。
