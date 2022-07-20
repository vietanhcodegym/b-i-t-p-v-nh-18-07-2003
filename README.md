## Bài 1: Theo luật từ năm 2020 thì mức giảm trừ gia cảnh được áp dụng cho bản thân người đóng thuế là 11 triệu/tháng. 
#Mức áp dụng đối với người phụ thuộc là 4,4 triệu/tháng. 
#Thu nhập tính thuế thu nhập cá nhân là thu nhập còn lại sau khi tổng thu nhập đã trừ đi các tổng giảm trừ gia cảnh. 
#Nhập tổng thu nhập trong tháng của một người, số người phụ thuộc. Tính thu nhập tính thuế TNCN của người đó.

#tongtienluongnhanduoc
luong=int(input('Nhập vào tổng tiền lương nhận được: '))
khoanmienthue=int(input('Nhập vào khoản được miễn thuế: '))

#Giảm trừ gia cảnh đối với bản thân người nộp thuế
a=11

#số người phụ thuộc đối với mỗi người phụ thuộc
b=int(input("Nhập vào số người phụ thuộc: "))

#Giảm trừ gia cảnh người phụ thuộc
c=b*4.4

#Thu nhập phải chịu thuế = Tổng tiền lương nhận được - Các khoản được miễn thuế.
thunhapphaichiuthue= luong - khoanmienthue

#Thu nhập tính thuế = Thu nhập phải chịu thuế - các khoản giảm trừ.
thunhaptinhthue=thunhapphaichiuthue-a-c
print("Thu nhập tính thuế là",thunhaptinhthue,"triệu đồng" )
Nhập vào tổng tiền lương nhận được: 134
Nhập vào khoản được miễn thuế: 24
Nhập vào số người phụ thuộc: 1
Thu nhập tính thuế là 94.6 triệu đồng
