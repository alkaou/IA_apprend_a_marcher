





quick overview:
	- my_config.yaml in the config directory
		In particular, need to choose the environment, ie the game. If the game has not been used yet, you need to add the mapping to play the game in pygame in the file human_play.py. For that, you need to read the doc for this specific game on gym website, and find all the possible actions. 
	- human_play.py to play as human
	- train.py to to train.
		To see nice charts during training, just open another terminal and the type the command:
		tensorboard --logdir=logs
	- AI_play.py to watch a model try to walk after training.
		Make sure to 
		a/ select the correct path to the saved model
		b/ select the correct model type, for example: PPO in  PPO.model()


Enjoy


