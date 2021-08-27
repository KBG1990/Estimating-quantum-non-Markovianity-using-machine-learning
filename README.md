# Experimental characterizaton of a non-Markovian quantum process
We use machine learning techniques to estimate the temporal correlation in a non-Markovian quantum process. Here, I will give a brief motivation to our problem. For a detailed result, please have a look at our paper: https://doi.org/10.1103/PhysRevA.104.022432.

Most noise characterisation process assumes Markovianity: a memoryless evolution where the description of the evolving quantum state is fully detemined by the previous time-step and is compleltely independent of the past time-steps.  Such evolution occurs when the evolving quantum state is perfectly decoupled from the environment. However, in practical scenario this condition is often violated --- the system-enviornment interaction becomes unavoidable. Such system-environment interaction leads to a non-Markovian evolution, where a time-step of distant past can affect the present quantum state. 

We are dealing with a particula example of such non-Markovian process. For the sake of amusement, consider the environment is my human-friend who agreed to help me by putting two quantum gates, one is now and the other one is at some future point of time. The friend, who has a considerable number of quantum gates to choose from, rolls two dice and depemding on the result applies the quantum gate. When the dice are indepent, then the process will be Markovian. However, suppose the friend is lazy, just like me, and instead of rolling two dice, rolls one. Based on the roll, he applies two same gates at different times. In this scenario, a present quantum operation is correlated with the future opearation, and the process will be non-Markovian. 

Note, although I am considering a conscious environment, please don't go into the debate of quantum consicousness. We just need to model the environment by two random variables having a joint distribution, but this is not fun to describe. 
