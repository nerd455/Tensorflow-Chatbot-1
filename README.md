#Tensorflow-Chatbot-1:


##Usage:
<b>$ python3 data.py</b><br>
This will do all the pre-processing for the Cornell dataset.


<b>$ python3 chatbot.py --mode [train/chat]</b><br>
If mode is train, then you train the chatbot. By default, the model will
restore the previously trained weights (if there is any) and continue
training up on that.

If you want to start training from scratch, please delete all the checkpoints
in the checkpoints folder.

If the mode is chat, you'll go into the interaction mode with the bot.

By default, all the conversations you have with the chatbot will be written
into the file output_convo.txt in the processed folder.
