# Excel 企业级模板库

25 个可直接下载使用的 Excel 成品模板：数据与展示分离，关键数字全部是公式，含原生图表、结构化表与命名区域。每本附"Copilot 提示词"页与可粘贴进 Power Query 高级编辑器的 M 代码页。

## 文件一览

| 文件 | 内容 |
|---|---|
| [00-enterprise-multi-view-model.xlsx](00-enterprise-multi-view-model.xlsx) | 企业级多视图总示例工作簿：30 张表 + Copilot 提示词 + Power Query 脚本，六层架构，一套数据贯穿全书 |
| [01-ceo-dashboard.xlsx](01-ceo-dashboard.xlsx) | CEO 驾驶舱 YTD Dec 2024：损益表、6 张 KPI 卡、eNPS/CSAT、销售与人力成本 |
| [02-gantt-chart.xlsx](02-gantt-chart.xlsx) | 甘特图 Example Project：任务表 + 条件格式甘特条 + 堆积条形图版甘特 |
| [03-kanban-board.xlsx](03-kanban-board.xlsx) | 看板：任务数据库 + 五列看板，改状态自动联动 |
| [04-health-cross-analysis.xlsx](04-health-cross-analysis.xlsx) | 健康状况交叉分析：6 病种 × 7 年龄段百分比热力图，合计 55,500 |
| [05-chart-gallery.xlsx](05-chart-gallery.xlsx) | 图表模板库：11 种原生图表，各配示例数据与适用场景 |
| [06-smartart-hierarchy.xlsx](06-smartart-hierarchy.xlsx) | SmartArt 层级图：项目规划树 12 节点 + 层级数据表 |
| [07-executives-dashboard.xlsx](07-executives-dashboard.xlsx) | 高管驾驶舱：财务 KPI、运营指标、7 张图表 |
| [08-strategy-map.xlsx](08-strategy-map.xlsx) | 战略地图：平衡计分卡四层，13 个目标，14 条因果箭头 |
| [09-kpi-dashboard.xlsx](09-kpi-dashboard.xlsx) | KPI 驾驶舱：地区销售、KPI 卡、季度图、收入预测、环形图 |
| [10-sales-funnel.xlsx](10-sales-funnel.xlsx) | 销售漏斗：线索到成交转化率与流失率 |
| [11-variance-analysis.xlsx](11-variance-analysis.xlsx) | 预算差异分析：预算 vs 实际、差异额与差异率 |
| [12-forecast-model.xlsx](12-forecast-model.xlsx) | 收入预测：历史实际 + 预测 + 目标区间 + 预测误差 |
| [13-calendar-schedule.xlsx](13-calendar-schedule.xlsx) | 月度排班日历：月视图排班 + 任务截止提醒 |
| [14-inventory-management.xlsx](14-inventory-management.xlsx) | 库存管理：入库出库结存、安全库存预警、周转率 |
| [15-crm-card-view.xlsx](15-crm-card-view.xlsx) | 客户管理卡片：客户卡片区 + 明细表 + 价值分级 |
| [16-project-timeline.xlsx](16-project-timeline.xlsx) | 项目时间线：里程碑时间线 + 计划 vs 实际 |
| [17-risk-matrix.xlsx](17-risk-matrix.xlsx) | 风险矩阵：概率 × 影响 5×5 热力图 + 风险清单 |
| [18-employee-ranking.xlsx](18-employee-ranking.xlsx) | 员工绩效排名：排名、业绩、增长率、目标达成率 |
| [19-expense-workflow.xlsx](19-expense-workflow.xlsx) | 费用报销流程：申请到报销全流程状态跟踪 |
| [20-data-entry-form.xlsx](20-data-entry-form.xlsx) | 数据录入表单：结构化录入区 + 数据验证 + 必填校验 |
| [21-org-tree.xlsx](21-org-tree.xlsx) | 组织架构树：5 部门 12 小组 47 编制 |
| [22-geographic-sales.xlsx](22-geographic-sales.xlsx) | 地理销售分布：12 城销售、达成率、客户数 |
| [23-comparison-analysis.xlsx](23-comparison-analysis.xlsx) | 对比分析：年度对比、同比、预算完成率 |
| [24-city-operations-dashboard.xlsx](24-city-operations-dashboard.xlsx) | 城市运营经营驾驶舱：KPI 卡、客户等级分布、开发进度、运营效率、成本趋势、服务质量、项目进度、城市概况 12 项、路线图、KPI 与服务评审 |

每本的预览图在 [preview/](preview/) 目录下。

## 使用说明

- 打开后先看"使用说明"页：黄色单元格为输入，白色单元格为公式，只改黄色格。
- 所有数字均为示例数据，使用前替换为真实数据。
- 适用 Excel 365 / 网页版 Excel；LibreOffice 可打开，XLOOKUP、LET、UNIQUE、SORT、FILTER 等新函数在 LibreOffice 下显示 #NAME?，live 值已用兼容公式兜底。
- Power Query 脚本以文本页形式附在每本中，复制进高级编辑器即可使用，未伪造原生 PQ 连接；M 代码与 Copilot 提示词未在真实 Excel 内执行验证。

## 诚实说明

- 01 号 CEO 驾驶舱：截图原数字自相矛盾（按截图的数算净利润应为 392,834，不是截图写的 658,835），文件按公式计算并在说明页写清了修正。
- 07 号高管驾驶舱：截图文字多为 AI 生成乱码，未照抄，按合理经营数据重编。
- 24 号城市驾驶舱：城市名称、成本、客户样本、项目与问题清单均为示例数据。
