# RL_TermProject

|   <span style = "background-color : lightgray">MDP</span>  |                                                                                          <center>Contents</center>                                                                                         |
|:------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| State  | ① Velocity of Kart <br> ② Rays of distance between kart and the object * 9 <br> ③ Inner product value between the next destination and the kart direction vector of the kart <br> ④ Kart acceleration or not |
| Action | ① [left, straight, right] <br> ② [accleration, stop, brake]                                                                                                                                    |
| Reward | ① hit: -2 <br> ② pass next goal: 1 <br> ③ velocity of kart is 0: -0.002 <br> ④ Inner product value: 0.03                                                                                                 |

state는 위 표의 state를 4개 쌓은 벡터를 사용한다.
