**2. How to read a Paper**

When reading a scientific paper, it is useful to follow a structured approach instead of reading everything from beginning to end immediately\.

First, I look at the **title, abstract, and keywords** to understand the general topic and the main research question\. After that, I read the **introduction and conclusion**\. This gives me an overview of the problem, why it is relevant, what the authors investigated, and what the main results are\.

In the next step, I examine the paper in more detail\. I focus on the **methodology, experimental or simulation setup, figures, tables, and results**\. For simulation\-based papers, it is especially important to identify which simulator was used, which parameters were varied, which parameters were kept constant, and which performance metrics were measured\.

I also check whether the results actually answer the original research question and whether the authors mention any **limitations or possible future work**\. Figures and graphs are particularly useful because they often show the most important relationships between the investigated parameters\.

Finally, I summarize the paper in my own words\. I identify the **problem, method, main results, and conclusion** and consider how the work could be reproduced, modified, or extended for my own project\.

For my project, I will pay particular attention to the NTN simulation setup, the QoS performance metrics, and the parameters that could later be changed in my own ns\-3 simulations\.

**3. Project Proposal**

I will take the advanced path and investigate Quality of Service QoS in 5G Non\-Terrestrial Networks NTN using ns-3 NTN

The project is based on the paper "5G NR Non-Terrestrial Networks: From Early Results to the Road Ahead.” The main problem is that satellite communication introduces additional propagation delay and different network conditions compared to terrestrial networks, which can affect the Quality of Service.

The project will investigate how different NTN configurations and network conditions affect network performance. Two input parameters will be varied at a time while the remaining parameters are kept constant.

The main performance metrics will be:

- Latency
- Throughput
- Packet Delivery Ratio / Packet Loss
- Jitter

Possible input parameters include:

- Satellite altitude / orbit
- Number of users
- Network load
- Traffic type

The simulation results will be analyzed and visualized using Python, including 2D and 3D plots. The project can later be extended by comparing different satellite configurations and traffic scenarios.
