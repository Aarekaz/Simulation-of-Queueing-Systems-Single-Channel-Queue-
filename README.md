## Simulation of Queueing Systems(Single-Channel Queue) Solved in C Program

### Example

A grocery store has one checkout counter. Customer arrive at this counter at random from 1 to 8 minutes apart and each interval time has the same probability of occurrence. The service time vary from 1 to 6 minutes, with probability give below:

| Services (minutes) |  1   |  2   |  3   |  4   |  5   |  6   |
| ------------------ | :--: | :--: | :--: | :--: | :--: | :--: |
| Probability        | 0.10 | 0.20 | 0.30 | 0.25 | 0.10 | 0.05 |

#### Simulate the arrival of 10 customers and calculate: <br>

a) Probability that a customer has to wait <br>
b) Probability of a server being idle
c) Average service time <br>
Use the following sequence of random numbers: <br>

| Random digit for Inter-arrival time | 302 | 915 | 48  | 235 | 15  | 500 | 650 | 423 | 258 | 700 |
| ----------------------------------- | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: | :-: |
| Random digit for service time       | 83  | 45  | 74  | 65  | 17  | 79  | 30  | 61  | 89  | 20  |

Customer arrive at this counter at random from 1 to 8 minutes apart and each interval time has the same probability of occurrence.
So, Probability 1/8=0.125

| Time between arrival | Probability | Cumulative Probability | Random digit for assignment |
| :------------------: | :---------: | :--------------------: | :-------------------------: |
|          1           |    0.125    |         0.125          |            1-125            |
|          2           |    0.125    |          0.25          |           126-250           |
|          3           |    0.125    |         0.375          |           251-375           |
|          4           |    0.125    |          0.5           |           376-500           |
|          5           |    0.125    |         0.625          |           501-625           |
|          6           |    0.125    |          0.75          |           626-750           |
|          7           |    0.125    |         0.875          |           751-875           |
|          8           |    0.125    |          1.00          |           786-000           |

**Table: Distribution time between arrival** <br>

The service time vary from 1 to 6 minutes, with probability give below:

| Services (minutes) |  1   |  2   |  3   |  4   |  5   |  6   |
| ------------------ | :--: | :--: | :--: | :--: | :--: | :--: |
| Probability        | 0.10 | 0.20 | 0.30 | 0.25 | 0.10 | 0.05 |

| Service TIme | Probability | Cumulative Probability | Random digit for assignment |
| :----------: | :---------: | :--------------------: | :-------------------------: |
|      1       |    0.10     |          0.10          |            1-10             |
|      2       |    0.20     |          0.30          |            11-30            |
|      3       |    0.30     |          0.60          |            31-60            |
|      4       |    0.25     |          0.85          |            61-85            |
|      5       |    0.10     |          0.95          |            86-95            |
|      6       |    0.05     |          1.00          |            96-00            |

**Table: Service time distribution**

## Project Flowchart

![simulation-of-queueing-systems-single-channel-queue-flowchart](https://user-images.githubusercontent.com/15130238/50600884-b728a900-0edc-11e9-98eb-3cbe327b8f8a.jpg)

```



## Project Output
![simulation-of-queueing-systems-single-channel-queue](https://user-images.githubusercontent.com/15130238/50599879-8004c880-0ed9-11e9-95fb-5ac28be8dde4.png)
```
