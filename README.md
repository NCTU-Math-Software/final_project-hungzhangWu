# final_project-hungzhangWu 
# Project 16
已知 1^1+2^2+3^3+......+10^10=10405071317.
找出 1^1+2^2+3^3+......+1000^1000 的小數點前十位數字


# Method of using the function
可輸入任意正整數(參數為X)來獲取小數點前十位數字，但是若想在1分鐘內跑完，建議輸入的正整數不要超過45000 。
例如: Input X=10，可以得到 0405071317 ;
      Input X=100，可以得到 9027641920 ;
      Input X=1000，可以得到 9110846700 。
      

# The idea of the project
這個專題是為了找出極大數字的好幾次方的前10位數字，由於電腦無法跑出準確數字，所以只取前十位數字，
藉由這個概念 ，我們可以將X^X 拆成X乘以自己X次，可以利用函數1的for迴圈來得出答案。
每當for迴圈跑一次，便會判斷是否超出10位數，也就是判定是否大於等於10^10，如果超出，就會只留下那個數的小數點前10位數字，然後在加起來，
加起來的同時還會再判斷一次是否和前面的數加起來會超過10位數，如果超出，便會用到函數2，而函數1和函數2差不多，
最後便會呈現出使用者輸入的參數的答案。



