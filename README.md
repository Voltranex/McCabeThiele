# McCabe–Thiele method

The McCabe–Thiele method is considered to be the simplest and perhaps most instructive method for the analysis of binary distillation. This MATLAB script allows 2 main features. One of them is using excel database to draw boiling point curve and equilibrium diagram of binary components using the combination of Antoine equation and Raoult's law. Second methods is takes the xA, yA equilibrium values to draw equilibrium diagram. 

After equilibrium diagram drawn, the second script called graphandler performs McCabe-Thiele method to calculate theorotical stage number, minimmum stage number and minimum reflux ratio graphically. Just run the mcCabeThiele.m file,

Here is the example of usage:

Choosing the method

![alt text](https://media.discordapp.net/attachments/861530555715682304/861530604251250698/Screenshot_1.png)

# Method a (From database)
Number of the components choosen from component list.pdf than pressure of the system is defined
![alt text](https://media.discordapp.net/attachments/861530555715682304/861530992593862656/Screenshot_2.png)

Here is the output of the Benzene and Toluen binary mixture;
<a href="https://github.com/Voltranex/McCabeThiele/edit/main/README.md">
  <img align="left" src="https://media.discordapp.net/attachments/861530555715682304/861531660243042304/antonie.png" />
</a>
<a href="https://github.com/Voltranex/McCabeThiele/edit/main/README.md">
  <img align="center" src="https://media.discordapp.net/attachments/861530555715682304/861531661027246080/Antoniexaya.png" />
</a>

McCabeThiele method option;
![alt text](https://cdn.discordapp.com/attachments/861530555715682304/861532957638262814/Screenshot_4.png)

![alt text](https://cdn.discordapp.com/attachments/861530555715682304/861532966852886528/Screenshot_5.png)

Here is the results of  McCabeThiele method

![alt text](https://media.discordapp.net/attachments/861530555715682304/861532872711864330/McCabe-Thiele.png)

Red lines represents theorotical stage number, dashed black line is feed line and the black line represents minimum stage number.

![alt text](https://cdn.discordapp.com/attachments/861530555715682304/861532965933547520/Screenshot_6.png)


# Method b (From user given data)
![alt text](https://media.discordapp.net/attachments/861530555715682304/861534004251197490/Screenshot_7.png)

xA, yA values must be an array as shown below.
![alt text](https://media.discordapp.net/attachments/861530555715682304/861534005584592927/Screenshot_8.png)
Here is the output without McCabeThiele method
![alt text](https://media.discordapp.net/attachments/861530555715682304/861535485864050698/untitled.png)

Example of q defined feed condition;
![alt text](https://media.discordapp.net/attachments/861530555715682304/861534006813917184/Screenshot_9.png)
![alt text](https://media.discordapp.net/attachments/861530555715682304/861534008441176084/Screenshot_10.png)
![alt text](https://media.discordapp.net/attachments/861530555715682304/861534009438896188/Screenshot_11.png)

Here is the results of  McCabeThiele method
![alt text](https://media.discordapp.net/attachments/861530555715682304/861535278555856896/McCabe-Thiele.png)
Red lines represents theorotical stage number, dashed black line is feed line and the black line represents minimum stage number.
![alt text](https://media.discordapp.net/attachments/861530555715682304/861536391195262976/Screenshot_13.png?width=953&height=188)


Thank you for time, for any suggestion or possible bug contact with me via e-mail or pull a request.











