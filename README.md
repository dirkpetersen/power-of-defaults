# The power of good default configs in BioMed HPC 

## Abstract

**The blog Codinghorror wrote in 2007: “Choose good defaults, and users will sing the praises of your system and how easy it is to use. Choose poor defaults, and you'll face down user angst over configuration, and a host of tech support calls as well.” 
We will discuss how choosing good defaults can help us increase the productivity of our less sophisticated users. Ultimately, we want HPC to be more inclusive and welcoming towards an increasingly diverse user community, for example from life and social sciences background.**

## More details 

“Civilization advances by adding things we can do without thinking of them.” Do you think that this simplified version of Alfred North Whitehead’s famous quote is still true today, after more than a century? If you support research computing systems, providing training, documentation, office hours and other outreach sessions, but you feel are users are advancing a bit glacially and you are getting as many questions as ever? Web-based science gateways have been developed for HPC environments to avoid confronting inexperienced users with command line interfaces that require them to read, learn and memorize too much. 
But have we already done enough to provide new and infrequent users with a standard setup that will work for them out of the box? Have we provided good defaults? Should the default settings work best for the expert user or for the new or infrequent user? Do we know how many minutes pass between the time a new user receives their credentials and the time they submit their first HPC job? What is their first impression when they log in? What should users think of a system that presents directory names in a barely readable dark blue color by default? Are night vision goggles required? And is our expectation that every user who is embracing the command line interface is going to embark on a long journey from apprenticeship to knighthood at which state they will customize their environment with elusive bash prompts? Or is there a path for users to become reasonably productive a little sooner and with less drama?  There are several relatively simple questions for which there is no consensus answer: 

•	What should be the default umask on a system?
•	How should local scratch spaces be setup? 
•	What is the best way to get an interactive session on a GPU node? 
•	Should cp, rm, mv or rsync be the default option for managing files, is it a web UI? 
•	Does everyone need to understand the concept of wall clock time before submitting a job? 
•	What is the philosophy behind error message like “command not found?”. 
•	Why do I only learn about ProxyPass after 10 years as a user?
•	Where is docker?

In this BOF we will attempt to seed a community of HPC staff that deeply care about improving the experience of new and infrequent users especially from less technical domains such as life and social sciences. We will discuss if we can achieve a better experience for these users with little exposure to Unix based computing systems. . We will attempt to capture these conversations through the new Github discussions feature and provide examples through a Github repository. If we generate momentum, we will continue the discussions at SC23 and establish this as a longer term BOF.
In some cases, we could narrow down choices but not achieve a consensus on the best default.  We will explore how these narrowed down choices can be best presented to the user, for example through terminal user interfaces (TUI). 
