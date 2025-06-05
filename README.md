# blookchain TRO CHOI DOAN SO

⦁	TỔNG QUAN VỀ ĐỀ TÀI
1.1 Bối cảnh phát triển công nghệ
Trong thời đại công nghệ số, sự phát triển nhanh chóng của Internet đã mở đường cho hàng loạt xu hướng mới, trong đó nổi bật là sự trỗi dậy của Web3 – thế hệ tiếp theo của Internet, tập trung vào phi tập trung, quyền sở hữu cá nhân và bảo mật dữ liệu. Một trong những nền tảng cốt lõi của Web3 chính là blockchain – công nghệ chuỗi khối cho phép lưu trữ dữ liệu theo cách minh bạch, không thể thay đổi và không cần bên trung gian.
Bên cạnh tài chính phi tập trung (DeFi), một trong những lĩnh vực ứng dụng blockchain sôi động nhất hiện nay là blockchain gaming – nơi người chơi có thể thật sự sở hữu vật phẩm, kiếm được tài sản kỹ thuật số và tương tác minh bạch thông qua smart contract.
1.2 Tổng quan về trò chơi trên blockchain
Khác với trò chơi truyền thống, trò chơi trên blockchain cho phép:
⦁	Người chơi sở hữu tài sản kỹ thuật số (token, NFT).
⦁	Tính minh bạch vì dữ liệu được ghi lại trên blockchain.
⦁	Sự phi tập trung, không phụ thuộc vào máy chủ hay công ty trung gian.
⦁	Giao dịch tài sản trong trò chơi diễn ra ngang hàng giữa các người chơi.
Các trò chơi như Axie Infinity, Decentraland hay The Sandbox đã chứng minh sức hấp dẫn và tiềm năng của lĩnh vực này.

1.3 Giới thiệu về MetaMask
MetaMask là một ví điện tử phi tập trung (non-custodial wallet) được sử dụng phổ biến trong hệ sinh thái Ethereum. Nó giúp người dùng:
⦁	Lưu trữ, gửi và nhận token (ETH và ERC-20).
⦁	Kết nối với các dApp (decentralized applications).
⦁	Dễ dàng xác thực và thực hiện các giao dịch với blockchain.
Trong các trò chơi blockchain, MetaMask đóng vai trò như "tài khoản người chơi", giúp xác thực danh tính và tương tác với smart contract.
1.4 Ý tưởng trò chơi đoán số tích hợp blockchain
Trò chơi đoán số là một dạng mini-game phổ biến, có luật chơi đơn giản: người chơi chọn một số, nếu đoán trúng sẽ nhận được phần thưởng. Khi kết hợp với công nghệ blockchain, trò chơi này không chỉ mang tính giải trí mà còn thể hiện được cách các thành phần Web3 hoạt động:
⦁	Smart contract quản lý logic trò chơi và phần thưởng.
⦁	MetaMask dùng để xác thực và thanh toán.
⦁	Frontend kết nối smart contract bằng thư viện như ethers.js.
1.5 Mục đích của nghiên cứu tổng quan
Việc nghiên cứu tổng quan giúp người thực hiện:
⦁	Hiểu rõ bối cảnh và công nghệ nền tảng.
⦁	So sánh giữa trò chơi Web2 và Web3.
⦁	Xác định được tiềm năng, điểm mạnh và hạn chế của mô hình ứng dụng blockchain trong giải trí.
 5.Công cụ phát triển
Công cụ	Vai trò
Visual Studio Code	Môi trường lập trình
Hardhat	Triển khai, kiểm thử, biên dịch contract
MetaMask	Kết nối và ký giao dịch
Remix IDE	Viết và kiểm thử hợp đồng nhanh chóng
Node.js + npm	Quản lý gói và môi trường frontend
Vite + React	Khởi tạo và phát triển giao diện Web

Quy trình hoạt động của hệ thống
⦁	Người dùng truy cập website.
⦁	Frontend yêu cầu kết nối ví MetaMask.
⦁	MetaMask yêu cầu người dùng chấp thuận kết nối.
⦁	Người dùng nhập số đoán vào form.
⦁	Số đoán được gửi dưới dạng giao dịch đến smart contract.
⦁	Smart contract xử lý logic, so sánh số và phát phần thưởng nếu đúng.
⦁	Frontend hiển thị kết quả (thắng/thua).

4.4 Triển khai và môi trường hoạt động
⦁	Frontend được chạy trên môi trường localhost (npm run dev) hoặc có thể triển khai lên nền tảng như Vercel/Netlify.
⦁	Smart contract được triển khai lên Ethereum testnet bằng Hardhat.
⦁	Ví người dùng sử dụng MetaMask đã cấu hình mạng testnet và nạp ETH thử nghiệm từ faucet.

4.5 Ưu điểm của cấu trúc
⦁	Phi tập trung: Không phụ thuộc vào máy chủ riêng, mọi dữ liệu lưu trên blockchain.
⦁	Minh bạch: Người chơi có thể kiểm tra code hợp đồng và lịch sử giao dịch.
⦁	Bảo mật: Dữ liệu và logic không thể thay đổi sau khi triển khai contract.
⦁	Tương tác dễ dàng: MetaMask là ví phổ biến, giúp người dùng dễ tiếp cận Web3.



