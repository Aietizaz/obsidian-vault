

SLIDE 1

- Afternoon, thank you for coming to my EPR
- During the presentation, run through:
	- My background and general things about me
	- My team and my role including an overview of tasks and things we work on
	- My journey so far
	- 2 examples of some of the projects i have mostly focused on: ModelDeploy and ISEs
	- A general breadth of experience section with general things i've worked on or with
	- Where I think I need to develop and improve - building from my current experience
	- What my future looks like
	- Finally, a reflection and summary section to end off on

SLIDE 2

- Starting off, a little more about me
- My academic route to where I am now wasn't exactly traditional, I started off studying Medical Genetics for my BSc at QMUL
- During that degree, my final dissertation project was focused on analysing The distribution of uncongressed chromosomes and their effect on spindle pole movement - not to get too in depth on that but the main point is that the project involved the development of an image and data analysis tool that can work on a microscopic level
- That's when I was first introduced to programming and software in general - participating in the development of the tool and learning R which is a statistical programming language
- From there, I took a little time to consider if i wanted to continue into the biology route or potentially pivot to computer science and as you can guess, i chose the latter
- I went to study Computer Science for my MSc at Cardiff University.
- Eventually joining BAE

- On a more personal level and outside of work, I have a variety of hobbies, reading, swimming, going to the gym, a big fan of motorcycles and working on some projects that i think are interesting in the moment like an app that recommends recipes based on your mood, energy levels and time you have

SLIDE 3

- Before getting too in depth, a little about my team and my role over the last 18 months. 
- I work on the Integration team for Shared Infrastructure project, SI for short
- A little summary, SI is an adaptable environment designed for combat systems and provides an all in one operator experience for hosted systems with a focus on resilience, efficiency and scalability
- On a lower level, Integration is responsible for
	- Build and release creation 
	- installation and deployment of the software
	- configuration management
	- infrastructure support across the many platforms
		- T45 / QEC /T26
	- Automation 
		- More on a project I've been working on independently later
	- System Testing
		- Build checks to ensure functionality is as expected from a standard baseline
		- Factory Acceptance Testing (FAT) which often happens with a customer
		- Vulnerability Assessments support
	- Troubleshooting issues, the role requires a broad view of the system because an issue may come from networking, storage, configuration files, virtualisation problems or any number of possibilities

SLIDE 4

- This is a summarised rundown of my journey here
- In Jan 2025, I joined BAE systems and had to spend the first few months understanding the processes, standards and ways of working. Also, i was focused on building relationships with those within my team and slowly expanding outwards to other teams, essentially making my presence known
- Starting April 2025, I began to get more involved in the actual technical aspect of the work and learning the platforms / SI in general. I spent time contributing to installations, build checks and even had the opportunity to work on the aircraft carrier. A lot of this period was learning as much as i can from the experienced engineers.
- By September, I felt like i could work independently across the majority of the platforms and was confident to work on most of the expected integration activities. I was beginning to get a better understanding and things started to just click into place. This is when i began to help and support new members which went towards my developing people value
- at some point, i was provided responsibility for models, which is what we use as templates to simulate what it would be like to have hosted system vms/devices on the system, mostly used for testing and to ensure everything works as intended. I noticed our method of deployment of these virtual machines was not as efficient or consistent as it should be so i began to work on my independent project and developing a tool for Multi-VM deployment/configuration to improve consistency, reliability and efficiency
- By April 2026, I was consistently supporting FAT on the ISEs, vulnerability assessments and participating in all Integration activities/tasks and adapting where necessary
- And now we're here at today

SLIDE 5

- This is one of my main projects that i have focused a lot of my time on since before Christmas.
- The main issues with the original process was that we could only deploy one virtual machine at a time and it was quite repetitive. The process often led to inconsistent results and configuration failures which then had to be fixed, and the original was about 4000 lines in a single script making it impossible to read, debug or extend
- My goal was to redesign the original process as an application with a user interface so that anyone could use it, create a dynamic workflow so that editing files/directories or the script itself is kept at the bare minimum to avoid any issues, and most importantly is the parallel processing and live status reporting, basically letting multiple virtual machines to deploy at the same time and monitoring the exact stages they are at and where they fail if they do.
- So far, I've managed to reduce the amount of manual intervention, and the overall deployment time relative to the number of parallel sessions that are run which is a variable in the script that you can change as needed
- This project really let me be creative and add my own thoughts on something that is my own, I had something in mind and i wanted to make it work. I was also a bit hesitant in committing to it since i was worried about what would happen if i wasn't able to do it - especially since i knew little to no PowerShell, it took some courage to finally just focus on it and share the idea.

SLIDE 6 
- For the second main focus of my work, i wanted to talk about ISEs, which are essentially a reduces replication of the main SI platforms that is built so it can be delivered to Hosted systems for them to test
- The main challenges are that each hosted system might have different requirements and introduce different infrastructure, software and configuration while the main SI software and configuration cannot be applied as is from the main system because of the differences in scale
- My contribution with these ISEs is setting them to work, meaning to install operationg systems on servers and configuring the iDRAC (remoting tool) as well as the NAS (storage). I've also changed configuration files in order for the system to work as intended. 