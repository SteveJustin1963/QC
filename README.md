![image](https://github.com/user-attachments/assets/bc7053c5-bf58-401f-bbc9-be4cb36125bb)

# QC


 
# Introduction to Quantum Computing for Everyone

# UChicagoX QUAN12000

# Goals

Welcome! In this course, we delve into the interdisciplinary endeavor of quantum computing, with a focus on developing intuition about the major benefits and limits that are imposed on quantum computing by the quantum phenomena as well as getting comfortable with how basic quantum operations behave. The specific goals of the course are:

Learn the intuition behind the quantum mechanics principles that affect quantum computing.
Learn basic quantum computing operations
Learn the mathematics necessary to calculate quantum operations
Learn how individual quantum operations are combined to create higher-level operations and algorithms
As a virtual course, most of the content will be included as videos followed by individual questions to practice / check understanding. In each section, there will be a larger homework assignment that tests the understanding of all videos of the section. 

# Resources
Textbooks that might be useful:

# Recommended: 
Q is for Quantum, Terry Rudolph
Dancing with Qubits, Robert S. Sutor
Course Pacing and Access to Assignments
This is a self-paced course. Please note that access to graded problems is only available to those enrolled for the verified certificate.

# Grading / Assignments
For those enrolled in the Verified track, each student’s final grade will be computed according to the following:

Practice questions following videos: 20%
Homework problems for each section: 35% 
Exam: 45%
Your lowest 2 scores on the practice questions will be dropped. 

An overall grade of 70% or higher will be considered a passing grade. 

# Section Overview

Quantum information science (QIS) is useful for a small set of very compelling applications, some of which we will introduce in this section. Then we’ll introduce some current quantum computing hardware and take a historical perspective on the development of quantum computing. Quantum operations occur at a qubit level. Unlike classical computing, there are not yet programming languages that allow programmers to abstract away critical details of quantum operations without needing to understand them. In this section, we will introduce operations on a single qubit.

# Quantum Computing: Introduction and Applications

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

The decision of what makes one path the ‘best’ as compared to the rest is often made with respect to reducing a cost such as number of required resources for the trip or total time taken for the journey. For example, in their routing problem, UPS optimizes routes for minimal left turns rather than shortest route.


# Practice Questions due Jan 11, 2025 02:45 AEDT
Visit the website that hosts a simulation of the Traveling Salesman Problem that optimizes for the shortest path. Pick a map and complete the simulation at least twice, once with 10 stops and once with 30 stops. For each simulation, take note of the length of the optimal tour, length of your tour, and calculation time (how long it took the computer to find the optimal route). Afterwards, feel free to continue experimenting with the simulator by varying the number of included cities each time.

https://algorithms.discrete.ma.tum.de/graph-games/tsp-game/index_en.html

Travelling Salesperson Simulation
Yes	No
Were you always able to find the optimal route?


Audit Learners: Travelling Salesperson Simulation

Visit the website that hosts a simulation of the Traveling Salesman Problem that optimizes for the shortest path. Pick a map and complete the simulation at least twice, once with 10 stops and once with 30 stops. For each simulation, take note of the length of the optimal tour, length of your tour, and calculation time (how long it took the computer to find the optimal route). Afterwards, feel free to continue experimenting with the simulator by varying the number of included cities each time.


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











  
