# Showroom-Network-Setup
Hạ tầng mạng showroom bán lẻ cho công ty
# Triển khai hệ thống mạng Showroom Gearvn

## 1. Giới thiệu dự án
- **Quy mô:** Showroom diện tích 90m2.
- **Vai trò:** Lên sơ đồ mạng, cấu hình Router, Switch, AP, triển khai Camera.

## 2. Giải pháp hạ tầng
- **Router:** DrayTek (Cấu hình Load balancing, VPN).
- **Network:** Chia VLAN (VLAN 1: Management, VLAN 10: Camera, VLAN 20: LAN, VLAN 30: Wifi).
- **Thiết bị khác:** Grandstream, Camera Dahua.

## 3. Sơ đồ mạng (Network Topology)
![Sơ đồ mạng](mapnet-showroom.drawio.svg)

## 4. Các vấn đề đã xử lý
- Tách VLAN Camera riêng để tránh ảnh hưởng băng thông cửa hàng.
- Tối ưu hóa bandwidth để ưu tiên băng thông cho POS bán hàng.
- Triển khai VPN Tunnel Site-to-site

## 5. Kết quả
- Hệ thống hoạt động ổn định 24/7.
- Thời gian triển khai: 3 ngày.
