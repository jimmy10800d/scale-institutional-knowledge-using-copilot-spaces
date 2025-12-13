# OctoAcme — Release & Deployment Guide
# OctoAcme — 發布和部署指南

## Purpose
## 目的
Standardize how OctoAcme releases features to production to reduce risk and improve observability.
<!-- 標準化 OctoAcme 如何將功能發布到生產環境,以減少風險並提高可觀察性 -->

## Release Types
## 發布類型
- Patch: hotfixes addressing critical production issues
  <!-- 修補程式:解決關鍵生產問題的緊急修復 -->
- Minor: incremental features and improvements
  <!-- 次要版本:增量功能和改進 -->
- Major: significant functionality or breaking changes
  <!-- 主要版本:重大功能或破壞性更改 -->

## Pre-release requirements
## 發布前要求
- All acceptance criteria met and PRs merged
  <!-- 所有驗收標準已滿足且 PR 已合併 -->
- Passing CI and security scans
  <!-- 通過 CI 和安全掃描 -->
- Release notes drafted
  <!-- 發布說明已起草 -->
- Rollback / mitigation plan documented
  <!-- 回滾/緩解計畫已記錄 -->
- Smoke tests prepared
  <!-- 煙雾測試已準備 -->

## Deployment Checklist
## 部署檢查清單
- [ ] Deployment window scheduled (if needed)
  <!-- 部署視窗已安排(如需要) -->
- [ ] Backup or snapshot (if applicable)
  <!-- 備份或快照(如適用) -->
- [ ] Deploy to staging and run smoke tests
  <!-- 部署到準備環境並執行煙雾測試 -->
- [ ] Deploy to production (automated pipeline preferred)
  <!-- 部署到生產環境(優先使用自動化管道) -->
- [ ] Run post-deploy verifications
  <!-- 執行部署後驗證 -->
- [ ] Announce release to stakeholders and support
  <!-- 向利害關係人和支援團隊公告發布 -->

## Rollback & Incident Playbook
## 回滾和事件運行手冊
- If a deployment fails or causes a critical issue:
  <!-- 如果部署失敗或導致關鍵問題: -->
  - Trigger incident response and notify on-call
    <!-- 觸發事件響應並通知值班人員 -->
  - Rollback to last known-good release if necessary
    <!-- 如有必要,回滾到最後一個已知良好的發布 -->
  - Triage root cause and capture action items
    <!-- 分類根本原因並記錄行動項目 -->

## Release Notes Template
## 發布說明範本
- Release name / number:
  <!-- 發布名稱/編號: -->
- Date:
  <!-- 日期: -->
- Summary:
  <!-- 摘要: -->
- Notable changes:
  <!-- 顯著變更: -->
- Migration steps (if any):
  <!-- 遷移步驟(如有): -->
- Known issues:
  <!-- 已知問題: -->
