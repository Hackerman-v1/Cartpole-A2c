# Performing Cartpole environment using Actor-Critic agent

## Introduction to Cartpole

 I still remember starting my Systems Engineering course with Cartpole environment by interacting and printing the observation spaces and action spaces. Cartpole is always special to me..!
 Cartpole is  just a simple game with hanging pivot over the axis and supporting structure on the bottom. The main concept of Cartpole is to support the hanging pendulum over the pivot point. Anyhow its not as easy as we said ! what makes it more difficult ? Is it not easy to maintain the Centre of gravity of the pendulum over the pivot point! But wait ... it gets more complicated when it is completly controlled by the brain of computer.Okay lets get into Technical part...!
Here i have used Gym Environment as a [Reference...](https://gym.openai.com/envs/CartPole-v1/)
 The observation space has 4 input values [dispalcement, velocity, theta, angular velocity] and 2 action values [left, right] either 0 or 1 in order to move the pendulum position to balance the CG of the pendulum. [Reference..](https://towardsdatascience.com/how-to-beat-the-cartpole-game-in-5-lines-5ab4e738c93f#:~:text=CartPole%20is%20a%20game%20in,the%20power%20of%20machine%20learning.&text=Although%20it%20is%20only%205,completely%20beats%20the%20CartPole%20game)
![1_vslpUR9-ii_T-flNmmvgXg](https://user-images.githubusercontent.com/77123547/117442632-52ac0780-af37-11eb-83b9-5f28554e2f8f.png)

## Before Training 
 Initially the pendulum tends to ocillate because created actor critic network does not what action to be taken and performs actions randomly. This is because the neural network certainly has been intiallised and hyperparameters are intiallised to the random values. Hence the performance of neural network looks similar to this.
![Before-training](https://user-images.githubusercontent.com/77123547/117444505-d961e400-af39-11eb-82ec-22eb4dba6624.gif)

## Training Usind Actor critic agent.


![After-training](https://user-images.githubusercontent.com/77123547/117444526-e2eb4c00-af39-11eb-811e-6245f690bd43.gif)

![a2cstepsvsepi](https://user-images.githubusercontent.com/77123547/117444571-f1d1fe80-af39-11eb-8200-043bb1f356fb.png)
![a2crewardvsepi](https://user-images.githubusercontent.com/77123547/117444572-f26a9500-af39-11eb-94e1-ea54e6f4de46.png)
![a2closs](https://user-images.githubusercontent.com/77123547/117444573-f3032b80-af39-11eb-988a-b2495a00a60b.png)


