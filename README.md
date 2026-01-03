D2K Plugin [![GitHub Release](https://img.shields.io/github/v/release/2K9XTEAM/d2k-plugin?style=flat)](https://github.com/2K9XTEAM/d2k-plugin/releases) [![Discord](https://img.shields.io/discord/1068941579244539904.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://discord.gg/d44nKJU5Tm) ![Supported server version](https://img.shields.io/badge/minecraft-1.12%20--_1.21-green)
===========
D2K là plugin thanh toán tự động dành cho Minecraft, giúp máy chủ hỗ trợ donate và nạp tiền theo thời gian thực. Plugin tích hợp trực tiếp cổng nạp thẻ cào Card2K và dịch vụ thanh toán ngân hàng SePay, mang đến trải nghiệm thanh toán nhanh chóng, tiện lợi và ổn định cho người chơi.

Hiện đang hỗ trợ cổng nạp thẻ cào [Card2K](https://card2k.com) và cổng bank [Sepay](https://sepay.vn).

**Lưu ý:** hiện đang trong quá trình phát triển, vui lòng báo cáo mọi vấn đề bạn gặp phải tại [cộng đồng Discord chính thức của Card2K](https://discord.gg/d44nKJU5Tm).

Tính năng hiện có của Plugin
===========

- Hoạt động từ phiên bản 1.12 cho tới phiên bản 1.21 trở lên.
- Hỗ trợ nạp thẻ qua cổng thanh toán Card2K.
- Hỗ trợ nạp ngân hàng qua cổng thanh toán Sepay.
- Hỗ trợ thông báo hoạt động nạp thông qua Discord Webhook.
- Hỗ trợ hiển thị thông tin nạp thông qua PlaceholderAPI.
- Config sự kiện khuyến mãi trong config theo ý muốn (x2/x3 nạp theo thời điểm,...).
- Quà mốc nạp theo từng giai đoạn nhất định.

Hướng dẫn sử dụng
============
> Tham khảo cách cài đặt và thiết lập plugin [tại đây](ok)

**Danh sách lệnh**

| Lệnh    | Mô tả lệnh                  | Quyền hạn         |
|---------|-----------------------------|-------------------|
| /atm    | Mở menu nạp qua ngân hàng   | `atm.use`         |
| /napthe | Mở menu nạp qua thẻ cào     | `napthe.use`      |
| /d2k    | Lệnh sử dụng dành cho admin | `d2k.admin.basic` |

**Placeholder**

| Placeholder                       | Mô tả Placeholder                                                                                                                                    | Ví dụ                          |
|-----------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------|
| %d2k_total_<SERVER>%              | Hiển thị tổng tiền đã nạp của người đang xem tại server chỉ định.                                                                                    | %d2k_total_server1%            |
| %d2k_total_<SERVER>_<PLAYER>%     | Hiển thị tổng tiền đã nạp của một người chơi cụ thể tại server chỉ định.                                                                             | %d2k_total_server1_card2k%     |
| %d2k_total_raw_<SERVER>_<PLAYER>% | Giống như trên nhưng trả về số thô (không có dấu phẩy và chữ VND). Dùng cho tính toán.                                                               | %d2k_total_raw_server1_card2k% |
| %d2k_top_<SCOPE>_<SERVER>_<RANK>% | Hiển thị thông tin người đứng top nạp thẻ (Tên + Số tiền).  SCOPE: DAY (Ngày), WEEK (Tuần), MONTH (Tháng), ALL (Tổng).  RANK: Thứ hạng (1, 2, 3...). | %d2k_top_ALL_server1_1%        |

---
Plugin được phát triển bởi 2K9XTeam và các cá nhân liên quan. Copyright (c) 2K9X Team. All rights reserved.
