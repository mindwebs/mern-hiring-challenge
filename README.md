# MERN Stack Hiring Challenge

[Mind Webs Ventures](https://mindwebs.org) actively hires full stack developers who can be part of the product development teams in order to make the organization grow.  
If you are willing to apply for any open position, Fork this repository, complete your code and submit it. The codebase should have a dedicated front-end and back-end folder.  
  
After publishing your fork and completing your code, you should email your repository link with a cover letter why you want to join our organization at careers@mindwebs.org

### Task Description 

Keshav, a 16-year old, young innovator has built a unique solution to automate street lights. His solution provides automatic turning them on and off, reporting its health and functional condition alongside providing a mesh based Wi-Fi hotspot across the zone it is implemented. He pitches the idea to the local municipal community and they promise his award winning idea all support to run a pilot over an urban zone of five square kilometres.  
The zone however looks like a piece of pie with the parent server (providing data and connection) located at the corner (vertex) of the plot.  


![1](https://user-images.githubusercontent.com/38533808/212271490-da9157cf-409c-40fd-987a-35e43750c47b.png)  
<p align="center">Visual Understanding of a Map with Servers at a corner location.</p>

Now Keshav decides to make the most effective use of the plot and implement his solution using Tree Topology to accommodate the entire area. Each device (node) he has devised in a way that is capable of taking the internet from one device in one direction and again stream the internet to 2 or more devices in the other three directions. Here's what he has planned so far. 

![2](https://user-images.githubusercontent.com/38533808/212271661-d35e29b5-e49f-46ac-8ee7-c8c6d15f7208.png)

But the municipal corporation wants to visualise and understand faults happening across the street light system using a web dashboard. **Keshav having no idea of web development seeks your help in assisting him to build a web dashboard for the same.** 

**Keshav expects his dashboard to allow him to do the following -**  
- [ ] Add multiple nodes by simply feeding the street address, latitude and longitude of the street lamp. You should store this data  in the database of your choice. All data should be effectively maintained in the database.
- [ ] Each node will have a Boolean value known as functional which will store the operating condition of the node. 
- [ ] Implement links between the nodes to visualise how each node is getting network from an upper node. The linking logic should be provided to Keshav as a document for him to understand how it works.
- [ ] Show the tree of all nodes (as clickable dots in the system) in a single page while clicking them can display their details and if it’s functional or not. 
- [ ] Zoom across the tree to visualise the links and the links (branches) will be of green colour to show that it’s functional. 
- [ ] In case if any node is non functional, it should be shown in red and all links that are getting internet from it should also be red recursively. 

Keshav however hopes to help you with the following hand drawn sketch of what he is willing to see. 

![3](https://user-images.githubusercontent.com/38533808/212271694-7bc6056a-523b-4116-94fa-43dd18b23053.png)
<p align="center">If a node goes down, all its child nodes also become down.</p>

**Bonus Part -**
Keshav also promises you a chocolate if you can provide him -
- [ ] An API to update the statistic of the node that takes in the node id and the functional variable and updates it. 
- [ ] And as soon as any nodes become non-functional the dashboard changes in real-time using something called sockets that he got to know over the internet. 

<p align="center"><b>- End of Task Description -</b></p>

**_TL;DR - You will need to create a single dashboard for visualization of tree based nodes for a set of smart lights that are interdependent on each other. How the visualization works and logic is described above. The bonus part ensures a higher probability of the selection._**
