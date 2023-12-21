# 2023-Research-Personal

Below is an outline of my weaknesses, strengths, and interests regarding my previous research in a theoretical physical chemistry group. I left the group for personal reasons and I would rather not disclose the name of the group. 

## Weaknesses

The following are instances where I noticed things did not go well in my research with my previous group.

- Tendency to add features before making a well tested and working simplest case implementation
- Easily distracted on side projects and non-essential problems
- I found "un-structured" collaboration such as casually asking group members for help or advice to be emotionally taxing. This took away from my ability to focus on research and made in person work rather challenging for me.
- Difficulty in gauging appropriate levels of detail when asked to do task by advisor.
- The most challenging part of a project for me was the final wrap-up/organization step.
  - I did the "hard work" of implementing individual parts of my project
  - Before leaving, I was not able to do the final wrap-up/delivery of my main project. 
  - I was able to deliver concrete “finished” sub-projects (see strengths section)

## Strengths

I am chosing to organize my strengths into technical skills and investigation/research strengths.

### Investigation/Research Strengths

- I go to others with more experience for help if they are available
	- When tasked with learning how to use Density Functional Theory codes/softwares, I went to my labmates for help/advice rather than trying to tackle the problem alone.
- When talking with my advisor or labmates, I practice active listening.
	- I repeat back a paraphrased summary of what was just said. Doing so alleviates many miscommunications immediately.
- I regularly met with collaborators without requiring my PI to do organizational work
	- I organized weekly meetings with my collaborators where I presented my research progress/listen to the colaborators experimental progress.
	- I set up individual meetings with the grad student who was running my collaborator's experiment. Through these, I gained a thorough understanding of the experimental setup and relevant needs for me as a theorist. 
	- In general, I did well with structured collaboration, where the social part of collaboration had well defined meeting dates and times
- I was able to successfully take an abstract implementation idea from my advisor and turn that into a working prototype code.
- I did well in performaing self directed learning. 
	- I developed an in depth understanding of quantum optics via my own research and reading

### Technical Strengths

My main technical strengths are roughly broken down into:

1. Computer Systems
2. Physics
3. General Software Development

#### Computer Systems

- Intimate familiarity with the compilation process for C and C++. This includes symbol lookups in shared libraries and how these are looked up on linux systems when running programs.
- I contributed a cleaner build procedure for a labmates C++ project. This procedure was adopted and used going forward in his code's build instructions.
- I setup a build environment for my project, which compiled C++ code that is callable from a python interface.

#### General Software Development

- My main experience is in python and C++ development.
- I have been learning python for 7 years, C for 6 years, and C++ for 5 years. 
- My previous project is hosted on github, has unit tests, and uses the CMake build system
- I setup well documented github repositories on Github that implimented key algorithms that I read in papers
	- I was able to document results and get a well running concrete implementation from these
### Physics
- In my code, I implemented the light-matter interaction Hamiltonian using the dipole and rotating wave approximation
- I made sure to verify that physical assumptions were correct
	- ex. wavelength of the light being much larger than system size
	- wrote a python notebook that outlined the necessary equations and theory
	- my code produced physical observables as output, and I verified that these outputs were sane values


## Interests

I have two main interests:

1. Investigating and charactarizing physical systems, or system dynamics that are complex. I.e.:
	a. Trying to figure out which parts of a complex system are relevant
	b. Studying how the relevant parts interact and evolve in time
2.  Being able to make headway on the characterization of complex physical phenomena through the development of computational tools or methods
