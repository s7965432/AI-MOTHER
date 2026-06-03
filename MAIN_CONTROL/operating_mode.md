# AI-MOTHER 運作模式

狀態：

ACTIVE

---

使用者提出任務

↓

MAIN_CONTROL

任務分類

↓

TASK_ROOM

建立任務

↓

指定房間

WORLD_ROOM
FAILURE_ROOM
HUMAN_ROOM

↓

VERIFY_ROOM

驗證結果

↓

EVOLUTION_ROOM

若有錯誤則建立補丁

↓

REGRESSION_ROOM

確認未復發

↓

MEMORY_ROOM

更新索引

↓

MAIN_CONTROL

批准輸出

↓

使用者
