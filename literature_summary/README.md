# 1064 nm激光光伏电池上传文献数据汇总

本次依据用户上传全文，核对出 **33篇不同论文**，另有3份重复上传文件。汇总为 **69条器件/测试条件记录**；同一论文的不同结数、样品、温度或测量方式分行，不能当作69项独立器件纪录。范围仅限本次上传文献，不代表该领域完整公开文献库。

- [下载Excel完整汇总（含5个工作表与批注，约51 KB）](https://github.com/ynyzzygm-cpu/ppt/raw/refs/heads/main/literature_summary/1064nm_literature_summary.xlsx)
- [下载PDF排版表（18页，约2 MB）](https://github.com/ynyzzygm-cpu/ppt/raw/refs/heads/main/literature_summary/1064nm_literature_summary.pdf)
- [查看完整Markdown表与文献目录](1064nm_literature_summary.md)
- [下载CSV数据表（UTF-8 BOM，可用Excel打开）](https://github.com/ynyzzygm-cpu/ppt/raw/refs/heads/main/literature_summary/1064nm_literature_summary.csv)
- [下载浏览器HTML表（保存后用浏览器打开）](https://github.com/ynyzzygm-cpu/ppt/raw/refs/heads/main/literature_summary/1064nm_literature_summary.html)
- [完整JSON数据、核对说明与定位摘录](1064nm_literature_data.json)

## 表格字段

主表保留参考图同样的11列：吸收层外延组分（基区/发射区）、衬底类型、结数、转换效率、辐照功率密度、辐照均匀性、波长、面积、连续/脉冲方式、研究机构、文献编号。

Excel另含“测试条件与核对”“文献目录_33篇”“原文证据定位”“说明与差异”。文献编号为本次重新编排的[1]—[33]，与参考截图编号不同。原文定位采用上传PDF文件内部页码，不一定等同于期刊页码。

## 引用时需要保留的区别

- 基区/发射区顺序统一；吸收层未给精确原子比例时保留材料名及已报告带隙，不凭带隙猜化学式。
- 直接激光效率、Xe模拟器换算的等效单色效率、理论模拟结果分开标注；温度、面积、均匀性及实际波长须一起引用。
- W与W/cm²不混用；所有面积换算和名义器件平均强度均明确标注。芯片面积、有效孔径、光敏面积和光斑面积分别说明。
- 单独标出1056、1070、1080 nm及1020 nm对照；[30]实际是1300/1550 nm模拟，[32]是DBR材料/电学研究，均不可列为1064 nm实验效率纪录。
- [5] RIT的39.8%对应单结参考器件；[6]/[14]四片平面串联为4×1J组件；[24] Fraunhofer 54.7%为等效单色效率。
- [22] Broadcom小芯片57.9%–59.0%的温度为20°C，参考截图“200°C”有误。
- [1]基区材料文字与结构图有矛盾；[26]个别组分不归一、[33]面积单位笔误保留在核对说明中。
- “未报告/未明确”表示上传全文缺乏足以确认的信息；不表示零值，不用其他论文或文件名补填。

整理日期：2026-11-04。本文只分享数据整理与少量定位摘录，未重新发布原论文全文。
