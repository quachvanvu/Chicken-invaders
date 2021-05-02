                     ------------------------------------Quách Văn Vũ-20020505--------------------------------------



**Demo game:
	+Tên game: CHICKEN INVADERS - Giải thích tên game : ý nghĩa tên game là ' những kẻ xâm lược gà ' vì game gồm hai đối 
		tượng là những con gà và chiếc tên lửa. Chiếc tên lửa sẽ xâm lược bắn những con gà, và những con gà này sẽ 
		phải chiến đấu với chiếc tên lửa này.


	+Cách chơi: 
		-Người chơi dùng hai nút di chuyển sang trái và phải để di chuyển nhân vật " tên lửa " sau đó nhấn chuột để 
		bắn những con gà. Chuột trái sẽ bắn ra đạn laze, chuột phải sẽ bắn ra đạn tròn, khi những viên đạn này bắn trúng 
		con gà thì con gà này sẽ bị nổ. sua một thời gian thì con " boss chiken " sẽ xuất hiện nhiệm vụ của người chơi 
		là bắn con boss này cho đến khi boss nổ thì sẽ chiến thắng.

		-Nếu nhân vật tên lửa mà bị trúng đạn của gà hoặc chạm vào gà thì sẽ bị nổ tung và tên lửa sẽ có 3 mạng nếu chết đến
		mạng thứ 3 thì sẽ bị thua. Lúc đó màn hình sẽ hiển thị error:"yes" "no" nhấn chọn "yes" để chơi tiếp chọn "no" để thoát
		trò chơi.
** Cách vận hành game: Trong project gồm có các lớp đối tượng mỗi lớp đối tượng thực hiện một chứ năng trong game.
		mỗi đối tượng gồm có một file.h và file.cpp, file.h dùng để khai báo hàm và biến còn file.cpp để thực hiện 
		các hàm đó.
		
		1. CommonFunc: đưa những thành phần sử dụng chung vào đây.
		2. BaseObject : lớp đối tượng cơ sở có các thuộc tính chung. Các đối tượng khác sẽ thừa kế từ lớp này.
		3. AmmoObjec: đối tượng đạn bắn.
		4. MainObject: đối tượng nhân vật chính.
		5. ExplosionObject: đối tượng xuất hiện khi va chạm
		6. HealthObject: mạng nhân vật.
		7. ThreatsObject: đối tượng gà trong game
		8. TextObject: đối tượng text trên mà hình.
		9. game sdl : hàm chính xử lí chung