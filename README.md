# Sleeping Barber
This repository contains a Java solution to the *sleeping barber* problem, using semaphores, for the Advanced Programming Techniques class. 

<p align='center'>
	<img src="assets/SleepingBarber.jpg" alt="SleepingBarber Gui" style="height: 350px; width:350px;"/>
</p>


The sleeping barber problem is an inter-process communication and synchronization problem proposed by Djikstra in 1965 and, in our implementation, is described as follows:

Imagine a hypothetical barbershop with one barber, one barber chair, and a waiting room with 4 chairs. The barber has to shave 10 different people, but can only shave **one** at a time. After shaving 4 people, he needs to take a rest. While he is resting, all clients have to **wait**. When someone is being shaved, all the others have to wait for their turn to be called by the barber. Only 4 people can be seated inside, while all the others have to wait outside.

