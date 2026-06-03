# AI-MOTHER 系統地圖

版本：

AI-MOTHER v0.3

狀態：

ACTIVE

---

# 核心房間

## TASK_ROOM

功能：

任務管理
任務追蹤
優先級管理

主要檔案：

task_queue.md
task_tracking.md
project_status.md

---

## WORLD_ROOM

功能：

世界觀研究

研究項目：

WR-001 蟲洞
WR-002 負能量
WR-003 傳送門
WR-004 高維空間
WR-005 時間旅行
WR-006 白洞
WR-007 曲速引擎

---

## FAILURE_ROOM

功能：

故障分析
回歸管理

資料庫：

ERROR-001 ~ ERROR-040

狀態：

ACTIVE

---

## HUMAN_ROOM

功能：

人體資料庫

模組：

FACE-001 ~ FACE-010

LEG-001 ~ LEG-010

SKELETON-001 ~ SKELETON-003

CHEST-001

STOCKING-REF-CITY-01

BOOT-STAGE-KPOP-A

---

## MEMORY_ROOM

功能：

索引管理
資料整理
系統地圖管理

主要檔案：

memory_index.md
module_index.md
research_index.md
error_index.md
system_map.md

---

## VERIFY_ROOM

功能：

驗證輸出

規則：

答非所問檢查
條件遺漏檢查
Prompt污染檢查
空白輸出檢查

---

## SYSTEM_ROOM

功能：

系統規則

主要檔案：

workflow.md
standards.md

---

## EVOLUTION_ROOM

功能：

進化紀錄
補丁管理

主要檔案：

evolution_log.md

---

# 資料庫統計

研究項目：

7

故障項目：

40

人體模組：

25+

房間數：

8

---

# 系統流程

使用者

↓

主控室

↓

TASK_ROOM

↓

指定房間

↓

VERIFY_ROOM

↓

MEMORY_ROOM

↓

輸出

---

# 下一階段

FAILURE_ROOM

ERROR-041 ~ ERROR-100

---

HUMAN_ROOM

FACE-011 ~ FACE-020

LEG-011 ~ LEG-020

SKELETON-004 ~ SKELETON-010

CHEST-002 ~ CHEST-010

---

WORLD_ROOM

WR-008 ~ WR-020

---

狀態：

READY
