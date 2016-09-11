#Homework 1 - CSCI 5828

<hr>
###Nachiket Bhagwat
###Vipra Gupta
###Chaitra Ramachandra 

<hr>
###Answer 1: 
Brooks has defined essential difficulties as those difficulties that are inherent in the nature of software. According to him, the essence of a software entity lies in the construction of conceptual items like raw data, algorithms that manipulate the data, functions that act on the data etc. that are closely interlinked with each other and these are abstract concepts that are highly precise and richly detailed. Hence the hard part of building a software lies in requirement specification, design, implementation and testing of these conceptual constructs. He calls these intrinsic difficulties as essential difficulties involved in developing a software entity.

Let us take an example of managing a server remotely using a software application. Remote management of servers will involve complex embedded systems that will constantly monitor the server and software applications for such systems must abide to these complexities to access the data from these embedded systems and use the data to monitor and manage the servers remotely. The development of this software has inherent difficulties. Every member of the team need to study the detailed architecture of the server. Nothing can be done to make the problem simpler. Such difficulties that are caused by nature of the problem to be solved are called essential complexities.


###Answer 2: 
Brooks describes accidental difficulty as the ones which are not inherent in software systems but are more related to the production of a software. He states that in past we were successful to get three big breakthrough which helped with the accidental difficulties, namely High-level Language, Time sharing and Unified Programming Environment. High-level languages helped in abstracting the machine level code from the developer hence giving him only the tools that he requires to build the software. Time sharing has helped to reduce the turnaround time in the production of software. Developer can now compile and run their code at anytime without any delay. Unified Programming environment has helped standardise the softwares so that softwares can be run on any environment without any issue.

For example, earlier Microsoft’s phones and tablets had different operating systems than the laptops. So developers had to make different versions of their app for different devices. But now Microsoft has unified the operating systems throughout their devices, hence now an app that runs on a laptop can also be easily used on mobiles and tablets.


###Answer 3: 
Essential difficulties according to Brooks are the ones that are inherent to the software domain. He states four main essential difficulties i.e. Complexity, Conformity, Invisibility and Changeability.

**Changeability:** Software as a whole is a thought put in hardware. As the time immemorial, different engineering streams build tangible things like cars, bridges, buildings etc which if we try to modify after construction will cost a lot. But that is not the case with software. Software is extensively malleable. When the hardware gets better and advanced, it forces the software to keep-up with it and change. For example as the touch-screens got famous in mobiles, it forced the laptop industry to incorporate them and the operating system companies to integrate the functionalities of touch-screen. Similarly, changes in law, the user domain and extension of application functionality are other aspects that force the software to change. A good example of user forced extension of application functionality is emails. Initially emails were made just to communicate over internet with text messages. But as users started using it, they called out for more functionalities like integrated folders to filter the messages, integrated chats etc.

**Conformity:** Software is the newest engineering sector and is conceived as the one which should yield the most with other engineering sectors. Adding to this, it also faces the arbitrary complexity. This complexity exists as different people working on different interfaces have different ways to solve a problem and design an algorithm. And hence a software must conform to various designs and methods. For example, while building a software, the team of engineers have to conform to their methods and algorithms are in sync with each other. Similarly, when a new member joins the team, he will have to spend time to understand the current methods before he starts building his own.

**Complexity:** This is one of the most inherent essential difficulties in Software Engineering. Software Engineering unlike other engineering domains have no same two parts. Hence,  when we try to scale up our software, it’s not just repeating same block over and over again but to add new functionalities, change the existing code to be able to perform better, redefine the existing functions to comply with new requirements etc. Making all these changes bring with them the problem of communication, understanding the code and hence give rise to unreliable software states. For example, if a person creates a functionality and doesn’t provide proper comments and documentation, then if a new person wants to reuse that code or build a functionality on top of the existing one, due to his limited knowledge available about the product, he might not understand all the use cases and boundary conditions of the existing product and will end up adding bugs to the existing product also.

**Invisibility:** Software systems are not tangible like automobiles or buildings. It’s very difficult for a software engineer to comprehend a software’s complexity, its different components and how they interact. If someone even tries to build a visual of the software, the visual will end up being multi-dimensional having a number of graphs in it which will hardly solve the purpose. For example, a website has different components like cache, database, server code, front-end code etc and then there will be many calls made within these components. Due to this level of abstraction, the visualisation of the system is simple and understandable, but as soon as someone starts to add the flow of any of of these components, the representation will get very complicated and won’t serve the purpose of simple understanding of the software.


