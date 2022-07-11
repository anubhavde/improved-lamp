# improved-lamp

Installed a custom gym environment created to play TicTacToe and implemented an Agent using Temporal Difference Learning to play TicTacToe. Also humans can play TicTacToe with my trained agent in this environment. Finally, created a GUI for the game. I have used Python 3.8.12.

### Objectives
- Install custom OpenAI Gym environment built to play TicTacToe.
- Demonstrate Reinforcement Learning and Temporal Difference Learning.
- Create Agent using Temporal Difference Learning to play TicTacToe.
- Train & Test agents using this environment.
- Play games AGAINST trained agent.

### Setup
First we need to install the required libraries of python i.e OpenAI Gym using the command:
```
!pip install gym
```
#### Install Custom Gym Environment
To install the environment files that we need for playing TicTacToe, we have run the following command:
```
!wget https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/playing-tictactoe-with-reinforcement-learning-and-openai-gym/gym-tictactoe.zip
```
The output should resemble something like this:
```
--2022-07-09 09:09:12--  https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/playing-tictactoe-with-reinforcement-learning-and-openai-gym/gym-tictactoe.zip
Loaded CA certificate '/etc/ssl/certs/ca-certificates.crt'
Resolving cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud (cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud)... 169.63.118.104
Connecting to cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud (cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud)|169.63.118.104|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 10119 (9.9K) [application/zip]
Saving to: ‘gym-tictactoe.zip’

gym-tictactoe.zip   100%[===================>]   9.88K  --.-KB/s    in 0s      

2022-07-09 09:09:14 (91.2 MB/s) - ‘gym-tictactoe.zip’ saved [10119/10119]
```
Next, we have to unzip 
