# Infrastructure Capacity Planner

## Storage Forecast

| Field | Type | Description |
|---------|---------|---------|
| current_storage_tb | number | Kapasitas saat ini |
| used_storage_tb | number | Storage terpakai |
| monthly_growth_gb | number | Pertumbuhan per bulan |
| retention_days | number | Lama penyimpanan |
| backup_multiplier | number | Faktor backup |

---

## Cost Forecast

| Field | Type | Description |
|---------|---------|---------|
| rack_cost_monthly | currency | Biaya rack |
| power_cost_monthly | currency | Biaya listrik |
| colo_cost_monthly | currency | Biaya colocation |

---

## Forecast Result

| Field | Type | Description |
|---------|---------|---------|
| forecast_6m | number | Forecast 6 bulan |
| forecast_12m | number | Forecast 1 tahun |
| forecast_36m | number | Forecast 3 tahun |
