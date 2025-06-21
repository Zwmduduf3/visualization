# Early Childhood Education & Developmental Vulnerability Analysis | 早期教育与儿童发展脆弱性分析

## 项目概述
本仓库包含为澳大利亚教育部开展的关于早期教育服务与儿童发展脆弱性的综合分析，覆盖全澳各地方政府区域（LGA），整合以下数据：
- AEDC数据（儿童发展脆弱性指标）
- 学前教育入学记录
- 教育服务质量评级
- Google评论情感分析

## 核心研究问题
- 高脆弱性区域：识别DV2（两个及以上领域脆弱）比例最高的LGA及其社会经济-地理特征。
- 领域差异：分析不同社会经济水平（SEIFA）下5大AEDC领域的脆弱性差异。
- 服务分布：评估教育服务数量/质量与儿童发展结果的空间匹配度。
- 政策缺口：揭示脆弱区域的服务可及性短板。
- 公众反馈：基于10,000+条Google评论的NLP语义聚类分析。

## 核心发现
**1. 空间差异**
- DV2比例最高的10个LGA（>70%）多为偏远原住民地区（如Tiwi群岛）。
- 极偏远地区DV2发生率是主要城市的3倍（17% vs 5%）。

**2. 服务质量悖论**
- ACT地区41.5%服务获"Exceeding NQS"评级，而NT仅6.4%。
- 高质量服务与语言/认知能力改善无显著相关性（r≈0.17）。

**3. 服务容量缺口**
- 高容量LGA反而呈现更高DV1/DV2，表明数量≠质量。

**4. 公众评论分析**
- 高DV1地区评论聚焦资源短缺（如"等待更久"、"稀缺名额"）。
- 低DV1地区高频词为情感关怀（"爱心"、"优秀员工"）。

**5. 政策建议**
- 定向投资：优先资助SEIFA Decile 1的偏远原住民社区。
- 文化适配：建立超越NQS的本土化质量评估体系。
- 基建方案：为极偏远地区设立流动服务站点。
- 人才激励：制定高DV2地区教育工作者补贴政策。

## 文件说明
- original_data.zip：原始多层嵌套Excel数据（需ABS授权）。
- processed_data.zip：清洗后的结构化CSV（含LGA地理编码）。
- education_services_by_lga-checkpoint.html：展示服务分布与DV1相关性。

-------

## English Version

### Project Overview
This repository contains a comprehensive analysis of early childhood education services and developmental vulnerability across Australian Local Government Areas (LGAs), conducted for the **Department of Education**. The study integrates:
- **AEDC data** (developmental vulnerability metrics)
- **Preschool enrollment records**
- **Education service quality ratings**
- **Google Reviews sentiment analysis**

### Key Business Questions Addressed
1. **High-Vulnerability LGAs**: Identified regions with the highest developmental vulnerability (DV2) and their socio-geographic determinants.
2. **Domain Disparities**: Analyzed how socio-economic status (SEIFA) correlates with vulnerability across 5 AEDC domains.
3. **Service Distribution**: Evaluated alignment between service quality/quantity and developmental outcomes.
4. **Policy Gaps**: Highlighted critical service availability gaps in vulnerable regions.
5. **Public Sentiment**: Extracted insights from 10,000+ Google Reviews using NLP clustering.

### Core Findings
1. **Spatial Disparities**  
   - Top 10 LGAs with highest DV2 rates (>70%) are predominantly Indigenous and remote (e.g., Tiwi Islands).  
   - Very Remote areas show 3× higher DV2 than Major Cities (17% vs 5%).  

2. **Service-Quality Paradox**  
   - 41.5% of ACT services rated "Exceeding NQS" vs only 6.4% in NT.  
   - No significant correlation found between high NQS ratings and improved language/cognitive outcomes (r≈0.17).  

3. **Operational Capacity Gap**  
   - High-capacity LGAs paradoxically show higher DV1/DV2, suggesting quantity ≠ quality.  

4. **Google Reviews Insights**  
   - High-DV1 areas' reviews focus on access barriers (e.g., "longer wait", "gratitude for scarce spots").  
   - Low-DV1 reviews emphasize emotional care ("love", "great staff").  

### Policy Recommendations
- **Targeted Funding**: Prioritize remote Indigenous LGAs with SEIFA Decile 1.  
- **Cultural Adaptation**: Develop localized quality metrics beyond NQS.  
- **Infrastructure**: Establish mobile service hubs for Very Remote areas.  
- **Workforce**: Incentivize educator placements in high-DV2 regions.  




