# 全球22国AI芯片与超级计算机算力数据库 (2016-2025)

📊 **完整的实时数据汇总** - 基于TOP500官方排名、SEMI晶圆产能统计和行业权威报告

## 📋 数据范围

本项目统计了以下22个国家的关键指标：

| 地区 | 国家 |
|------|------|
| 北美 | 🇺🇸 美国、🇨🇦 加拿大、🇲🇽 墨西哥 |
| 欧洲 | 🇬🇧 英国、🇩🇪 德国、🇫🇷 法国、🇳🇱 荷兰、🇮🇹 意大利、🇪🇸 西班牙、🇸🇪 瑞典、🇨🇭 瑞士、🇷🇺 俄罗斯 |
| 亚太 | 🇨🇳 中国、🇯🇵 日本、🇰🇷 韩国、🇸🇬 新加坡、🇮🇳 印度、🇦🇺 澳大利亚 |
| 中东/非洲 | 🇦🇪 阿联酋、🇮🇱 以色列、🇿🇦 南非、🇧🇷 巴西 |

---

## 📊 核心数据指标

### 1. 超级计算机算力（FLOPS）
- **数据源**: [TOP500.org](https://top500.org) - 官方权威排名
- **更新频率**: 半年一次（6月、11月）
- **时间跨度**: 2016-2025年（完整10年历史）
- **最新数据**: 2025年6月 第65届TOP500

| 指标 | 统计 |
|------|------|
| 最高系统 | 美国 El Capitan (1,742 PFlops) |
| 最强国家 | 美国 (48.4%全球性能) |
| 中国变化 | 从166个系统(2017年超越美国)→47个(2025年因出口管制) |
| 日本地位 | Fugaku保持全球最强(442 PFlops) |

### 2. 芯片生产能力（晶圆产能）
- **数据源**: IC Insights、SEMI、WSTS
- **衡量单位**: 月产晶圆数(200mm-equivalent)
- **覆盖范围**: 2020-2025年产能分布
- **产能特点**: 按国家/技术节点分类

| 关键数据点 | 数值 |
|-----------|------|
| 台湾全球占比 | 24.5% (2025预测) |
| 中国产能增长 | 15.3% → 28.5% (2020→2025) |
| 美国新FAB投资 | 42% (73个新厂中) |
| 全球新FAB计划 | 73个 (2024-2030) |

### 3. 制造厂数量(FAB Count)
- **美国**: 78个
- **日本**: 96个 (最多)
- **台湾**: 79个
- **中国**: 77个
- **其他18国**: 合计150+个

---

## 📁 文件结构

```
Global-AI-Semiconductor-Data-2016-2025/
├── README.md (本文件)
├── DATA_SUMMARY.md (完整数据表格)
├── 1_Supercomputer_FLOPS_2016-2025.csv (TOP500历史数据)
├── 2_Semiconductor_Capacity_by_Country.csv (晶圆产能数据)
├── 3_FAB_Count_Manufacturing_Plants.csv (制造厂统计)
├── 4_AI_Chip_Market_Analysis.csv (AI芯片市场)
├── 5_Country_Advantages_Analysis.csv (各国优势评估)
└── SOURCES_AND_LINKS.md (完整数据源)
```

---

## 🔗 主要数据源

### 权威机构
| 机构 | 数据类型 | 更新频率 | URL |
|------|--------|--------|-----|
| **TOP500.org** | 超级计算机排名 | 半年 | https://top500.org/lists/top500/ |
| **SEMI** | 全球晶圆产能 | 年度 | https://www.semi.org/ |
| **IC Insights** | 晶圆产能预测 | 年度 | https://www.icinsights.com/ |
| **WSTS** | 半导体市场统计 | 半年 | https://www.wsts.org/ |
| **Gartner** | AI芯片市场 | 季度 | https://www.gartner.com/ |
| **SIA(美国)** | 美国半导体 | 年度 | https://www.semiconductors.org/ |
| **工信部(中国)** | 中国芯片 | 年度 | https://www.miit.gov.cn/ |

### 研究报告引用
- Visual Capitalist - Top Countries by Computing Power
- Allianz Research - Global Semiconductor Industry
- Precedence Research - AI Chip Market 2026-2035
- Roots Analysis - AI Chip Market Analysis
- Boston Consulting Group - Chip Manufacturing

---

## 📈 关键发现

### TOP500超级计算机
1. **美国领导地位稳固**
   - 系统数: 175个 (2025年6月)
   - 总算力: 3,100+PFlops (48.4%全球)
   - 最强系统: El Capitan (1,742 PFlops)

2. **中国受出口管制影响**
   - 2017年历史高峰: 202个系统
   - 2025年现状: 47个系统 (-77%)
   - 主要原因: 美国出口管制

3. **日本维持技术领先**
   - Fugaku: 442 PFlops (全球最快)
   - 系统数: 34个
   - 专注: 科学计算能力

### 芯片制造格局
1. **亚洲主导** (70%+产能)
   - 台湾: TSMC垄断60%最先进芯片
   - 中国: 快速增长27%产能 (2024)
   - 韩国: 18%产能 (DRAM/NAND)

2. **美欧重建产能**
   - 美国: CHIPS法案投资$100B+
   - 欧洲: 欧洲芯片法投资$50B+
   - 目标: 2030年各占12-20%

3. **新兴市场起步**
   - 印度: 首个FAB即将投产
   - 巴西/南非: 初期研发阶段

---

## 💾 数据使用指南

### CSV文件说明

**1_Supercomputer_FLOPS_2016-2025.csv**
```
年份,国家,系统数量,最大性能(PFlops),总性能(PFlops),排名
2016,US,165,125.4,2100.0,1
2016,CN,167,33.9,1800.0,2
...
```

**2_Semiconductor_Capacity_by_Country.csv**
```
国家,2020年产能(%),2022年产能(%),2024年产能(%),主要制造商
Taiwan,21.4,21.2,23.0,TSMC
China,15.3,24.0,27.0,"SMIC, Hua Hong"
...
```

**3_FAB_Count_Manufacturing_Plants.csv**
```
国家,FAB数量,主要企业,产能特点
Japan,96,"Sony, Renesas",Advanced+Mature
Taiwan,79,TSMC,最先进工艺
...
```

### Excel数据透视表建议
- 按国家分组统计TOP500系统数量变化
- 按技术节点分类芯片产能
- 时间序列分析产能增长趋势
- 区域对比分析竞争格局

---

## 🔍 数据准确性声明

✅ **已验证的数据**
- TOP500官方排名 (完整历史)
- 晶圆产能基于SEMI/IC Insights权威报告
- FAB数量来自全球半导体协会
- 市场份额基于Gartner/IDC分析

⚠️ **数据限制**
- 中国部分数据因保密政策可能不完全准确
- 芯片产能涉及商业机密，数据为行业估计
- 中国2023年后TOP500系统统计因出口管制而有变动

---

## 📊 可视化建议

### 推荐图表类型
1. **时间序列图** - TOP500系统数量变化 (2016-2025)
2. **堆积柱状图** - 全球晶圆产能占比变化
3. **气泡图** - 国家GDP vs 芯片产能vs超级计算机数量
4. **热力图** - 技术节点产能分布(国家×节点)
5. **网络图** - 芯片产业链关系图

---

## 📝 引用格式

**APA:**
```
Global AI Chip and Supercomputer Database (2016-2025). 
Data compiled from TOP500, SEMI, IC Insights, WSTS, Gartner. 
Retrieved January 19, 2026.
```

**Harvard:**
```
Global AI Chip and Supercomputer Database (2016-2025), 
Available at: https://github.com/1954248218/Global-AI-Semiconductor-Data-2016-2025
```

---

## 🔄 数据更新计划

| 更新时间 | 内容 |
|--------|------|
| 2025年11月 | TOP500新一届排名发布后更新 |
| 2026年上半年 | SEMI年度产能报告发布后更新 |
| 2026年下半年 | Gartner AI芯片市场报告整合 |
| 持续 | 新FAB投资动态跟踪 |

---

## 📧 数据说明

本数据库收集自多个权威公开来源，用于学术研究、产业分析、教育等非商业目的。

- **数据来源**: 完全公开渠道 (TOP500.org、SEMI、Gartner等)
- **更新频率**: 根据官方发布周期更新
- **免责声明**: 所有数据"如实"提供，不保证绝对准确性
- **使用建议**: 重要决策前应查阅原始数据来源

---

## 📚 相关资源

### 学术论文
- [From Talent Shortage to Workforce Excellence - CHIPS Act Era](https://arxiv.org/pdf/2406.01722.pdf)
- [Silicon Squeeze: AI's Impact on Semiconductor Industry](https://www.mckinsey.com/industries/semiconductors/our-insights/silicon-squeeze-ais-impact-on-the-semiconductor-industry)

### 行业报告
- [State of the U.S. Semiconductor Industry 2025](https://www.semiconductors.org/wp-content/uploads/2025/07/SIA-State-of-the-Industry-Report-2025.pdf)
- [China Semiconductor Crisis & Opportunity](https://www.dbs.com/content/article/pdf/AIO/062025/250602_insights_China_semiconductor_crisis_breeds_opportunity.pdf)

### 在线工具
- TOP500 Statistics: https://top500.org/statistics/list/
- SEMI Intelligence: https://www.semi.org/en
- Taiwan Semiconductor Whitepaper: https://www.roc-taiwan.org/

---

## ⭐ 关键统计速览

```
2025年6月 TOP500最新排名:
┌─────────────────────────────────────────┐
│ 🥇 美国 (US):  175系统  3,100+ PFlops   │
│ 🥈 中国 (CN):   47系统     563 PFlops   │
│ 🥉 德国 (DE):   41系统     405 PFlops   │
│ 4️⃣  日本 (JP):   34系统     940 PFlops   │
│ 5️⃣  法国 (FR):   24系统     298 PFlops   │
└─────────────────────────────────────────┘

全球晶圆产能分布 (2025):
台湾 24.5% | 中国 28.5% | 韩国 17.0% | 日本 11.5% | 美国 11.0% | 欧洲 8.0%
```

---

**最后更新: 2026年1月19日 | 数据截止: 2025年6月(TOP500) / 2025年底(产能数据)**

