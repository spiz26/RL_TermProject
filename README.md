# RL_TermProject

|   MDP  |                                                                                          Contents                                                                                         |
|:------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| State  | ① Velocity of Kart  ② Rays of distance between kart and the object * 9  ③ Inner product value between the next destination and the kart direction vector of the kart  ④ Kart acceleration or not |
| Action | ① [left, straight, right]  ② [accleration, stop, brake]                                                                                                                                    |
| Reward | ① hit: -2  ② pass next goal: 1  ③ velocity of kart is 0: -0.002  ④ Inner product value: 0.03                                                                                                 |

state는 위 표의 state를 4개 쌓은 벡터를 사용한다.