⦁	QUY TRÌNH NGƯỜI DÙNG
 Mục tiêu của người dùng
Người dùng truy cập ứng dụng với mục tiêu:
⦁	Kết nối ví cá nhân (MetaMask).
⦁	Nhập một số để tham gia trò chơi dự đoán.
⦁	Gửi giao dịch đến blockchain để kiểm tra kết quả.
⦁	Nhận thông báo thắng/thua và nhận thưởng nếu đoán đúng.

 Các bước thao tác của người dùng
Bước 1: Truy cập website trò chơi
Người dùng mở trình duyệt và truy cập đường dẫn frontend (ví dụ: http://localhost:5173 nếu chạy cục bộ hoặc đường dẫn deploy thực tế). Trang chủ sẽ hiển thị giao diện trò chơi đơn giản.

Bước 2: Kết nối ví MetaMask
⦁	Người dùng nhấn vào nút “Kết nối ví”.
⦁	Trình duyệt sẽ mở cửa sổ MetaMask yêu cầu người dùng cho phép truy cập ví.
⦁	Sau khi chấp thuận, địa chỉ ví Ethereum sẽ được hiển thị trên giao diện.
 Nếu người dùng chưa cài MetaMask, hệ thống có thể hiển thị thông báo hướng dẫn cài đặt tiện ích này.

Bước 3: Nhập số cần đoán
⦁	Sau khi kết nối thành công, người dùng sẽ thấy một ô nhập số từ 0 đến 9 (hoặc giới hạn tùy theo cấu hình).
⦁	Người dùng nhập vào số họ đoán là số “bí mật” mà hệ thống đã tạo trước đó trên smart contract.

Bước 4: Gửi giao dịch
⦁	Khi nhấn nút “Gửi dự đoán”, frontend sẽ gọi smart contract thông qua ethers.js.
⦁	MetaMask hiện cửa sổ xác nhận giao dịch: người dùng xác nhận gửi giao dịch và trả một khoản phí gas (ETH testnet).
⦁	Giao dịch được gửi lên Ethereum testnet.

Bước 5: Nhận kết quả
⦁	Sau khi giao dịch được xác nhận trên blockchain (khoảng vài giây đến 1 phút tùy mạng), hệ thống sẽ:
⦁	Hiển thị thông báo kết quả là “Đoán đúng” hoặc “Đoán sai”.
⦁	Nếu đoán đúng, người dùng sẽ nhận một phần thưởng là một lượng ETH testnet được gửi từ hợp đồng đến ví.
⦁	Nếu đoán sai, không có phần thưởng, nhưng có thể chơi lại.

Bước 6: Tiếp tục chơi hoặc rời khỏi
⦁	Người dùng có thể tiếp tục đoán số khác hoặc ngắt kết nối ví.
⦁	Dữ liệu trò chơi (kết quả, phần thưởng) đều được ghi nhận vĩnh viễn trên blockchain và có thể truy xuất qua trình khám phá block như Etherscan.

5.3 Trải nghiệm người dùng (UX)
Ứng dụng được thiết kế đơn giản, dễ sử dụng:
⦁	Giao diện trực quan, thao tác chỉ qua vài nút bấm.
⦁	Không yêu cầu đăng ký tài khoản.
⦁	Việc sử dụng MetaMask giúp xác thực an toàn và hạn chế gian lận.
⦁	Giao dịch được hiển thị công khai nên người dùng có thể tin tưởng vào tính minh bạch của trò chơi.

5.4 Những lưu ý dành cho người chơi
⦁	Đảm bảo đã cài đặt MetaMask và nạp sẵn ETH testnet từ faucet trước khi chơi.
⦁	Kiểm tra kỹ mạng testnet đang sử dụng (ví dụ: Sepolia, Goerli).
⦁	Giao dịch sẽ tiêu tốn một lượng nhỏ ETH testnet dưới dạng phí gas.
⦁	Người chơi cần kiên nhẫn chờ xác nhận từ blockchain sau khi gửi giao dịch.


⦁	ĐÁNH GIÁ
 Đánh giá về tính năng
Hệ thống trò chơi đoán số được đánh giá là hoàn chỉnh về mặt chức năng cơ bản của một ứng dụng phi tập trung (dApp). Các tính năng đã được xây dựng và kiểm thử bao gồm:
⦁	 Kết nối ví MetaMask thành công.
⦁	 Gửi số dự đoán đến smart contract trên blockchain.
⦁	 Nhận phản hồi từ hợp đồng thông minh (đúng/sai).
⦁	 Phát phần thưởng nếu đoán đúng.
⦁	 Hiển thị kết quả và quản lý trải nghiệm người dùng mượt mà.
Những chức năng cốt lõi này đều hoạt động ổn định trong môi trường testnet (Goerli hoặc Sepolia) và đáp ứng đúng yêu cầu ban đầu của đề tài.

