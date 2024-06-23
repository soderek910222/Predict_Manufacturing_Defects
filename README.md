# Predict_Manufacturing_Defects

### 1. 生產指標 (Production Metrics)
- **ProductionVolume (Integer)**: 每天生產的單位數量。
  - 範圍: 100 至 1000 單位/天

- **ProductionCost (Float)**: 每天的生產成本。
  - 範圍: $5000 至 $20000

### 2. 供應鏈和物流 (Supply Chain and Logistics)
- **SupplierQuality (Float %)**: 供應商的質量評分。
  - 範圍: 80% 至 100%

- **DeliveryDelay (Integer days)**: 平均交貨延遲天數。
  - 範圍: 0 至 5 天

### 3. 質量控制和缺陷率 (Quality Control and Defect Rates)
- **DefectRate (Float)**: 每千個生產單位中的缺陷數量。
  - 範圍: 0.5 至 5.0 缺陷

- **QualityScore (Float %)**: 整體質量評估。
  - 範圍: 60% 至 100%

### 4. 維護和停機時間 (Maintenance and Downtime)
- **MaintenanceHours (Integer)**: 每週維護所花費的時間。
  - 範圍: 0 至 24 小時

- **DowntimePercentage (Float %)**: 生產停機時間的百分比。
  - 範圍: 0% 至 5%

### 5. 庫存管理 (Inventory Management)
- **InventoryTurnover (Float)**: 庫存周轉率。
  - 範圍: 2 至 10

- **StockoutRate (Float %)**: 庫存缺貨率。
  - 範圍: 0% 至 10%

### 6. 勞動力生產力和安全 (Workforce Productivity and Safety)
- **WorkerProductivity (Float %)**: 勞動力的生產力水平。
  - 範圍: 80% 至 100%

- **SafetyIncidents (Integer)**: 每月的安全事故數量。
  - 範圍: 0 至 10 事故

### 7. 能源消耗和效率 (Energy Consumption and Efficiency)
- **EnergyConsumption (Float)**: 能源消耗（千瓦時）。
  - 範圍: 1000 至 5000 千瓦時

- **EnergyEfficiency (Float)**: 能源使用的效率因子。
  - 範圍: 0.1 至 0.5

### 8. 增材製造 (Additive Manufacturing)
- **AdditiveProcessTime (Float hours)**: 增材製造所花費的時間。
  - 範圍: 1 至 10 小時

- **AdditiveMaterialCost (Float $)**: 增材材料每單位的成本。
  - 範圍: $100 至 $500

### 9. 目標變數 (Target Variable)
- **DefectStatus (Binary)**: 預測的缺陷狀態。
  - 0 表示低缺陷，1 表示高缺陷
