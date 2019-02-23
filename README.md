<h1>Tensorflow-Chatbot-1:</h1>


<h2>Usage:</h2>
<b>$ python3 data.py</b><br>
This will do all the pre-processing for the Cornell dataset.


<b>$ python3 chatbot.py --mode [train/chat/production]</b><br>
If mode is train, then you train the chatbot. By default, the model will
restore the previously trained weights (if there is any) and continue
training up on that.

If you want to start training from scratch, please delete all the checkpoints
in the checkpoints folder.

If the mode is chat, you'll go into the interaction mode with the bot.

By default, all the conversations you have with the chatbot will be written
into the file output_convo.txt in the processed folder.

If the mode is production, both train and chat will be invoked
