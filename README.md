![n8n](https://img.shields.io/badge/n8n-certified-red)
![AI-Agent](https://img.shields.io/badge/AI--Agent-Brain--Memory--Limbs-blue)
![License](https://img.shields.io/badge/License-MIT-green)


# An-Introduction-of-AI-Agents
This is just a testing/beginner project aimed to understanding the AI agent properly and what they can do when trigggered. It is aimed at understanding what Ai Agents can do. It is my life's first ever successfu AI automation system. I am also uploadig its photo help others build their simple E-mail sender.

Now let's understand what an AI Agent is basically

  AI Agent: An AI Agent is an automated software combining mutiliple external softwares that do tasks autonomously. In simple terms, you can say them as workers who work 24/7 non-stop which is the basic difference between a normal human and an AI Agent. Once they are properly setup, they ca run 24/7 and do tasks autonomously. It saves a lot of time and toil.

<img width="912" height="506" alt="workflow - Copy" src="https://github.com/user-attachments/assets/8279c3f2-2dce-4b32-9590-8c17e0797568" />

 An Ai Agent has three core parts to function properly. They are:
        
 1) Model: An Ai Agent's most important and significant part is its Model. They are know as LLM(Large Language Models). If you compare an Ai Agent with a human, then the Model will be the Ai Agent's Brain. They are the main commander of an AI Agent.

<img width="912" height="506" alt="workflow model" src="https://github.com/user-attachments/assets/9a0e6342-7674-49c9-83af-fd5e6fb7997c" />


Here in this picture the squared node is called Model(LLM). The model here is Google Gemini chat model, a model of Google.


  There are basically thousands of LLMs in the world. You may choose one based on its Accuracy, Quality, Cost, Latency and Context.


  2) Memory: A memory is a place where the output(given by the LLM) or input(from previous outputs) are stored. Memories are important for real life usage.

 <img width="912" height="506" alt="workflow memory" src="https://github.com/user-attachments/assets/f41af3f4-45f0-4b23-ac4a-56138e98436e" />


 Here I used Redis. You may also use Postgres, Mongo DB or Xata.


 3) Tools: Tools are the main functioning part of an AI Agent. They are like limbs of an AI Agent. They interact with other based on the commands, provided by the LLMs, and previouse data, stored on memory. You can add multiple tools to a single AI Agent. A single tool can also perform multiple types of tasks.

<img width="912" height="506" alt="workflow tools" src="https://github.com/user-attachments/assets/6022258c-2134-4fad-9be9-bae215dd28c0" />


Basically any software can be used as tools. Here I used G-mail. The tool you need to use depends on the tas you want to perform. In this project, i used G-mail tool because I built an auto E-mail sender.



If you want to get real experience, then, just download the "AI E-mail sender.json" file, import it to the n8n and execute. 

N.B. You will need to add credentials or APIs and acivate G-mail API to execute this workflow. Otherwise it won't work. So. in my next repository, I will show you how you can get credentials or APIs from Google cloud and activate the G-mail API.


If this guide helped you, please give it a ⭐ to help others find it!
