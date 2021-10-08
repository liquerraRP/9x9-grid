# 9x9-grid
## START STATE
![first_state](https://user-images.githubusercontent.com/73216938/136429766-da1fbe1e-9f69-4011-a0de-6bb30890b289.png)

### the size of the state space untuk semua kotak adalah **81!**

## DIVIDE TO 3X3 Sub-Square
![proses](https://user-images.githubusercontent.com/73216938/136429773-09307959-c3b8-4a6d-9635-fd5454930d4b.png)

 ### Given the goal, we need consider only colorings where each sub-square is uniformly colored. After we reformulate the grid form 9x9 to 3x3 sub-square, the problem and the size of the state space is **9!**

## GOAL STATE


### ada dua solusi yang dapat dilakukan untuk mencapai goal state yang dapat dilihat pada gambar dibawah
## goal state 1

![goal_state](https://user-images.githubusercontent.com/73216938/136429772-2f246a6a-bedc-4159-895a-a02f0e596e3c.png)

## goal state 2

![goal_state_2](https://user-images.githubusercontent.com/73216938/136482138-be27c810-a464-4ee7-91ab-786548d6f648.png)

### goal state 1 memerlukan jumlah states yang lebih sedikit jika diandingkan dengan goal state 2. Pada goal state 1 kita hanya perlu merubah 36 squares or 4 sub-squares untuk mencapai goal state, tetapi pada goal state 2 maka kita perlu merubah 45 squares or 5 sub-squares untuk mencapai goal state
