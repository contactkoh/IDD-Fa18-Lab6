# ChatBot

*A lab report by Hongyun Oh*
ho247@cornell.edu

## In this Report

To submit your lab, fork [this repository](https://github.com/FAR-Lab/IDD-Fa18-Lab6). You'll need to upload any code you change into your fork, as well as upload a video of a friend or classmate using your chatbot.

## Make the ChatBot your own

**Describe what changes you made to the baseline chatbot here. Don't forget to push your modified code to this repository.**

I like the question tree of the chatbot. 
So my chatbot used the features of it but added more contents and logics.
My chatbot is to allow non-English speaking users to learn English with the chatbot, by playing the Guess game with the chatbot.
Chatbot would ask questions and user would have to guess what is being described.
I used questions array and answers array to store many questions and answers to scale later. So question[1] would match to answer[1] and on each loop the chatbot can simply check if the question[index] == answer[index].
If wrong answer, the question can loop. If right answer, user can decide to go to next question or quit. 

## Record someone trying out your ChatBot

**Using a phone or other video device, record someone trying out your ChatBot. Upload that video to this repository and link to it here!**

---
Starter code by [David Goedicke](mailto:da.goedicke@gmail.com), closely based on work by [Nikolas Martelaro](mailto:nmartelaro@gmail.com) and [Captain Anonymous](https://codepen.io/anon/pen/PEVYXz), who forked original work by [Ian Tairea](https://codepen.io/mrtairea/pen/yJapwv).
