# GAMES
## Đề bài: 
 An và Bình chơi trò chơi như sau: An viết một dãy liên tiếp gồm N số 0 hoặc 1. Sau đó Bình lần lượt hỏi An các câu hỏi có dạng: Đoạn từ i đến j có chẵn số 1 hay lẻ số 1 $(i \le j)$ An sẽ trả lời đoạn từ i đến j là chẵn hay lẻ số 1. Nhưng sau một số lần hỏi, Bình biết được là An đã không trả lời đúng các câu hỏi của mình.

 **Yêu cầu**: Cho các câu hỏi của Bình và các câu trả lời của An, hãy lập trình giúp Bình tìm ra câu trả lời cuối cùng chưa mâu thuẫn. 
 ## Dữ liệu
 - Dòng đầu tiên là số N.
 - Dòng thứ hai là số K - số câu hỏi được trả lời.
 - K dòng sau, mỗi dòng mô tả câu hỏi và trả lời có dạng: hai số nguyên dương i, j cách nhau một dấu cách và cách đó một dấu cách là một xâu ‘odd’ hay ‘even’ cho biết đoạn từ i đến j có chẵn (‘even’) hay lẻ (‘odd’) số 1.
 ## Kết quả
 - Thứ tự câu trả lời cuối cùng chưa mâu thuẫn.
 
 #### Input
 ```
 5
 2
 1 2 odd
 1 2 even
 ```
 ### Output
 ```
 1
 ```