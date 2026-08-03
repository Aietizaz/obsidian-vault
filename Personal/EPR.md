

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
- My contribution with these ISEs is setting them to work, meaning to install operating systems on servers and configuring the iDRAC (remoting tool) as well as the NAS (storage). I've also changed configuration files in order for the system to work as intended + testing the system for both the standard functionality required and expected from SI and against the requirements for the respective hosted system.
- As we progressed through the ISEs, we started to get more efficient with resolving problems, fixing common issues and filling documentation. FAT was often successful without any major hiccups. 
- I learnt a significant amount of what i know today from working on the ISEs since they always started broken in some way or another, that exposure helped me. 
- On the right there's a little diagram with some of the segments and things that I have learnt to work with. 
- A lot of the work on these mini systems needed collaboration, not just from within my team but other teams such as network and console, as well as the customer and the technical authorities of the projects
- You have to adapt to the systems as needed and things change.

SLIDE 7
- This is more of an overview of things that i've worked on or have become familiar with during my time in Integration. 
- I've worked on if not all, almost all the platforms, Services and software we commonly use - including exposure to DNS, DHCP, NTP, etc. General infrastructure stuff such as servers, storage, operating systems. Virtualisation, the tool i'm working on, VMware, hypervisors. Automation and development, reading, debugging and working with PowerShell, C# .NET. Professional and behavioural development, improving my technical confidence, communication and explaining things to people in a way that makes sense, ownership of my project, etc. 

SLIDE 8 
- Obvuiously, there's no way i would know everything after just 18 months and i'm the type to always want to know more when i'm interested. So these are some of the things i feel like i haven't had much of a chance with or there's a lack of in my work.
- Starting off with software development, this is something that i was worried about a bit when i started my role since there's little to no actual software development in my team. However, i plan to continue my ModelDeploy script, strengthen my knowledge of architecture and automated testing and look for more opportunities to potentially improve or automate our work.
- Hopefully, by doing this i can retain my academic knowledge and develop meaningful tools or processes


- Second, this is probably the hardest for most grads, leadership and ownership, of course i have my project but there aren't that many opportunities to lead for people early in their career and develop people, or inspire. You can try your best to participate and teach new members of the team for example but creating more chances is difficult, hopefully this is a mid to long term goal as career progresses.
- Finally, advanced problem solving, i'm pretty confident in where to look, how to analyse a problem and my though process. especially once you've been exposed to an issue once. But sometimes i come across complex problems that i don't know where to start with, i might spend a couple of hours trying to work it out but eventually seek some senior advice. which isn't bad but eventually i would want to work it out myself and i think that would just come withy experience and exposure

SLIDE 9
- I always struggle with this type of question because honestly most of the time i'm not sure.
- But i can say in general, i'm learning a lot while in this team and believe there is still more to learn. I want to strengthen my skills as much as possible and potentially find more chances to take ownership
- In the mid term thats when i'll start thinking about if there is something new i can learn, or use. Hopefully at this point too i would have the chance to support and inspire new members who join us.
- And the long term, maybe one day i'll be aim for a leadership role, or potentially consider a new project of business unit if there's something that interests me there

SLIDE 10
- A final short reflection and summary of going from a graduate to an independent engineer
- I've had an unreal technical growth, i knew nothing of what we work on when i started this role and it was never something that was taught to me. this was the perfect role to work on my problem solving skills too.
- I've worked directly with customers and third parties which definitely improved my communication
- I've created and am still developing my own project which hopefully ends up being useful
- and overall, this role has been a great learning opportunity for me to develop as a person, professional and an engineer

