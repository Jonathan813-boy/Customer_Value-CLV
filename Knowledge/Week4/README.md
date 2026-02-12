# Week4 知识
1.折扣（Discounting）
* Present Value = Future Value / (1 + d)
（d = 月/年折扣率）

2.不同情况下的CLV计算公式
* 情况1：无限期、无折扣  
  CLV = S × R / (1 − R)
（S = 月/期边际贡献，R = 留存率）  
* 情况2：无限期、有折扣  
  CLV ≈ S × R / (1 + d − R)
 （d = 折扣率）
* 情况3：加入促销投入p（Promotion）  
  假设促销能提升边际贡献：S = S₀ + α × p  
  总CLV（未扣除促销成本）：CLV = (S₀ + α × p) × R / (1 + d − R)
  净CLV（扣除促销成本，无限期）：CLV_net = (S₀ + α × p) × R / (1 + d − R) − p / d  
* 情况4：加入CRM/关系管理投入q（Retention提升）  
  假设投入能提升留存率：R = R₀ + β × q  
  净CLV（需自行推导）
  CLV_net = S × (R₀ + β × q) / (1 + d − (R₀ + β × q)) − q / d
 （分母中R随q变化，需注意当R接近1时的敏感性）

3.如何处理异质性？
* 四大细分维度
  Geographic（地理）、Demographic（人口统计）、Psychographic（心理）、Behavioural（行为）
* 流程:  
  对每个细分群体分别估算S和R  
  计算该群体的CLV  
  决定（哪些群体值得重点投入（高CLV）？ 对哪些群体减少促销/CRM投入（低CLV）？ 差异化营销策略（定价、促销、保留政策）？）
  
