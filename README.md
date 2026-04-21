[readme.txt](https://github.com/user-attachments/files/26938504/readme.txt)
Loom is a cognitive operating system. It is designed to sit on top of any generalist LLM, turning them into thinking machines. Loom accomplishes this with a list of heuristic files.

Each heuristic is a defined process that breaks down the steps of a specific cognitive process. By chaining one heuristic into another, Loom can perform complex cognitive tasks reliably.

The long term vision of this project is to democratize this technology by making it run on desktop computers. It has been demonstrated that small models performing specific tasks with small, high quality training data can outperform the large generalist models at those specific tasks.

The plan is to use this system to generate training data. Then I will train 30 or so 7B parameter models on that data. That should create a cognitive system that you can run on desktop. No need for datacenters.

Loom uses a persistent memory state that operates on two different levels. With each turn, Loom updates a working_anchor.md file that provides immediate context and sets a heuristic to use on the next turn.

The long term memory consists of schema files, in which each element is tagged. All of the tags from all of the schema files are presented in an inverted tag map, which uses the tags as elements and the elements as tags. This is a Peripheral Awareness Index that affords the machine awareness of a lot of context, while not cluttering the context window with details that are irrelevant to any given task.

Negative instructions suck up a lot of resources and produce low quality results. The machine attempts to follow the positive instruction, puts all of the resources into predicting the token. But then it checks them against the negative instruction, and has to scrap that work and redo the prediction with a lower quality result.

Loom addresses this in two ways. Well written positive instructions do not require negative instructions. The machine just gets it right the first time. Where positive instructions are insufficient, Loom uses oppositional processes.

For instance, one process adds context to the working_anchor.md file. The next process prunes obsolete context. And the process after that checks to make sure that there wasn't any load-bearing context lost in the pruning. This is far more reliable and uses less resources than just telling the machine to prune the file with negative instructions to prevent load-bearing context loss.
