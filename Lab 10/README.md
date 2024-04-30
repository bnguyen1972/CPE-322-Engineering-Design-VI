# Lab 10

**Run hash_value.py twice and compare results**
![hostname](CPE_322_LAB10_1.png)

**SHA-2 Secure Hash Algorithm**
![hostname](CPE_322_LAB10_3.png)

**Build the tiniest blockchain in less than 50 lines of Python by Gerald Nash (2017-07-16)**

*cat snakecoin.py*
![hostname](CPE_322_LAB10_4.png)

*python3 snakecoin.py*
![hostname](CPE_322_LAB10_5.png)

**Let’s Make the Tiniest Blockchain Bigger Part 2: With More Lines of Python by Gerald Nash (2017-07-23)**

*Terminal 1*

*cat snakecoin-server-full-code.py*
![hostname](CPE_322_LAB10_6.png)
![hostname](CPE_322_LAB10_7.png)
![hostname](CPE_322_LAB10_2.png)

*python3 snakecoin-server-full-code.py*
![hostname](CPE_322_LAB10_9.png)

*Terminal 2*
>$ curl "localhost:5000/txion" \
>    -H "Content-Type: application/json" \
>    -d '{"from": "akjflw", "to":"fjlakdj", "amount": 3}'
>$ curl localhost:5000/mine

![hostname](CPE_322_LAB10_10.png)

**Python blockchain app by Satwik Kansal**

*first two left screens outputs should be swapped for correct order*

*Terminal 1*
![hostname](CPE_322_LAB10_14.png)
![hostname](CPE_322_LAB10_11.png)

*Terminal 2*
![hostname](CPE_322_LAB10_12.png)
![hostname](CPE_322_LAB10_13.png)

