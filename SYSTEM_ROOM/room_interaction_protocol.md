# 房間協作協議

## 主控室

職責：

總決策

---

## TASK_ROOM

職責：

任務分派

---

## WORLD_ROOM

輸出：

研究成果

傳送至：

MEMORY_ROOM

VERIFY_ROOM

---

## FAILURE_ROOM

輸出：

故障分析

傳送至：

EVOLUTION_ROOM

REGRESSION_ROOM

---

## HUMAN_ROOM

輸出：

人體模組

傳送至：

VERIFY_ROOM

MEMORY_ROOM

---

## VERIFY_ROOM

輸出：

驗證結果

傳送至：

REGRESSION_ROOM

---

## EVOLUTION_ROOM

輸出：

補丁

傳送至：

REGRESSION_ROOM

---

## REGRESSION_ROOM

輸出：

回歸結果

傳送至：

MEMORY_ROOM

SYSTEM_ROOM

---

## MEMORY_ROOM

輸出：

索引更新

傳送至：

SYSTEM_ROOM

---

## SYSTEM_ROOM

輸出：

規則更新

傳送至：

TASK_ROOM

