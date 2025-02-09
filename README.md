## 信用卡詐欺偵測

# 專案簡介

本專案旨在開發一個機器學習模型，用於偵測信用卡詐欺交易。目標是根據提供的數據集，準確分類交易為合法或詐欺，從而幫助減少財務損失。專案探討了包括數據預處理、特徵選擇、模型訓練和評估等不同技術。

# 資料來源

本專案使用的數據集包含信用卡交易，並標示交易是否為詐欺。特徵已經過轉換以保護隱私，且數據集極度不平衡，以合法交易占多數。

# 技術與工具

● 監督式學習：LogisticRegression、XGBoost

● 特徵工程：SMOTE 過採樣

● 其它：網格搜索 (GridSearchCV)

# 關鍵步驟

1. 數據探索：深入了解數據集，包括分佈分析、處理類別不平衡和特徵相關性分析。

2. 特徵工程：使用適當技術處理類別不平衡。

3. 模型選擇：實施多種模型，包括 LogisticRegression、XGBoost，測試提升準確度。

4. 模型評估：使用準確度、精確率、召回率等指標評估模型，專案目標是在降低誤報與漏報之間取得平衡。

# 結果

最佳模型達到了較高的準確度，包含 accuracy、precision、recall 等各項評估指標在陽性與陰性都有獲得 0.97~0.99 的預測成績，並以學習曲線檢查過擬合狀況，模型表現健康，沒有明顯過擬合跡象。

# 結論

本專案展示了如何利用機器學習模型來高效偵測信用卡詐欺交易，從而減少財務損失，同時強調在偵測詐欺時平衡敏感度和特異性的重要性。
