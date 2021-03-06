# Iteration 1: Establishing Overall Website Architecture
The first iteration outlines the initial results of the design process for the ADD steps. In the first iteration, we are thinking very high-level. We are simply choosing what would be the best general reference architecture based on the drivers. We considered several, but ultimately decided that the **Rich Internet Application** was proven to be the most useful reference architecture for this application. 


The [full pdf](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Iteration%201%20Final.pdf) of iteration 1 will also be included.

### Step 2: Establish Iteration Goal by Selecting Drivers
Driver selection was based on what influenced the structure of the system. This helps establish the iteration goal of achieving the architectural concern of establishing an overall system structure. The drivers are listed below:
![](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Driver%20Table%20%26%20Images/driver%20table.jpg)
![](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Driver%20Table%20%26%20Images/context%20diagram.jpg)


### Step 3: Choose One or More Elements of the System to Refine
This is a greenfield development effort, so in this case the element to refine is the entire video game website system, which is shown in Figure 1. In this case, refinement is performed through decomposition.

### Step 4: Choose One or More Design Concepts that Satisfy the Selected Drivers
The following table summarizes the selection of design decisions:
![](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Design%20Decisions/Iteration%201%20Step%204.1.jpg)
![](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Design%20Decisions/Iteration%201%20Step%204.2.jpg)

The following table is the framework decision:

![](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Design%20Decisions/design%20decision%203.jpg)

### Step 5: Instantiate Architectural Elements
For the most part, the RIA reference architecture suits our use well. The only difference is that we will be making use of the Isolated Storage.

![](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Design%20Decisions/design%20decision%204.jpg)


### Step 6: Sketch Views and Record Design Decisions
The diagram in Figure 2 shows the sketch of the module view of the two reference architectures that were selected for the client and server applications. These have now been adapted according to the design decisions we have made.

![fig2](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Driver%20Table%20%26%20Images/Iteration%201%20Figure%202%20-%20Client%20and%20Server%20Side%20Architecture.jpg)

Each of the elements that have been selected is explained with a short description of its responsibilities. The following table summarizes the information that is captured in Figure 2:
![fig2chart1](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Driver%20Table%20%26%20Images/Iteration%201%20Figure%202%20Chart%201.jpg)
![fig2chart2](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Driver%20Table%20%26%20Images/Iteration%201%20Figure%202%20Chart%202.jpg)

The deployment diagram in Figure 3 sketches an allocation view that illustrates where the components associated with the modules in the previous diagram will be deployed. The responsibilities of the elements are summarized here:
![fig3](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Driver%20Table%20%26%20Images/Iteration%201%20Figure%203%20-%20Deployment%20Diagram.jpg)
![fig3table](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Driver%20Table%20%26%20Images/Iteration%201%20Figure%203%20Table.jpg)

### Step 7: Perform Analysis of Current Design and Review Iteration Goal and Achievement of Design Purpose
The following table summarizes the design progress using the Kanban board technique:
![](https://github.com/JoeyVillafuerte/SOFE3650-Final-Project/blob/main/Phase%203/Iteration%201/Deployment%20Models%20%26%20Chart/concern%20chart.jpg)
