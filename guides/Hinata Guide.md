## Các lệnh cơ bản cần biết với bot Hinata

##Danh mục
- [Roles / Chức danh](#roles)
- [Hệ thống tiền tệ](#currency)
- [Trò chơi](#games)
- [Gambling](#gambling)
- [Games](#games)
- [Music](#music)
- [NSFW](#nsfw)



### Roles

Lệnh | Chức năng | Ví dụ
----------------|--------------|-------
`.lsar` | Xem danh sách các role có thể tự sử dụng | `.lsar`
`.iam` | Chọn role bạn muốn sử dụng | `.iam Chuẩn vozer`
`.iamnot` `.iamn` | Xóa role bạn đang sở hữu | `.iamnot Chuẩn vozer`

Hiện tại server đang có 6 roles có thể tự set (có thể thay đổi)

Gay detected: Hồng

Dầu ăn Neptune: Vàng

Chuẩn vozer: Tím

Đảng viên gương mẫu: Đỏ

Nông dân chăn rau: Nâu

Đã tốn tiền: Xanh

### Currency

Lệnh | Chức năng | Ví dụ
----------------|--------------|-------
`.$` `.$ @someone` | Kiểm tra số tiền đang sở hữu hoặc số tiền người khác đang sở hữu | `.$` `.$ @SuHao`
`.lb` `.leaderboard` | Kiểm tra bảng xếp hạng những người giàu nhất server | .
`.give X @someone` | tặng X số tiền cho người nào đó | `.give 10 @SuHao`
`.shop` | Cửa hàng | .
`.buy X` | Mua vật phẩm có số thứ tự X trong cửa hàng. Lưu ý cần bật chế độ gửi tin nhắn riêng tư để bot có thể gửi vật phẩm | `.buy 1`

### Games

Các trò chơi vui vẻ

Lệnh | Chức năng | Ví dụ
----------------|--------------|-------
`.raffle` | Ngẫu nhiên chọn ra tên của một người đang ONLINE trong server, hoặc trong 1 role chỉ định | `.raffle` `.raffle TênRole`
`.raffleany` | Ngẫu nhiên chọn ra tên của một người trong server, hoặc trong 1 role chỉ định | `.raffleany` `.raffleany TênRole`
`.race` | Khởi động 1 cuộc đua kì thú giữa các loài động vật | .
`.jr` `.joinrace` | Tham gia cuộc đua. Có thể cược số tiền. Bạn sẽ nhận lại SốBạnCược*(SốNgườiThamGia-1) nếu bạn thắng | `.jr` `.joinrace 5`
