Deep Q Network is called DQN, is the combination of Q learning and Neural networks. If we use tabular Q learning, for each state, action we need to be stored in a table of Q_table. If in real life, the situation may be more complicated than the maze of the situation, we have billions of states. If there are the billions of states on the table, obtain and update the data from the table is not efficient. This is the reason DQN coming up. We can use the neural network to estimate the value of state, so do not need a Q_table.

System Requirement:
Ubuntu and Python 2.7

Step:
1. Install Anaconda on your computer followed by this link:
https://docs.anaconda.com/anaconda/install/linux
2. Install Tensorflow with Anaconda(Tensorflow cpu version without GPU)
https://www.tensorflow.org/install/install_linux#installing_with_anaconda
3. Install Pygame in Anaconda use the following command:
pip install pygame
4. Install Opencv in Anaconda use the following command:
conda install -c menpo opencv
5. Install Juputer in Anaconda
conda install jupyter
6. Start jupyter use the following command:
jupyter notebook
7. Enter the path where you store source code and open FlappyBirdDQN.ipynb 
8. Run the program in FlappyBirdDQN.ipynb 


