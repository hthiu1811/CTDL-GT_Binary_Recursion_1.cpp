# CTDL-GT_Binary_Recursion_1.cpp
Binary Recursion 
Nguồn tham khảo : 
* Cai đặt : 
+ Chúng ta có thể hiểu rằng: 

   - Đệ quy nhị phân là dạng đệ quy gọi hai lần chính nó. Hiểu đơn giản là trong một hàm đệ quy, mà có dòng lệnh gọi chính hàm đó hai lần nghen. 
* ví dụ :
+ ta dùng ví dụ : 
- Ta có một hàm tìm dãy số Fibonacci sử dụng đệ quy nhị phân là : 

int fib(int n){
  if(n <= 2) return 1;
  return fib(n - 1) + fib(n - 2);
}
