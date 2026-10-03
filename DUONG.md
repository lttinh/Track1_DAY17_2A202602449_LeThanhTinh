CHECKPOINT 1: ĐẶT GIẢ THUYẾT (PROBLEM HYPOTHESIS)

Thời lượng: 60 phút | Case B: AI Notes: Personal Learning Notes

1. Solution — Gỡ solution khỏi hình thức cụ thể
Case đã chọn: Case B — AI Notes: Personal Learning Notes
Solution directive (nguyên văn):

"Trong khi học, học viên có thể highlight một đoạn nội dung, đánh dấu “Chưa hiểu”, hoặc viết một câu hỏi hay ghi chú ngắn. Khi bài học kết thúc, AI Notes kết hợp những dấu vết này với nội dung bài để tạo một bản ghi chú có cấu trúc. Học viên có thể chỉnh sửa và xác nhận trước khi lưu."

Capability trung tính:

Khả năng tự động thu thập, liên kết các tương tác vi mô của người học (điểm chú ý, điểm nghẽn nhận thức, câu hỏi cá nhân) với ngữ cảnh bài học gốc thành một tài liệu học tập có cấu trúc, hoàn chỉnh và có thể chỉnh sửa ngay sau phiên học mà không bắt người học phải tự tổ chức thủ công.

2. Change — Làm lộ chuỗi thay đổi được kỳ vọng

Chuỗi mắt xích chuyển dịch hành vi ngầm định:

