# Performing Cartpole environment using Actor-Critic agent

## Introduction to Cartpole

### I still remember starting my Systems Engineering course with Cartpole environment by interacting and printing the observation spaces and action spaces. Cartpole is always special to me..!
### Cartpole is  just a simple game with hanging pivot over the axis and supporting structure on the bottom. The main concept of Cartpole is to support the hanging pendulum over the pivot point. Anyhow its not as easy as we said ! what makes it more difficult ? Is it not easy to maintain the Centre of gravity of the pendulum over the pivot point! But wait ... it gets more complicated when it is completly controlled by the brain of computer.Okay lets get into Technical part...!
### Here i have used Gym Environment as a Reference. https://gym.openai.com/envs/CartPole-v1/
### The observation space has 4 input values [dispalcement, velocity, theta, angular velocity] and 2 action values [left, right] either 0 or 1 in order to move the pendulum position to balance the CG of the pendulum. Reference .. ###### https://towardsdatascience.com/how-to-beat-the-cartpole-game-in-5-lines-5ab4e738c93f#:~:text=CartPole%20is%20a%20game%20in,the%20power%20of%20machine%20learning.&text=Although%20it%20is%20only%205,completely%20beats%20the%20CartPole%20game.
![1_vslpUR9-ii_T-flNmmvgXg](https://user-images.githubusercontent.com/77123547/117442632-52ac0780-af37-11eb-83b9-5f28554e2f8f.png)

