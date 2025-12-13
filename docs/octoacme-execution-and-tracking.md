# OctoAcme — Execution & Tracking
# OctoAcme — 執行和追蹤

## Purpose
## 目的
Guidance for managing day-to-day execution and tracking progress toward project milestones.
<!-- 管理日常執行和追蹤專案里程碑進度的指導 -->

## Team Rhythm
## 團隊節奏
- Daily standups (15 min) — focus on progress, blockers, dependencies
  <!-- 每日站立會議(15分鐘) — 關注進度、阻礙、相依性 -->
- Weekly delivery sync — show progress, updates, and flagged risks
  <!-- 每週交付同步 — 展示進度、更新和標記的風險 -->
- Demo/Review at the end of each sprint or milestone
  <!-- 每個衝刺或里程碑結束時的演示/審查 -->

## Workflows
## 工作流程
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
  <!-- 使用專案看板(例如 GitHub Projects)並設置欄位:待辦事項、就緒、進行中、審查中、QA、完成 -->
- Pull Request workflow:
  <!-- 拉取請求工作流程: -->
  - Small PRs (<= 400 lines when possible)
    <!-- 小型 PR(盡可能 <= 400 行) -->
  - Include issue link and acceptance criteria in PR description
    <!-- 在 PR 描述中包含議題連結和驗收標準 -->
  - Run automated tests and linting in CI before requesting review
    <!-- 在請求審查前在 CI 中執行自動化測試和語法檢查 -->
  - Require at least one approval before merging (or team-defined policy)
    <!-- 合併前至少需要一個批准(或團隊定義的政策) -->

## Quality & Testing
## 品質和測試
- Unit tests for new logic
  <!-- 新邏輯的單元測試 -->
- Integration tests where applicable
  <!-- 適用的整合測試 -->
- End-to-end smoke tests for critical flows before release
  <!-- 發布前關鍵流程的端到端煙雾測試 -->
- Security scanning in CI
  <!-- CI 中的安全掃描 -->
- Manual QA for feature acceptance when needed
  <!-- 需要時進行功能驗收的人工 QA -->

## Reporting & Metrics
## 報告和指標
- Track velocity and burndown
  <!-- 追蹤速度和燃盡圖 -->
- Monitor success metrics identified in the Project One-pager
  <!-- 監控專案一頁摘要中識別的成功指標 -->
- Use dashboards for key signals (errors, latency, usage)
  <!-- 使用儀表板顯示關鍵信號(錯誤、延遲、使用情況) -->

## Blocker Escalation
## 阻礙升級
- Level 1: Team-level triage in daily standup
  <!-- 第一層:在每日站立會議中進行團隊級別分類 -->
- Level 2: PM escalates to Product Lead and dependent teams
  <!-- 第二層:PM 升級至產品負責人和相依團隊 -->
- Level 3: Sponsor-level escalation for business-impacting issues
  <!-- 第三層:對影響業務的問題進行贊助者級別升級 -->

## Execution Checklist
## 執行檢查清單
- [ ] Branching and PR conventions documented in repo
  <!-- 分支和 PR 約定已在儲存庫中記錄 -->
- [ ] CI configured for tests and lint
  <!-- CI 已配置測試和語法檢查 -->
- [ ] Regular demos scheduled
  <!-- 定期演示已安排 -->
- [ ] Risk register updated weekly
  <!-- 風險登記表每週更新 -->
