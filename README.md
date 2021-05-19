# Computing-Dissertation-Unity-Machine-Learning-game
# VIABILITY OF USING MACHINE-LEARNING IN GAMES.
Narukkottil Hameed Mohammed Unais 
2021
- Abstract
- Introduction
- Purpose of the Investigation
- The Context of the Investigation
- Aim & Objectives
- SMART Objectives
- Analysis and Specification
- Proposed Design
- Project Implementation
- Conclusions
- Critical Review and Reflection
# ABSTRACT
Machine Learning (ML) in games are mainly used in three major areas: Testing of ML in game, using ML for games AI and using the ML for the asset of the game. These are the major areas where all the interest has rested and use of ML as the games main mechanic has been less investigated. This can probably be attributed to the lack of computers not capable of handling real time learning capabilities and gaming community not having these model for use in game. Some of these simulations of gaming like experience do exist and uses ML to achieve it, but these are just experiences and do not provide wide variety of interaction and restrict the user from the initial setup.
This paper will create a multi-player racing game prototype where the player is racing against AI opponents where their base parameters are set, and their behavior is dictated by the Neural-Network (NN). This work will describe what sort of decisions were made with some consideration and compromises to create a good gaming experience for the player. The prototype being designed will be used to showcase that creative and inspiring game design can be created using ML and will aid the design opportunities and research in the future.
Keywords: Machine-Learning, Neural-Network, Artificial Intelligence, Game Design.
# Introduction	
In developing with machine-learning (ML), it is possible to see games that are made to specifically designed to be developed for showing the capabilities of the algorithm and systems. Games like Chess, Go and StarCraft where all games were there are set rules and goals that are well defined, so these games Artificial Intelligence (AI) were developed to satisfy the intellect of humans.
AI is a focus in the development of games for a long time, usually it takes in the form of scripted actions or non-player-character (NPC)reacting to the specific actions that is taken by the players actions. As the ML technology advances the game industry can implement more ML techs into their games. Unity game engine which is the most popular game engine used for developing for small titles as well as big ones have ML-based features which has been used in research and in game development.
The AI used in games are made using traditional programing, so the AI follows a specific rule designed by the game developers. The AI is not capable of making any dynamic moves apart from the initial implementation and becomes very easy to predict or exploit. Increasing the difficulty of AI will also become challenging as programming AI to do specific task will have to be taken into consideration. Making AI using traditional programming is time consuming and makes the development harder. 
In the world of gaming there is always the need to keep the games fresher or more entertaining by means of programming or better technology. Machine-Learning can be used to train the AI in such a way that the AI will be much more dynamic as it can learn more using machine learning and will make the process of programming much easier as the need for tedious programing for specific outcomes is not necessary.
# Purpose of the Investigation
The main problem that is being solved in this paper is that rubber banding issues that come up in playing racing games in normal games. In these games the AI is programmed in such a traditional way that AI player is incapable of “thinking” for itself and uses tricks and other hacks to make it look like the game is being fair. Especially the racing game have a mechanic known as rubber banding which will make the AI player move very fast in relative speed to the player as to catch up to the player or the ai will move very slowly if it sees that the player is very behind. The purpose of this mechanic is very clear it is to create an environment where the race can be enjoyed by everyone even if they are very bad at the game. But this can bring a problem for players who might be very good, and they are far ahead of the AI player and the AI player will try to move past the player to make it “Fair” Even if it means by breaking the physics of the game. This can become very frustrating for the player as this can be seen as punishment for good player playing relatively well. It also brings aa situation that to win it might be better to just drive the vehicle slower.
This became a problem because the game designers never expected human players to play very well. These kinds of logic can affect players who are especially trying to speed run the game.
So, the purpose of the paper is so that an AI can be created which will be able to learn the patterns in a track and take paths which is very efficient and does not break the game.  ML allows the AI to learn way more pattern and will also be capable to make moves that will be almost impossible with traditional programming as the complex code required for it will be astronomical.
# The Context of the Investigation
ML and games are used together usually in; Game Environment being used for ML testing or demonstrating ML based game mechanics[ (David Silver, 2017), (Bowen Baker, 2020), (Volodymyr Mnih, 2013), (Ontañón, et al., 2013)], Game-AI that uses ML[ (Matos, 2014), (Ontañón, et al., 2013)], ML used for assets (Ting-Chun Wang, 2018), and finally ML beings used for performance in games[ (Sebastian starke, 2019), (Kelly, 2020)]. Riedl and Zook (Riedl, 2013) describes that the AI can be used every aspect of game development from playing role in designing, as an actor, and as a producer.
ML being used for assisting in improvement of game mechanisms have been studied and researched less that the use of ML in conventional games which just used ML to enhance the features of a game. 
Progress was slow or non-existent before the introduction of hardware’s that was capable of handling learning real-time and the unavailability of algorithms. Game experience were created in which the ML is implemented very specifically so it will only allow minimal interaction with the game and is almost like watching simulations of ML. There are also other development taking place in the ML community like HCL and ML system which allows the players to interact with the AI which is already in the process of training these are called “interactive machine learning” (Saleema Amershi, 2014) (Mick Grierson, 2017).
In the current game development environment, lot of games are focused on developing multiplayer games. Multiplayer games survive on the basis of the number of players playing a game so a game developer could use AI using machine learning to implement character AI or other AI to give the real players a feeling of higher involvement that is mimicking the other human players witch can be of ethical concern if lacking in transparency (Jacob, 2020).
Gaming industry is one of the largest growing sectors and companies can leverage the ML technology to make more advanced game which will in turn allow companies to have a more competitive advantage and a change to occur more customer base.
Gaming industry is being scrutinized for implementing a system where games containing gambling mechanics for making more profit through social engineering ML can be used in a way that these practices can be potentially implemented in a more exploitative way thus might run into legal issues (Kelly, 2020).	
# Aim & Objectives
Get a game prototype working with AI that has been trained using ML. This will provide much more varieties and different gameplay challenges than normal games.
If possible, have different modes and levels of game where the difficulty or variety can be achieved using different variation of ML. A working prototype game must be created using the above-mentioned features. The main target audience for the deliverable will be gaming industry looking for achieving better gaming AI as well as researchers who are looking for better AI to compete against humans.
# SMART Objectives
•	Make a racing game
•	Implement AI using ML
•	The ML must be implanted in the enemy player
•	ML should have a positive effect on the gameplay
•	Make sure the game is fully functional without any bugs.
# Analysis and Specification	
First the game prototype design must create then as all the actors of the games are created these actors can be turned into AI then use the ML learning to make work.
As experimental approach there will be several AI with different ML training given and they will be mixed and match to see which one will provide the most desirable results.
The following data collection methods will be used.
•	Online surveys
•	Previous industry usage.
•	Current trends
Data collection for the project will be conducted using online forums where surveys will be conducted on what the users want from and expects from usage of ML. Users will be asked to ask what extra features will be expected compared to the traditional gaming method.
Alternative methods could have been chosen like Unreal engine but developing difficulty is a higher than the Unity engine so finally the unity engine was selected.
The main resource required are the knowledge of C# to code in Unity as Unity uses C# as the programming language.
Computer capable of running the training for the ML especially the GPU as it uses TensorFlow. This can be mitigated by using google TensorFlow and offloading computer requirements to googles servers.
# Proposed Design
Here we will be looking at all design elements and explain why the decision was taken as well as a well-structured explanation of how the game is Going to work. A wireframe of the program will be shown following the explanation of what it does.
There are mainly 11 different screens for the game prototype, and it will be further detailed below.
- Main menu design

