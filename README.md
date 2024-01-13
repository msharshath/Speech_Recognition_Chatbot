# Scripted Chatbots

Scripted ai chatbots are chatbots that operate based on pre-determined scripts stored in their library. 

When a user inputs a query, or in the case of chatbots with speech-to-text conversion modules, speaks a query, the chatbot replies according to the predefined script within its library. 

One drawback of this type of chatbot is that users must structure their queries very precisely, using comma-separated commands or other regular expressions, to facilitate string analysis and understanding. 

This makes it challenging to integrate these chatbots with NLP-supported speech-to-text conversion modules, and they are rarely suitable for conversion into intelligent virtual assistants.

**Installing Packages required to Build Speech Recognition Chatbot**

pip install SpeechRecognition  #(3.8.1)

pip install gTTS  #(2.2.3)

pip install transformers  #(4.11.3)

pip install tensorflow #(2.6.0, or pytorch)

pip install pyaudio

NLP or Natural Language Processing has a number of subfields as conversation and speech are tough for computers to interpret and respond to. One such subfield of NLP is Speech Recognition. 
Speech Recognition works with methods and technologies to enable recognition and translation of human spoken languages into something that the computer or AI chatbot can understand and respond to.

For computers, understanding numbers is easier than understanding words and speech. 

When the first few speech recognition systems were being created, IBM Shoebox was the first to get decent success with understanding and responding to a select few English words. 

Today, we have a number of successful examples which understand myriad languages and respond in the correct dialect and language as the human interacting with it. Most of this success is through the SpeechRecognition library.

So here, A **popular Google API** is used.

The first task that our chatbot must work for is the speech to text conversion. Basically, this involves converting the voice or audio signals into text data. 

In summary, the chatbot actually ‘listens’ to your speech and compiles a text file containing everything it could decipher from your speech. 

You can test the codes by running them and trying to say something aloud. 

It should optimally capture your audio signals and convert them into text.