⚠️ Failed to render LaTeX: KaTeX parse error: Expected 'EOF', got '&' at position 96: …w \text{Review &̲ Sở hữu sau bài…
\text{Solution} \longrightarrow \text{Micro-action trong lúc học} \longrightarrow \text{Review & Sở hữu sau bài học} \longrightarrow \text{Outcome ôn tập & hiểu sâu}
text
Solution (Gom vết & tự động cấu trúc hoá)
  └──> [Thay đổi 1]: Học viên thoải mái đánh dấu/ghi chú tức thời mà không phải dừng mạch học để sắp xếp
         └──> [Thay đổi 2]: Học viên dành 2-3 phút sau buổi học để xác nhận bản ghi chú cá nhân hóa thay vì bỏ xó
                └──> [Thay đổi 3]: Học viên quay lại ôn tập đúng những chỗ mình từng yếu thay vì đọc lại từ đầu
                       └──> [Outcome kỳ vọng]: Tăng tỷ lệ ghi nhớ dài hạn, giảm 50% thời gian ôn tập và tự tin ứng dụng

Các thay đổi được kỳ vọng cụ thể:

Thay đổi trong phiên học (In-session behavior): Người học không còn phải "chia đôi màn hình" vừa nghe vừa gõ tóm tắt vào Notion/sổ tay; họ chỉ để lại các vi hành động (highlight, bấm "Chưa hiểu") mà không sợ bị ngắt mạch suy nghĩ.
Thay đổi ngay sau phiên học (Immediate post-session behavior): Người học có thói quen dành 2 phút cuối buổi để rà soát bản ghi chú do hệ thống dựng sẵn, biến nó thành tài sản học tập cá nhân thay vì đóng tab rời đi.
Thay đổi khi ôn tập (Retrieval behavior): Khi làm bài tập hoặc ôn thi, người học mở bản ghi chú có cấu trúc này ra để xử lý đúng các lỗ hổng kiến thức đã được gắn cờ, thay vì phải lướt lại toàn bộ video/slide bài giảng.
3. Actor — Xác định các nhóm người có liên quan
Actor	Họ đang làm gì?	Pain hoặc hậu quả có thể có	Họ hưởng lợi thế nào?
1. Học viên (Learner) (Trực tiếp dùng)	Tiếp thu kiến thức, highlight, ghi chép nháp, chụp màn hình bài giảng.	Mất tập trung khi vừa học vừa note; ghi chú rời rạc thành "nghĩa địa thông tin"; tốn hàng giờ xem lại bài khi cần ôn tập.	Có ngay tài liệu học tập chuẩn hóa, đúng trọng tâm và đúng lỗ hổng cá nhân mà không tốn công biên tập.
2. Giảng viên / Trợ giảng (Instructor/TA)	Giảng dạy, chấm bài, giải đáp thắc mắc của học viên.	Quá tải vì phải trả lời lặp đi lặp lại những thắc mắc mà bài giảng đã nói; không nắm được học viên đang "nghẽn" ở đâu.	Học viên tự giải quyết được các điểm "chưa hiểu"; có thể nhận báo cáo ẩn danh về các điểm học viên hay thắc mắc để cải thiện bài dạy.
3. Nhà phát triển học liệu (Content Creator)	Soạn bài, quay video, thiết kế quiz/tài liệu đọc.	Không biết đoạn bài giảng nào bị tối nghĩa khiến học viên bỏ ngang (drop-off).	Nhận diện được đoạn kiến thức nào có nhiều tag "Chưa hiểu" nhất để biên tập lại video/tài liệu.
Actor nhóm chọn để điều tra trước: Học viên tự học / học trực tuyến có thói quen ghi chép (Learner).
Vì sao chọn nhánh này: Học viên là người trực tiếp chịu chi phí nhận thức (cognitive cost) cao nhất, là người phải tạo ra input (highlight, tag) và là người quyết định sản phẩm đầu ra có giá trị hay bị vứt xó. Nếu học viên không cảm thấy nhu cầu tái sử dụng ghi chú sau bài học, toàn bộ giả thuyết về sau sẽ sụp đổ.
4. Situation & Job — User đang cố làm gì trong tình huống nào?
Mô tả Situation & Job:

Khi tham gia một bài học trực tuyến mới có khối lượng kiến thức dày hoặc độ phức tạp cao, học viên đang cố nắm bắt kiến thức cốt lõi và đánh dấu những chỗ mình chưa hiểu để sau này ôn lại bằng cách vừa nghe vừa bấm dừng video để chép vào sổ/Notion, hoặc dùng công cụ highlight trình duyệt, chụp màn hình slide.

Điểm bắt đầu gặp vướng mắc: Sau khi kết thúc bài học, họ có một đống ảnh chụp màn hình hoặc highlight rời rạc không ngữ cảnh; họ không có đủ thời gian và năng lượng tinh thần để ngồi tổng hợp lại thành một trang note hoàn chỉnh, dẫn đến việc bỏ quên toàn bộ.

JTBD Hypothesis:

Khi học một bài học chuyên môn mới trực tuyến, tôi muốn nhanh chóng ghi nhận lại các ý chính và các khúc mắc cá nhân mà không làm gián đoạn dòng tập trung, để có thể dễ dàng ôn tập và lấp các lỗ hổng kiến thức sau này mà không phải tốn thời gian xem lại từ đầu.

5. Pain — Viết các cách giải thích cạnh tranh
Pain Hypothesis A (Quá tải nhận thức trong lúc học - Split-attention effect):

Khi đang trong bài học trực tuyến, học viên gặp khó khăn trong việc tiếp thu và ghi nhớ vì việc vừa theo dõi bài giảng vừa phải chuyển qua lại giữa các ứng dụng để diễn đạt lại và định dạng ghi chú làm phân mảnh sự chú ý, dẫn đến bỏ lỡ kiến thức tiếp theo, ghi chép đối phó sơ sài hoặc bỏ cuộc không ghi chép nữa.

Pain Hypothesis B (Rào cản tổng hợp sau bài học - The Synthesis & Retrieval Barrier):

Khi hoàn thành bài học trực tuyến, học viên gặp khó khăn trong việc ôn tập và áp dụng kiến thức vì các dấu vết rời rạc họ để lại trong lúc học (highlight vụn vặt, ảnh chụp màn hình, câu hỏi nháp) bị mất ngữ cảnh gốc và đòi hỏi quá nhiều nỗ lực biên tập lại, dẫn đến việc các ghi chú trở thành "nghĩa địa dữ liệu" và học viên buộc phải học lại từ đầu mỗi khi cần dùng đến kiến thức đó.

Giả thuyết nhóm chọn để điều tra trước: Giả thuyết B (The Synthesis & Retrieval Barrier).
Lý do chọn:
Trigger của directive là "Khi bài học kết thúc" và output là "Bản ghi chú có cấu trúc". Trọng tâm giải pháp nhắm vào khâu tổng hợp sau học.
Người học hiện tại đã có nhiều cách đánh dấu rất nhanh (workaround có sẵn: chụp màn hình, bôi đen highlight). Vấn đề nhức nhối thực sự khiến họ lãng phí thời gian và thất thoát kiến thức nằm ở khâu chuyển đổi từ "dấu vết thô" sang "tài liệu ôn tập có thể dùng được". Nếu người học không thấy đau ở bước tổng hợp sau bài, họ sẽ không có lý do để mở bản AI Notes ra xem.
6. Evidence — Xác định điều cần tìm trước khi viết câu hỏi
Cần kiểm tra	Evidence làm nhóm tin hơn (Validation)	Evidence làm nhóm nghi ngờ hoặc bác bỏ (Invalidation)
1. Situation có thật	User kể được rõ ràng lần gần nhất (trong 7 ngày qua) họ học 1 bài online có ghi chú/highlight: nêu rõ môn học, công cụ dùng, thao tác họ đã làm.	User nói chung chung, không nhớ lần cuối mình học hay ghi chú là khi nào, hoặc thừa nhận chỉ xem thụ động chứ không bao giờ ghi chép gì.
2. Pain có ý nghĩa	User thể hiện sự bực bội khi mở lại thư mục ảnh chụp/highlight cũ mà không hiểu mình đã note cái gì; thừa nhận từng bỏ cuộc khi nghĩ đến việc ngồi tổng hợp lại note.	User thấy note nháp thế là đủ dùng; hoặc họ học theo kiểu "cần gì search lại Google/hỏi AI" chứ không cần giữ bộ note cá nhân nào cả.
3. Workaround tồn tại	User cho xem được các tài liệu thực tế: một trang Notion chia cột, một file Google Docs ghi chép dở, một thư mục ảnh chụp màn hình slide, hoặc dùng extension như Glasp/Weava.	User hoàn toàn không có bất kỳ hành động lưu trữ nào; họ chỉ dựa 100% vào tài liệu/slide có sẵn của giáo viên cung cấp.
4. Consequence tồn tại	Thi điểm kém hoặc bị kẹt trong dự án thực tế ở đúng phần kiến thức từng ghi chú sơ sài; phải bỏ ra 1-2 tiếng xem lại video x2 chỉ để tìm 1 định nghĩa.	Không có hậu quả nào: dù note lộn xộn họ vẫn qua môn, vẫn làm được việc, không thấy bị lãng phí thời gian hay giảm sút hiệu quả.
5. Pattern có lặp	Tình trạng "đầu khóa note rất hăng hái, về sau nản và bỏ xó một đống note rác" lặp lại ở hầu hết các khóa học/chủ đề họ tham gia.	Đây chỉ là một trường hợp ngoại lệ ở một môn học quá đặc thù; các bài học khác họ vẫn quản lý ghi chú rất gọn gàng.
Chốt Problem Hypothesis và park solution
Problem Hypothesis nhóm mang sang Chặng 2:

"Người học trực tuyến có thói quen đánh dấu và ghi chép nhanh trong lúc học nhưng gặp khó khăn lớn trong việc tổng hợp các dấu vết rời rạc đó thành một tài liệu học tập có hệ thống sau bài học, dẫn đến việc họ bỏ xó các ghi chú cũ và tốn nhiều thời gian học lại từ đầu khi cần ôn tập."

Điều gì phải đúng để giả thuyết đứng vững:
Người học thực sự có nhu cầu sở hữu và tái sử dụng ghi chú cá nhân để ôn tập (chứ không chỉ thỏa mãn với slide tóm tắt có sẵn của giảng viên).
Người học thường xuyên gặp rào cản về thời gian và công sức (friction) trong việc ngồi xâu chuỗi, biên tập lại các ghi chú nháp sau khi bài học kết thúc.
Việc bỏ quên ghi chú dẫn đến hậu quả có thể đo đếm được (tốn thời gian học lại, quên kiến thức khi làm bài tập/ứng dụng).
Điều gì có thể khiến nhóm sửa hoặc bác bỏ giả thuyết:
Hiệu ứng tự ghi chép (Generative Learning Effect): Người học nhận ra giá trị duy nhất của ghi chú là quá trình tự tay viết/tổng hợp bằng não của mình; nếu máy móc tổng hợp hộ, họ cảm thấy không đọng lại được gì và không muốn dùng.
Nhu cầu tra cứu tức thời thay vì ôn tập: Khi quên, họ thích dùng search engine hoặc chat với AI trên toàn khóa học hơn là đọc lại một bản ghi chú bài học cố định.
Thói quen "học một lần rồi thôi": Họ chỉ cần hoàn thành khóa học để lấy chứng chỉ/chấm điểm, không có nhu cầu thực tế phải lưu giữ hay ôn tập dài hạn.
Solution Parking Lot (Tạm cất giải pháp & Brainstorm hướng mở)
Hướng giải quyết có thể có	AI / Không sử dụng AI	Mô tả sơ bộ
1. Template Cornell tự động chèn Timestamp	Không sử dụng AI	Giao diện ghi chú chia 3 phần (Cues - Notes - Summary) gắn cạnh video; mỗi khi gõ phím hoặc bấm tag, hệ thống tự bắt mốc thời gian (timestamp) mà không cần can thiệp AI.
2. Bookmark & Review Canvas tổng hợp tĩnh	Không sử dụng AI	Sau bài học, hệ thống tự gom toàn bộ đoạn text bôi đen và ảnh chụp thành 1 trang checklist/flashcard tĩnh có link nhảy thẳng về đúng giây trong video để user tự duyệt.
3. AI Structured Summary Co-pilot (Directive gốc)	AI	AI kết hợp toàn bộ transcript bài giảng với highlight, câu hỏi và tag "Chưa hiểu" của user để viết một bản ghi chú Markdown có phân cấp, giải thích riêng cho điểm user chưa hiểu.
4. AI Spaced Repetition Quiz Generator	AI	AI tự động chuyển các đoạn highlight và điểm "Chưa hiểu" của user thành bộ câu hỏi trắc nghiệm/flashcard gửi qua email hoặc app sau 1 ngày, 3 ngày, 7 ngày để ôn tập chủ động.
5. Peer Notes Marketplace / Co-learning	Không sử dụng AI	Cho phép học viên so sánh ghi chú của mình với các bản ghi chú chất lượng cao nhất của bạn học cùng lớp đã hoàn thành bài học trước đó.