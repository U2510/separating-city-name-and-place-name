# python-codes
import ast,sys
input_str = input()
print(input_str)
city=''
place=''
str_len=len(input_str)
#print("length of string", len_name)
for i in range(0,str_len) :
    if i%2==0 :
     city=city+input_str[i]
    else :
     place = place+input_str[i]
message1=city.rstrip('#')
message2=place.rstrip('#')
print(message1+","+message2)