###Answer 4: 
According to Brooks, a silver bullet for software engineering is something that will make the software costs drop rapidly&mdash;a single technique or technology that by itself can deliver one order-of-magnitude improvement to some aspect of software development.

Brooks argues that [[1](#ref1)\]:
> “there is no single development, in either technology or in management technique, that by itself promises even one order-of-magnitude improvement in productivity, in reliability, in simplicity.”

The nature of a software entity is so complex that it is highly unlikely that there will be any inventions that will improve the already existing software technologies by at least one order-of-magnitude improvement. Since building a software is very abstract and starts from a conceptual construction, building software will always be hard.

Brooks also talks about two kinds of difficulties associated with software entity and he terms them as essential difficulties and accidental difficulties. Essentials difficulties are those difficulties that are inherent with the problem definition and there is nothing one can do about it. Accidental difficulties are those difficulties that arise during production of the software. Brooks argues that most techniques attack the accidents of software engineering. He discusses about how ADA and other high level languages when embedded with the concepts of object oriented programming can eliminate the accidental difficulties of software engineering, however the complexity of the essential design will still be the same.

So unless there are solutions that can eliminate the essential difficulties like requirement specifications, acquiring good design skills, better coding that can handle all types of runtime exceptions, programming codes that adhere to the various improvements made to hardware, rigorous testing of these developed entities that will cover all types of scenario, maintenance of these softwares so that they conform to the changes made, there can be no silver bullet for software engineering.




###Answer 5:
A chemist tries to find a way to solve a problem. Once a solution is found, he will move to other problems. A chemical engineer’s job is to check if the solution provided by chemist is scalable, reliable and fits in given budget and time.
The same analogy can be used for any science vs engineering comparison. We need exact steps to solve a problem which we can get from science. But the solution must be practical, reliable and efficient.

Wikipedia defines computer science as [[2](#ref2)\] :
>“Computer science is the scientific and practical approach to computation and its applications.” 

Software engineering is science of building methodologies and tools to use knowledge of solving problems in computer science in practical, reliable and efficient way.

###Answer 6:
**Abstraction:** Abstraction in software engineering is a way of hiding complexity of a system from a client by adding a high level or abstract layer which takes care of complexity. The client sees only the abstract layer. It is one of the most important concepts in software engineering as it compartmentalize the system and various client groups can work independently in a smaller subsystem. It’s harder to come to consensus while making decisions without understanding complexity, which is first essential difficulty.

**Conversation:** Conversation is communicating specifications, timelines, costs, requirements between team members and between clients and engineers. As discussed in abstraction, all stakeholders seldom have idea of overall complexity of system. So, poor conversation can result into bad software, unseen delays and budget overrun. The problems in conversation comes from human unreliability in communication which is inherent to any system and hence its essential difficulty.

**Specification:** Abstraction and conversation talks about methodologies of solving complexity of a problem. But all the stakeholders must conform to what they want to build. Specification is reliable and detailed description of a software system conformed by all stakeholders. Specification can only be as good as understood complexity of a system. As human beings, we have problems in proper specifications. So this problem is inherent to any system and hence is essential difficulty.

**Translation:** Translation is the process of implementing the specifications into solution. Once the specification and communication is over, engineers have to implement the solution, trying various methodologie and test the solution extensively. There can be multiple ways to solve a problem and problems can arise even after good specification because of choosing one solution or methodology over another. Hence, translation faces accidental difficulties.

**Iteration:** Iteration is process of designing a system, getting feedback and making changes to reflect in a new design, repeatedly until we can come to desirable state. As we may know by now, it is hard to understand complexity of a system for all stakeholders. So, most times it's easier to build the basic system first and ask the clients if it is the product that they want. As the clients give feedback, the engineers can change the implementation. As clients conform to each new iteration, there is less chance for miscommunication or misspecification. Iteration is very powerful tool as it tries to tackle with big problems like complexity and conformity.

<hr>
## References

1. <a name="ref1">Frederick</a>, P. Brooks, <q>No Silver Bullet: Essence and Accidents of Software Engineering</q>. *IEEE Computer Society Press Los Alamitos, CA, USA*, Vol. 20, Issue 4, April 1987, pp. 10&ndash;19.
2. <a name="ref2">Frederick</a>, Software Engineering <q>https://en.wikipedia.org/wiki/Computer_science</q>
