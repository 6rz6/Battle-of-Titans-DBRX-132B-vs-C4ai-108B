## Huge Battle of Titans DBRX 132B ⚔ C4ai-108B - [Collection page](https://huggingface.co/collections/AI6rz/132b-dbrx-instruct-5-x-7b-36b-output-vs-c4ai-104b-output-661aa042a12a10bd0d6e003e)

#### [DBRX](https://huggingface.co/databricks/dbrx-instruct) 132B (MOE) 5x7B-Instruct-36B is Fast Accurate and extremely suitable for complex tasks with low margin for error. 
Best use cases IMO are fast decision making situations like automated driving where a split of a second or any mistake can cost dearly
and an accurate swift resoponse would be the game changer.

####  [C4ai-r-Plus](https://huggingface.co/CohereForAI/c4ai-command-r-plus) is a fast 108B Endless token output  has the largest output context window i've encountered, 
suitable for summarizing and analyzing large amounts of data in a very short time, with low resource demands. 
suitable for writing and working with large amounts of text where quantity has higher priority than quality. 
amazing for research and summarization & Translation.

The task I comapred them with was a fraction of the original task i've tested C4ai with, due to the smaller 32k output context window of DBRX, but never the less, 
the answer it gave with a lot less information was far more accurate compared to the 50,000 character C4ai output in less than 10 minutes (!)

```
  [reminder]This is the summary of the project we are working on:
    my plan is to create out of the box edge cases of combinations of ML, LLMs Automation using open-interpreter which will each own a pod with an OS of his
    choice and allow each trained micro LLM to manage the pod as he desires (like its house and garage workshop) while the k8s cluster will be the parallels to a street where each a machine running a cluster
    of pods (is a Node) and the node network will be the equvilant to a neighborhood which will act as a 'SIMcity' of AI's each with the freedom to interact with its neighbors (or not) write any code he feels
    would contribute to the AI sim society (or some will choose to be villain's and disrupt their surroundings). I have already experimented with a cluster of 3 pods on 2 different nodes instructing
    them 2 things 1. gave them a task to replicate meaning create more pods with interpreters connected to an LLM (reproduction) and 2. build me a UI which i can see whom says what to whom while i see in real
    time their plans conversations, successes and failures. I have in the UI an input filed where i can send a message to one or all the SimAIs directing them if they get stuck in a loop and re-enforced training them
    to be productive and cooperative with each other.
[/reminder]
  [task]Think of me as a student with zero knowledge beyond Docker and Linux as base ---->> List each of the following docker images describe it and grade it according to how much it overall suits the project[/task]  
  [options]Jupyterlab,Argilla, Livebook, LabelStudio, AimStack, AutoTrain, Shiny (R), Shiny (python), ZenML, ChatUI, Panel, Giskard, and Quarto.[/options]
```

