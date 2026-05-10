README.md gồm đủ:
  Bước 1: Tạo Google Sheet, hàng 1 là tiêu đề, dữ liệu từ hàng 2.
           Cột A: Mã GCN | B: Họ tên | C: Chiến dịch | D: Ngày | E: Số tiền | F: SĐT | G: Link GCN
  Bước 2: Extensions → Apps Script → dán Code.gs → Lưu.
  Bước 3: Project Settings → Script Properties → thêm:
              API_SECRET_KEY = FLY2SKY_SECRET_XXXX  (tự chọn chuỗi bí mật)
  Bước 4: Deploy → New deployment → Web App
              Execute as: Me | Who has access: Anyone → Copy URL.
  Bước 5: Trong index.html thay YOUR_SCRIPT_ID và FLY2SKY_SECRET_XXXX.
  Bước 6: Tạo repo GitHub → push code → Vercel import → Deploy.
  Bước 7: Hướng dẫn đổi secret key định kỳ (đổi Properties + index.html + redeploy).
  Bước 8: Test thủ công:
              [WEB_APP_URL]?query=GCN-2024-001&auth=FLY2SKY_SECRET_XXXX
