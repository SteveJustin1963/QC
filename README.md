![image](https://github.com/user-attachments/assets/1ad9ff5a-a098-4937-b1a2-5a8b3bd1e7db)![image](https://github.com/user-attachments/assets/bc7053c5-bf58-401f-bbc9-be4cb36125bb)

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

 Start of transcript. Skip to the end.
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
 

- Audit_QOps1_practice_questions.pdf
- Audit_Intro_to_QC_and_QOps_1_Homework.pdf




