 

# QC
 
# Course Welcome
Welcome!

This course will introduce you to the key principles of quantum computing. We will use two key methods to build this knowledge: intuition and math. First, you'll explore the unique features of quantum computing through relatable activities. Then, we'll provide you with the mathematical background to be able to calculate the results of quantum operations.

f transcript. Skip to the end.
Hello and welcome to Introduction to Quantum Computing for Everyone.
Quantum information science is an exciting field that draws from information theory, computer science, and quantum mechanics to process information in fundamentally new ways.
Quantum mechanics emerged in the 1920s to describe certain puzzling behaviors of elementary constituents of matter and light.
It revolutionized physics and chemistry and led to the inventions like transistors, lasers, and GPS.
Subsequently, we came to understand that information itself can be acquired, encoded, and manipulated in quantum systems, giving birth to the new field of quantum information science.
Quantum information scientists draw on the work of physicists, computer scientists, and mathematicians as well as materials scientists, chemists, and engineers.
Cross-disciplinary teams are applying QIS to new quantum technologies in communications, networking, data security, navigation, and medical diagnostics.
They are also making headway in developing quantum computing systems that may allow us to tackle challenges previously out of reach in areas such as cryptography, logistics, optimization, and across the natural sciences.
As with many emerging technologies, QIS will likely affect how we live and work and may lead to new developments in broader aspects of society such as commerce, governance, privacy, employment, and education.
This evolution contrasts that with that of classical computing, which was a particular solution for a particular problem: How can we make an automated calculator?
As a result, classical computers were designed to mimic the operations that you and I do every day.
We can learn how to program a computer by assuming that it holds information, performs mathematical operations, and can make decisions based on the information it has.
All programs are created with those same building blocks and they largely match the way you and I perform operations ourselves.
The advances made since the 60s have been in four areas:
making faster hardware,
optimizing hardware based on frequent software operations,
redesigning software based on the strengths and weaknesses of the technology,
and making larger and faster storage.
And throughout these advances, the programming approaches have also been improved.
But everything still largely mimics human tasks.
The differences between classical and quantum computing start from those very fundamental building blocks.
Instead of building something that mimics a calculator, scientists discovered something interesting: powerful quantum phenomena.
And then they discovered they could perform computation with it.
So then they asked: how can we use these to perform computation better, faster or bigger than this automatic calculator we made?
Quantum computing is fundamentally different in the ways that it stores information and operates on that information.
In this course, we're going to cover the fundamentals of quantum computing.
We'll answer such questions as: How are quantum computing and classical computing different?
What is a quantum operation? What kinds of problems will quantum computers solve that classical computers cannot?
How does quantum computing leverage phenomena from quantum mechanics? How does this give quantum computers an advantage?
Are bits and qubits the same thing? And if not, how are they different?
So this course will first introduce you to quantum applications and what the hardware looks like.
Then we'll gradually build your knowledge of quantum computing in general.
We'll start with an intuitive introduction to a quantum mechanics phenomenon and the quantum operations that exploit that phenomenon.
Next we'll introduce you to the quantum notation that we use to communicate those concepts.
Finally, we'll go through the mathematical calculations related to that concept.
Don't worry, only basic algebra is required for this course. We'll teach you the rest!
And the idea is that on each subject we progress from ideas related to everyday understandings and gradually build up to the more technical content. If you're not taking this for credit then you can sort of restart every time we have a new concept.
And this course segment will end with an algorithm that illustrates the power of quantum computing.
This course is the first of a two-course sequence. In the next course we will build skills from operations to circuits to algorithms, explore quantum computing concepts via quantum programming.
We'll learn quiskit, IBM software for their current quantum computer, and build up the mathematical skills necessary for understanding more complex algorithms.

# Course Summary
Quantum mechanics emerged in the 1920s to describe certain puzzling behaviors of elementary constituents of matter and light. It revolutionized physics and chemistry and led to inventions like the transistor, lasers, and GPS. In time, we came to understand that information itself can be acquired, encoded, and manipulated in quantum systems, giving birth to the new field of quantum information science (QIS). QIS studies how information science relates to quantum mechanical effects, and the field is highly multidisciplinary. In QIS, the work of physicists, computer scientists, mathematicians, materials scientists, chemists, and engineers comes together to tackle challenges in areas such as cryptography, logistics, optimization, and across the natural sciences. Notably, QIS can be applied to solve computing problems previously assumed to be out of reach without massive amounts of resources or compute time.

QIS in the form of quantum computing is projected to become a revolutionary computational model. A quantum computer encodes information and operates on information in a fundamentally different manner than implemented in a classical computer such as a laptop or supercomputer. These differences in the computational model may allow a quantum computer to solve some types of problems at a much faster rate than ever demonstrated before. In this course, the principles of quantum computing will be introduced in an intuitive manner. Supporting mathematics needed to understand quantum operations will be introduced on an as-needed basis. The only prerequisites are a basic understanding of algebra as well as the desire to learn more about an emerging and disruptive technology. 

This course will proceed as follows. First, we introduce you to quantum applications and what the hardware looks like. Then, we will gradually build your knowledge of quantum computing. In general, we’ll start with an intuitive introduction to a quantum mechanics phenomenon, followed by quantum operations that exploit that phenomenon. Next, we will introduce the quantum notation that we use to communicate those concepts. Finally, we’ll go through the mathematical calculations related to that concept. By the end of this course, you will have enough understanding to examine a well-known quantum algorithm, the Bernstein-Vazirani algorithm. 

After finishing this course, you will be able to answer the following questions:
```
How are quantum computers and classical computers different?
How does quantum computing leverage phenomena from quantum mechanics? How does this give quantum computers an advantage? 
What is a quantum operation and circuit?
What is entanglement?
What kind of problems will quantum computer algorithms solve that are challenging for classical computers?
```
# Pre-course Survey
This survey will help your instructors understand your prior knowledge about quantum computers and quantum information science. We don't expect you to know all the answers!! If you did, you probably wouldn't be taking this course. Please answer each question to the best of your ability.

# Syllabus
```
Introduction to Quantum Computing for Everyone
UChicagoX QUAN12000
Goals
```
Welcome! In this course, we delve into the interdisciplinary endeavor of quantum computing, with a focus on developing intuition about the major benefits and limits that are imposed on quantum computing by the quantum phenomena as well as getting comfortable with how basic quantum operations behave. The specific goals of the course are:
```
Learn the intuition behind the quantum mechanics principles that affect quantum computing.
Learn basic quantum computing operations
Learn the mathematics necessary to calculate quantum operations
Learn how individual quantum operations are combined to create higher-level operations and algorithms
As a virtual course, most of the content will be included as videos followed by individual questions to practice / check understanding. In each section, there will be a larger homework assignment that tests the understanding of all videos of the section. 
```

### Resources
Textbooks that might be useful:

### Recommended: 
- Q is for Quantum, Terry Rudolph
- Dancing with Qubits, Robert S. Sutor

### Course Pacing and Access to Assignments
This is a self-paced course. Please note that access to graded problems is only available to those enrolled for the verified certificate.

### Grading / Assignments
For those enrolled in the Verified track, each student’s final grade will be computed according to the following:

``` 
Practice questions following videos: 20%
Homework problems for each section: 35% 
Exam: 45%
Your lowest 2 scores on the practice questions will be dropped. 
 
An overall grade of 70% or higher will be considered a passing grade. 
```


# Quantum Computing: Introduction and Applications
Quantum information science (QIS) is useful for a small set of very compelling applications, some of which we will introduce in this section. Then we’ll introduce some current quantum computing hardware and take a historical perspective on the development of quantum computing. Quantum operations occur at a qubit level. Unlike classical computing, there are not yet programming languages that allow programmers to abstract away critical details of quantum operations without needing to understand them. In this section, we will introduce operations on a single qubit.

There's been a lot of excitement surrounding quantum computing, so in this video we're going to provide a little bit of an introduction as well as describe some applications that quantum computers are proposed to be really good at.

