# 9x9-grid
## START STATE
![first_state](https://user-images.githubusercontent.com/73216938/136429766-da1fbe1e-9f69-4011-a0de-6bb30890b289.png)

### the size of the state space is **81!**

## DIVIDE TO 3X3 Sub-Square
![proses](https://user-images.githubusercontent.com/73216938/136429773-09307959-c3b8-4a6d-9635-fd5454930d4b.png)

 ### Given the goal, we need consider only colorings where each sub-square is uniformly colored. After we reformulate the grid form 9x9 to 3x3 sub-square, the problem and the size of the state space is **9!**

## GOAL STATE
![goal_state](https://user-images.githubusercontent.com/73216938/136429772-2f246a6a-bedc-4159-895a-a02f0e596e3c.png)

### Solusi dari masalah ini yaitu 9 x 9 Kotak adalah state awal pengerjaan
dengan membagi 3 x 3 sub kotak untuk mewarnai sub kotak sesuai dengan warna
yang di tentukan sehingga solusi untuk mewarnai setiap sub kotak adalah 81
