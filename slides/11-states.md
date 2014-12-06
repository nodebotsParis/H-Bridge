##  H bridge States


| S1  | S2  | S3  | S4  | state  |
|---|---|---|---|---|
|  1 | 0  | 0  | 1  | Turn left  |
| 0  | 1  | 1  | 0  | Turn right  |
| 0  | 0  | 0  | 0  | Freewheel |
| 1  | 0  | 1  | 0  | Brakes |
| 0  | 1  | 0  | 1  | Brakes |
| 0  | 0  | 0  | 0  | Short ! |
| 1  | 1  | 0  | 0  | Short ! |
| 0  | 0  | 1  | 1  | Short ! |
| 1  | 1  | 1  | 1  | Short ! |

![image](../images/hbridge.png)
