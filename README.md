# ECLIPSE-Math-engine-Algorithm-unreal-engine-
This is a realtime algorithm for calculating numbers inside UE5. This algorithm is made only with blueprints and does not require installing plugins or compilers.


![unnamed(2)](https://github.com/user-attachments/assets/2f6e2ca4-16b2-4b59-8b02-69fab0b78a38)



---
# this is how it looks

<img width="422" height="314" alt="Screenshot 2025-10-10 155015" src="https://github.com/user-attachments/assets/3da39cfd-43af-4630-9820-567192c40237" />

---

# also you can make graph with it (realtime)


https://github.com/user-attachments/assets/edd0b0a0-db7c-4fc1-88b7-0d43bd7817c5

---

#so how it works??
- first your expression goes to check if you use brackets or no if you use it will calculate them first and sort them
- then the float and operation is saved in arrays  
- by using the shunting yard algorithm it organized and sort from high priority to low
- then it goes to operator mode and calculate the math
- it will replace you operations with calculated number
- then it feed to checker to check if we have another high priority function
- if it isn't it will go to next priority one
- then all your expressions will be replaced by one number and that number is the answer

# how to install
1. download the file 
2. put the file in your project content folder

---
# my algoritm my way:
- you need to keep this in mind
1. if you use brackets --->() put your math expression without space between brackets like this --> (x + x)-(x ^ 2)
2. if you dont use brackets --->() put you math expression with space like this --> x + x - 5
---
# varibles

1.code:

<img width="332" height="131" alt="Screenshot 2025-10-10 155606" src="https://github.com/user-attachments/assets/1d7a659c-4c15-4bd2-84c2-ab971c38ed4c" />

- put your math expression here like x + x

2.quantity


<img width="261" height="308" alt="Screenshot 2025-10-10 155802" src="https://github.com/user-attachments/assets/585139cc-f35c-44e6-bd83-697c3a49e729" />

- you can put a quantity in your math expersion like ---> x + x => x=3 =>> 3 + 3


---
# supported math expressions 


2. # sin
- returns the sin of x in rad
- example: sin x or sin(x + x)

  
2. # cos
- returns the cos of x in rad
- example: cos x or cos(x + x)

  
3. # tan
- returns the tan of x in rad
- example: tan x or tan(x + x)  

4. # log
- returns the log of x by  10
- example: log x or log(x + x)

4. # abs
- returns the absolute of x
- example: abs x or abs(x + x)

5. # *
- returns the multiply of x by y
- example: x * 3 or (x + 3)*(x - 2)

6. # /
- returns the divide of x by y
- example: x / 3 or (x + 3)/(x - 2)  

7. # ^
- returns the power of x by y
- example: x ^ 3 or (x + 3)^(x - 2)  

7. # #
- returns the squre root of x by y
- example: x # 2 or (x + 3)#(x - 2)  

8. # +
- returns the add of x by y
- example: x + 3 or (x + 3)+(x - 2)  

9. # -
- returns the subtraced of x by y
- example: x - 3 or (x + 3)-(x - 2)  

---

# also you can add this things in front of your expersion
1.pi

2.pi/2

3.e

example: sin pi or sin(pi + 2)