![image](https://github.com/user-attachments/assets/094a13b8-00e5-4aa2-b2ff-3c09976230dc)

First, I want to highlight though that classical computing is everywhere. 
This classical computing paradigm is seen in everything from laptops to cell phones, super computers, etc.
And what powers these devices are different types of software like operating systems, apps, web browsers, etc.
So, if we have all this computing power available to us, why would we even need a quantum computer?

![image](https://github.com/user-attachments/assets/5ec15da5-4c6a-4392-a7cc-915fa1502a7f)

Well, that's because we have limitations on our classical computation.
Classical computers are really good at solving many day-to-day problems, such as algebra and calculus.
And they can do so faster than a human.  
But there are still many complex problems that  are intractable.
So, what does intractable mean, exactly? That means that we need an infinite or a lot of resources or time to solve these problems.  
Some examples of these types of problems include natural processes and finding a solution when there might be an exponentially large set of potential solutions.

![image](https://github.com/user-attachments/assets/c51de922-ae05-49e6-b208-a10e986c0c63)

One particular example of this type of problem is  chemistry simulation.
So, chemistry simulation is a modeling of a natural process as well as trying to find a solution and a state space where there are many different types of possible solutions.
So, whenever we think about chemistry simulation, that can involve simulation of molecules.   
And it can be applied to develop improved chemicals and materials such as pharmaceuticals or fertilizers.So, classical simulation techniques for chemistry are implemented with a sort of guess and check type of mechanism.  
In this kind of process, theorists will develop a hypothesis, we'll have experiments that are outlined and performed and then these results are analyzed.
And then with those results, we develop new theories.  So the efficient simulation of atoms and simple  molecules is one of these things that we suspect that near-term quantum computers are going to be really, really good at.So, we can look at an example of this. Classical computers have a really difficult time representing information associated with chemical bonds and that's because all the components in a molecule in a way fuel each other.

![image](https://github.com/user-attachments/assets/646c6d91-5348-4743-a31f-626e6fb05b50) 

So if you adjust one placement of one of those particles, all of the rest are impacted.
So that creates many, many different variations that can exist with how the structure of the molecule is set up.
So molecules of course have protons, neutrons, electrons, and these can all be organized in different variations of configurations. So caffeine, pictured here, is simply a 24 atom molecule but we would need 10^48 bits to represent that and that's a lot!
All the possible different energy arrangements would equal quite a lot of information to represent in the classical computer, so it's intractable.
However, a quantum computer could hold all this information in 160 cubits, which is a lot less than 10^48 bits. Another proposed application for quantum  computers would be optimization problems. 

![image](https://github.com/user-attachments/assets/18b19570-d94a-4c32-abbe-89bc10a4cdd7)

So, optimization problems fall into that category  of problems that have a very, very large state space for the answers that are possible.  
So when we think of optimization, we can try to maximize resources in terms of time, energy, hardware.
And one example of this is the fact that UPS optimizes its routes for minimal left turns rather than shortest route. So because of this, it's able to save 10,000,000 gallons of fuel each year and deliver 350,000 more packages.
So that's pretty significant.
Classical optimization involves really computationally expensive types of search algorithms. Most of the time we can't even find the best, we just have to find a good enough solution out of all the potential solutions. So, because quantum computers are good at exploring large state spaces, they're anticipated to be really good at finding optimum solutions for these types of optimization problems.

![image](https://github.com/user-attachments/assets/75098047-a857-48b2-afc9-37f7fabb9d8f)

So let's kind of dig a little deeper into that. An example application for quantum computers would be an optimization problem known as the traveling salesman problem. So, the traveling salesman problem is a problem that aims to find the shortest route in a round trip journey.
So here we have a picture of a tour of Italy and we have the optimum route, outlined here.
We want to try to find the route where we we travel the shortest amount of distance possible.
And that can get to be quite a lot of different variations of the journey as we include more cities in our trip. So let's look at this. If we have 20 cities that we're visiting.  
We actually implement a factorial all the way down  to 20 x19 x18... all the way down to 1.  
And that creates a very, very large number of combinations for the possible journeys that we can take. So quantum computers model optimization in such a way that qubit optimization or qubit observation has a high probability of determining the best route without having to check each single one.
So, that's done through the simple procedure of defining a target solution and defining the cost, encoding qubits with our search equation, and then allowing those qubit values to converge to the ideal route in relatively few number of iterations. 

![image](https://github.com/user-attachments/assets/f827502e-2386-4856-893d-42af1139d9b5)

So to kind of summarize some of the applications that quantum computers are targeted to be really good at, we have chemistry applications such as battery material discovery, fertilizer production, drug discovery, material durability. We have optimization problems, so financial market analysis, manufacturing applications, and then transportation optimization as well.
Security applications. So, we have more robust encryption schemes and more secure key generation are some examples of ways that we can apply quantum computing to security.
And then, of course, machine learning. So we can apply quantum computers in applications, potentially for artificial intelligence, audio and image generation, and predictive models. 

![image](https://github.com/user-attachments/assets/4f57d3d0-cae5-42b2-91de-0809cdf30f57) 

So let's look a little bit more into what the difference between a classical and quantum computer is physically.
So, we look here. To the left we have the Summit supercomputer and to the right we have a UChicago quantum computer.
So here we have around 250x10^15 bytes of storage.  
That's a lot of storage compared to the tens of  qubits of storage on the Shuster quantum computer.  
So, although the quantum computer is a lot smaller in terms of number of fundamental units it includes, so we have the qubit over to the right on the quantum computer rather than the bit on the left with the classical computer, we have a lot of benefits in the way that we encode information that allows us to get those those speed-ups with certain types of computation. 

![image](https://github.com/user-attachments/assets/5dac03b4-2f5e-4e10-b76a-6a97cc5a8714)

So moving forward with quantum machines, we need to make them more robust, more reliable, and generally scale them so that we can implement these different types of algorithms: for optimization, for simulation of natural processes, and for security purposes.
So there's many technical challenges that exist currently with scaling these machines in the terms of number of qubits.
And that's because we have relatively short lifetimes and they're very error-prone. They're very willing to communicate, not only  with each other but the surrounding environment.  
So we want to make sure that we make the world more robust from interactions outside of their computation.
So we have these devices that are currently very sensitive and we have limitations due to hardware and software, so we need to have more of these, not only more qubits, but more connections between these qubits. Finally, we also need to think about improving the control and hardware that will allow for more sophisticated systems and algorithms.
We just have a couple of applications that we've outlined here but there's a lot more potential to discover new applications, especially as these devices become a lot more robust, reliable, and increase in size.

![image](https://github.com/user-attachments/assets/a702ce62-a614-480c-bcb6-d121405e8f79)

So some takeaways: quantum computing is projected to be revolutionary and can potentially drastically change the way we solve some of the most challenging problems that exist for us today.
In this course, we'll learn a little bit more about why quantum information is different from classical information and how it potentially can change the world.

# Defining Optimization

Optimization problems involve finding the best solution out of all possible solutions. These types of problems require all elements of the set of possible solutions to be examined in order to find the optimum. As the number of variables included for optimization increases, the amount of elements in the possible solution space increases drastically. 

Imagine you are leaving home and on your way to work, but you want to stop for coffee. There is only one possible path for you to take: from home, to the coffee shop, and then to work. But perhaps you also need to send a letter at the post office. Now you have two options for your trip: the post office first and then the coffee shop or the coffee shop first and then the post office before going to work. 

Now let’s add a third stop at the bank. Now the options for paths from home to work include:

```
coffee shop, post office, bank
coffee shop, bank, post office
bank, coffee shop, post office
bank, post office, coffee shop
post office, bank, coffee shop
post office, coffee shop, bank
```

The problem of deciding what path to take from home to work is an example of the Traveling Salesperson Problem, and the number of possible solutions grows as a factorial, n! = n*(n-1)*(n-2)...*1, where n is the number of stops that must be taken. As the value of n increases, the total number of possible solutions calculated by n! increases rapidly. 

Returning to the example of the trip from home to work, we can see how the number of paths increases as a function of the included stops:

```
3 stops: 3! = 6 paths
4 stops: 4! = 24 paths 
5 stops: 5! = 120 paths
6 stops: 6! = 720 paths
7 stops: 7! = 5,040 paths
```

By the time we reach 7 stops, there are more than FIVE THOUSAND options to consider. Which is best? How would you know? 

The decision of what makes one path the ‘best’ as compared to the rest is often made with respect to reducing a cost such as number of required resources for the trip or total time taken for the journey. 
For example, in their routing problem, UPS optimizes routes for minimal left turns rather than shortest route.  

https://theconversation.com/why-ups-drivers-dont-turn-left-and-you-probably-shouldnt-either-71432

https://algorithms.discrete.ma.tum.de/graph-games/tsp-game/index_en.html


# Travelling Salesperson Simulation
Practice Questions due Jan 11, 2025 02:45 AEDT
Visit the website that hosts a simulation of the Traveling Salesman Problem that optimizes for the shortest path. Pick a map and complete the simulation at least twice, once with 10 stops and once with 30 stops. For each simulation, take note of the length of the optimal tour, length of your tour, and calculation time (how long it took the computer to find the optimal route). Afterwards, feel free to continue experimenting with the simulator by varying the number of included cities each time.

https://algorithms.discrete.ma.tum.de/graph-games/tsp-game/index_en.html
```
Travelling Salesperson Simulation
Yes	No
Were you always able to find the optimal route?
```

# Audit Learners: Travelling Salesperson Simulation
Visit the website that hosts a simulation of the Traveling Salesman Problem that optimizes for the shortest path. Pick a map and complete the simulation at least twice, once with 10 stops and once with 30 stops. For each simulation, take note of the length of the optimal tour, length of your tour, and calculation time (how long it took the computer to find the optimal route). Afterwards, feel free to continue experimenting with the simulator by varying the number of included cities each time.

https://www-m9.ma.tum.de/games/tsp-game/index_en.html

Consider the following questions: 

Were you always able to find the optimum route? 
As the number of cities on the route increased, how did the amount of time it took the computer to find the optimal route change? 


# Connection to Quantum Computing

As the number of cities increases in the Traveling Salesman simulation, so do your connection options in your attempt to optimize for the shortest path between them all. Because of the way classical computers store information, they are inefficient at solving optimization problems, taking long periods of time to search for the optimum set of variables that generates the best outcome for reducing cost, or in this case, total distance travelled.  The way quantum computers store information could potentially allow them to solve complex optimization problems, like the Travelling Salesman Problem, much quicker than classical computers can. 

In this course, we will learn about some of the advantages that quantum computers have, as well as the constraints that exist. In other words, we will explore the types of operations quantum computers can do quickly or compactly that allows them to outperform classical computers for certain problems. We will also discuss the things classical computers can do that quantum computers cannot!

# Encryption and Quantum Computing

![image](https://github.com/user-attachments/assets/23a573de-753d-4dbe-b00b-e50381e3ce70)

In this video, we're going to discuss encryption and quantum computing, and the intersections between the two.
We currently live in a data-driven world and I say that because we have so many internet users out there transmitting a lot of data. 
In 2020, we saw approximately 4.5 billion internet users and each of them are transmitting an enormous amount of data in the form of communications, such as emails and texts and social network interactions, and then transactions for commerce or online banking.
So all these communications are holding very sensitive data so we want to make sure that these communications are kept secure and encryption helps us do that.

![image](https://github.com/user-attachments/assets/4113f526-53b7-4561-be7a-e66cf243c120)

So how does encryption work? On a high level, we have a message that, here in this example, we see a message to our friend. And we combine that with a secret key in order to generate ciphertext.
Once we have ciphertext, it almost makes the message seem completely random and unusable so the contents of that message are kept safe.

![image](https://github.com/user-attachments/assets/a80af141-4b60-4120-b0b7-c97ba1f645c9)

So how is encryption secure? Encryption is based on one-way cryptographic functions.  
A one-way function is a function that's easy to compute but difficult to invert. Multiplication can be thought of as an example and that's because it's easy to multiply but a little bit more difficult to factor.
That actually becomes the basis of key generation for a lot of encryption schemes because we take prime numbers and then we multiply them in order to create a key. Knowledge of the keys or the key factors allows for data decryption, so we want to make sure that we keep those secret and away from anyone who might want to try to read the data.
So we think about generating a key. We can think about it, uh, in like how we think of mixing paint. It's easy to mix paint but it's really difficult to unmix paint once it's combined.
So we have here two prime numbers that we multiply together but once we have them multiplied together it's difficult to pull them back out into their factors. 

![image](https://github.com/user-attachments/assets/184dfdb1-a2d4-4413-b93d-8fbf925360ac)

So how does quantum computing disrupt modern encryption? Modern encryption uses large keys and because it's hard to, it's really challenging to factor a large number, our data stays relatively secure just because it's a pretty intractable problem to try to come up with the factors for that key.
So for example, if we have a key that is 1024 bits in length that is equivalent to 309 decimal digits and even the best quantum or even the best classical computers will have a difficult time factoring that value.
So what if factoring was more efficient? Encryption would essentially be broken. And we have Shor's algorithm, which is a quantum algorithm that factors numbers exponentially faster than the best classical algorithm.
So, if we have a quantum computer that can implement Shor's algorithm, in theory all encrypted messages--past and present--would be vulnerable to decryption. 

![image](https://github.com/user-attachments/assets/30070c66-e17f-4f62-9a13-c7b54c80034c)


So with that in mind, how concerned should we be?  
Well, quantum computers are currently not large enough to run Shor's algorithm. And decades are needed to make our computers a little bit more robust, in the sense that we need to refine and scale our devices.
And additionally, security has adapted in the past, as technology improves, so in post-quantum cryptography we'll be able to assist in our transition to a quantum future. 


# Summary

Classical computers are everywhere in the form of supercomputers, smartphones, and laptops. Advances in classical computation have become a catalyst for many scientific and technological innovations, but there are still many problems that are difficult for classical computers to solve. Examples of such computational tasks include modeling natural processes like determining molecular structure and problems that have large state spaces for possible outcomes like the Travelling Salesperson Problem. Quantum computers are projected to have the ability to solve these kinds of problems in a much more efficient manner than the best-known classical approaches.  

Quantum computing resources are targeted for applications in chemistry, optimization, security, and machine learning. While current quantum hardware, which we will discuss in the next section, may be modest in size, experiments have already demonstrated that the technique in which quantum information encodes data allows for significant computational gains. We do not yet have large enough quantum computers to implement notable quantum algorithms such as Shor’s algorithm for factoring, but it is anticipated that more robust quantum computers will appear in the decades to come.  

# Quantum Hardware

![image](https://github.com/user-attachments/assets/e867955c-3f06-4c1a-af14-a3efaf66fc6a)

Start of transcript. Skip to the end.
Hello! Today I'd like to give you a little  bit of an introduction to quantum hardware.
Computers come in many forms.
There are familiar ones, like computers, laptops, tablets, and even your smartphone. 
There are less obvious computers, like those that control robotic arms or your microwave, the hundreds in your car, satellites, even smart refrigerators and thermostats. Computers are all around us and they come in many forms. 
Yet, there are now quantum computers. Why is it that all of these myriad devices are actually quite similar when quantum computers are so different? 

![image](https://github.com/user-attachments/assets/baf9ee84-9b8d-4015-b8a6-2cc76b448a1d)

The classical devices are all different variations of the same technology with very similar ways of programming them. They are merely different trade-offs.
A satellite needs reliability because you can't repair it easily and the rays from the Sun are very damaging without Earth's atmosphere to protect it.  
Microwaves need very little storage or speed, so they are optimized for low cost. 
Laptops and desktops provide large storage and fast computation, but supercomputers supercharge those two aspects.
Phones, tablets, and watches depend heavily on communication with much less storage.  

![image](https://github.com/user-attachments/assets/d61f9f97-923b-4242-b492-4e3295e0b2a5)

There are currently many competing technologies for implementing quantum computers. 
There are currently many competing technologies for implementing quantum operations. 
Why? Because it is very difficult to sustain quantum operations accurately for any length of time.
These different technologies trade off speed, reliability, and scalability. Ion track machines have taken an early lead because they depend on very mature laser technology, allowing them to leverage decades of development in that area.
For small systems, they have fast communication between qubits and the manufacturing is more consistent.
However, it is hard to build a large machine and they are slow - a thousand times slower than other technologies. Superconducting technologies leverage the decades of development in silicon used for classical computers.
However, they are much larger than ion trap machines. 
These just show a few of the examples of technologies being used to implement quantum technologies. 

# A Historical Perspective 

 
Hello! Today, before we dive into quantum operations, I want to give you a little bit of a historical perspective.
It gives you insight into why we're teaching you to code in quantum computing much differently from how one would normally go about learning to code in a classical computing environment. So let's look at the development of classical computers.
Classical computers were designed to mimic human operations. Calculations, in fact.
So, Pascal invented a calculator.
And in World War II, the development was driven by the need to calculate firing tables that would look at the angle, and the distance you needed to fire, and weather conditions so that that we could have accurate firing during the war.
And it was actually other people, like Ada Lovelace, who envisioned other uses for this like composing music. And it was Grace Hopper who took a step back and said, "Wait these are really hard to program. We should really use a programming language that has some English language features instead of writing all of our programs just so the machine can understand it."
And over decades, these languages have changed and developed so that they're quite easy to understand, especially the ones designed for children learning coding.

![image](https://github.com/user-attachments/assets/4f99ba3d-6c49-4a3e-833a-62cf6007ecda)

Development of quantum computing has been completely different.
This started with scientists observing phenomenon and not knowing what to do with it.
And eventually, there have been many uses. Only one of which is computing.
And so, someone said, "Oh, well, maybe we could harness these for for computation." And only if we harness these unique features are we going to get something that gives us an advantage over classical computing, because we're looking at a technology that wasn't designed for that.
Right. Quantum computers were never designed to mimic how humans perform tasks. We already have a technology that does that and does that well for certain tasks, certain tasks that humans do quickly.
And so these are the products of an observation of these unique features that can be harnessed. And so the only way we're going to win is if we are able to do things that humans can't do quickly, in a way that somehow the quantum properties allow it to be faster. So in some sense, quantum computing is a hammer in search of a nail.
What are those applications that are both very hard for classical computers, intractable in fact, and also able to be solved on quantum computers? 

![image](https://github.com/user-attachments/assets/b4e81dcc-64be-4c32-a9c4-dcca7b332120)

So really, the differences are at the most basic level and we don't yet have languages that hide those basic level details.
So, to understand how quantum computers perform computation, we really need to start with those basic quantum operations.
And we recognize that this is very different from how people learn to program classical computers today.
But that's how we go about it until someone figures out how to express those operations and features in a way that hides the detail and still retains the ability to get the benefit out of it. We're stuck with this system and no one has thought exactly how to do that yet successfully.

# NOT, SWAP, C-NOT

Hello! Today we're going to talk about quantum operations. 
And this is inspired by the visual representation presented in “Q is for Quantum'' by Terry Rudolph. 

![image](https://github.com/user-attachments/assets/c5c0b98f-1b8c-4b87-b340-907ce3e8938b)

So imagine that we drew operations this way. Let's say we have an operation named “eat one cookie.”
I would start with a plate with four cookies on it and, if the operation “eat one cookie” is applied, then I have three cookies left.
Okay. Likewise, I could start with three cookies and apply the “eat one cookie” operation, and I would be left with two cookies.
So, a few important points about this representation. 
One is that you can see operations progressing from left to right.   That is merely the order of operations. It doesn't mean that this plate moved through a box, a cookie was eaten inside the box, and then it emerged on the other side. This is just an abstract representation that tells you that you started with four cookies, and then the “eat one cookie” operation was applied, and then the result was three cookies. We could also have two operations in a row, in sequence. 
So if we started with four cookies, and then we ate one cookie two times (twice), then we would end up with two cookies instead of three. So once again this doesn't mean that there were two separate “eat one cookie” boxes. 
It just means that the “eat one cookie” operation was applied twice.  

![image](https://github.com/user-attachments/assets/01470a7a-91ce-4a18-be36-39e702920627)

All right. So let's imagine an operation we call “not,” and in quantum we have two values. 
So it could be apples and bananas, it could be happy and sad, and so a not operation toggles between these two values.
So if we had a system where we had apples and bananas, if I started with a banana and put it through a not I would get an apple. If I started with an apple I would get a banana.
And so we could use any two items, and the not toggles between them.
So, in a quantum system, we're using zero and one and we've put them inside this ket.  

![image](https://github.com/user-attachments/assets/5ad251d8-f55a-41a8-b3ea-aa3ec230ab30)

We'll learn about the bra-ket notation later, but right now we just know that we have a zero and one.
We will label the white ball zero and the black ball one. 
So in this representation we have two choices, white and black balls. So the not operation toggles between them. So if I start with a white ball then I end up with a black ball; if I start with a black ball I end up with a white ball. 

![image](https://github.com/user-attachments/assets/238fac3b-08e4-4c16-b77d-3b113011f2d8)

All right. So I'm going to have a series of examples in this video that are challenges for you to figure out.
And so, each time you see one, feel free to pause the video, think about it, have a guess.
You want to predict the answer and then put the video back on, and I'll go through the solution. So go ahead and pause the video now and try to figure out what it would be if we had multiple nots in a row in these cases.
Okay, so let's go through the solutions. If you start with a white, apply a not, that'll be black, and apply it again, it'll be white again. 

![image](https://github.com/user-attachments/assets/10e4f934-89f0-4feb-8228-ab5b505ae69b)

Likewise, if I start with a black, then we'll end up with a white after a single not and then a black after a second not.
So we've applied these nots twice. We get back to the original value. 
Okay, all right. So if I were to apply it three times, the first two get it back to the original value, and now I apply it again and I'm left with a white ball. 

![image](https://github.com/user-attachments/assets/c447e09a-ddf2-419f-987d-da53ace7a468)

All right, so here's the second operation. It's called the “swap” operation, and in this case each ball takes on the value of the opposite ball.
So it's not moving the balls. Notice the dotted lines are to indicate that the top ball is still the top ball, it just changed color.
So if we have a black on top and a white on the bottom starting out, then we'll have a white on top and black on the bottom at the end.
Likewise, the white on the top and black on the bottom will end up with a black on the top and white on the bottom.
If the two values coming in are the same, then a swap does nothing. They will remain the same. 

![image](https://github.com/user-attachments/assets/ec8d5617-f1f0-4866-b075-0b0331c22ca1)


All right, so now let's try some multiple swaps, as well as combining nots and swaps. 
So again, you can pause the video, think about it, predict what the outcomes are, and then we'll check our work.
Okay. So if I start with a black ball on top and white ball on the bottom, after a single swap the white will be on the top and the black will be on the bottom.
And then the values will swap back again, so we end up with the same values we started with, just like the not operations. So these are their own inverse. If we apply it twice, we get what we started with. All right, let's look at the second one. So first I will apply the not gate to the bottom ball, which gives me a white ball on the bottom and a black ball on the top, and then a swap so they'll swap values but not location. So now the top ball will become white and the bottom ball will become black. 

![image](https://github.com/user-attachments/assets/1a89c814-a144-49a6-a82e-1aefc0678605)


All right, so now our third operation is called a “controlled not.” This is interesting because the swap operation was symmetric.  
It didn't matter which one was which, the operation was the same.  A controlled not is not like that. Order matters. So let's look at this. 
We have two inputs. One is called the target and one is called the control. 
So the control does not change, and if the control is white then the target does not change.  If the control is black then the target changes. So we can see here that, for the two left-handed operations, the control ball was white.
And so the inputs in the outputs are the same. 
For the second operation, in the right hand column, we can see that the control ball was black, so that means the output applied a not.    We applied a not to the target and so the output of the target is opposite of the input. 

![image](https://github.com/user-attachments/assets/12b4cbaa-0c93-488c-ab60-260d92301fed)

All right, so let's try a few. 
Okay, let's go through them. So first we swap the black and the white. 
So now the top ball is white and the bottom ball is black, and then we apply the c-not. 
And the c-not control is white, which means the outcome will not change. Now let's look at the second one. We have the not gate, which toggles the black ball from black to white and then we have the c-not.   
And we can see with the c-not in this case the control is black and so we will toggle the value of the target. So now the target becomes black.
And now we have two black balls going into a swap. We know that if we have two of the same value going into swap, then none of the values change. So we end up with two black balls. 

![image](https://github.com/user-attachments/assets/12ea8b87-6c13-4a48-a879-fbe600cc9b3f)


Okay, let's look at this one. I want you to look at this picture very carefully because what's important here is that I've swapped the order of the control and target on the second one because the order of the inputs matters.
We can connect the c-not in either way we want. 
And so you can see that the symbol, the filled-in spot, versus the plus sign with the spot are opposite in these two. So we're going with a zero and a one into the first c-not gate and in the first c-not gate the control is white.
And so we end up with a white ball and a black ball in the first one. 
But in the second one we can see that now the control is black, and so we will toggle the top bit.
Okay, so I just want you to be aware that when you're looking at a c-not it is not always the case that the control is on top and the target is on the bottom. You always have to look for that symbol.
 

- [Audit_QOps1_practice_questions.pdf](https://github.com/SteveJustin1963/QC/blob/main/Audit_QOps1_practice_questions.pdf)
- [Audit_Intro_to_QC_and_QOps_1_Homework.pdf](https://github.com/SteveJustin1963/QC/blob/main/Audit_Intro_to_QC_and_QOps_1_Homework.pdf)


# Quantum Operations: Part 2 / Section Overview
In this section, we continue learning about operations and introduce a physical concept critical to quantum computing: superposition. Qubits in superposition don't just have one value or another - they have two values at once, with a probability of reading one or the other when you measure the qubit. We’ll also talk about another attribute that is important for quantum computation: phase.

# Introduction to the H Gate
In this section, we continue learning about operations and introduce a physical concept critical to quantum computing: superposition. Qubits in superposition don't just have one value or another - they have two values at once, with a probability of reading one or the other when you measure the qubit. We’ll also talk about another attribute that is important for quantum computation: phase.


![image](https://github.com/user-attachments/assets/15f5b757-281f-4aa1-9f01-608556b13ffb)

Hello! Today we're going to talk about the quantum H gate.
It is a probabilistic gate and we'll go into what that means in a moment.  
Now, let's look at how this gate works. We put in a black ball, maybe we get out a white ball.  

![image](https://github.com/user-attachments/assets/b11ae9e7-c3cd-4221-be57-8db7e4b38424)


 We put in a black ball, sometimes we get out a black ball.
So, if we were to give it lots of balls in sequence, lots of black balls, we would end up with the results being half black,  half white.
Which means that 50% of the time when we apply an H gate, we end up with a black ball and half of the times when we apply the H gate we end up with a white ball. That seems very odd. Okay. Well, likewise, it won't be any surprise to you that if you give it a white ball and apply the H gate, then sometimes you get a white ball out and sometimes you get a black ball. And by out, I don't mean physically out of it. When we apply an H gate, our result is either a black ball or a white ball. And just like the black ball, if I were to do this many times then my results: 50% of the time would be white and 50% of the time would be black. You might be thinking this seems completely random!   

![image](https://github.com/user-attachments/assets/fd479d0c-e782-4e71-aafe-39d05ec450d9)


Well, let's look at what happens. The observed outcome from a single gate is, in fact, random.
So, we'll indicate this here. We need something else now, we need a measurement symbol.
So that means that whatever H produces, if I apply H to a white ball and then measure the result, it's either black or white. But before I measure the result, it can be also either black or white; but I don't know what it is. I don't know the state of it until I measure it. And this is what all of this has been, we just haven't really talked about the role of measurement and we're actually going to talk about it a lot more in the next video. 
But for now, we'll look at the fact that this means that when I measure, I have a 50/50 chance of measuring a black value or a white value.
But the probability itself is predictable -- it's not the case that 70% of the time I get a black ball and 30% of the time I get a white ball. It is 50/50.
Okay, but in a single instance, I have no idea if I'm going to get a black or a white ball -- it could be either one. So we can depict this this way.

![image](https://github.com/user-attachments/assets/71a11965-9b55-4574-93c3-5f05a120cec9)


Alright, so we're going to explore this H gate a little bit, because it ends up covering a lot of quantum concepts that are important.
So what is going on with these  probabilistic gates? We'll look at some of their odd behavior and how to explain it, and then we need to figure out how to represent this probabilistic output visually in a way that we can have it be inputs and outputs to other gates. And then in this course, we're also going to start introducing the mathematics so that you can calculate the values and predict what's going to happen, and so we'll need a representation, a mathematical representation, and then we'll need to learn the operations to calculate them. 

![image](https://github.com/user-attachments/assets/847f1728-db79-4357-92ae-5b1e3519ee62)


We won't do this all right now, we'll do this over the course of several videos.
So the first thing we want to ask is, is the H gate truly random and how would we know?
It appears random right now and what I mean by random is that if I looked inside, no matter what I give it, there's a 50% probability that nothing will happen to that and a 50% probability that I will apply a NOT gate to that. 

![image](https://github.com/user-attachments/assets/e498a1d0-98e6-472f-bed0-aafd99427395)


That's what we'll describe as random. And so let's look at whether this is random. 

![image](https://github.com/user-attachments/assets/95db1158-8832-4306-a55b-211e909b54be)


So, if I had random gates and I gave it a set of black balls or a set of white balls, and I applied two random gates in a row -- what would happen?  
Well, it would all be random, right? Because at the end of the first gate, I would have either something that's black or white and then I would have a 50/50 probability of flipping that back or keeping that value.
And so it would look like once I get one random gate, it doesn't matter how many I apply in a row, the output will always be 50/50 probability of white versus black values measured at the end.

![image](https://github.com/user-attachments/assets/10397ecb-254d-4357-ba9d-906c307b0f51)


Okay, but let's look at what happens with the H gate.
If I give it a sequence of black balls and I don't just apply one H gate but I apply two in sequence, I actually get back black balls. Every time I measure, I will always get a black ball.
And if I start with a white ball, every time I measure I will get a white ball. So that means that H is its own inverse. But if it were truly  random, we wouldn't be able to invert it because we wouldn't know if it had been flipped or not. So there must be something extra going on here. So, although it appears random when I only do one of them, it's not actually random. 

![image](https://github.com/user-attachments/assets/7d6a3f20-43c7-4820-9eb8-79f62149ff4b)


And so we need to explore what makes the H gate different from a purely random gate.

![image](https://github.com/user-attachments/assets/a2861c80-4486-465a-97d1-296e9d05e51c)

Alright so what we know is that after two gates it's different from a random gate.  
We also know that there's some state in the middle of those H gates that we haven't depicted, because measurement is not the same as the state.
So, after an H gate but before measurement, the ball can't be just simply black or white -- it needs to be something more complex after an H gate. 

![image](https://github.com/user-attachments/assets/dc565197-e8ef-43d7-8b6e-529498022dd6)

So what we need first is a visual representation and so we're going to represent it this way.  
It turns out that an H gate we know has a 50/50 probability of measuring black or white.
So this is something we've already observed and so we know  this to be true, so we're going to depict it this way -- with a rounded box, rounded rectangle, with black and white, which means equal probability of black and white.
No matter how many things I have in this block, it means that they're equal probability of each of them. So, because there are two of them that means it's a 50/50 probability of the black or the white.
But what you'll notice down here is that when the black ball gets applied the H gate there's a negative sign in front of that black ball. And this is indicating that even though the H gate had a probability of measuring black or white, the negative sign does not affect the probability of measuring black and white. But what you'll notice down here is that when the black ball gets applied the H gate there's a negative sign in front of that black ball.
And this is indicating that even though the H gate had a probability of measuring black or white, the negative sign does not affect the probability of measuring black and white.
It means there was something we were missing about the state; somehow, the state reflected the fact that the black ball had produced it versus the white ball produced it and so we're going to use the negative sign. In quantum, that actually has a physical property which is called phase. And so we'll get into that later, but right now what we need to know is that this is how we'll depict the output from an H gate. And we'll see how doing that allows us to calculate and actually figure out, “oh yes, it should go back to its original state if we apply the inverse.” 

![image](https://github.com/user-attachments/assets/ef94826b-71ff-4ca0-82e3-530b0689354c)


So, what we've figured out is that in the H gate, the states are not identical between the black and the white, but they are 50/50 probability of being measured a black or white.
And what we know: that for random, it's also 50/50 probability of measuring black or white. But even when we go through the random again, it ends up with a 50/50 probability of black or white. So that's what's different in our observations. We'll have to see mathematically what that would mean.

[https://github.com/SteveJustin1963/QC/blob/main/audit_H_Gate_Intro.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_H_Gate_Intro.pdf)

# VIsual Representation of Superposition

![image](https://github.com/user-attachments/assets/e2e4e894-5ccb-45f3-aa34-8c9bf9f52989)


Start of transcript. Skip to the end.
Okay, now I'm going to go into a few more details about how this visual representation depicts the superposition state.
So, we've been showing a 50-50 probability, in which case we have two spots: one that's black and one that's white.
And that indicates a 50-50 probability of measuring black or white. But what happens when we have other probabilities? The idea with this representation is that in a certain rectangle, all of the choices are equal probabilities.
So if I have one black and three white in four different spots, that means that I have a 1/4 chance or 25% chance of measuring black and a 3/4 chance or 75% chance of measuring the white. 

![image](https://github.com/user-attachments/assets/5e882643-ff2d-4459-979b-0605483a8d7d)


Okay. So, we can also have superposition states as input and operate on them. So, let's imagine that we have a NOT gate.
What we do is we essentially split this NOT gate so that the NOT gate is applied to each one.
So now we have the top one going into its own NOT gate and the bottom one going into its own NOT gate.
And so then on the other end we see that now we have the white ball on top, or the black ball has turned into a white ball on top, and the white ball has turned into the black ball on the bottom.

![image](https://github.com/user-attachments/assets/fa058489-17c9-45b4-ada7-ba17717e0ceb)


Alright. We can also do this with our four input or our four part superposition, where each one is worth 25% instead of 50%.
So, once again, we would split this NOT gate into four little NOT gates and each state would go through this NOT gate and get to the output.
And so we can see that if we have a state that's 25% chance of measuring black and 75% measuring white, if we put that state through a NOT gate we're going to get a state that has 25% chance of a white ball and 75% chance of a black ball.
I hope that you also see that that's somewhat intuitive, right? A NOT should swap it and so it makes sense that my black and my white probabilities would swap.

![image](https://github.com/user-attachments/assets/71baf41a-dcbd-42aa-b5a6-cb936a19e590)


 Okay, so now let's use this to revisit some odd behavior with the H gate. So, we have the H gate and it outputs a certain superposition state.
And we have this, we have this state, this condition where when we put it through the H gate again, it no longer is in superposition.
And so let's look more closely at the second part of this H  gate and understand really what's going on.  

![image](https://github.com/user-attachments/assets/f98a34b1-fd49-469a-95df-aaef57e1aa27)


So, don't worry if you feel the need to come back to these slides and do the movement a little bit more slowly.
But what we want to do is break this down. And so we have two little H gates, one that we put the black into and one that we put the white into.

![image](https://github.com/user-attachments/assets/57747463-e4d1-4d16-b594-2066d58c74f5)


And so now we know that the black one turns into the negative black over the white and the white one turns into black over white, and we have a superposition of those two choices.
Now, what's interesting about this is that if I have, if I have a 50% chance of a 50% chance of either the top ones and a 50% chance of a 50% chance of the bottom ones, because these are all independent we can use that rule we learned before where we multiply the probabilities.
And so 50%, ½ times ½ is ¼ so we can actually now say, “oh, well, we have four possibilities with equal probability.” Right?
And so now when we look at those possibilities something very interesting happens, and this is what's so interesting about choosing the negative sign.
It turns out that this negative sign wasn't just arbitrary, it turns out that mathematically we can actually add and subtract. And so I see a negative black and a positive black and those  actually cancel each other out.
And we'll be learning the full mathematics for that later, but  in this case we're just doing it with the visual representation.
And that's the rule, is that you have, if you have a negative and a positive of exactly the same within a superposition of equal probabilities then you can remove them.
And so now we have the case where we have a 50-50 probability of measuring white or white.
Well clearly, that's the same as 100% probability of measuring white.  

![image](https://github.com/user-attachments/assets/060e3a8b-2e5a-4409-8852-1675770d5cb8)


Okay, likewise, if we start with the black then we'll do the negative through, negative black through an H gate and then the white through an H gate.
So we have now, which is interesting, we have a negative sign preceding the state. That's negative black over white.  
And then we have the black over white from the white ball.
Now this is also interesting, again. Because like algebra I can distribute the, multiply by the negative sign. 
So what I'm going to do is I'm going to not only  say, “oh, these are all four equal probabilities,”  but before I do that I'm going to take the negative sign.
And so the negative and negative on the black turn into a positive. But the negative is with the white.
So now we have this situation, we have a negative white ball and a positive white ball which cancel out. And so now I'm left with 50-50 probability of a black or black, which is 100% probability of a black.
So this is the math, the mathematics using the visual representation. And it's very powerful because with certain problems we can actually do quite sophisticated algorithms using only this visual representation and not needing to learn the matrix multiplication operations.
But we will also be learning those in case you're taking this for required credit or are going for a certificate of any course, any kind. 

![image](https://github.com/user-attachments/assets/f042f309-77de-49e4-ae66-8c8b714e786e)

Alright, so, what did we learn? The H gate puts the qubit in superposition. We know that.  
And then it's applied to a pure state of 0 or 1, and that results in a 50-50 chance.  
But two H gates in sequence reverse each other, resulting in the original input, which seemed really counterintuitive and that's what really told us that there was more going on there and there must be more to the state than just simply probability of white and black.
And so then we introduced the negative sign for phase and then I showed the calculation with the phase value that accurately models or predicts the reversing behavior. Thank you.

# Working with Phase

Okay, we just learned about a new attribute of quantum state called phase.
And so I want to just talk a little bit about it. 

![image](https://github.com/user-attachments/assets/f6140400-ad21-4a33-a4d5-202c2970fcd2)

So, you might recall that in the superposition video we saw that if we put a black ball into the H gate, then we get a state that's 50-50 black versus white, but the black ball has a negative sign on it.
So, we want to explore how that negative sign works. So, that's an indication of phase.

![image](https://github.com/user-attachments/assets/0a2d48ee-0242-4f11-b04b-1ec12717f916)

And we don't need superposition to have phase.
So we actually have a Z gate, which I like to call the phase flip gate.
And if you give it a white ball, then nothing happens.
But if you give it a black ball, then it changes the phase of the black ball from positive to negative or from negative to positive.

![image](https://github.com/user-attachments/assets/3dfbf6d8-d1c9-415e-aadd-d03d266c386b)


All right. So, let's also look at a little bit, let's look at what would happen if we gave a NOT gate the superposition that was resulting from that H gate from the black ball.
So, we're giving it as input a 50-50 chance of a black ball and white ball, with a negative sign.
And so if we put this through the NOT gate, that would flip the color of each of the balls but retain the negative sign, because the NOT gate doesn't do anything to phase.
And so, what we see is, we end up with a state that has the negative sign on the white ball.
And there's nothing inherently wrong with that, except convention.
And so negative phase is actually an attribute of the qubit as a whole. It's not associated with the white ball or black ball, but the convention is that we always put that negative sign on the black ball.
So, once you've completed your operation, then there's an additional step that we sometimes have to do to fix the negative signs, to put them in the right place.
And so, in this case, we would swap it from the white ball to the black ball.
Because this is only talking about one qubit and it's really just saying that the phase is negative for this entire qubit. Even if this qubit measured a white, it still could measure, if we measured just for phase, we can't measure for phase and white and black at the same time.
We would have to choose which measurement we're doing.
And we've only in this course talked about measuring white and black.
And that is actually all we're going to talk about, most of the time.
But the point is that if we were instead to do a measurement about what the phase is, the fact that the phase is with the black or the white doesn't affect it. This is just about whether or not it's negative phase or positive phase. 

![image](https://github.com/user-attachments/assets/b9c19353-2410-44a9-afa7-c4d9856426e5)


Okay. Let's go one step further.
We have the Z gate that you already saw and it ends with the black ball with the negative phase.
Now let's imagine we were to put this through two NOT gates.
We know from learning about NOT gates that whenever you put something through two NOT gates, you should get back your original state. That includes the phase.
So, here we have our negative black ball at the end. So the question becomes, what should the state in the middle be?
Specifically, the phase aspect of the state.
Because we know that we should have a white ball that's not affected by the phase. And so the question is, should we have the phase negative sign here? 
Because I just got through saying that the phase is, by convention, placed with the negative ball, which is the black ball.
I just got through saying that the negative phase symbol is placed with the black ball and not the white ball.
But here we have something that's 100% white ball, so there is no black ball aspect to the phase in the superposition.
So, it is true that we need to have the negative sign or else if we put it through NOT, we know what a positive white ball is NOTed. It's a positive black ball. So we need to have the negative phase there.
So, when there's no superposition it actually can be the case that you have to put a negative symbol on white ball.
Because, as we recall, the negative phase is about the qubit itself and not just the white or the black.
It's just convention as to where we put it, because that's where the mathematics works out for all of these operations. Especially when we get to two-bit operations soon. 

![image](https://github.com/user-attachments/assets/794682bf-8c38-4c77-85c9-e6488888f9b5)


All right. Now let's consider this last situation.
We have a situation that has 25% chance of measuring black and a 75% chance of measuring white.
Or a 1/4 chance of black and a 3/4 chance of white.
And we put it through a NOT gate. Right. And then we get 1/4 chance of white and 3/4 chance of black.
So let's look at what happens if this had been with phase.
So, let's imagine that we started out with a negative phase.
So, you can see the negative on the black ball. We put it through a NOT gate.
That would end up with the negative sign on the white ball and three black balls with no negative phase. And we know that we're supposed to put the negative phase on the black ball.
And the question is, do we do it on all black balls or just one black ball?
And it turns out that we would do it on all black balls because if we were using those as inputs to later gates, we want the negative signs to all be there.
Because all of our gates in quantum are set up assuming that the negative sign is going to be on the black ball. So there we go.
So in summary, phase is associated with the entire qubit, not the zero or the one element.  

![image](https://github.com/user-attachments/assets/bb2eec5e-1e0f-4804-8d2a-61541eb902eb)

However, by convention, we place the negative sign with the one term.
And if there is no one term, it'll go on the zero.
And for the visual representation, if there's more than one black ball in a single qubit superposition state, we'll put the negative sign on all of the black balls.

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_Visual_Superposition.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_Visual_Superposition.pdf)

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_QOps2_homework.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_QOps2_homework.pdf)

# Probability basics
Because qubits can exist in superposition, the outcomes of quantum operations can be probabilistic. Therefore, this section begins with an overview of calculations involving probabilities. We also discuss the important fact that measurement “collapses” the state of a qubit in superposition. Just like measuring the strength of a vase by using a hammer destroys the vase, measuring the state of a quantum bit can also modify its value.

![image](https://github.com/user-attachments/assets/84a8da73-7218-4032-96d0-36fcd1d7f604)

Hello! I'm just going to give you a really short introduction to probability. We only need a little bit of it for quantum computing but we want to make sure we understand it correctly.
So let's just look at a popular example of probabilities: You get a prediction about the weather.
When I look at my phone I might see this in the morning. For each time of the day, it gives me a probability that it will rain. And so what we want to explore is what does that really mean.
What does the probability of rain at any one moment really mean?

![image](https://github.com/user-attachments/assets/2519baea-0054-4bc1-b14e-89aa8cc9fef7)

So let's see. Does it mean it's going to rain at 11 p.m. because at 11 p.m. it's at 6%?
Or does does it mean that it's not going to rain at 11 p.m.? Or perhaps that it is going to rain at 4 a.m.? Or does it just mean that it's more likely to rain at 8 a.m. it is to rain at 8 p.m.?
It is not a valid conclusion that it is not going to rain at 11 p.m. It still could rain at 11 p.m.
The probability wasn't zero. In addition, we don't know that it's going to rain at 4 a.m. It only has a 40% chance of raining, so it might rain but it might not.
Now, is it more likely to rain at 8 a.m. than 8 p.m.? Why yes! It is in fact more likely to rain at 8 a.m. than 8 p.m. But notice: being more likely still doesn't mean it's going to happen, so this prediction doesn't actually tell us whether or not it will rain on Sunday.

![image](https://github.com/user-attachments/assets/906b51ea-ced0-4fc8-9109-314972d3d15f)

So then we have to ask ourselves: What does this information give us? Well, what it says is that given our limited information, because we don't know everything, we don't understand well enough how weather works, if we know what it's like right now we're not perfect at predicting what
it's going to be like later. So given our limited information, if we experienced a hundred thousand, a million, a billion, an infinite number of days with these identical conditions then we could predict. If it were 100,000 days with identical conditions to now, approximately
40,000 of them would have rain at 4 a.m. So i don't know if this particular Sunday will have rain, I just know that less often than half of the time when I have conditions like this, I get rained on at 4 a.m.
Okay, so when we think about probability let's first think about things that probability is not. Probability is not actually predicting that something is definitely going to happen or not happen for an individual action. Okay, unless it's at 100% or 0%.
So if I have a 75% probability of something happening, that means I don't know it's going to happen. However, what I do know is that if I were to repeat this trial, this test, if the test has a 75% probability of having a certain outcome, that if I try it many, many times then 75% of those will have that outcome.


Likewise, I can't tell whether a prediction, a probability, was correct by the outcome of a single one. If I say that it it has 99% probability of something happening, so there's a 99% probability of rain at 10 am and then there isn't rain, does that mean that my probability was wrong? Well, no. This could have been the 1 in 100 that didn't have rain.
So we can't tell whether a probability is accurate by just looking at a single trial. We actually would have to do many, many, many identical trials or experiments and see the outcomes of many, many of them to see if our probability was correct. This is very important for quantum because quantum has outcomes that are probabilistic. And so that means that most of the time we don't know exactly what the quantum outcome is going to be that particular time. We can only tell after many, many times.
So, there's a second really important thing about probability for quantum computing which is that if I have two independent events with their own independent probability, I need to be able to calculate the probability of both events happening, both events not happening, the first event happening but the second event not, or the first event not happening and the second event happening. So I need to be able to take the probabilities associated with independent events and combine them to be a probability of certain combinations of those multiple events.
So let's take this as an example. Let's imagine that there's a 50% probability of rain this afternoon and unfortunately there's only a 25% chance probability that I will remember to bring my raincoat, because that's just the way I am. So the question is: What is the probability that it will both rain and I will forget my raincoat?
So first we're going to reason this out with sort of a visual representation and then I'll show you how to calculate it only with mathematics.

![image](https://github.com/user-attachments/assets/65b7113e-de5c-4517-9db6-a1aaf497f676)

So, we can set this out so I have I only have a 25% chance of remembering my raincoat, which is a 1 in 4 chance. So 3 out of 4 chances, 3 out of 4 times, I will forget my raincoat and I'll just have this nice shirt on. And then for rain and shine it's 50-50, so I have equal probability of each one.
So these are the independent probabilities and this is a way of visualizing these independent probabilities. So if we were to say, well, what about raining and jacket? So we could combine these by saying, well, I could have sun and in the case that I have sun I have all of these chances. Right, 3 chances for a shirt and 1 chance for my raincoat.

![image](https://github.com/user-attachments/assets/6906de2e-17a4-4165-8eea-cffe600435d1)


![image](https://github.com/user-attachments/assets/b0d1c064-8262-44aa-a299-5cc65088344d)

Same with raining. So I can picture it this way, where the first 4 are all in the sun and the second 4 are all with rain. So what I end up having is 8 equally likely, non-unique scenarios, 4 of which are sunny, 4 of which are rainy and 3/4 of which have me in my shirt and 1/4 of which have me in a raincoat. So I can look at this. I say, oh, 3 of these scenarios have me getting wet, in the rain with no raincoat. So out of the 8 total scenarios, 3 of them were the ones I was hoping not to encounter. So that's 3 out of 8 or 37.5% probability.

![image](https://github.com/user-attachments/assets/ff66ae47-08ed-4436-9aa0-6157e2e594ba)

The way you calculate this with mathematics is that you use the original probabilities, 0.75 or 0.25 and then 0.5 and 0.5, and you lay out all four possible combinations. And you just multiply the probability of one happening with the other. So, the probability of a shirt is 75% and a probability of rain is 50%, so I multiply 0.75 times 0.5 and I get 37.5%.
And I can look at this for all four combinations. So there are four unique combinations and if I add up all my percentages I could just check to make sure I'm right. Or to have one sanity check is just to check to make sure everything adds up to 100%.
And it does. And in fact, all the things with the sun add up to 50%, all of the things with the cloud add up to 50%, everything with the raincoat adds up to 25%, and everything with the shirt adds up to 75%. So that's a way that I can double check my math.
So just long story short: if you want to find the probability of two events happening, if you have the probability of each one of the independent events you just multiply those probabilities together.
So how is probability used in quantum computing? Well, each qubit in superposition has a probability of being measured 0 or 1. That's a single independent probability. It turns out, though, to do any useful computation you need to use multiple qubits. And so, once we combine individual qubits to be multiple qubits working together, that putting them together we multiply each combination of outcomes by multiplying the probabilities. And then once we have them in those multi-cubit probabilities, then we can do multi-cubit operations and calculate the outcomes.
I would like to conclude with a few random thoughts. Or, more accurately, some thoughts about the word random.
So, now that you've seen probability and different ways to look at it, I want to introduce this fact that "random" is used differently at different times.


![image](https://github.com/user-attachments/assets/316f88d8-0ee0-4f1e-a7eb-9dff5aad0b00)



For example, "That was such a random comment!" That means that it was unpredictable to me, right? Because whoever made the comment didn't necessarily think it was unpredictable. They thought of it.
But when you use that word, random, in that context, you're just meaning that you would never have thought of that, that was so unexpected to you. So, random can just sometimes mean unexpected, which could mean unpredictable, which means very low probability.
We could also say, "Draw a number at random!" or "Pick a number at random." That means each number has equal probability of being drawn or chosen. So, sometimes random means low probability or "I didn't expect that" and sometimes it means equal probability.
In quantum, when physicist talk about random, they might say something like, "Quantum measurements have random outcomes." It does not mean what it meant in the previous two.
What it means is what we've been seeing. that there's a probability, a known probability, of the outcome. The outcome of a single measurement is not guaranteed. It is indeterminate or nondeterministic.

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/Audit_Probability_PQ.pdf](https://github.com/SteveJustin1963/QC/blob/main/Audit_Probability_PQ.pdf)



# Measurement and Superposition

of transcript. Skip to the end.
This time, we're going to take a lot closer look at two concepts that we've been touching on: superposition and measurement.
I'm going to start out by having analogies to daily life and what we know about superposition and measurement in daily life, and then we'll look at how this is applied to quantum, what we've seen before and some new phenomenon because this is the key to how quantum operations are more powerful than classical operations, along with one that we haven't introduced yet called entanglement.
So, superposition, measurement, and entanglement are going to be both the power and the limitations behind quantum computing.
Okay. Let's consider measurement. And when I say measurement, we need to realize that this actually consists of three things.

![image](https://github.com/user-attachments/assets/019b0947-f498-4d71-becc-95c76d6c60fc)

One is a question we're trying to answer. Another is a device, some sort of measurement device. And a method by which we use this measurement device.
So for example, if my question is, “What is the table length?” then my measurement device is the tape measure and my method is to pull that tape measure along the length of the table and read out the number at the end.
Okay. So we're all used to measurement, there are lots of measurements that occur in our daily lives. Let's look at another one.

![image](https://github.com/user-attachments/assets/b8ef7ac8-b647-4662-a3a2-e609c9566596)


My question is, “How is this baby feeling?” and my measurement device is my own eyes and ears.
Alright. So, my method is, I'm going to look for smile, frown, tears and I'm going to listen for laughs, silence, or screams.
Okay. And let's think about how accurate this measurement method is and device. So if I see a smiling baby and I don't hear anything, then that could be happy, excited, or proud.
I don't know exactly what that baby is feeling. And now, if I see, if I hear crying and I see tears and a frown, well that could be several things, as well: hungry, frustrated, tired.
You know, my child used to cry and we couldn't figure out why. We'd ask her if she was hungry and she would say no.
And then if you could just get the banana to touch her tongue, all of a sudden she would just consume the banana and she would be back to her happy self.
So, measurement devices with babies and small children are just not accurate. Okay.
Alright, so what we want to understand from this is that some measurements give only partial information and this is going to be key for quantum.

![image](https://github.com/user-attachments/assets/3aa5edc3-cee2-4dc0-ae7e-2439adafc0ef)

Alright, how about another one? So, how long can  you hold your breath?
Now, our measurement device is going to be a stopwatch and our method is going to be to use a stopwatch to time how long you can hold your breath.  
Alright. And let's think about how accurate this is. Well, what's interesting about this is that you might think it's accurate the first time, but if you do it immediately afterwards your time is likely to be lower and lower and lower and lower.
And so why is that? If the measurement device were accurate and the method, wouldn't that mean that we should get the same result every time?
This has a second phenomenon, which is that some measurements affect the item being measured. If I hold my breath for 30 seconds or 45 seconds or however long I can, now I am short of oxygen.
That measurement process, it wasn't the device that did it but the method of holding my breath for the measurement changed me in the sense that now I have less oxygen in my system and now after this I cannot hold my breath as long.
So, we have two very important aspects for measurement that we've seen which is that sometimes measurement doesn't reveal the full state and the second is that measurement can perturb the state.

![image](https://github.com/user-attachments/assets/6a2c8d66-ee44-4274-9803-c9ff6fa8d814)

So, let's look back at our H gate that we learned about.  
We know that when we come out of the H gate, we have a certain state. Then we can measure this state.
And so, I just want to point out, we've been seeing this the whole time, but I just want to point out the fact that this measurement only revealed part of the state.
And the other thing it does is, it collapses the superposition and so now the state is either black or white ball.
It's not just that I measured black or white ball, it is that the state now goes back to being 100% probability of subsequent measurements measuring the black or the white.
It's not the case that I can measure it once,  “oh, I got black this time. I'll measure it again. Oh, I got white,” and then keep measuring it and in the end maintain a 50% chance of measuring white or black upon the first measurement.
Now, further measurements will be always that same value unless I put it through another H gate or another gate that puts it in superposition. Okay. So both of these are very important.

![image](https://github.com/user-attachments/assets/66cde187-7bef-4964-9a6a-466a98805d3b)

Alright. So, now let's look at superposition. So, there are superpositions in our daily lives.  
If I look at this picture, some people might see a duck, some people might see a rabbit.
Okay. We have this famous one is that two faces or a vase.
And then is this a young woman looking back behind us with a tiny nose and eyelash or is this an old woman where the cheek and chin of the young woman is actually just the nose of the old woman and her mouth is near the bottom of the picture?
So, these are all, these could be considered superpositions because it's a single image with multiple pictures in it.
And we don't want it just viewed as something that is two things, it's that it has two values potentially and the observer chooses at any moment in time which one they're seeing.
But this isn't like quantum in that when I observe it, it changes it. Right. It's still, I can observe it. I see it as a vase. I look a little differently, “oh, I see the two faces now. Oh, I see the vase.”
So, this does not, the observation or measurement does not disturb the state at all. Okay. Let's consider another one. Let's look at this word.

![image](https://github.com/user-attachments/assets/3d9a66bc-88aa-47e4-860d-2d71a1c5e5b7)

How do we pronounce this word? Hmm. I don't know.  Is it something you can use to make things shine on your floor or your furniture? Or is this something related to the country Poland?
Okay. So let's think. The word alone is ambiguous. If I just put that word there, there's no way for you to know. So, what is your measurement device? Well.

![image](https://github.com/user-attachments/assets/6953d6ee-7a46-49b0-9aee-eb1f4559202e)

We can measure this to resolve the superposition. Right. So, I need a device and a method. My device can be my ear. So if someone said it aloud, my ear would tell whether they said polish or Polish.
Or, if I'm reading it, I can read the words around it for context. Right. So, polish makes the floor shine or Polish sausage is delicious.

![image](https://github.com/user-attachments/assets/bdd35145-8d52-4c69-9602-c97ff3131152)

Alright. So, let's look at this again. And so, if we look at our H gate, we already saw the calculation that if we put a ball through the H gate twice and measure it, then we get out the same as we put in.
And we saw all those calculations. Okay. So, now we're going to introduce something interesting. What happens if we measure in the beginning?

![image](https://github.com/user-attachments/assets/88e7febf-a8d3-42c8-93de-3a263cac7076)

Okay. So, let me just show more carefully what happens if  we don't measure. Right? So, if we don't measure, then we get out the black ball and the white ball.
But we had a superposition in the middle and the superposition was the output of the first H gate and the subsequent input of the second H gate.

![image](https://github.com/user-attachments/assets/c2c6ef36-0f81-4e72-b0d1-c01abb177dd5)

What would happen if we measured in the middle, and then we put it through the gate, and then we measured? What would happen?
So, go ahead and pause the video and think about what you think is going to happen on the output based on this measurement.
Alright. So, you're ready to move on. Okay. Let's look at it. So, we start with this H gate and we know that when we go through the first H gate we have this superposition.

![image](https://github.com/user-attachments/assets/02ef0587-46b3-4855-b8d4-37a339627e87)

But this measurement collapses it into black or white, and so now I have either black or white going into an H gate.
So, now what I get out. If it's a black ball, then I'm going to get a negative black on the top and a white on the bottom.
And if it's a white ball, I'm going to get a black on the top and white on the bottom.
So, I've made the negative sign gray because the  negative sign may or may not be there. Right.
The negative sign is based on the outcome of the first measurement.
However, what we do know from this is that, regardless of the phase, the measurement for this has a 50-50 probability of black or white.
This is very different from what happened when we didn't measure in between.  
And so this just shows you the profound effect that measurement has on quantum gates.
So, if we have the measurement in between these two H gates, we have an unpredictable outcome.  
Whereas when we didn't have a measurement at the in between, there was a predictable outcome.

![image](https://github.com/user-attachments/assets/2be07553-b9c1-4d1a-9a3e-f3102a890c3f)

Alright. So, let's just make sure we're on the same page here. So, quantum superposition has two values, right? Zero or one.
And a part of the quantum state is the probability of measuring zero or one. We've been seeing this for a while now.
But the probability is, is a measurement, it's not of the state, it's the probability of a measurement detecting it.
And that probability gets manipulated through quantum operations. That's what quantum operations are for.
Their job is to manipulate those probabilities and the other  parts of the state, like phase, because that also impacts future operations.
Okay. But what's really important is that measurement cannot detect the entire state, it only detects a zero or one.
Or if you go farther in quantum computation, you will see that there are other aspects of the state that you can measure, but you only get one measurement because once you get the, once the measurement happens, it collapses an aspect of the quantum state.
And so you can't just continue as before, pretending that no measurement occurred.

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_SuperpositionMeasurement_PQ.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_SuperpositionMeasurement_PQ.pdf)

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_Prob_Superposition_Measurement_HW.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_Prob_Superposition_Measurement_HW.pdf)

# Bits and Qubits: Bra-ket Notation

So far, we’ve been working with visual representations of qubits and operations. In this section, we introduce two types of mathematical notation for quantum state. Using mathematical notation has two purposes. First, we can quickly glean what the probabilities are of measuring each possible outcome. Second, it allows us to easily calculate the results of quantum operations.

Today we're going to introduce bra-ket notation. This is the mathematical notation for expressing the quantum state of one or more qubits. 

![image](https://github.com/user-attachments/assets/0a5daab9-dc4c-400f-a7db-e60a0d17282a)

Let's just take a look at the classical computer and decompose it. So, everything in a classical computer is stored as a number in a variable.
So, each letter of the sentence has a number. For example, lower case s is 115 and capital is is 83. The color of the font is a number.
The number of slides in the presentation. Every image in this presentation is stored as lots and lots of numbers and sounds from audio files are stored as numbers.
So, everything that a computer does is based on numbers and so all of those numbers are in fact stored in binary.

![image](https://github.com/user-attachments/assets/ac9fcfe5-e118-4c86-a06a-0ca96c015fe2)

A binary digit holds a one or a zero at any given time. That binary digit is called a bit and eight bits is a byte.
So, when you hear about the capacity of a hard drive or memory all of that is in eight bit chunks or a byte.
And just for fun, four bits is a nibble but that's rarely used; bytes are what's used.
What's nice is that programming languages typically hide these details, so even people who program for a living don't need to worry about bits or bytes.
They just worry about numbers and often they can just worry about colors. You can say red and the language will have a number associated with red, but as a programmer you can just use the word red and so programmers can often ignore these details as a service from the programming language.

![image](https://github.com/user-attachments/assets/9d48fe07-54ac-48d0-ba69-fa3b29e34037)

However, the quantum computer we don't have that yet, we don't have programming languages that allow us to abstract away all these details. And when we do, they're heavily steeped in math.
And so, we're going to start from bits. So, the classical bit is a zero or one. And the quantum bit, we've already been using this notation to try to get you used to it, and so the quantum bit is a zero or a one in that funky notation.
And so, what that means is that the zero is in that ket is the probability of measuring zero. And the other one's the probability of measuring one, which is why we don't state it's just zero or one.
It's actually related to the probability of measuring that. And then we know that the phase can either be positive or negative.
In this course we're not going to cover anything other than positive or negative, and then the probabilities of measuring zero or one.  
But there is one more aspect that you can do as bonus material, if you wish. Okay.

 ![image](https://github.com/user-attachments/assets/18f90ae7-ae64-4e0f-975c-8379a3cf4985)

So a classical variable is a group of bits. So, let's say you have 8 bits or 16 bits or 32 bits.  
Typically machines like your desktop is going to be 64 bits for most variables, which is a lot of possible values. So, for every bit you add, you double the number of values you can store.
And so, in a classical variable, in that 2^n variable, you can store a single one value at a time.  
I can have 64 bits. That doesn't change how many values I can store at once, that changes how big of a single value I can store.
So, instead of being limited between 0 and 232, well 0 to 232 minus 1, I can, if I have 64 bits, I can store all the way from 0 to 264 minus 1.
Alright. So, likewise, quantum variables have grouped up these qubits, because if you just have, if you can only store a 0 or 1 that's not very useful in computing.
And so, quantum computers also group groups of qubits to work cooperatively. And so, instead of storing a single value of 0 to 2n minus 1 it can actually store any number of those 2n possible values.
But here's the kicker, that we saw before with measurement and superposition, is that we can only measure one of those values!
And so what a quantum computer is doing is manipulating the probability of measuring each individual value.
And so, I could be storing the numbers 8, 12, and 24 and maybe I want it to be 50% probability of measuring the value 8 and 25% probability of 12 and 25% probability of 24.
So, that's what we're doing in quantum computing. So, this means if I set up uneven probabilities for measuring different values, I can use it to make my videos a little less certain.
Maybe I would choose the next slide based on a quantum measurement and then I would press return and I would have no idea what I'm supposed to say next because I don't know what slide is kind of going to come up.

![image](https://github.com/user-attachments/assets/3794d375-2e5b-4e73-8220-839b42b51bb9)

Alright. So, let's look at how to show these in bra-ket notation.  
So, what we've got is, we've got a ket, those funny symbols are called a ket, and so we have something in that ket.
Which you've been seeing as a zero or one, but it could be anything. 
And so I've got an apple and a banana here. So, I'm expressing the probability of finding an apple or a banana, let's imagine.
So, we have what's called a probability amplitude. I don't directly store the probability and the reason is because we want a notation that makes it so that we can do the mathematical calculations easily.
And while it is true that if I stored the probability straight that would make it for me, the human, reading it to say, “oh, I know what the probabilities are.”
But it turns out that then I would have to do extra steps in order to do the mathematics for the operations.
So, what we do is we store it in the numbers that make sense for the operations, and then we convert it when we want to know the probability.
But it's not about calculation. So, let's look at this.  
So, it turns out that if you square that a you'll get the probability of measuring an apple and if you square that b with the absolute value, you'll have the probability of measuring the banana.
And it turns out that because we're not using the third aspect of state, we're only using positive and negative signs, and we're using the probability of measuring, we don't need that absolute value sign because squaring it will make the negative positive anyway.
So, for the purposes right now for you, you can ignore the absolute value sign.
But if you if you do get introduced to the third element of state, which is imaginary numbers, then we do need that, we do need the absolute value sign.
Alright. So, here we have the probability amplitude and so this means that I can take the a and I square it to get the probability.
And whatever is in that ket is the probability of is what that probability pertains to.
Okay. So, don't get confused by the zeros and ones that are inside the ket, and the zeros and ones that are outside the ket, which is why we're doing this example with apples and bananas.
Okay. So this b, if you square the b you get the probability of measuring whatever is in the ket next to it, which in this case is bananas.
So, let's look at, oh and interestingly enough, not surprisingly, because we have only two choices here, right, we have to measure one or the other.
So there needs to be 100% probability of one or the other
And so, if you add up the probabilities, that's always 1 because 1 is 100%. And we're storing these as fractional probabilities between 0 and 1, so 1 indicates 100%.

![image](https://github.com/user-attachments/assets/711a6235-f85c-4bca-bc20-fa6c8bfa1ccb)

Alright. So, for quantum we know that we're measuring 0 or 1 so in the ket, we're always going to see a 0 or 1. And then we have the numbers in front of the ket.
Okay. So, like we just saw, the a, if you square the a that's the probability of measuring the 0 and if we square the b that's the probability of measuring the 1.
And just by convention, we always put the 0 on the left and we always put the 1 on the right. We wouldn't have to but we do because it's better to just be consistent because then everybody can read it more quickly.
If I have to find the 0 and find the 1 and figure out which one's first or second, then that's going to make it slower. So we just always put the 0 first and we always put the 1 second.
Alright. So, let's relate this to the balls. So now, we have, let's say our probability is just a 0; that means that we know we're going to measure a 0. That means the probability of measuring a 0 is 100% and the probability of measuring 1 is 0%. And the phase is positive.

![image](https://github.com/user-attachments/assets/fa7a64fc-9ff6-4ce2-8bb8-fbccbf5c3120)

So that would give us the state of a 1 in front of the 0 and a 0 in front of the 1. This is why I did it with apples and bananas first, you can see that because a lot of our states have a 1 or a 0 as the probability it is sometimes confusing to distinguish that from the 0 and 1 in the ket, which is what you would measure.
Now let's look at the black ball. So, that is 100% chance of measuring a 1 and a 0% chance of measuring the 0.
Go ahead and pause the video each time and see if you can predict what the bra-ket notation is going to be for each one of these. So, pause and then when you're ready go ahead and continue.
Okay, let's try it now. We have a 0 in front of the 0 because there's a 0% probability of the 0 and we have a 1 in front of the 1.
Alright. Now let's try superposition. So, I've got a 50-50 probability of 0 or 1. Okay. Alright. And then I also have a positive phase.  
So what does that mean, 50% probability? We know, over here I know that if I square the number in front of my ket then I get the probability.
But I'm being given the probability and I need to figure out what to put in front of the ket. So, what is the opposite operation to squaring?
It's the square root. So, a 50-50 probability is ½ and so the square root of ½ is 1/√2 because the square root of 1 is 1. So, we can just put the 1/√2 in front of each one.
Now let's look at if there's a negative sign. Okay. So, if there's a negative sign that means that my phase is negative and so we put that as a negative sign instead of a positive sign.

![image](https://github.com/user-attachments/assets/6ab5af7c-a3bb-4907-8744-37cb5100d621)

Alright, let's look at when we have more than just two states. Okay. So, remember this four state means that each one of those has equal probability. Which means that we have ¼ probability of measuring a 0 and ¾ probability of measuring a 1.
Alright. So, how would we write this in bra-ket notation?  
Okay. Well, we would have 1/√4. What's the √4? 2. So, we would have a ½ in front of the 0 and a √3/2 in front of the 1. But we've left it as square root for you so that you can see the calculations more easily.
Alright. So, then we would square it to get the probability, which is why we get ¼ and ¾.

![image](https://github.com/user-attachments/assets/767bbb4a-764d-4dbe-a4cb-4441855eba7b)

Okay. So, I do want to show you a few shortcuts that people use with bra-ket notation, which again is very analogous to algebra. You saw that we used some of the algebra principles when we were doing the visual representation for calculating the H gate. So let's look at this.
We have both conventions that some people believe improve readability and then we also simplify algebraic expressions. So, let's give a few examples.
So, in algebra, if I have 0 times something then I just drop that term, right?
And so, we have something analogous in quantum. So, if I have a term, in this case it's 100% probability of measuring a 0 and 0% chance of measuring the 1, well there's no point in even having the 1 there so we take that out.
And then we drop the 1 in front of the 0 because it's 100% probability. That's the only one. So, we've been using this the whole time.
So, if you just see a 0 inside of a ket, that means 100% probability of 0 and 0% probability of 1. Okay.
Alright. So, another convention is to factor out equivalent constants. And I will tell you that I don't do this when we're in bra-ket notation.
There are other times I do, we're about to see vector notation, but I don't use it with bra-ket notation. But other people do.
So, sometimes you'll see something that's 0 + 1 and you might think, “wait, that doesn't make sense! I was told that a^2 + b^2 must equal 1. And in this case what you're seeing is a and b are both 1, a^2 + b^2 would be 2.”
So, when there aren't any things preceding the kets, that means they're equal probability. And so, that in this case that would be 50-50 probability, which you know is 1/√2.
We're never going to use that in this class because I think that this is actually confusing, and so I will never use it. But I want you to know about it in case you ever see it, so it doesn't throw you off.

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_bra-ket_PQ.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_bra-ket_PQ.pdf)




# Vector Notation

Okay, now I'm going to introduce you to a second notation. It's called vector notation. 

![image](https://github.com/user-attachments/assets/1dea1749-13d2-4e9f-a79b-b6ec64f3ae20)

We did bra-ket notation already and this made it easy for us to extract the probability of measuring each possible state and knowing the phase.
Okay, so just a reminder that the probability of measuring zero in this case is |a|^2 and probability of measuring one is |b|^2. Okay. Now let's look at vector notation.

![image](https://github.com/user-attachments/assets/75804302-4912-4633-b702-730e996273ec)

Vector notation, you might think is no different, but it turns out that vector notation is really important for making the calculation of gate operations.
So we're going to store it as a vector. What is a vector? 
A vector is just a way of storing a list of numbers - of depicting the storage of a list of numbers.
So we can see - we have sort of a long bracket here. I make it as tall as I need to hold as many as I want.
Well, we will always be holding - for a single qubit we'll be holding two because there are two possible states with a single qubit.
So I just make the brackets up here tall enough to store these two values. 
And so I always put the probability amplitude for the zero on top and for the one on the bottom. 
So the the only confusing thing that I find with this is that the the reason the bra-ket was so nice was because I had the zero in the ket and the one in the ket and so I knew that a was the square root of the probability of measuring zero and b was the square root of the probability of measuring one.
But in this case, though, it could be positive or negative.
But with the vector notation we lose that visual reminder of where the position is for the amplitude corresponding with zero and where the position is with the amplitude measuring one.
So you're just going to have to remember that zero is always on top and one is always on the bottom and in fact when we get to having more it's just always in increasing order as you go down.
So zero is the smaller number - it comes on top - and so just think of it as smallest to largest from the top to the bottom.

![image](https://github.com/user-attachments/assets/2404c5be-74b2-41e2-b653-311d55fe8e4a)

All right. So if I had others - this is also why it's really important that when you do it in bra-ket notation you always put the zero on the left and you always put the one on the right.
So again, I've got the a at the top and the b on the bottom so if I were to do 1/root(2), I would put one 1/root(2) on top and one 1/root(2) on the bottom.
Now, these are equal probabilities, so it turned out that the order didn't matter, but normally it does.
Okay. All right, so then we have this example. This example is the one-fourth three-fourths, right?
The square root of 4 is actually 2. So I have the 1/2 on top and root(3)/2  is on the bottom.
So if I were to do something which I shouldn't be doing which is putting the 1 on the left and the 0 on the right then I would have to make sure, well, now it goes in vector notation in the opposite order.
We don't want to do that, but I just wanted to illustrate that it's not just that the one on the left is always going on the top.
It’s the one associated with the probability amplitude associated with zero and the probability amplitude for one.

![image](https://github.com/user-attachments/assets/b05adf11-4060-4031-8aee-501c237e9a25)

Okay. All right, so we also have algebra-like simplification for vector notations, and these ones we will do.
So remember this bra-ket notation. So if I have 1/root(2) and 1/root(2), I can factor out this 1/root(2), but I don't remove it.
I just take it out of the brackets. Okay, so this we will be seeing in this class. 
What I didn't like about that simplification in bra-ket notation was, though, that the 1/root(2) disappeared entirely, and I don't like that.
So in this case we just pull out the 1/root(2), which can make it a lot easier because the numbers get really small and drawing that root(2) sign gets really small.
And so it can be much more legible to have to pull out the 1/root(2) and then to have one and one inside.

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_vector_PQ.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_vector_PQ.pdf)


# Single Qubit Matrix Multiplication

In this section, we introduce how to apply gates to single qubits using mathematical operations. This requires using matrix multiplication, which we’ll teach you how to do!

All right, so now we're going to get into how to calculate quantum operations using mathematics. 
We've already seen the visual representation, and that's going to be adequate for the algorithms and examples we’re using in this course.
But, in order to do general quantum computation, you need to do the mathematical calculations. So we're going to introduce that now.  

![image](https://github.com/user-attachments/assets/23508865-31ea-43e1-8957-3e23245f47e2)

All right, and before I introduce that I want to relate what we're doing to fractions. 
Remember when you learn fractions - let's say we have this problem. You have a pie to share with three friends. You cut it in four equal pieces each with size one-fourth.
Your friend exclaims, “Just because there are four of us it doesn't mean we need to eat the whole pie! I only want half that much.” 
How much of the pie will you give your friend? 
Hopefully, you recognize this as a multiplication problem because of “one-half of one-fourth.” 
We know that when we say “of” that means multiplication. And so we'll do a half of one fourth and we calculate that to be one eighth. 
We can always also check to see if we see if we were right. And when we cut these in half we see - ah yes - when we cut those in half there are now eight equal sized pieces. And so it must be one eighth. 
Okay, so hopefully by this point in your life this makes sense. 
But I'm sure that when you were in fourth grade - I can't be positive about this - but this is not as intuitive as one might think.

 ![image](https://github.com/user-attachments/assets/0a5e6442-bce5-4602-995e-8d6c772fc60b)

Because we have these - 1/4, 1/2, and the 1/8 - it's arbitrary as to the fact that we put the numerator on top and the denominator on the bottom.
And furthermore: why is it that for multiplying we multiply both the numerator and denominator, but if we are adding we have to first make the denominators the same and then we add only the numerators? 
These seem - if we don't have an understanding of how this works as a whole, then it just doesn't make sense.
So when we're thinking about how someone came up with what are the rules behind fraction multiplication and what are the rules behind fraction addition.
What they did was they looked at a real problem, and they looked at what the real operation would do in real life separate from these numbers. 
And then they looked at the mathematical representation and they figured out what mathematics gets us the right answer: not just for this problem, but for every problem. 
And so it is often the case that, if you just look at the mathematics and what you're trying to do, it doesn't make sense on its own.
We just have to trust that someone has figured out that this always works and we could go through all of the mathematical proofs that show that. 
We're not going to in this class. We want to learn how to do these things, but certainly if you want to become someone who creates quantum algorithms you will also have to learn how to prove things.
Because then you'll be doing things that no one can check and if no one can check them then you need to prove they're correct on the mathematics. But we're not going to be doing that in this class.

![image](https://github.com/user-attachments/assets/9e66783d-7ba3-4d8e-8f54-03637fdae04d)

Okay so let's look at addition and multiplication. Right. Just to emphasize how natural it is hopefully to us now  but how it really doesn't make sense.
For example, when we're adding the same denominators we add the numerators but we make no change to the denominator.
When we're adding with different denominators we have to first multiply the two denominators together if there's no greatest common factor. 
And then we multiply the opposite: we do ay + bx. All of this just seems counterintuitive until you look at the full drawn out example and you understand why. 
Okay. And then for multiplication we just straight multiply the top two and multiply the bottom two. 
We will see that matrix - if we look at what we're learning today - it has the strongest correlation with addition with different denominators in terms of the sort of complexity of the actual mathematics we're doing.
Okay. So the whole point of this was just to point out that fraction multiplication is using the refraction addition even though multiplication of integers is actually harder than addition of integers.

![image](https://github.com/user-attachments/assets/0c63872d-da81-4733-bbb2-4f76fc0faf63)

All right. So what we want to learn is a mathematical calculation to calculate the not gain. Okay, and what do we have? 
We have bra-ket notation; we have vector notation. Okay, and we already learned that the whole point of vector notation was to be able to do operations. 
So it's going to be no surprise that we are going to use vector notation for this.
Okay. And so we remember that in the general case it's a/b, and then and then the not operation flips it to b/a.
Okay, so we want to figure out how this works, and we want to figure out how it works not only for a not gate but for any arbitrary gate. So for this we need to introduce a matrix. 

![image](https://github.com/user-attachments/assets/a0861a11-7077-4826-ab49-935b8c5f2afc)

A matrix is values laid out in a grid similar to a spreadsheet - a spreadsheet is a giant matrix. 
So let's say I have a grid of numbers and these numbers happen to represent: Each row is a student and each column is an assignment. 
And so, these numbers are not placed randomly. Their position in the row and column ties them to a specific student and assignment. And so this is how matrices work.
 And so we have the matrix symbol - notice that that's the same as the vector symbol. 
It's merely that the vectors are one dimensional. It's just a column, or you can write them in a row instead, but it's just a single line of numbers, whereas a matrix is a 2-dimensional grid. 
And the other thing about the matrix is that we take off the labels so we just see the numbers.
And if this were a spreadsheet, those labels would be just for humans, but for the computer it's just the numbers. 
All right, so let's see how this relates to quantum. 

![image](https://github.com/user-attachments/assets/7174020e-4447-490e-a65d-9933145756dc)

In quantum every gate is represented as a matrix. Why? Because the mathematics works out. 
Luckily, Einstein and others figured out the mathematics and we didn't have to. 

![image](https://github.com/user-attachments/assets/32aa8e3c-7ef4-4a82-b553-c1dab8564794)

All right, so let's look at how this works. To start out we need to learn an operation. 
This is called matrix multiplication, and now you can see why I related it to the fractions because we have the sum of products.
So we have a matrix and a vector. The width of the matrix needs to be identical to the height of the vector because what we do is:  
We go across each row of the matrix and the vector and we start with the first - the leftmost - item in the row and the topmost item in the vector and we multiply those. 
Then we go into the next one, b and y, and we multiply those, and then we sum those products. 
And then we move down to the next row in the matrix and we repeat on the vector. 
So we go down the vector every time, but we were using a different row each time. 
And the result vector - it sort of seems like it might be a matrix because I see four items there, but notice that the top one is a mathematical calculation which will result in a single term. 
So I do the two multiplications and then I add up the result and I get a single number. So my result will be a vector and not a matrix.
All right, so what are these? Well, the leftmost one is the quantum gate. 
The matrix is the quantum gate, and then we have the initial value of the qubit in vector notation: the state of the qubit. 
And then, when we calculate it, we will get the end state, the resulting qubit. And if we wanted we could put that back in  bra-ket notation if we find that easier to read. 

![image](https://github.com/user-attachments/assets/ae7526a6-d495-4359-a249-12c984dd04f5)

Let's try it with a not operation. So I start out with a one - a black ball - in my not. 
So my initial vector is zero percent probability of a zero and one hundred percent of a one, and so that's a zero on top and a one on the bottom.
And then I put in my not operator. I put it to the left, and so now I have these, and then I make my calculation. 
So I do the first row: 0 times 0 plus 1 times 1, and then I go down to the second row of my matrix and do that again with my same vector.
So 1 times 0 plus 0 times 1, and I get a 1 on top and a 0 on the bottom and that is exactly what I expected. I expected to get a 0. 
Likewise, we can take this initial vector with a 1 on top and a 0 on the bottom, take my same not operator and do the same operation, and I get the 0 on top and the 1 on the bottom. 
Feel free to pause this; you can go through it yourself if you need more time.
Then we get black as the result.

![image](https://github.com/user-attachments/assets/90f12877-8324-4ecf-abcf-5198804235dc)

All right, so now let's take something a little bit more complicated. 
Let's take the case where I have a single white ball and three black balls, which is a quarter probability of the white and three quarters probability of the black.
Which, when you take the square root of that is 1/2 and root(3)/2.
Okay. I invite you to pause now, write out the matrix and the vector, and go ahead and try to figure out the result on your own, and then you can check your work and if you've got anything wrong then you can see the video.
So, first we have to set it up correctly. We need to remember to put the not operator on the left and the initial vector on the right, and then we're ready to make our calculation. 
So we remember to do each row separately and then we can calculate our values and we get root(3)/2 on top and 1/2 on the bottom.

![image](https://github.com/user-attachments/assets/ce8103de-47eb-46e6-965c-bae996c9d201)

All right, let's try the H operator. So once again we get our initial vectors. Again, I invite you to pause and try to do this yourself  now that you've been introduced to the H operator. 
In fact, now if you look up on the internet the operator for a quantum gate, then you would be able to do any of the quantum operations.
All right, so then we multiply this out. 
And we have our expected results. And you see that that negative sign in the bottom right hand corner is what gives you  the negative sign when you're coming from a one from a black ball.

![image](https://github.com/user-attachments/assets/80c16616-00f7-4939-9de2-490fbb37f244)

We can do this again with the white ball, and what we'll notice is that the negative one gets multiplied with a zero, and that's why there's no negative sign when we start out with a zero ball.
And I want to emphasize how important it is for you to try these on your own before watching, before just letting the video skate through.
Because it's deceptively simple to watch mathematics go by on the screen and think that you could do it yourself but it's really important that you actually do it yourself so that you can check. “Can I do it myself?” 
“Am I going to remember to put the vector and the operator in the right side? Am I going to remember how to do all these calculations?” 
So make sure that you're doing at least some of these on your own just to try it.

![image](https://github.com/user-attachments/assets/c416e067-4ead-4233-9c5a-635a030fd354)

Okay, so what did we learn in this video? A matrix is a two dimensional grid of numbers in which position is important, it matters.
It's used in many, many things, but in quantum it's used for qubit operations, and those operators are stored as their own unique matrix.
So each operator has a matrix, and matrix multiplication is used to calculate the output of a quantum operation. 
And today you learned how matrix multiplication works!

[https://github.com/SteveJustin1963/QC/blob/main/audit_Single_Qubit_Matrix_Multiplication_practice_questions.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_Single_Qubit_Matrix_Multiplication_practice_questions.pdf)

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_Notation___Single_Qubit_HW.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_Notation___Single_Qubit_HW.pdf)




# Quantum Fun: Entanglement

One reason that quantum computers can be more powerful than classical computers is what happens when you use multiple qubits. In this section, we introduce entanglement, a new quantum property that we don’t totally understand and that does not have an intuitive example in everyday life. But like magnetism and gravity, we can use it before we understand it. We also introduce how to calculate multi-qubit operations using mathematics - which is actually no different from calculating single qubit operations! We will also use math to determine whether two qubits are entangled - if it's impossible to accurately express the combined two-qubit state as two individual qubits, then they are entangled.

How do we know what we know? The age-old question. 
Throughout human history, it's like this. A story in three parts: observation, use, explanation.

Our friend Carl the Caveman has just discovered fire. He observes that it is hot and keeps his cave cozy and warm.
He uses it to cook his dinner. And eventually science catches up to him to explain it.
A more interesting question, though, could be: How do we know what we know when the force at work is invisible?
When Sir Isaac Newton discovered gravity, it hit him on the head.  

He observed that when an apple falls from a tree it always falls down and that rivers always flow downstream. However, he didn't quite discover it.
Farmers already used the force and predictable directionality of the river to power a water mill.
The earliest water mills were in the 3rd century BCE, in Byzantia and China's Han dynasty.
Newton provided mathematical equations to model gravity's effects and that gravity wasn't just confined to Earth.

Even so, we don't know the explanation of it, why or how it works. But this doesn't stop us from using it.
This is what it's like when answering the question  of, What is quantum entanglement?
Scientists observe that when applied to two qubits, qubits are the basic unit of quantum information, quantum operations make their outcomes dependent. They entangle.  
Scientists use this characteristic to have multi-qubit numbers cooperate when in superposition.

And superposition is a state where the qubit can be in multiple states, just until it's measured.
Or transport a quantum state over a long distance, because the entangled qubits have this not yet understood connection with each other that continues even at a distance.
Scientists can model and predict the math associated with this phenomenon but don't know why it happens.

However, the potential for quantum entanglement and teleportation of information is just being tapped into.
Luckily, we don't need to understand why or how it works in order to use entanglement.  
All we need is to be able to predict its effects accurately.

# Entanglement

Now we're ready for the last major quantum computing concept: quantum entanglement.

![image](https://github.com/user-attachments/assets/02673efd-fe35-4e6e-b7c6-7f6f314828a9)

Let's think about this from a historical perspective. 
Let's consider fire, and we're going to consider a few other physical phenomena in our world that have transformed our lives from figuring out how to harness them. 
And so when we think about fire we start with observations. It's hot when I touch it and it's hot when I'm near it. 
So we know that fire is associated with heat, and so it has some uses. 
Warmth is the obvious one, but then the less obvious ones are that water goes away with heat, that water evaporates.
And so that was something to figure out, even if you don't understand why the wet clothing becomes dry even if it's placed a good distance from the fire.
And then cooking food: once again, not obvious, but when someone figured out figured that you could do that you could do it. 
Now, we can have all of those uses while not understanding at all how fire does these things. 
The point is that you can observe a phenomenon, figure out ways to utilize that phenomenon without understanding it. Of course, now we do understand fire. 
Warmth - radiation - is carried by invisible particles that carry the heat to you. Also, conduction can carry the heat through  visible particles, especially metal. 
And then convection: as molecules heat up, they expand, causing them to travel. 
So we have these different ways that the heat is transmitted, but we didn't need to understand that to figure out some uses.
However, understanding that provides us even more uses because now we have detailed information about how to use it.

![image](https://github.com/user-attachments/assets/dd77314a-ce9e-453d-ae54-3467f188e112)

Okay. Magnetism is also similar. So we know that some metal objects rotate and turn north.
We know that some metal objects are attracted to other metal objects, or the magnets attract metal objects. 
And we know that now, because they rotate and turn north, we can use a compass. And now we understand the Earth has a magnetic field. 
And magnets and magnetism are hugely useful: they're used in radios; they're used in any speaker device.
And so these more sophisticated uses are really based on understanding them to a very high degree, but we can still use them with a very rudimentary understanding. 

![image](https://github.com/user-attachments/assets/c7819a4b-f3e2-4d49-8c0a-d4f54e717e5b)

Finally, gravity. We can stick to the ground, things stick to the ground, things fall to the ground, and rivers flow downwards. 
So gravity, from this perspective, was understood for hundreds of years, right. 
We can use a water mill; those are thousands of years old. 
We can dam rivers - even beavers understand that - and Native Americans used to drive buffaloes off of cliffs and then use them for meat. They use lots of parts of the buffalo. 
It wasn't until Newton that we understood about celestial objects that, well, if this happens when an apple is this close to the ground, what does that mean about the planets that are in the sky? 
And then being able to figure out the equations for gravity is what has allowed us to put up long distance space probes that use gravity to slingshot around a planet and gain momentum and go in a different direction.
And so, as we learn more about a phenomenon, we certainly can use it much better. But even if we don't understand it, we're able to use it, and so that's really where we are with entanglement. 

![image](https://github.com/user-attachments/assets/49d0d0f6-2d82-47f2-87b9-c2156cfba682)

Entanglement is observed. 
So there exist quantum operations that, when applied to two qubits, make their outcomes dependent. Okay, and we'll see the uses of it today, but we don't know why.
We can model - we figured out the mathematics for it, and so we can predict it and we can use it, but we still don't understand why. 
Just like we don't actually understand why two planets are attracted to each other. 
Why is that? Why are two physically remote masses attracted to each other? 
I don't know - why is there a force between them? And so entanglement is similar, except that we don't see it every day and so we haven't gained that intuition that we gained about gravity. 
And so in quantum we want to exploit this phenomenon.

![image](https://github.com/user-attachments/assets/d55f9df7-5644-40c6-926b-b432bfd260aa)

So let's look at what entanglement looks like in quantum. 
So we know that when we have an H gate we put in black marbles we get this state on the outside which indicates a 50/50 probability of being white or black and the phase is negative. 
And so what does that mean? That means that each  individual qubit has a 50 percent probability of being measured white or black, and that over time each pair of qubits has a 25 percent probability of each resulting combination: two whites, white black, black white, black black.

![image](https://github.com/user-attachments/assets/8859a50f-fde6-440d-a42d-7e15b0978fc3)

All right. So, entanglement in quantum. What's interesting about entanglement is that we can have that same 50/50  probability of black and white, but we can make it so that there's some connection between the two. 
And so it's not an independent probability. So we're going to say, well, in this case: 50/50 probability of being measured white or black, but every pair of qubits has a 50 percent probability of only two result combinations: white white, black black. 
So we could compel these two qubits. Even though we don't know the outcome of one qubit, once that outcome is known  we know what the other qubit holds.

![image](https://github.com/user-attachments/assets/d772ed16-798f-4bf6-873a-f082f46a4e7c)

We can also entangle it opposite. So just because I showed you an example in which entanglement meant they had the same value, black versus white, we could also entanglement such that they have opposite values.
So now we have it such that when we measure it whatever is measured in the first one we'll have the opposite in the second one. 
And we still have a 50 percent probability of measuring white or black, and we have a 50 percent probability of two result combinations; this is just a different two than before.
But it's still the case that the first measurement determines the result of the second measurement. 

![image](https://github.com/user-attachments/assets/61ef1668-7dda-4e00-a29c-113d3ca935da)

So these are just two entanglement examples. If you have more qubits, you have more examples. And so there are many ways of entangling.

![image](https://github.com/user-attachments/assets/93fe903a-49ea-4123-9a3a-f4ddfddaa804)

So why is entanglement important? Well, it is one of the biggest keys to performance in quantum computing. It's something that classical computing doesn't do.
But let's just take a small example of how you actually couldn't do any quantum computing without it having to do with superposition. 
So imagine a variable that's storing a four digit number. 
And so we're going to use four qubits and they need to work cooperatively to store this four bit number, which would be fine if I want to just store 0100. 
But I want to store a superposition of particular combinations. 
Okay, so each qubit is going to hold one digit of my number, right? 

![image](https://github.com/user-attachments/assets/6917e2eb-1713-4e67-8580-022392960da4)

So what I'm going to say is, I want this variable to hold a superposition of four numbers and they have a specific pattern here.
The pattern is that each of these numbers has a single digit one and all the rest are zero. So we have 1000, 0100, 0010, and 0001. 
Okay, and all other possible combinations have a zero percent probability. 
So I have a 25 percent probability of each of these four, and a zero percent probability of all the rest.
Okay, so let's look at it from the perspective of independent qubits, right?
So if you look at each qubit independently, we can see that there's a 25 percent probability of measuring a one and a 75 percent probability of measuring a zero.
So let's revisit our weather example and remember how to go from independent probabilities to multi-qubit: the independent single qubit probabilities to multi-qubit ones.

![image](https://github.com/user-attachments/assets/4d7dbd41-4ce2-433a-9255-0c0c19fed552)

And so we remember that, if I know the probability of something that's independent, then the probability of the combination of multiple [choices] is the product of the probabilities of the independent choices. 
Okay, so if I were to look at this example, for each digit the probability of a 0 is 75 percent and the probability of 1 is 25 percent.

![image](https://github.com/user-attachments/assets/b3173745-2f5f-4cf3-925a-1bc07aed6606)

All right, so my probability of measuring four zeros is 0.75 to the fourth, right? 0.75 multiplied four times, which is about a third - .32 which is approximately a third. But what I want is for it to be zero.  
0000 should have a zero percent probability. Only these four should have a probability. 
So entanglement is present when the probability of outcomes does not follow the independent probability calculations, which means that I can't think of this as four independent qubits. 
They are working cooperatively, and if I measure a one in any of those four qubits then all of the rest have to be zeros, right? That's the only way this works out. 
And so, while on the first measurement my probability of measuring a 1 is 25 percent, once I've done that measurement, that changes the probabilities of the other ones. 
Because if I measure a one now, there's a hundred percent probability of zeros in the rest of them. 
If I measure a zero, then now I'm left with three bits, one of which is a one. 
So now my probability has just changed such that they have a 33 percent chance of measuring a one and a 67 percent chance of measuring a zero. 
So, normally, if I have independent probabilities measuring one should have no effect on the probabilities of the others, but clearly this does.

![image](https://github.com/user-attachments/assets/f5861b23-9d82-4ee9-a8bb-6e762d03ec9e)

All right, so that's just an introduction to entanglement. 
And so, just in summary, entanglement allows the outcome of one qubit to depend on the outcome of a different qubit, and entanglement is really key to quantum computing algorithms. 
Entanglement is required even to do something as basic as the superposition of a multi-digit variable, which clearly we're going to want to do. We don't want to just do superpositions of single qubits. Single qubits are not useful on their own. 
We want to do superpositions of multiple qubits working together to store a large number. 
And so now we've actually learned in this course, from an intuitive perspective, all of the most important things for quantum computing. Entanglement and superposition are the two things that provide the power of quantum computing.
Quantum operations form those entanglement relationships between qubits, and operations adjust the probabilities of the superposition so that when we measure we have high probability of measuring the answer we want. 
However, the limitations due to measurement are what curtail this power. 
And so all of quantum computing is trying to figure out: how can I take advantage of entanglement and superposition in the face of these limitations based on measurement? 
And those two limitations based on measurement are: That any measurement provides only limited information, which would be fine on its own but it collapses the superposition.
I've changed the state, and so now not only would I not get all of my information, once I measure it at all then I lose a big piece of that qubit. 
And so we have to be very careful about measurement, which means we can't use measurement very often, and measurement is really important in computing.

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_Entanglement_Intro_practice_questions.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_Entanglement_Intro_practice_questions.pdf)




# Multi-qubit Operations with Math

All right. Now we're ready to see how to calculate multiple qubit calculations.  

![image](https://github.com/user-attachments/assets/a160148f-74f0-475e-ab91-a0adf3af9056)

We already did this in the visual representation but now we need to learn how to do it with the mathematics, because the visual representation is limited in how many states it can express.
So, let's look at these examples and look at the process.
So, the process is going to be, in the first step we need to express the input as a two qubit combination instead of a single. So, we'll see how to do that.
And then we want to calculate the results of the qubit operation, which is actually no more difficult in the matrix multiplication than it was for a one qubit operation. It's the same process just a larger matrix and vector.  

![image](https://github.com/user-attachments/assets/be23d1b0-af30-4316-a1cc-04ef05e578b2)

All right, so let's, the first thing we need to do is figure out how to express two independent qubits as a two qubit state, and this is very similar to the examples we saw before with probability.
So, with probability you may recall we had a scenario, we had 75% chance of forgetting our raincoat and 25% chance of remembering it, and then a 50-50 chance of rain or sun.
So, in order to calculate the probabilities of each pair of combinations we multiplied the probabilities of each individual one.
This is the same process for quantum computing. So, if I have, so let's look at it for the weather.

![image](https://github.com/user-attachments/assets/8fc2e2c6-f9d7-40eb-8d36-c600d78aeffb)

So, we, for quantum we would express this as, not the actual probability, but the square root of the probability and so we would have root 3 over 2 and 1/2 for the probability amplitude of forgetting or remembering my raincoat.  
And then I have 1 over square root 2 probability amplitude of sun or rain.
Okay. So, this is like algebra: first outside inside last. And so, we take these and we take the first two, which are forgetting my raincoat and sunny, and then the outside are forgetting my raincoat and raining.
And then inside is remembering my raincoat and it's sunny.  
The last one is remembering my raincoat and it's raining. And so, we can calculate these probabilities by taking the product.
And it also works with the probability amplitude, so we can take the probability, the product, by multiplying the probability amplitudes. And that will also be correct.
So, we multiply these and this is what's going to get our resulting probability amplitude for the combination of the two choices.  
And in QIS this is called the tensor product, but you can think of it as going back to your algebra and just multiplying first outside inside last.  

![image](https://github.com/user-attachments/assets/86003969-d687-42d9-81b3-8ed349e0e62f)

Okay. So, let's look at it for qubits. So, I have two independent qubits that are not entangled, so those would be a and b and then c and d. And then in qubit notation, I just multiply.
I multiply a and c for the probability amplitude of 0 0, a and d for the probability amplitude of 0 and 1, b and c for the probability amplitude of 1 and 0, and b and d for the probability amplitude of 1 and 1.
And remember that order matters here. And so we take the qubit on the left and that one's going to be first in each of the pairs, and then we have our second qubit that's on the right.
So, this is the tensor product. Okay. So, let's take an example. Let's imagine we're doing this SWAP operation, which we already know how to do with visual representation, so it's nice to have it there to check our work.

![image](https://github.com/user-attachments/assets/65c0aa7d-eadc-4af6-b5b4-0133aa04196e)

So, the first thing we need to do is put it into our qubit notation. So, we have these two and in one-qubit notation the black ball has a 100% chance of being a 1 and a 0% percent percent chance of being a 0, and the the white ball has a 100% chance of being a 0 and a 0% chance of being a 1.
So, we can see the qubit there for the one-qubit notation. And then we do our multiplication and we end up with only a 1 in a single place, all the other ones are multiplying by 0.
And this is not surprising, actually, we have a 100% chance of measuring a 1 0 because the first one is always a 1 and the second one is always a 0.
So, our calculation, we can do a little sanity check and check it with what's going into the left hand of our SWAP gate.
All right, so, we apply the SWAP gate by doing a matrix, but first we need to put this in vector notation. So, as we recall from vector notation, we look at the number in front of each of these terms and this is when order really, really matters.
So, I have to have ordered these in increasing order 0 0, 0 1, 1 0, 1 1. And then I rotate that and put them vertically in the vector, and now I'm all ready to do my calculation.  
So, now that we've put it in two-bit vector notation, now I can go and actually calculate it.  

![image](https://github.com/user-attachments/assets/ab93187f-5e3c-41fb-a066-5f027f5b38fe)

Okay. So, let's do another example to practice putting something into two-qubit notation.
So, you have your first qubit and your second qubit.  And I urge you to pause the video at this point and try to do this on your own and then restart the video and we'll do it together.  
Okay, so we take these and we do our multiplication, first outside inside last.  
And so, we have 1/2 times 0, 1/2 times 1, root 3 over 2 times zero, and root 3 over 2 times 1. And so, we end up with two of the terms being 0 and so we end up with what you see there.
And this makes sense because you can see that our second qubit can't be a 0. So, that means that anything with a second qubit of 0, right most qubit being 0, in this case would be 0.  
All right. So now, we're ready to put it in vector notation.
So, we have these. So, we put them in the correct order, we rotate, and we put it in the vector. Now we're ready to do calculations.

![image](https://github.com/user-attachments/assets/a211e91c-823e-42e0-8782-8d5ccf3e372f)

Okay. So, let's try the two-bit calculation. So, we've already figured out what the initial vector is for this example. We did it in a previous slide.
And now we take the matrix of the SWAP operation, and you'll notice that because these are two bit inputs we have four choices, so our matrix is a four by four matrix and our vector is four long. But the process is just the same.
So, our result vector comes from doing the row and the red row and the green arrow sum of products, and then the orange, and then the blue, and then the purple.
So, it is exactly the same process. You always take the row and the corresponding row with the initial vector, and we do sum of products.
We take each pair, we multiply it. And so you'll see here, because there are so few ones and almost everything is zero, then almost all of the results are zero.
And in fact, the only one in this case that's non-zero is the row that corresponds with the same pattern as the vector.
So, you can see that that orange row and the green vector are both 0 0 1 0 and that's how we got a 1 out of it.
But all of the other ones have a 0 in one or both positions, resulting in a 0 for the sum of products.
Okay. So, we've got 0 1 0 0 and if we write this out in two-bit bra-ket notation then you can see we have a 0 on 0 0, a 1 on 0 1, 0 on 1 0, and 0 on 1 1.
Which gets us only a single term because remember in bra-ket notation we are allowed to drop terms with a zero in front of them. But we're never allowed to in vector notation, so we're left with a single term which is a 0 1.
And if we look back up at our vector notation, we'll see that that corresponds perfectly. The SWAP, in fact, starts with a 1 0 and ends up with the 0 1.

![image](https://github.com/user-attachments/assets/e6859baf-866e-4193-815e-1c85228954e1)

All right. So, here's another example we already figured out the input vector and so we're going to do the calculation.  
I encourage you to pause the video and try it yourself and then I'll go through it.
Okay, so you're ready to try it, we know we have the initial vector and then we have the SWAP operator, and we continue just as we did last time.  
So, our result vector is calculated by going across with the red and down with the green, then across with the orange and down with the green, across with the blue, and across with the purple.
Now, because this is a problem with all zeros and only one 1 per row and column, we can actually see again that our pattern is 0 1 0 0 in the initial vector, and that pattern we see in the blue row 0 1 0 0.
And that's why that one resulted in a 1 and all the others resulted in a 0.
Now, that intuitive way of looking at it only ever works if you have all zeros in all rows and columns, except for a single position that has a 1 in each one.  
All right. So, then we can put these back out in bra-ket notation, and that results in a 1 0. And so, if we put that back into our visual representation, we see that it matches. So, it matches what we got the visual representation.

![image](https://github.com/user-attachments/assets/eed901b1-7843-4889-8bad-c6bc9546d4fa)

Okay. Let me do one last example. And this is important because for the C-NOT gate these are not symmetric. With a SWAP, it doesn't matter which is the bottom or the top, the values SWAP positions.  
But for a C-NOT gate, one's a control and one's a target. And so, this affects the matrix multiplication operation that occurs. 
So, if I have this scenario where we know from our visual representation we've got our top qubit is the control qubit and the bottom qubit is the target, for this case. You can draw it the other way but we've tried to be consistent about control being the top and  target being the bottom.
The control is black so that swaps the value of the bottom.
Now, what's important here is that regardless of whether the control is depicted on the top or the bottom, control always has to be qubit 1.  
So, here, the control bit is black and so that's 100% probability of measuring 1. And the target is white, which is 100% probability of measuring a 0. So, we put this into two-qubit representation.
And we can see here that the control qubit is that left most qubit of each of these pairs. So, that's what's really, really important, is that the control bit has to end up on the left when you put them into two-qubit notation.

![image](https://github.com/user-attachments/assets/5139cff5-08b2-49c1-b0e4-5ccf4b7ae5ed)

All right. So, then everything's the same as you've seen before. We have our vector and then we put our initial vector down, we use our C-NOT operator, and we perform our matrix multiplication.
Once again, we go across the top row to get the top item. We go across the second row to get the second item, third row to get the third item, and fourth row to get the fourth item.
And it matches our answer from our visual representation.

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_multiqubits_calculations_PQ.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_multiqubits_calculations_PQ.pdf)



# Multi-qubit Operations with Superposition

Okay. Now that we've seen how to do multiple qubit calculations, both visual and mathematical notation, now we need to see how we use multiple qubits with superposition for the operations and the calculations.

![image](https://github.com/user-attachments/assets/dd5a5f97-ce89-466a-979b-68672191ba5c)

All right. So, let's look at the visual representation. So, I have this qubit operation SWAP and I have a superposition input.  
And we saw how to do superposition with single bits, we just split up that gate and put each individual bit and carry over the result in the same position on the left and the right.
We just have an extra step here, we need to put this into two-qubit notation, visual representation. So, what does that mean?  
That means that we need to express that, in this case, I have one bit that's 50-50 probability of black or white and a second bit that's always white.
That means that in two-qubit notation, I have two choices: one that's black-white and another one that's white-white.
And then, I get that from taking the first choice of the superposition and adding it to the second bit that's always white.
And then, I have that line and then I have my other choice is that second choice from the first one. And again, my second ball always being white, so we can see here that the line indicates a separate choice.
And so, now we have two balls in each choice, instead of just one. So, I have black-white and white-white. And again, order matters within these combinations.  
It doesn't matter if I put white-white on top and black-white on the bottom, but it matters that black is on the top of white in that pair. 
Okay. And so, once we've got that correct, that's the only extra step from what we did before. What we do is, we split the SWAP into two tiny SWAPs, and each of these pairs go through their own SWAP gate.

![image](https://github.com/user-attachments/assets/fef59ab5-7132-400a-a41f-c52ff87c6023)

So, I have my top pair black-white and those get swapped to white-black. And then I have my bottom pair white-white, and those get swapped, too. Well, not much swapping that happens with white-white, but that ends up with white-white.
And so, now we can see that our result is two choices, again, but our first choice is white-black instead of black-white and our second choice is still white-white.

![image](https://github.com/user-attachments/assets/d680d0a6-b341-488f-b885-a2085889be44)

Okay. Now let's look at a second one. And this is our C-NOT, so this is when order really, really matters.
But we're starting with the same inputs, so we go ahead and make ours where we take the first one and we split it into the two choices, and then we put the second one and that's the second choice both times.
Now we split up our C-NOT gate into two little C-NOT gates, and we put the first one through. And because the top ball is black, that means we'll swap the color of the second ball.

![image](https://github.com/user-attachments/assets/0c44c2e4-6409-4a02-bbf3-8a0791321c6e)

And then we have our second C-NOT gate, and those are both white. Because the top one is white, the second one does not swap. And so we have a white.
So, now we can see that our result is that either both balls are going to be black or both balls are going to be white.  
Now, let's look at how we do these with calculations. So, we can see that we start out, these are the same two examples just done with the mathematics, as well.  

![image](https://github.com/user-attachments/assets/d1ff50dc-f5c6-47ba-a228-4f9c06322717)

So, we have our first two that were 1 over root 2 0 plus 1 over root 2 1. Right. That's the notation for a black and a white with the line in between that has a 50-50 chance of being black and white.  
And then we have our white ball which is 100% chance of being a 0.  
And so, now we put this into vector, well bra-ket notation first and then in vector notation. And there are really two ways you can do this.
We can do this by doing our FOIL, our tensor product, and multiplying the terms in front of those two zeros, and then multiplying the terms in front of the top zero and the bottom one, and then the top one and the bottom zero, and then the both ones.
The other way to do this is to do the visual representation like we did and then say, “Oh, I see in visual representation that I have a 50-50 probability of being a 1 0 or a 0 0." And we express that.
Now of course, visual representation does not represent all possible bra-ket notation states, qubit states, and so it also does not express all possible two-bit qubit states.
But if you have one of these states, that can be expressed in visual representation, you should feel free to go that direction, as well.
So, now that I have this I can put down my initial vector.
And this is when it's really useful to pull out the 1 over square root 2, because I don't need it inside while I'm doing my calculations, and my calculations will be a lot simpler if I use ones and zeros instead.
So, having this one over square root of 2 outside that means that that's multiplied by all of those terms, and so that's when one over root 2 times one is 1 over root 2.
So, I can do the 1 over root 2 calculation at the very end if I want to.
All right. So, I have my swap operator and now I can do my calculation. We've already seen how to do calculations and it's no different when I have a superposition from when I don't. 
Except that now I have a vector with two ones in it, so I can't do my little shortcut that I did before, looking for the same pattern. So, here I can see that when I do the red and the green, I get a 1 because the first term was the same.  
And then I can see that in the orange row, the third terms are both 1, and so I have a 1 there, as well.
But in the blue and the purple rows, the ones are in positions that have zeros in the initial vector. And so, those are zeros. So, we have our 1 1 0 0.
And I have my one over root 2 before the vector to indicate that each of those terms is multiplied by one over root 2.
So now, I can switch this back to bra-ket notation. And now, I multiply out that 1 over root 2 and so I can see that I have 1 over root 2 for 0 0 and 0 1.
And I can do a little sanity check and I can see, oh yeah, my answer did have a 50% chance of being a 0 0 and a 50% chance of being a 0 1, so my calculation matches my visual representation.  
Let's try this again with the C-NOT gate. So, once again I'm starting with the same state, and so the state of my initial vector is going to be the same.

![image](https://github.com/user-attachments/assets/f4094fb4-e805-480d-b351-fcc91d130192)

So, all of those calculations are the same, the only difference in this problem is my C-NOT operator.
So, my C-NOT operator has a different vector or a different matrix, and so my answer is going to be different. So, let's look.
So, we do, we again, the 1 is there for both the red row and the green vector. And now we notice that it's the last row that has a 1 in the third position, like the initial vector.
So, we have a 1 on the first and the last position. So,  if we put this back into bra-ket notation that's easier for humans to read, we can see that our 1 over root 2 is in front of the 0 0 and the 1 1.  
And we go back to our solution and we see that, oh yes, those do match.

![image](https://github.com/user-attachments/assets/3bd7003e-22a2-4e73-a128-ce8ac1e91938)

All right. So, we've seen how to perform multiple qubit operations with the inputs in superposition.  
So, the first step is always to put the qubit state into multi-qubit notation, whether you're doing visual representation or the mathematical notation. And then, we calculate the result.
So, for visual representations, we pass through each pair through its own gate and then put the results on the right hand side, right where they come out.  
In matrix notation, actually, once you've got your multi-qubit notation in vector, then it's exactly the same as it was before.
You do a matrix multiplication of the gate operation matrix and the qubit state vector. And then when you have that result vector, if you want, you can put it back in bra-ket notation, if that helps you understand the result better.

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_multiqubits_superposition_PQ.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_multiqubits_superposition_PQ.pdf)



# Entanglement Circuit with Math

All right. Now we're ready for the entanglement circuit. We're going to do it two ways: visual representation and mathematically. 

![image](https://github.com/user-attachments/assets/06a6ca57-b9de-4340-9e88-acb6bcc17b7b)

So, our goal is to entangle two qubits, and recall that there are many different ways you can entangle but today we're going to do the same entanglement circuit.
So, the same entangle circuit takes all white balls and produces all balls that have a 50-50 chance of being measured black or white.  
But they do have a relationship, and that relationship is that if you take pairs of those, those pairs will always have the same measurement. 
And this is because the first measurement determines the value and the other pair now has been changed to match it. And that's what entanglement does.
So, remember that measurement is the action that determines whether something is black or white.
All right. So, let's see how this works. The entanglement circuit is very simple, it's merely an H block that puts the control bit in superposition before moving on to the target.  

![image](https://github.com/user-attachments/assets/41ecda91-bca7-400b-a89e-5b0df7ce1f5a)

So, we have a white target but we have our H gate that receives the white and spits out a black or white. Okay. And so we need to figure out what happens when the control is not simply a zero or a one pure state.
Well, let's calculate it. We're going to calculate it, like I said, two ways: one visual and one mathematically. And I would like to invite you to actually pause the video now and try it. You can try it with the visual representation and then you can try it mathematically.

![image](https://github.com/user-attachments/assets/fcdd44eb-229d-4637-9925-4bf7917073ad)

All right. So, let's look at it with the visual representation. We know that when we go through the H gate, we get black-white superposition. Now we need to put this into two-bit representation.  
So, we take the black and the white and that becomes the first ball of each pair. It's very important, remember, in a C-NOT that the control be the first in each pair.
And then our target ball is not in superposition, so that's going to be a white ball as the second of each pair.
So, we have two choices and each is a pair of qubits. Our next step is to take this C-NOT and replicate it and pretend we have two different C-NOTs  occurring on each of these two pairs of bits.
So, in the first C-NOT we can see that the control is black, which means that I'm going to toggle the state of my target. So, I have black-black. 
In my second C-NOT, my control is white, which means I'll make no change, which means we get the white-white.
So, now we can see that we have a 50-50 probability of getting each of these two pairs of results. One is both measuring black and one is both measuring white.
And the way we could figure out that this is entangled is to find that there are no individual states of bits that, if you do the tensor product to multiply it out, to figure out what it looks like in multi-bit state, it could never look like this. So, that's how we know we have entanglement.

![image](https://github.com/user-attachments/assets/877239e0-c157-40fb-b585-c598efae26ae)

All right. Let's try this again with mathematics. So, we know that when a white ball goes into superposition it becomes equal probability of black or white, with a positive phase.
So, 1 over root 2 |0> plus 1 over root 2 |1>. Okay. Or the vector above.  
Okay. So, then we put this in superposition state and so that is equal probabilities of |0 0> or |1 0> because again we always put the control bit first with no probability of getting a |0 1> or a |1 1>. 
So, now we calculate this using matrix multiply.

![image](https://github.com/user-attachments/assets/4ae07aa9-b72d-42dc-93e6-4f53b640aa9a)

Okay. So, we bring our vector down and we move that 1 over root 2 to the left because it's a multiplicative factor and so we'll multiply it out after we do our calculation.
So, we have our C-NOT gate and now our multiplication is simple, because it's just ones and zeros.
So, we see that instead of having 1 0 1 0 we end up with 1 0 0 1. Because if you look at the third row and fourth row, when you do the sum of products with our vector column that's what we get.  
And then if we put this back out into our multi-bit bra-ket notation we can see that that means that the 1 over root 2 is on the term |0 0> and the term |1 1>, and so that corresponds to a 50-50 probability of those outcomes.  
Which is two white balls or two black balls. And it doesn't matter that in my previous calculation the black balls ended up on top and the white balls on the bottom because, when we do the horizontal lines, it doesn't matter the order in which we do the different choices.  
What matters is the order within the pair, not between the pairs.

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_entanglement_circuit_PQ.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_entanglement_circuit_PQ.pdf)

[https://courses.edx.org/asset-v1:UChicagoX+QUAN11000+3T2024+type@asset+block/audit_multiqubit_Ops_HW.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_multiqubit_Ops_HW.pdf)


# Phase Fun

In this section, we introduce two algorithms that illustrate two quantum properties to do useful work. Phase has interesting properties that allow the phase to transfer between qubits in ways harnessed by quantum algorithms. Interference, which can be seen in patterns existing in the superposition of multiple qubits and which can cause probability amplitudes to cancel out with operations, is another quantum trait that is harnessed by quantum algorithms.


Now that we've seen how entanglement works, we want to build up our skills so that we can do some algorithms.
So, we're going to start out exploring a little bit more about phase and I'm going to call this Fun with Phase.

![image](https://github.com/user-attachments/assets/31d0b141-ffad-4c79-bebb-cb7305c92c6a)

All right. Let's look at a new gate. It's called the Z gate and I think of this as the phase flip gate.
So, if we have a zero ball, a white ball, it does nothing. But if we have a black ball, it changes it from positive phase to negative phase. Likewise, it also changes it from negative phase to positive phase.  
What we want to see is, like the controlled NOT, what happens if we have a control on this?

![image](https://github.com/user-attachments/assets/1ebdb987-ab0c-4d42-9cf3-f4b3d4d48f70)

![image](https://github.com/user-attachments/assets/35341d30-b545-4a47-9420-df8f4cb2078f)

So there is, we remember the controlled NOT that, as long as there is a white ball as the control nothing changes. But if there is a black ball as control, then it flips the result.  
Okay. Let's look at what a controlled-Z looks like. And we'll start out by doing it with what our intuition would tell us.
How should a controlled-Z work, if it works in a similar way as a C-NOT?
And so, what we would think is that it would only change the phase if the control ball is black. And that actually makes sense, because look, if the control is white, which is the left column, then the target doesn't change.  

![image](https://github.com/user-attachments/assets/4b68564e-e654-4848-8184-f6a2cf55c007)

If the control ball is black, then we apply a Z gate. But as we know, a Z gate applied on a white doesn't make any difference.
So, what we see is, the only time a change happens is when I have a black ball and that changes from black to negative black or from negative black to black.
All right. Now, let's look at what the math tells us about what's going on. So, I have here the matrix for the controlled Z. And you can see, whenever you see 1 0 0 1 in a square, that means to not do anything to those.

![image](https://github.com/user-attachments/assets/6d2a5425-f777-407b-9b75-641f72e44744)

So, with the ones down the middle, you see the first three choices |0 0>, |0 1>, |1 0> have no change. And the last one is going to be negative.
So, let's look, let's calculate this out and see. So, in the  first case, we start with a |0 1>, which is a 1 in the second position. And if we multiply it out, then we'll see that it had no change.
Likewise, when we start with a |0 0>, that's a 1 in the  topmost position, and that the result is 1 0 0 0, which is also no change. Then we have our third choice, which is a |1 0> . 0 0 1 0 on the vector.  
If we multiply this out, we'll get exactly the same as we started with. But then we come to our fourth choice and what we notice is, yes, we have that negative sign as we anticipated.
But notice that when we write this in bra-ket notation, the negative sign isn't in front of a single qubit. It's in front of the two-qubit pair.
And it turns out that either qubit could hold that negative one, or that negative phase. So, in this case, we have a phase that's being applied to a two-qubit pair, as opposed to a single qubit.
This is going to be very important later, so you want to keep remembering this about phase: when we calculate multi-qubit operations, phase is associated with a pair.
And then we use our algebra, or the opposite of the tensor product, to pull out what are the possible qubit assignments that could multiply together to get this multi-qubit result.

![image](https://github.com/user-attachments/assets/1b34b7b0-453e-4ba1-a0e0-3b4398fa8ace)

So, what we really want to understand from this is that multi-bit operations aren't solved neatly with visual representation. There are limits to the visual representation or there are some rules about phase that are not as clear when we use the visual representation.
So, phase is allowed to do more things than we think.  It's sort of, it's allowed to wander. So, phase is associated with two-bit pairs, not just the single bit of a pair.
And any mathematically correct separation to individual bits is acceptable.
And we also learned that control gates, we already saw that C-NOT led to interesting quantum behaviors. And now we're seeing that the C-Z gate also leads to interesting behaviors that are going to be  more important later, this type of behavior.

[https://github.com/SteveJustin1963/QC/blob/main/audit_Phase_PQ.pdf](https://github.com/SteveJustin1963/QC/blob/main/audit_Phase_PQ.pdf)

# Phase Kickback


All right. Now we're going to go over phase kickback. This isn't an algorithm but this is an interesting effect that you get by constructing a particular circuit, a little bit like entanglement, that we're going to use as a building block in our next algorithm.  

![image](https://github.com/user-attachments/assets/75ed5445-90b3-4700-8e34-e93e9e6dacc3)

All right. So, let's just revisit the C-NOT once again. When the C-NOT has a white ball for control, like in the left column, it does nothing to the target.
But when it has a black ball in control, on the right, it flips the target. It becomes, it applies a NOT on the second input.
Okay. So, the target toggles if and only if the control is black.  
Control never changes. Or does it? This is how we're going to explore the effect of superposition, phase, and entanglement on changing how the C-NOT works, and with our intuition.

![image](https://github.com/user-attachments/assets/be915af7-acf0-48b4-b881-30606a29be07)

All right. So, let's look at what would happen if we gave a C-NOT two inputs in superposition, with the target already having a negative phase but the control having a positive phase.
So, as always, we need to put this in multi-qubit format. And we have a negative phase, so that'll be multiplied along with the rest.
So, we put the first ball in the first two first positions and then the white ball in the first position of the next two.
And then we distribute the black balls and those two have a negative symbol, so the first and third are going to have a negative symbol with the black ball second.
And then the second and fourth spot will have that white ball, no negative sign. So, now we have four choices and two of which have a negative sign.
We put all of these separately into their own little C-NOT. But I do want to note that as we saw in the Fun with Phase video, I have assigned the negative sign to the pair instead of to the individual ball.
Just so we don't get messed up in remembering that, even though we're doing visual representation, that negative sign is going to be associated with the pair. And C-NOT doesn't affect the sign.
Okay. So, let's look at this. Let's put this, each of these balls through its input of the C-NOT.
And we can see that in the top two pairs our control is black and in the bottom two pairs the control is white. So, we're going to end up swapping those colors on the top two.
Okay. So, I went ahead and copied over my negative signs for the phase and I also copied over all of those control bits, because the control doesn't change in an individual C-NOT but the targets do when the controls are black.
So, now we have four pairs again, but we'll note they're in a slightly different order this time.
Which is fine because remember that while order matters within a pair, the order doesn't matter between pairs.  
But just so it's easiest for us to put it back into separate bit format, I'm going to just swap the order of those two so that we have black black, black white, white black, white white.
So that we can do our opposite tensor product or factor back out into individual bits.
So, let's see, let's figure this out. We have. And the other thing I want to note is that now that negative sign is on a different pair.
Okay. It used to be on the black black and now it is on the black white.
So, let's see how that affects us when we split that back out into individual pairs. So, we still have the same combinations and so an equal probability.
So, we know we still have black white black white. The question is, where do the negative signs go?  
And so, what we notice is well, so these two pairs there's a negative sign in the bottom pair and so I'm going to try putting it with the black.
And then that would mean that the top pair has one negative sign. The only way the top pair could be positive is if both are negative because we know that if we multiply negative 1 times negative 1 we get positive 1.  
So, that means that we should try having the black ball on top also be negative, which would cause that second pair to have a negative sign as well.  
Now, because those are all the negatives in the puzzle, in the problem, then that means that the two white balls are positive and everything works out..
What we want to note here is that if you look at our original start and what we got if you if you push out all the details, and just look at simply the inputs and outputs, what did get? We got a situation where we used a C-NOT and the target did not change but the control did.

![image](https://github.com/user-attachments/assets/0eaf6a23-4d99-443c-a071-1d36baf19a82)

This is very interesting and we are going to exploit this.  
But we want to notice this, that actually we had the situation where target affected control.  
And the way it affected the control was by copying the phase from the target to the control.   
Because if the target, turns out that if the target had been positive, if everything had been positive, then phase would never have been involved and the C-NOT would have done nothing.  
So, the only thing, the only time that this changes is when we have this negative phase.

![image](https://github.com/user-attachments/assets/8c2d9439-b0d3-4592-b56e-caf62f7a60e8)

Okay. So, let's look at what would happen if we put some things around the circuit.
So, to get to that starting point of the inputs to the C-NOT, that would be the same as having H gates.  
You started out with a white and a black, and you put them through H gates because black through an H gate turns into the negative phase and white through an H gate gives you superposition with positive phase.
Now, we already know what happens when we put these two through the C-NOT gate.  
And so, we know that we'll come out with both of these having a negative phase. All right. No problem.
Now we put these back through H gates and look what happened. We get black balls now.
So, with this circuit we were able to turn a white ball into a black ball.
Even more interestingly, if the second ball had been pure white then I would never have had a negative phase and they would both be white on the out side.
So, this means that we have a way of copying a pure state, white or black, to another pure state, white. 
Now, make sure, I need to make sure and remind you that it was only because it was a pure state that we were able to do this.  
So, it's not like if I have a superposition I can copy that, all of the state of that, to another qubit.
In this case, I'm able to copy the pure state one into the pure state of another using this circuit.

https://github.com/SteveJustin1963/QC/blob/main/audit_Phase_Kickback_PQ.pdf


# Bernstein-Vazirani Oracle Algorithm

And now, we're getting to algorithms.
I'm going to present a certain type of algorithm, which I like to call simultaneous computation with oracles.  

![image](https://github.com/user-attachments/assets/2547d475-a762-4fc1-a003-2a002d41a754)

We've actually used oracle-based games, which are related to algorithms, probably in our childhoods.  
And these are defined by having a protocol that provides limited information, in which the player needs to find an algorithm to determine the solution based on some decisions on what question to ask next of that oracle, based on information from a previous one.
For example, Battleship. Right. All you get to say is a location and all you hear back is hit or miss. You don't find out how close you were, only hit or miss. And you don't know what type of ship you've hit, if you've hit it.
Mastermind is sort of the canonical one because you're actually trying to guess a secret code and you're given information on how many of the colors are correct and how many both are correct in color and in position.
And then of course 20 Questions. 20 Questions has been around for generations and it's just a set of yes or no questions. The one person thinks of an object and the guesser tries to guess it in 20 yes or no questions.
So, these aren't just games, they're actually used extensively in computer science, in cryptography and security, because systems tend to leak very specific kinds of information.
I mean, even in a system that's secured, you know when you try a password you're told it's incorrect. That's information.
And so, computer scientists use oracles to try to figure out what's the most you can do with that limited information.
What happens if you, if you're able to read a message that's sent to, for example, the bank from an ATM. Could you then later send an identical message, even if you didn't know what the contents were? If you sent an identical message later, would that mess up things?
So, those are the sorts of useful reasons for having an oracle.
So, an oracle is any computerized system that you can interact with and get information out of. And we try to make algorithms to figure out what we can do with that information, so that then we can turn around and make the security higher, so that it leaks less or different information.
And now, this is a really good fit for quantum because in  quantum likewise we, in all calculations, we can't get full information. We can't find out the full quantum state. And so we want to figure out what operations we can do and short of measurement or measurement.
But the question is, what can we do if we can't get full information? Because that's going to be the reality in a quantum system.

![image](https://github.com/user-attachments/assets/70368a4c-70ad-4d73-b695-eb01344751da)

Oracle-based quantum algorithms start with an oracle in the middle. And this oracle, you can ask it a question. So, you give it some set of information and it gives you an answer back with some set of information.
And so the algorithm itself is all of the stuff you do with that information. What should I ask it and what should I do based on the answer it gives?
So, we want to put gates before and after the use of the oracle and the oracle is going to provide that piece of information.

![image](https://github.com/user-attachments/assets/f4f1e243-5871-4c1e-a099-1d2ee5bc8ccb)

Now I do want to note that we're not, at this moment we're not going to do useful algorithms. We're learning algorithms to try to get an intuition into the nature of quantum algorithms and how it is that quantum computers can get speed over classical computers in some cases.
So, I'm going to describe an oracle. So we're going to do two algorithms. I'm going to describe an oracle and then design the sequential and then the simultaneous algorithm based on that oracle.
And the idea is that a classical computer would be forced to do a sequential algorithm, but with quantum properties we can do a simultaneous algorithm that goes faster.
But again, only in these limited circumstances.

![image](https://github.com/user-attachments/assets/49340d31-6c27-4117-869b-6ff4266d4258)

So, you can think of these as proofs of concept of what quantum calculations might be able to do.
So, let's do one. It's based on the Bernstein-Vazirani algorithm and so I'll call it the BernVaz oracle.
So, there exists this three-bit secret code and you want to figure out what that is.
And so this oracle contains a sequence of CNOT gates, in which each input corresponds to a one in the secret code and the control for the response, which is the target.
So, this means that inside this oracle, there are some CNOT gates. But maybe not connected to everything.
So, in this case the secret code we're going to work with is 0 1 1. And so I've made these two a little bit darker to indicate these are the two that have a CNOT gate that are connected to the response.

![image](https://github.com/user-attachments/assets/ee4f9795-3e12-457e-818d-0235abb37768)

Alright. So, let me show you how this works. Let's imagine I give a guess of 1 0 1.
So, these two have CNOT gates and there's only one. We recall that if you have a white ball as the control to a CNOT gate, nothing changes. And so there's a single black ball connected to a CNOT. So then, the response is going to flip one time.
Now, a second guess is 0 0 1. Notice that the only thing I changed was the ball that wasn't connected to a CNOT at all.
So, that means my output will be the same. It'll toggle one time based on this black ball that's going in here.  
Now, if we give it 1 1 1, we can see that there are two black balls connected to CNOT as control, which means we'll flip this input twice, which will get us back out the black again.
So, that's how the oracle itself works. And now we need to figure out how to build something around it that will allow us to figure out what that secret code is.
All right. So, note that this does not directly tell us the secret code. We did three probes and we can't find out one some information from that probe.
Right. We can figure out that this top is a 0 because when we toggle just that one, nothing happened to the output.
So, that's one piece of information we got. But we didn't  necessarily figure out how many, whether these were ones and zeros on the output.
So, here with this probe 0 0 1, we actually did figure out that the third bit is a 1 because it's the only black ball going in and it caused a flip.
So, by the end of this, we figured out that this is a 0 and this is a 1, and we don't know the middle one yet.  
And then, on the third probe, we already know the first one doesn't matter. We already know that the last one is a 1.
And so, by giving a black for the middle one we actually figure out that this is a 1.
So, with this, these three probes, just how they happen to be constructed, which is chance, I was not doing it for this reason, we actually could figure out all three bits.
But there's a more methodical approach we can use to figure out the three bits.

![image](https://github.com/user-attachments/assets/0de590d7-6a4d-40bb-b5ea-3ef662201287)

So, I invite you to think about a methodical approach. No matter how many bits we have, we could have a five bit input, a ten bit input, right? However long this secret code is, what is the sequence of probes you should do and get out one piece of information each time? Right. Which is whether that black ball stayed black or turned to white.
What would we give as the sequence of probes and how many would it take?
And I will wait just a second. I invite you to pause the video right now and think about that, and try to come up with something yourself and then I'll go through it here.
All right. So, the sequential algorithm is to do a series of probes where you only ever have one black ball, because then that tells you whether that black ball is attached to a CNOT or not.
So, if the response does not flip, like this first case, that means it's a 0.
But in the second case it does flip, which means the second one is a 1.
And then in the third case it also flips, which means the third one is a 1. 
So, we're guaranteed that if I have an n-bit code, I can figure out the code in n trials.
All right. So, let's look at what we can do with quantum. All right. So, we're going to input all white balls for the guess and a black ball for the response.

![image](https://github.com/user-attachments/assets/0de91e73-fe30-489c-b073-f8a02e0e7b07)

And we're going to put H gates before and after the query to the oracle.
And we're going to expose phase flip, so that instead of having only a single piece of information that might change, which is the response, we're actually going to cause the other bits to change, which allows us to have more information.
Okay. So, we know that, and by the way this is a very common way to do an algorithm, is to put everything through a series of H gates at the beginning and then put them through a series of H gates at the end to get back pure states and then see what you've got.
So, we've got these H gates. Now we're in the situation that for these CNOTs, if there's a CNOT we've got a positive 50-50 going in as control and a negative 50-50 as a response.
And we already know that if that happens, if the response is a negative 50-50, it causes the control to change sign and ultimately, when it goes through an H gate, change from white to black.
But it doesn't change the response. So no matter how many CNOTs are connected to this negative 50-50 response, it will stay the same and perform that phase flip on every single one of those inputs that's a positive 50-50.
So, let's see what happens here. We had a 0 1 1 and so now the two ones got a negative sign.
And so then when we put everything through an H gate, we actually get the exact secret code 0 1 1.
And so in a single operation with this oracle, because we preceded and succeeded it with H gates, we actually end up finding out the secret code in a single trial.
So this is what I call simultaneous computation in that because it compels everything to 50-50, it stores all possible combinations.
But then the nature of the operations is such that when we take it out of superposition, it puts it into what we want.

# Archimedes Oracle Algorithm

![image](https://github.com/user-attachments/assets/9cba4c5d-ecaa-4fbd-9edd-7db72e124a0d)

All right. So, let's try another one.
So, there exists a set of three bit codes. And given a three bit guess, the oracle will flip the response if the guess is one of the three bit codes.
So, if I give it a black white black, it will give me the guess back black white black, but the response will be black or white based on whether or not this was one of the secret codes.

![image](https://github.com/user-attachments/assets/2f1ba708-7ec1-483b-be83-d09c2e5dd557)

So, imagine that there are four secret codes: 0 0 0 , 0 1 0, 1 1 0, and 1 1 1.
So, 0 1 1 is not one of the secret codes and so it will not flip its response.
1 1 0 and 0 1 0 are in the set, and so for each of these, regardless if I start out with a black or a white, when I give it one of these, it will flip the response. So, that is how the oracle works.

![image](https://github.com/user-attachments/assets/1ff092c9-eeb2-4b57-9908-38c41057ef0f)

All right. So, using this oracle, we want to figure out whether there are zero or four secret codes. We have some piece of information that's told us that there are either zero or four secret codes and we need to figure out which one it is.
So, go ahead and think about this. Pause the video and see if you can come up with an algorithm, and then we'll go through it together.
Okay, so let's go through the algorithm. We just try randomly or we can go in sequential order. It doesn't matter what we choose as the order.
However, once we find one secret code, we know it's not zero secret codes. So, we know we've got four secret codes.
The other way is that once we reach five non-secret codes, we know we can't have four secret codes.
So, I can either, so I just test in any order I want. And it's until I find five non-secret codes or one secret code.
So, in the worst case it takes five probes, which for a total of eight, that's half plus one.
And so, if we had a larger problem with ten bits, so two to the ten combinations, we would have to go to one half plus one.
So, this is a linear time algorithm, just like the last one was. Last one was linear time on the number of bits.
This is linear time on the number of combinations, which is actually a lot larger than the number of bits.
And so we would like to see a faster one.

![image](https://github.com/user-attachments/assets/1d684c11-6b19-4d4d-8b51-302802d047f2)

All right. So, let's look at what we do. This will be again familiar. We'll put in three white balls and have a black ball for response.
And this time it looks like it's the same, that we might be doing phase flips. But it's not actually the same because we don't have any knowledge of CNOTs inside.
So, we're not using phase flips, but we are putting everything in superposition so that there are all possible combinations.
And so, what it turns out is, that if there are no secret codes then the output will be all whites but if there are four secret codes then some of the outputs will be non-white.
So, let's look at an example where there are zero secret codes. Let's look at what happens if there are zero secret codes.
So, if there are zero secret codes, the oracle does nothing, okay, because I gave it white balls and it's gonna give me back white balls. And it doesn't flip the response, so I get back all white balls.

 ![image](https://github.com/user-attachments/assets/e61a5c09-b3f7-47d0-a0bc-248b8d4758d9)

What I want to figure out is, what happens when there are four? So, I'm gonna use these four codes and we're gonna go through what happens. And I must admit that this is quite dense.
So, what happens. I need to put these in a four bit combination, set of combinations.
And so, what I end up having is, I have this negative state at the end.
So, I have these combinations where I have all eight combinations of the first three bits.
And then I have 16 because then we have two choices, we either are negative phase with a black ball at the end or positive phase with a white ball.
So, you can see in all of these choices, whenever the last one is a black ball I have a negative phase.
So, I have these pairs, these two are the same in the first three bits, they're only different in the last one. Same with these two, these are the same in the first three bits, only different in the last two.
So, we have them all paired up and these are our 16 states going into the oracle.
And recall that what we would need to do is put each one of these individually through the oracle.
And what we know about the how the oracle works is, if it is one of the secret codes it will flip that last ball, the color of that last ball.
So, there are four of them.
0 0 0 which is down here. So, this pair will get flipped. 1 1 1. This pair will get flipped.
1 1 0. This pair will get flipped. And 0 1 0. This pair will get flipped. So, let's let's look at that happen.
So, those are the four pairs that got flipped because those are the secret guesses.
And so, what ends up happening is, the phase of those four pairs get flipped.
It's not a phase kickback, but it did flip the phase of those particular ones.
All right. So, it turns out that if I use algebra to factor out this same state, the negative black with a white, we can do this and we'll end up with eight combinations.
And anywhere the phase flipped on these, we're left with a negative phase. So, the four that are the secret codes now have negative phase for this combination of eight.
Whereas when we had all white balls going in and there were no secret codes, it didn't flip anything, which is why we then end up with white balls coming out.
But here we have now some negative phases and we have to figure out what those negative phases do. How does that turn into a black ball?
Well, we know that black balls result from things going through H gates.

![image](https://github.com/user-attachments/assets/a4a7f970-c23d-4164-9d0b-683f30d73733)

But this looks like a little bit of chaos because we don't know how that's gonna factor out into three individual bits and which ones are going, whether there will still be ones with negative phase or not.

![image](https://github.com/user-attachments/assets/4f7662d4-d2ed-4fde-b0a4-a8f21698c4ed)

So, let's break this down a little bit more and make sure if this seems confusing to you, you can always do it on paper. You can show more steps and you can always repeat the video.
All right. So, let's look at just one of these sets of three going through an H gate.
Okay. So, I have white black black and I put all three of those individual bits through the H gate.
And then I have these, all of these three bit combinations that are from the tensor product of these three superposition bits. Okay.
And then some of these are going to cancel, may cancel out in the end. Okay.
So, then what I do is I put each set of these three through these gates. And different sets are going to have negative signs on different sets of three.
So, when I'm multiplying them back out, so this one has a negative on the outside.
And so I do my internal calculations and then I distribute that negative sign and negate all of them.
So, if I have a positive one, I just do the H gates straight and I multiply everything out and into the different combinations. Right.
So, this top one is the black ball from all three. And there were two negatives, so that canceled out and became a positive.
This one, black black white, drew the black ball, the black ball, and the white ball so that was only a single negative, which is why it retained a negative.
So, basically, in this set of eight we will have a negative sign if only one of the last two are black. So, black white, black white, white black, white black.
But if both are black, the negatives cancel out. And if both are white, there were no negatives to begin with. So, we can use the same logic throughout.
This set of three has only one negative sign on this middle black, so any state that has that middle one being black, which is these four states, will have a negative sign.
And all of the ones that have that middle state being white will be positive.
But then I distribute the negative sign, and now the top four are positive and the bottom four are negative. So, we would go through, for each of these sets, we would calculate all the positive and negatives for each of those sets. Okay.
And then, I've lined them up differently so that I can easily see here. I can line up all of the like ones.

![image](https://github.com/user-attachments/assets/3e424460-cd32-41db-8652-1177dd90a081)

And so, notice that just because this one up top had a negative, it doesn't mean that internally it's negative.
So, we couldn't do a shortcut that said, “oh, well, these four are negative, so those are all going to be negative.” Okay.
But we do notice that in some of these rows, like this top row, there are four negatives and four positives, so those are going to all cancel out. Those are all gone.
We have another row, four negatives and four positives, so these are all gone. So, now it's impossible at this point to have all white balls.
Because we don't have all possible states left and, spoiler alert, these two rows also are half and half positive-negative.
And so we're left with these two rows up top and these two rows on the bottom, where some have been canceled out and some have not been cancelled out.

![image](https://github.com/user-attachments/assets/1d6cb68a-d1b2-471d-8ed7-6b47c681796e)

At the end, we ended up with four states left.
It's impossible to take these out to the original three qubits and that's okay. That means that they're entangled.
So, we ended up with three entangled qubits. And what we also notice is that all of these three ball combinations have a black ball in them.
So that's the reason why we're guaranteed not to get a white ball. It's because interference made it such that all of the three white ball combinations were no longer possible. And so, anything we read out will have a black ball in it guaranteed.

![image](https://github.com/user-attachments/assets/4584ee8c-e6cc-4874-87eb-e334e902ce27)

So, in the first algorithm we used phase kickback and in the second algorithm we used interference.
So, in summary, one paradigm for developing algorithms is using these oracles, which are already used in classical computer science for cryptography and security purposes.
But it turns out it's even more critical for quantum computing. And operating on multiple superposition states simultaneously is the key to performance.
And we saw that in both algorithms.
Bernstein-Vazirani used phase kickback to obtain information from those CNOTSs because we were told there were CNOTs inside.
Whereas, Archimedes, we weren't told what was inside. We used the oracle just as a blind oracle and we used interference to change the mix of the states left.
So it got very complicated with lots and lots of states, but many of them were negative and many of them were positive, and so a lot of them cancelled each other out.

https://github.com/SteveJustin1963/QC/blob/main/audit_Oracles_PQ.pdf

https://github.com/SteveJustin1963/QC/blob/main/audit_Algorithms_HW.pdf

https://github.com/SteveJustin1963/QC/blob/main/audit_Part_1_Exam.pdf

# Post-course Survey

This survey will help your instructors understand how this course improved your knowledge of quantum computers and quantum information science. Please answer each question to the best of your ability.

- What do you think superposition means?
- Why do you think superposition is important for quantum computing?
- What do you think reversibility means?
- Why do you think reversibility is important for quantum computing?
- What do you think entanglement means?
- Why do you think entanglement is important for quantum computing?
- In 2 or 3 sentences, explain why you think it is important for something to exist in two states at once.
- Describe what happens when a quantum bit (also called a qubit) is measured.
- Describe what you think a quantum computer looks like.
- Choose all of the problems that quantum computers are expected to be better at solving, compared to classical computers.

![image](https://github.com/user-attachments/assets/f1c06bc5-15ed-4fc2-8213-9544eb3f12e2)

- Some people have asked when there will be a hand-held quantum computer. Describe your thoughts on when or if that will happen, and why.
- What is the most interesting thing you learned about quantum computing?
- What questions do you still have about quantum computing?



