# Identifies you and your programming partner by name
- Caleb Cyr & Rafael Mendez

# Acknowledges help you may have received from or collaborative work you may have undertaken with others
- We used the rumload file provided by the professor but other than that, we used all of our own packages and did not receive any collaborite work outside of our own.

# Identifies what has been correctly implemented and what has not
- To our knowledge we have correctly implemented everything per the assignment description and requirements.

# Briefly enumerates any significant departures from your design
- The only "departures" that we had from our original design were some helper functions that we had to write in order to implement the functions originally listed. Otherwise, our implementation is exactly as listed in the design document.

# Succinctly describes the architecture of your system. Identify the modules used, what abstractions they implement, what secrets they know, and how they relate to one another. Avoid narrative descriptions of the behavior of particular modules.
- Our architecture is composed of a few files, but there are 3 main ones that are important for the purposes of this question. We have universal_machine.rs, in here we define the struct for our universal machine and our segments. We also defined some of the helper functions to assist with the register operations. The second file is register.rs, here we define all of our methods that  handle all of the register operations for the 8 registers in our universal machine, these methods make calls to some of the helper methods defined in universal_machine. Lastly, we have our rumdis.rs file, here we define an enum for each of the 14 operation codes that the Universal Machine is supposed to handle, and here we define our disassemble function that is responsible for calling the proper methods (from register.rs) based on what operation code is given. 

# Explains how long it takes your UM to execute 50 million instructions, and how you know
- After running 5 tests

# Says approximately how many hours you have spent analyzing the assignment
- 2 hours 

# Says approximately how many hours you have spent preparing your design
- ~5 hours

# Says approximately how many hours you have spent solving the problems after your analysis
- ~20-25 hours