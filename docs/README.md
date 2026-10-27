# Hệ Thống Giám Sát Trạm Cảm Biến Nông Trại (SmartFarm Monitor)

###Lenh chay script

```bash
bash auto_report.sh 
```

### Kiem tra thiet bi

- [x] Raspberry Pi 4 Model B
- [ ] Intel NUC i3
- [ ] Mini PC Fanless N100


### Bang danh mục linh kien

| Ten | Don gia | Loai Storage |
| --- | --- | --- |
| Raspberry Pi 4 Model B | 1450000 | SSD |
| Intel NUC i3 | 6200000 | SSD |
| Orange Pi 5 | 2300000 | SSD |



### Phân tích hệ thống: xác định Input – Process – Output của chức năng lọc log

- Input: Du lieu File .log.
- Progress: He thong doc File, tim tu khoa, ghi du liệu vào file .txt.
- Output: Du lieu file .txt

### DIKW (Data, Information, Knowledge, Wisdom):

- Data: (b) “2026-10-12 08:15:01 [ERROR] sensor-03 Connection TIMEOUT after 30s”
- Information: (c) “Hôm nay hệ thống ghi nhận 8 sự cố, trong đó 4 sự cố đến từ trạm sensor-03.”
- Knowledge: (d) “Trạm sensor-03 hay mất kết nối vào buổi chiều do sóng yếu, nên cần lắp thêm anten.”
- Wisdom: (a) “Quyết định thay modem trạm sensor-03 trước thứ Sáu.”

