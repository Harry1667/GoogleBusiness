    # 4-googlebusiness｜智簡 Zhi Jian 子專案

    > **本專案是母品牌「智簡 Zhi Jian」的子專案。**
    > 路徑：`/Users/harryhwa/Documents/0-Dev/0-WebDev/1-zhijian`

    ---

    ## 🔗 與母品牌的關係

    智簡是「一人式 AI 駐點顧問」，月費 10–30 萬。
    **本專案是智簡的低門檻產品線**：用 Google 商家代管當信任入口，把小店家從 NT$ 2,000 一路養到智簡 10 萬月費方案。

    漏斗位置：
    ```
    本專案（4-googlebusiness）           智簡（1-zhijian）
    L1 建檔 2,000–5,000 一次性    →
    L2 月代管 1,500–3,000 / 月    →
    L3 加值（網站/LINE/廣告）     →     標準駐點 100,000–300,000 / 月
                                        深度整合
    ```

    ---

    ## ⚠️ 工作前必做（每次開工前）

    **在動本專案任何檔案前，先檢查母專案是否有更新**：

    ```bash
    ls -la /Users/harryhwa/Documents/0-Dev/0-WebDev/1-zhijian/
    ls -la /Users/harryhwa/Documents/0-Dev/0-WebDev/1-zhijian/01-doc/
    git -C /Users/harryhwa/Documents/0-Dev/0-WebDev/1-zhijian log --oneline -10
    ```

    **為什麼要看**：
    - 智簡的品牌定位、月費方案、三大支柱可能更新 → 本專案的話術 / 報價 / 服務矩陣要同步
    - 智簡的 Demo（OCR / 合約比對 / AI 客服）可能新增 → 本專案的 L3 加值清單要對齊
    - 智簡的視覺、Logo、口徑變動 → 本專案對外文件（同意書、月報、名片）要跟著改

    **檢查重點檔案**：
    - `1-zhijian/01-doc/9-readme.md` — 智簡網站文案總綱（八區塊）
    - `1-zhijian/02-web/index.html` — 對外官網
    - `1-zhijian/01-doc/2-talk.md` — 文案核心來源

    ---

    ## 📁 本專案核心文件（在 `01-dev/` 內）

    - **`00-positioning.md`** — 核心定位（受眾 × 服務 × 與智簡整合）★ 必讀
    - **`project-info.md`** — 完整專案說明（目錄、技術棧、開發鐵律、商業紅線、Milestone）
    - **`2-operations-manual.md`** — 實戰營運手冊（找客 → 月代管完整 SOP）
    - **`3-execution-plan.md`** — 執行計畫 + 任務細部手冊
    - **`1-tools-prd.md`** — 7 個輔助工具的 PRD
    - **`9-task-list.md`** — 任務總覽（已併入 3-execution-plan.md）
    - **`git-secrets-rules.md`** — Git secrets 規則
    - **`0-run.md`** — 便攜指令（勿動）

    ---

    ## 🚦 Claude 工作守則（簡版）

    1. **每次開工前**：先 `ls 1-zhijian/` 看母專案有沒有更新
    2. **改動本專案前**：確認改動不會違反智簡的品牌口徑（月費制、三支柱、一人駐點）
    3. **新增服務 / 報價時**：要對齊智簡的 L1→L3 漏斗邏輯
    4. **詳細專案說明、開發鐵律、商業紅線**：去看 `01-dev/project-info.md`
    5. **詳細受眾分析、服務矩陣**：去看 `01-dev/00-positioning.md`

    ---

    ## 📝 工作記錄

    - `SESSION_NOTES.md`：每次工作的進度記錄（在本專案根目錄）
