# Graph Report - raw  (2026-04-14)

## Corpus Check
- Corpus is ~636 words - fits in a single context window. You may not need a graph.

## Summary
- 31 nodes · 39 edges · 8 communities detected
- Extraction: 69% EXTRACTED · 26% INFERRED · 5% AMBIGUOUS · INFERRED: 10 edges (avg confidence: 0.83)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_AI 轉型與技術領導|AI 轉型與技術領導]]
- [[_COMMUNITY_高併發系統設計|高併發系統設計]]
- [[_COMMUNITY_工作風格與協作文化|工作風格與協作文化]]
- [[_COMMUNITY_跨國簡訊平台|跨國簡訊平台]]
- [[_COMMUNITY_台灣大哥大與轉職|台灣大哥大與轉職]]
- [[_COMMUNITY_個人背景與工程能力|個人背景與工程能力]]
- [[_COMMUNITY_Java 微服務架構|Java 微服務架構]]
- [[_COMMUNITY_MVP 快速交付|MVP 快速交付]]

## God Nodes (most connected - your core abstractions)
1. `韓世翔 (Brian Han)` - 8 edges
2. `團隊協作與溝通` - 4 edges
3. `AI/ML 整合` - 4 edges
4. `台灣大哥大` - 4 edges
5. `台灣之星電信` - 4 edges
6. `多國電信簡訊平台` - 4 edges
7. `高併發系統設計` - 4 edges
8. `技術團隊領導` - 4 edges
9. `AI 應用` - 3 edges
10. `Agentic Workflows` - 3 edges

## Surprising Connections (you probably didn't know these)
- `AI 應用` --semantically_similar_to--> `AI/ML 整合`  [INFERRED] [semantically similar]
  raw/面試補充資訊.md → raw/履歷匯總.md
- `轉職動機` --conceptually_related_to--> `台灣大哥大`  [AMBIGUOUS]
  raw/面試補充資訊.md → raw/履歷匯總.md
- `技術主管發展目標` --conceptually_related_to--> `技術團隊領導`  [INFERRED]
  raw/面試補充資訊.md → raw/履歷匯總.md
- `Agentic Workflows` --conceptually_related_to--> `AI 驅動軟體工程職涯目標`  [INFERRED]
  raw/面試補充資訊.md → raw/履歷匯總.md
- `Java NIO Socket 重連機制` --conceptually_related_to--> `多國電信簡訊平台`  [INFERRED]
  raw/面試補充資訊.md → raw/履歷匯總.md

## Hyperedges (group relationships)
- **AI Career Focus** — resume_summary_ai_ml_integration, resume_summary_ai_career_goal, interview_info_ai_applications, interview_info_agentic_workflows, interview_info_technical_leadership_goal [INFERRED 0.88]
- **Team Enablement Style** — resume_summary_team_leadership, interview_info_team_collaboration, interview_info_code_review_sharing, interview_info_preferred_work_environment, interview_info_remote_work_process_discipline [INFERRED 0.84]
- **Delivery at Scale** — resume_summary_iot_enterprise_platform, resume_summary_double11_auth_system, resume_summary_high_concurrency_system_design, interview_info_distributed_lock_refactor, interview_info_thread_safety_gap [INFERRED 0.83]

## Communities

### Community 0 - "AI 轉型與技術領導"
Cohesion: 0.38
Nodes (7): Agentic Workflows, AI 應用, 技術主管發展目標, AI 驅動軟體工程職涯目標, AI/ML 整合, 資策會 ASR 語音辨識平台, 數位轉型技術架構師目標

### Community 1 - "高併發系統設計"
Cohesion: 0.47
Nodes (6): 分散式鎖重構, 高併發重複交易的 Thread-Safety 缺口, 雙11 認證系統, 高併發系統設計, 物聯網企業平台, 台灣之星電信

### Community 2 - "工作風格與協作文化"
Cohesion: 0.5
Nodes (5): Code Review 與技術分享, 開放信任型工作環境, 具流程紀律的遠端協作, 團隊協作與溝通, 技術團隊領導

### Community 3 - "跨國簡訊平台"
Cohesion: 0.67
Nodes (3): 外部簡訊服務不穩定, Java NIO Socket 重連機制, 多國電信簡訊平台

### Community 4 - "台灣大哥大與轉職"
Cohesion: 0.67
Nodes (3): 轉職動機, 台台併後文化落差, 台灣大哥大

### Community 5 - "個人背景與工程能力"
Cohesion: 0.67
Nodes (3): 韓世翔 (Brian Han), CI/CD 自動化, 資深軟體工程師

### Community 6 - "Java 微服務架構"
Cohesion: 1.0
Nodes (2): 企業客戶入口網站重構, Java 企業級應用與雲端微服務架構

### Community 7 - "MVP 快速交付"
Cohesion: 1.0
Nodes (2): MVP 優先交付策略, 原型優先學習方式

## Ambiguous Edges - Review These
- `轉職動機` → `台灣大哥大`  [AMBIGUOUS]
  raw/面試補充資訊.md · relation: conceptually_related_to
- `台灣之星電信` → `多國電信簡訊平台`  [AMBIGUOUS]
  raw/履歷匯總.md · relation: conceptually_related_to

## Knowledge Gaps
- **9 isolated node(s):** `外部簡訊服務不穩定`, `台台併後文化落差`, `開放信任型工作環境`, `原型優先學習方式`, `MVP 優先交付策略` (+4 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `Java 微服務架構`** (2 nodes): `企業客戶入口網站重構`, `Java 企業級應用與雲端微服務架構`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.
- **Thin community `MVP 快速交付`** (2 nodes): `MVP 優先交付策略`, `原型優先學習方式`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What is the exact relationship between `轉職動機` and `台灣大哥大`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **What is the exact relationship between `台灣之星電信` and `多國電信簡訊平台`?**
  _Edge tagged AMBIGUOUS (relation: conceptually_related_to) - confidence is low._
- **Why does `韓世翔 (Brian Han)` connect `個人背景與工程能力` to `AI 轉型與技術領導`, `高併發系統設計`, `工作風格與協作文化`, `跨國簡訊平台`, `台灣大哥大與轉職`, `Java 微服務架構`?**
  _High betweenness centrality (0.594) - this node is a cross-community bridge._
- **Why does `技術團隊領導` connect `工作風格與協作文化` to `AI 轉型與技術領導`, `個人背景與工程能力`?**
  _High betweenness centrality (0.272) - this node is a cross-community bridge._
- **Why does `台灣之星電信` connect `高併發系統設計` to `跨國簡訊平台`, `個人背景與工程能力`?**
  _High betweenness centrality (0.266) - this node is a cross-community bridge._
- **What connects `外部簡訊服務不穩定`, `台台併後文化落差`, `開放信任型工作環境` to the rest of the system?**
  _9 weakly-connected nodes found - possible documentation gaps or missing edges._