# Speedometer for cycles

Riding a cycle is fun but can get boring sometimes, so to tackle that, I put up a rechargeable speedometer on it, which with small tweaks in code, can display distance travelled by cycle too.



https://github.com/ChiragKotian/Speedometer/assets/117931123/8f22386f-ed2d-49ae-aa1e-d24cb117afc0



## Engineering Description:

The whole system is built upon Arduino Nano encased by a custom 3D-printed enclosure.

![20230505_091925](https://github.com/ChiragKotian/Speedometer/assets/117931123/cb1716fd-581c-4a3e-9547-03ab225757e6)
![20221221_193547](https://github.com/ChiragKotian/Speedometer/assets/117931123/2a550a3c-92c9-4510-bdb9-b584f27e217d)

This system uses magnets and hall sensors to count the number of revolutions taken by cycle in unit time to calculate the moving average speed of the cycle.

![image](https://github.com/ChiragKotian/Speedometer/assets/117931123/b2482d88-1064-4dc3-a97d-bd57356f87a3)

The speed thus calculated is displayed on the OLED screen attached to the enclosure.

![20221221_204132](https://github.com/ChiragKotian/Speedometer/assets/117931123/8f3bd439-70ce-42f2-b313-ddac0a9e1402)

A magnet is attached to the wheel spokes; also, 2 hall sensors are attached to either side of the bicycle fork. The reason why two hall sensors are used is that if in case the user stops the cycle exactly 
when the magnet coincides with the hall sensor or moves the cycle such that the magnet passes the hall sensor again and again, Arduino will count it as one revolution of wheels
and give ridiculous speed values. This system also helps in determining the reverse speed as by using the sequence of activation of sensors; we can calculate the direction of motion
of movement of cycle.




The entire system is powered by two Li-ion batteries which are in series while using the speedometer and while charging it, charge parallelly using TP4056 Li-ion charging boards.

![20221221_175108](https://github.com/ChiragKotian/Speedometer/assets/117931123/8a8e4dad-a51b-45da-9645-9a8173fa7be6)



The system is also equipped with a voltage monitor so that the user charges the batteries when low.

![20221221_105354](https://github.com/ChiragKotian/Speedometer/assets/117931123/984f89bd-3a79-4084-ba96-d2590b2f8892)

![20221221_105405](https://github.com/ChiragKotian/Speedometer/assets/117931123/ae3aad68-1419-4d08-9699-af561231cbde)

![20230505_091919](https://github.com/ChiragKotian/Speedometer/assets/117931123/1317cbd0-5081-4e50-80ca-e417e39acc15)

## Demonstration:



https://github.com/ChiragKotian/Speedometer/assets/117931123/5cfc90d4-da46-4923-8614-b739c6a52a25



https://github.com/ChiragKotian/Speedometer/assets/117931123/3803ed2a-83c4-4494-982c-5eb7385b6f7f



## Some Videos and Photos:

https://github.com/ChiragKotian/Speedometer/assets/117931123/adae2b78-4afb-4776-b8cd-b11a2e0c6df9



https://github.com/ChiragKotian/Speedometer/assets/117931123/0a35f298-a930-4cde-bb3f-6fc82d64a0b3



## Credits:
_This project was solely made by [Chirag Kotian](https://github.com/ChiragKotian)._
