## Các lệnh cơ bản cần biết với bot Hinata

##Danh mục
- [Roles / Chức danh](#roles)
- [Hệ thống tiền tệ](#currency)
- [Hệ thống kinh nghiệm](#exp)
- [Trò chơi](#games)
- [18+ ( ͡° ͜ʖ ͡°) ](#nsfw)
- [Một số lệnh vui vẻ](#fun)



### Roles

Roles (chức danh). Hiện tại server có rất nhiều chức danh, mỗi chức danh có một ý nghĩa riêng.
Điểm qua một số role của vozGaming như


Moderator: mod của server, hiện tại có Key và dtieubinh (cũng là mod F253 voz)

DJ: role này cho phép thành viên tự do skip, next bài... mà không cần vote khi có nhiều người cùng nghe

Dream Team: role này riêng dành cho team custom LMHT của server vozGaming, cho phép truy cập vào channel voice riêng của team, tránh trường hợp các member khác vào phòng

*6 roles tự set đọc phía dưới*

Team Leader/member: dành cho các team đã đăng kí, có quyền truy cập vào channel voice của team, riêng Leader có quyền mute/move thành viên giữa các room voice


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

![Imgur](https://i.imgur.com/xuQciVf.png)


### Currency

Hệ thống tiền tệ của server vozGaming mang đậm bản sắc voz: cục gạch ![Imgur](https://i.imgur.com/TkZiDH5.png)

Khi tán gẫu tại channel #thao-luan-chung, sẽ có tỉ lệ rơi ra gạch, khi xuất hiện thông báo, ai gõ .pick nhanh nhất sẽ là người sở hữu số gạch đó

![Imgur](https://i.imgur.com/yXDatoH.png)

Một lưu ý nữa, đó là các tài khoản mới tham gia Discord sẽ có hạn chế nhất định về các tính năng (tránh sử dụng clone trục lợi)


Lệnh | Chức năng | Ví dụ
----------------|--------------|-------
`.$` `.$ @someone` | Kiểm tra số tiền đang sở hữu hoặc số tiền người khác đang sở hữu | `.$` `.$ @SuHao`
`.lb` `.leaderboard` | Kiểm tra bảng xếp hạng những người giàu nhất server | .
`.give X @someone` | tặng X số tiền cho người nào đó | `.give 10 @SuHao`
`.shop` | Cửa hàng | .
`.buy X` | Mua vật phẩm có số thứ tự X trong cửa hàng. Lưu ý cần bật chế độ gửi tin nhắn riêng tư để bot có thể gửi vật phẩm | `.buy 1`
`.pick` | Nhặt lượng tiền được sinh ra ngẫu nhiên tại kênh chat | `.pick`
`.plant` | Tốn một lượng tiền để tung ra kênh chat. Mặc định là 1 | `.plant` hoặc `.plant 10`
`.timely` | Nhận phần thưởng theo giờ. Hiện tại phần thưởng khi gõ .timely là 1 gạch/giờ | .



### exp

Bạn sẽ nhận được kinh nghiệm khi chat tại channel #thao-luan-chung. Hệ thống không tính theo số câu chat, nên vui lòng không spam tin nhắn để lên cấp

Lên cấp tương ứng sẽ được thưởng các phần quà tương ứng


Lệnh | Chức năng | Ví dụ
----------------|--------------|-------
`.xp` | Hiển thị thông tin kinh nghiệm hiện tại | `.xp` hoặc `.xp @aiđó`
`.xprews` | Hiển thị các phần thưởng khi lên cấp | .
`.xpn server channel` | Thông báo mỗi khi lên cấp tại channel chat cuối cùng | .
`.xpleaderboard` `.xplb` | Bảng xếp hạng XP | .

![Imgur](https://i.imgur.com/QNvPWdP.png)


### Games


Các trò chơi vui vẻ

Lệnh | Chức năng | Ví dụ
----------------|--------------|-------
`.choose` | Chọn 1 thứ ngẫu nhiên từ danh sách | `.choose Ăn cơm;Ăn cứt;Ăn c*c`
`.8ball` | Hỏi một câu hỏi có/không (đúng/sai) | `.8ball admin đẹp trai vl đúng không?`
`.rps` | Chơi Kéo-Búa-Bao (oẳn tù tì) với Hinata | `.rps Rocket/Paperclip/Scissors`
`.connect4` `.con4` | Tạo một trò chơi connect4, yêu cầu tối thiểu phải có 2 người. Mục tiêu là đưa 4 mảnh vỡ thành 1 đường thẳng hoặc ngang hoặc chéo | `.connect4`
`.tictactoe` `.ttt` | Mở game chơi cờ caro. Yêu cầu phải có 2 người cùng sử dụng lệnh để bắt đầu game. Sử dụng số 1-9 để chơi | `.ttt`
`.hoidap` | Hỏi bot và bot sẽ trả lời :shame: lưu ý câu hỏi dạng có/không | `.hoidap admin đẹp trai vl đúng không`


![Imgur](https://i.imgur.com/Xv5V68O.png)



Pokemon

Lệnh | Chức năng | Ví dụ
----------------|--------------|-------
`.attack` | Tấn công với kĩ năng được chỉ định. Dùng lệnh `.movelist` để xem các kĩ năng có thể sử dụng. | `.attack "vine whip" @aiđó`
`.movelist` `.ml` | Danh sách kĩ năng có thể sử dụng | .
`.heal` | Hồi máu cho ai đó. Hồi sinh nếu người đó đã bị thương nặng. Tốn 1 gạch | `.heal @aiđó`
`.type` | Xem chủng loại Pokemon của đối phương | `.type @aiđó`
`.settype` | Chọn chủng loại pokemon. Tốn 1 gạch. Có thể gõ `.settype` để xem toàn bộ danh sách | `.settype Fire` hoặc `.settype`

Các trò chơi ngẫu nhiên & cá cược

Lệnh | Chức năng | Ví dụ
----------------|--------------|-------
`.raffle` | Ngẫu nhiên chọn ra tên của một người đang ONLINE trong server, hoặc trong 1 role chỉ định | `.raffle` `.raffle TênRole`
`.raffleany` | Ngẫu nhiên chọn ra tên của một người trong server, hoặc trong 1 role chỉ định | `.raffleany` `.raffleany TênRole`
`.race` | Khởi động 1 cuộc đua kì thú giữa các loài động vật | .
`.jr` `.joinrace` | Tham gia cuộc đua. Có thể cược số tiền. Bạn sẽ nhận lại SốBạnCược*(SốNgườiThamGia-1) nếu bạn thắng | `.jr` `.joinrace 5`
`.roll` | Tung xúc xắc từ 0-100. Nếu thêm số `X` thì sẽ tung tới tối đa 30 con xúc xắc. Nếu tách 2 số bằng chữ cái `d` theo dạng `XdY` thì sẽ xúc xắc `X` con từ 1 tới số `Y`. Có thể thay đổi `Y` thành chữ F để xúc xắc theo kiểu Đúng/Sai (Âm/Dương) | `.roll` hoặc `.roll 7` hoặc `.roll 3d5` hoặc `.roll 5dF`
`.rolluo` | Tung xúc xắc ngẫu nhiên không sắp xếp thứ tự. Cách thức sử dụng như `.roll` | .
`.nroll` | Tung xúc xắc trong 1 khoảng chỉ định. Nếu bạn chọn một số thay vì một khoảng. Nó sẽ xúc xắc từ 0 tới số đó | `.nroll 5` hoặc `.nroll 5-15`
`.rollduel` | Thách đấu một ai đó tham gia trò xúc xắc bằng cách chỉ định số tiền sẽ tham gia và tên người muốn thách thức. Để chấp nhận lời thách thức, chỉ cần chỉ định tên người thách thức, không cần điền số tiền | `.rollduel 50 @SuHao` hoặc `.rollduel @SuHao`
`.betroll` `.br` | Cược số tiền chỉ định và tung xúc xắc. Tung được điểm lớn hơn 66 sẽ được x2 số tiền cược, trên 90 được x4, được 100 sẽ được x10 | `.betroll 5` `.br 5`
`.draw` | Ngẫu nhiên rút ra 1 lá bài trong bộ bài server. Có thể rút tối đa 10 lá bằng cách thêm số lá | `.draw` hoặc `.draw 5`
`.drawnew` | Rút ra một hoặc nhiều lá từ bộ bài MỚI. Tối đa 10 lá | `.drawnew` hoặc `.drawnew 5`
`.deckshuffle` `.dsh` | Xáo trộn lại toàn bộ bài | .
`.flip` | Tung đồng xu - Ngửa (head) hoặc sấp (tail), có hình ảnh minh họa | `.flip` hoặc `.flip 3`
`.betflip` `.bf` | Cá cược trò tung đồng xu với BOT của server xem kết quả là heads/h (ngửa) hay tails/t (sấp). Phần thưởng là 1.9x số tiền cược (có thể thay đổi). | `.bf 5 heads` hoặc `.bf 5 t`
`.wheel` | Cược số tiền vào bàn quay, quay vào số nào sẽ nhận lại phần thưởng tương ứng. | `.wheel 10`


Lưu ý: luôn vui chơi lành mạnh và biết điểm dừng, tránh như bet thủ Cứt đã phải trả giá :shame:

![Imgur](https://i.imgur.com/hvPTUZ6.png)



### NSFW

18+, không dành cho trẻ em có thai, phụ nữ có cu và người già đang cho con bú :">

Lệnh | Chức năng | Ví dụ
----------------|--------------|-------
`.hentai` | Post ngẫu nhiên một ảnh hentai từ một trang web hentai (gelbooru hoặc danbooru hoặc konachan hoặc atfbooru hoặc yandere). Có thể thêm 1 tag | `.hentai yuri`
`.hentaibomb` | Không phải một ảnh, mà là 5 ảnh :v | .
`.boobs` | Real vếu ( ͡° ͜ʖ ͡°)  | .
`.butts` `.ass` `.butt` | Real đýt ( ͡° ͜ʖ ͡°) | .


### Fun

Lệnh | Chức năng | Ví dụ
----------------|--------------|-------
`.rip` | RIP | `.rip @aiđó`
`.weather` `.we` | Thời tiết | `.we Hà Nội`
`.meow` | Mòe cute <3 | .
`.woof` | Chó cute <3 | .
`.randomimage` `.rimg` | Ảnh ngẫu nhiên với tag chỉ định | `.rimg voz`
