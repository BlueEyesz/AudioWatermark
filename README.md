# AudioWatermarkDemo

Sử dụng thuật toán LSB để watemark (chèn signature) vào file nhạc  (*.WAV)

!!! LƯU Ý !!!

	* Phiên bản PHP is 7. Chỉnh lại trong file PHP's config in "php.ini"
		upload_max_filesize = 50M
		post_max_size=50M
	khi chạy.

	Định dạng tệp * .WAV cần có Tiêu đề, Subchunk1, Subchunk2, Subchunk3. Subchunk2 (SubchunkID = "LIST") 

	Tất cả các tệp âm thanh được tải lên và tải xuống từ, đều được lưu trữ trong Google Drive của mình (Mình đã sử dụng API Google Drive). Các bạn có thể thay đổi thành Google Drive của mình bằng cách thay đổi tệp có tên là "service_account_keys.json" thành JSON khóa tài khoản dịch vụ của các bạn

    *Vì kích thước tập tin lớn (30-40MB) nên bạn nên đợi 2-3 phút trước khi mua bài hát hoàn toàn. Cảm ơn!
		
!!! QUAN TRỌNG !!!

	Administrator:
		id: nguyendoanh	
		pw: nguyendoanh

	User:
		id: doanhdoanh		
		pw: doanhdoanh

