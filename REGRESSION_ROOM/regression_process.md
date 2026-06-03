# 回歸測試流程

狀態：

ACTIVE

---

第一步

接收補丁

來源：

EVOLUTION_ROOM

---

第二步

執行驗證

來源：

VERIFY_ROOM

---

第三步

執行回歸測試

檢查：

是否再次出現舊問題。

---

第四步

判定結果

PASS

FAIL

---

第五步

更新資料庫

REGRESSION_ROOM

FAILURE_ROOM

MEMORY_ROOM

同步更新。

---

規則：

曾修復問題再次出現。

直接標記：

回歸失敗。