![image](https://user-images.githubusercontent.com/77618309/118789524-72dcae80-b8c7-11eb-8c41-f133b90a6560.png)

- Control’s menu design

![image](https://user-images.githubusercontent.com/77618309/118789549-7839f900-b8c7-11eb-8f0b-3a351b11bd11.png)

- Settings menu design

![image](https://user-images.githubusercontent.com/77618309/118789584-81c36100-b8c7-11eb-99bc-0422cc14a339.png)

- Difficulty menu design.

![image](https://user-images.githubusercontent.com/77618309/118789609-85ef7e80-b8c7-11eb-997c-4bfe5d2b2712.png)

- Player selection menu design

![image](https://user-images.githubusercontent.com/77618309/118789624-89830580-b8c7-11eb-97f2-5ebbdb043b79.png)

- Stage selection menu design

![image](https://user-images.githubusercontent.com/77618309/118789632-8c7df600-b8c7-11eb-929b-030cd55173a9.png)

- Level selection menu design

![image](https://user-images.githubusercontent.com/77618309/118789646-8f78e680-b8c7-11eb-96d1-9712ba323807.png)

- Confirmation menu design

![image](https://user-images.githubusercontent.com/77618309/118789657-930c6d80-b8c7-11eb-8155-cee06a079eb6.png)

- Gameplay screen design

![image](https://user-images.githubusercontent.com/77618309/118789668-96075e00-b8c7-11eb-982b-9fc01ddc8bfc.png)

- Pause menu design

![image](https://user-images.githubusercontent.com/77618309/118789681-99024e80-b8c7-11eb-9725-763ace55abf7.png)

- Result menu design

![image](https://user-images.githubusercontent.com/77618309/118789691-9bfd3f00-b8c7-11eb-95c5-57d5841f102b.png)

# Project Implementation 
The game prototype will be created in the UNITY engine. Unity engine was chosen as it is very friendly to develop on and can work on 25 different platforms.
It is the best method as it also has an open-source machine learning agent which connects to ML programs which include TensorFlow.
The main resource required are the knowledge of C# to code in Unity as Unity uses C# as the programming language. Computer capable of running the training for the ML especially the GPU as it uses TensorFlow.
First, we had to install the Python and its dependencies for everything to work. The following are the dependencies are installed.
•	Python
•	PyTorch
•	CUDA
•	ML-Agents
The main objective is to implement unity ML-Agent into a working game. A new project is created called “ML-Agent testing” to have an environment where ML-Agent can be implemented. In the Environment ML-Agent is installed from the packages. If everything is installed properly you can import the project and run the examples.
Machine learning is subset of AI where instead of explicitly programming behaviors we teach the Machine how to accomplish the behaviors. This is analogous to how we as humans learn over time such as learning how to crawl and walk when were toddlers. ML -agents toolkit is a unity feature which enables games and simulations to serve as specialized environment to train intelligent agents. In context of UNITY ml-agents are typically represented as game objects. So, training intelligent agents means we are training game Objects to accomplish a particular set of goals in our games without programing instructions to do so.
So, in our game the game is set up by having a track in it which is the level in which we want our agents to observe and familiarize with. The enemy agents are the game objects we want to train so they can achieve a goal which is driving without colliding with the track walls. So, all the observation is collected and used to train the agents. We can look at the track which we are going to train out game objects with as shown in Fig 7.1. Inside this game objects we have two more game objects called the Décor, the meshes that make up the trach and a series of agent checkpoint colliders as seen in Fig 7.1.
- Fig 7. 1 Training Track

![image](https://user-images.githubusercontent.com/77618309/118789714-a28bb680-b8c7-11eb-8224-c475129251f2.png)

These colliders help move the training agent to move in the correct direction during training. In the track game object, there is a component called Debug Checkpoint Ray this helps to identify the order of the check points and their relative directions. Typically, the colliders must be in order and facing the forward direction in the track because this greatly help our agents to learn the environment. 
So, the agent we intent to train is the ML_Enemy which will racing against the player. This agent is the same as the player but with the exception that there is an added behavior parameters and Kart Agent component Fig 7.2. Behavior parameter allows the agents how we should allow the agent to interpret its own actions. We want the agents to mimic the actual human players by generating input data like that of a controller or keyboard. This is done in the vector actor configuration of the behavior parameters a vector action type of discrete means that we define the actions to be an array of integers. For the game we define two branches which are representative of our x and y input axis. By defining branch 0 size to three we allow the agent to understand there are three possible integer values that are generated for the x input axis 0,1, and 2. A branch 1 size of two indicates there are two possible integer values that can be generated for the y axis 0 and 1. 
Now we can look at the Kart Agent components Fig 7.2. The kart agent component is the primary agent components which will observe the training environment and generate the inputs needed to drive the kart. If we view the observation params we define how the agent will define the environment by using the transforms defined in the sensors raycast distance and Mask fields. At each training step the agent will raycast in a radial ark and will determine how close it is to the track walls if the agent is too close to the wall. Then a crash is detected you can manipulate what it means to be too close to the wall by modifying the hit threshold of each sensor field. The hit threshold is typically a value between zero and 1 and is the fraction of the value defined by the distance. By viewing the colliders fields in the check point section of the kart agent component we can see that agent check point colliders that was previous in the track in the scene is now assigned to the agent these colliders simply help the agent in the right direction when driving.
- Fig 7. 2 Behavior Parameters

![image](https://user-images.githubusercontent.com/77618309/118789733-a7506a80-b8c7-11eb-9cc1-97d16575118b.png)

With reinforcement learning we can reward the agent when it successfully drives towards the check points and discourage the agent if it crashes into the track walls. After successfully completing the number of steps defined in the kart agent components, max step field or crashing. The agents reset on a random checkpoint and trains again. This allows the agent to adopt a strategy of trail and error to infer what kind of input works. We can adjust the rewards in the rewards section in the kart agent component.  We generally want to give the agent small rewards when it moves toward the checkpoints and large reward when it is passing through the checkpoint. This introduces a positive feedback for the agent as it trains over time.
- Fig 7. 3 Kart Agent

![image](https://user-images.githubusercontent.com/77618309/118789759-addee200-b8c7-11eb-97f8-c9ad362fc615.png)

To train the AI first we must create a virtual environment in the game project path as show in Fig 7.4. This creates a virtual environment for python specifically for the project instead of a global one which will be used in every subsequent python related projects. To activate the virtual environment on windows and installing the ML-Agent dependency is shown in Fig 7.4. This package will also install TensorFlow and the Unity ML agent’s bindings that allow communication between a unity training instance and TensorFlow. Now go back to the Unity editor. Make sure the mode field in Kart agent is set to training instead of inference in kart agent component. To train agents brain fasted you can duplicate the kart classic ML agents as many times as needed but the more agents you add the slower the simulation runs adding more agents will allow for more observation to be processed and will contribute to the single brain that is learning but will not mean you are training multiple brains simultaneously.
- Fig 7. 4 Installing mlagents dependency

![image](https://user-images.githubusercontent.com/77618309/118789779-b2a39600-b8c7-11eb-818e-2f79503c0c0c.png)

In the command prompt run the command shown in Fig 7.5. This will make the unity editor start training the game object with all out parameters.
- Fig 7. 5 Training the game object

![image](https://user-images.githubusercontent.com/77618309/118789791-b59e8680-b8c7-11eb-99c1-220ff8fa0de4.png)

To stop Training press the play button in the editor and the trained brain will be saved at the path to your projects like shown in Fig 7.6.
- Fig 7. 6 Stopping and saving trained NN file.

![image](https://user-images.githubusercontent.com/77618309/118789800-b8997700-b8c7-11eb-90e0-d2aa89178729.png)

Import the NN file that was trained into the project and assign it to behavior parameters components model field in the Enemy game object. To view the result just change the mode field in the Kart Agent from training to inference. Then press the play button again to see the result of the training.
Thus, we have successfully implemented ML-agents into our game. The rest of the game can be built around this now and the final game can be exported to an EXE file to run and play in different computers.


All the main testing went smoothly, and the testing provided very consistent and stable game. When it came to testing AI all the AI behaved just like how they were trained and followed the path.
# Conclusions
This report successfully showed a prototype which uses the ML to create a NN model and use that NN model to race against the player. And the player can be engaged in the gameplay even though the player racing against an AI. Through this prototype we can discuss the use of game design choices which can be focused on ML-mechanics and will inspire game design. The future of gaming will be AI based as AI is getting capable of learning more and more complex pattern and hardware comes out to support these changes the future will be such a way that AI will be almost unrecognizable from a human player because machines learning and watching the patterns of humans.
This shows a scenario where the base games where already built, and the AI had to be used to enhance it. It also relies on the pre trained data algorithms. Once the ML can be done in real time it will make a huge impact as the AI could adapt to the player as the player is playing and would not have to deal with the limitation of using a pre trained model. AIs could also take part in making and development of games itself as the Design, gameplay and other mechanics can be made using patterns from previous games data’s, this can be used to make future research.
# Critical Review and Reflection
The most important thing to take away is that ML is not going to drastically change the Game design or any other aspect of gameplay mechanics soon. It can only be used to enhance the gameplay. And, if developers are willing to put time competent Ais can be implanted, but that is a point for the ML as it needs minimal work. 
The main hurdle towards making ML a widespread industry use is to make complex behavior to happen and as how the current situation is training these nuances with the AI takes time and the parameters that are already being set up to train the AI itself could be wrong. Only after training the AI any result can be inferred. Also, AI can behave in a unexpected ways and the developers might not know why since it uses NN and its working is invisible to the humans and the other hand traditional programming allows programmers to pin point any behavior problem given enough time.






