# MDP REPRESENTATION

## AIM:
To represent any one real-world problem in MDP form.

## PROBLEM STATEMENT:
To develop a game application the role of the agent is to promote if the level is cleared or depromote if the game is loss

### Problem Description


### State Space
{A1,A2,A3}--> {0,1,2}
A1--> LEVEL 1
A2--> LEVEL 2 
A3--> LEVEL 3

### Sample State
A1--> 0 --> LEVEL 1

### Action Space
{W,L}-->{0,1}
W-->True
L-->False

### Sample Action
W--> 0 --> True

### Reward Function
R = { +1 , if we come closer to the winning
       0 , if not

### Graphical Representation


## PYTHON REPRESENTATION:
P = {
    0:{
        0: [(0,1,1,True)],
        1: [(1.0,0,1.0,False)]
    },
    1:{
        0: [(0,2,1,True)],
        1: [(1,0,1,False)]
    },
    2:{
        0: [(0,2,1,True)],
        1: [(1,1,1,False)]
    }
}
P

## OUTPUT:
Write your Python output here

## RESULT:
Write your output here

