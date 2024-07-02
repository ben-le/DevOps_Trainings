## How to Learn Linux Shell Scripting for DevOps?
**by Bibin Wilson, April 29, 2023**

For aspiring DevOps engineers, it is essential to know shell scripting or bash scripting. In this shell scripting for DevOps guide, I will share my tips and resources to learn Linux shell scripting the right way.

I have spoken about the importance of shell scripting in my guide on becoming a DevOps engineer. This guide is for anyone who wants to learn shell scripting the right way that can help you with your day-to-day work and DevOps interviews. It’s very important to have patience and discipline in the learning process.

If you are someone who wants to just get things done, then Google & Stack Overflow are more than enough 🙂

### Table of Contents
- [Shell Scripting for DevOps](#shell-scripting-for-devops)
- [How to Get Started With Shell Scripting?](#how-to-get-started-with-shell-scripting)
- [What are the Best Free Shell Scripting Learning Resources?](#what-are-the-best-free-shell-scripting-learning-resources)
- [Real-world Shell Scripting Use Cases](#real-world-shell-scripting-use-cases)
- [Shell Scripting Real-Time Scenarios](#shell-scripting-real-time-scenarios)
- [Shell Scripting Languages](#shell-scripting-languages)
- [Shell Scripting DevOps Interview Questions](#shell-scripting-devops-interview-questions)
- [Shell Scripting FAQs](#shell-scripting-faqs)

### Shell Scripting for DevOps

The first question you might have is, how important is shell scripting for a DevOps engineer? I have got this question from freshers as well as experienced IT folks.

The answer is, it’s very important. The following image shows the Stack Overflow 2021 survey, where 27% of the respondents said they use shell scripting.

![Shell scripting Stack Overflow survey results](link-to-image)

But most of the time, I get asked, saying that there are many automation tools out there, do we still need to learn and write shell scripts? The answer is yes. We no longer create shell scripts for full-fledged automation, but we use scripting along with automation tools and for ad-hoc tasks.

For example, if you use the AWS user data option, there is a chance you will use a shell script inside it. Another example is, while creating AMI images using a packer, you will end up using a shell script for the AMI configuration. Also, I have had instances where I had to use shell scripts with configuration management tools, containers, etc. We will talk more about this in the following sections.

Also, shell script comes in handy for repeatable development tasks. For example, it could be spinning up a Vagrant VM with the essential software or setting up the development environment itself.

Most importantly, hands-on scripting and programming are becoming mandatory in preliminary interview rounds in DevOps interviews. So it is another crucial reason why you should learn shell scripting.

### How to Get Started With Shell Scripting?

The prerequisite to getting started with shell scripting is hands-on experience with Linux. Therefore, before getting started with shell scripting, you should be comfortable working with Linux commands.

If you are totally new to the Linux world, you could start by spinning up a few Linux servers locally using Vagrant or on cloud platforms like AWS, Google Cloud, etc. Every platform offers free credits for beginners. You can check out the free $100 credit from DigitalOcean as well. It’s effortless to get started.

If you think you are comfortable with Linux, you can get started with Shell scripting basic tutorials. Also, I want you to do the following:

Create a GitHub repo, create folders for each concept you learn, and commit all your work scripts. It doesn’t matter if the script is available online. Have your own documentation. You can add references and credit websites/blog links in the README section. Once your learning is over, you can share it on LinkedIn. Trust me; it will help you retain the knowledge and will help others as well.

### What are the Best Free Shell Scripting Learning Resources?

You don’t need to pay for any expensive courses to learn Linux shell scripting. There is too much marketing around courses that promise to make you a DevOps shell scripting ninja. However, I don’t have anything against courses; go for it if you feel comfortable learning via a paid course. I will add those resources as well.

I have listed the best free shell scripting resources for you to get started. Go through all the resources once, pick one resource you feel comfortable with, and ensure you go through the material from start to finish. As I said earlier, mastering technology requires patience and discipline.

Follow the free resources. It has web-based content, web-based interactive tutorials, free courses, and PDF materials.

- [Linux Shell Scripting Tutorial](link-to-tutorial) [Web]
- [Free interactive shell scripting tutorials](link-to-tutorial) [Web]
- [Shell Scripting tutorial](link-to-tutorial) [Web]
- [Bash Guide](link-to-guide) [Web]
- [Shell Scripting Free Course](link-to-course) [Udemy]
- [Advanced Bash Scripting Guide](link-to-guide) [PDF]
- [Bash Academy](link-to-academy) [Web]
- [Bash Notes for Professionals](link-to-notes) [PDF]
- [Bash Reference Manual](link-to-manual) [PDF]
- [The Linux Command Line](link-to-command-line) [PDF]

But if you say, hey, I am a person who likes guided courses, here are some of my recommendations:

- [The Complete Guide to Bash Programming – Educative](link-to-course)
- [Shell Scripts for Beginners – KodeKloud](link-to-course)
- [Shell scripting with Bash – Pluralsight](link-to-course)
- [Operationalizing Bash and Z Shell Scripts – Pluralsight](link-to-course)
- [Linux Shell Scripting: A Project-Based Approach to Learning](link-to-course)

### Real-world Shell Scripting Use Cases

Assuming you have learned all the shell scripting concepts and probably written and executed shell scripts for learning purposes. The next question anyone would have is, how to learn real-world shell scripting use cases?

If you work in a company, you can find project documentation and infrastructure automation codes where existing projects use shell scripts.

If you don’t have access to project documents and code, here is what you can do:

Find the GitHub repo of the most common Docker base images, for example, the Nginx base image.

There you will find an entrypoint folder with multiple scripts or an entrypoint.sh script file. Here is an [Nginx example](link-to-nginx-example).

Try to understand the shell script and its functionality. In this process, you will figure out many concepts and logic that can be used while writing a shell script (functions, conditionals, switch cases, and many more).

It is not just limited to Docker repositories, you can find scripts in many open-source community repositories.

### Shell Scripting Real-Time Scenarios

It is always better to learn with some real-time scenarios in terms of DevOps engineer interviews. So I have come up with some real-world scenarios you can try out. I will keep updating this list.

- Write a shell script function to find and kill all the zombie processes.
- Find the first 10 biggest files in the file system and write the output to a file.
- Shell script to gracefully unmount a disk.
- Shell script to send an email.
- Shell script to monitor CPU, memory, and disk usage and send the output to a file in table format and send an alert if either of them exceeds a certain threshold.
- Shell script to find the files created and their sizes. It should accept the number of days as input. Or a from and to date format as inputs.
- Write a shell script to automate the process of creating new user accounts on a Linux server and setting up their permissions and SSH access.
- Write a shell script to list the users logged in by date and write it to an output file.
- Shell script to copy files recursively to remote hosts.
- Shell script that displays the number of failed login attempts by IP address and location.
- Shell script parses a log file and forwards a specific value with a timestamp to an output file.
- Write a shell script to automate the process of rotating log files and compressing old files to save disk space.
- Write a shell script to check the status of a list of URLs and send an email notification if any of them are down.
- Write a shell script to automate the process of updating a list of servers with the latest security patches.

Ensure you include the following concepts in the shell scripts you are writing:

- Variable definitions
- Use `cut`, `awk`, and `grep`
- Handling input/output/error redirections
- Conditions/if-else statements
- Case statement scripts
- Loops (for/do-while)
- Exit status
- Command line arguments

### Shell Scripting Languages

First of all, there are no specific shell scripting languages. When it comes to shell scripting, it refers to `sh`, `bash`, `csh`, `tcsh`. Here we are primarily talking about bash shell scripting. Bash is an interpreted scripting language for Unix-based systems.

A shell script is a computer program designed to be run by the Unix shell, a command-line interpreter. 

> Wikipedia

But scripting languages, in general, mean multiple languages. The following are the common scripting languages:

- PowerShell
- Python
- Perl
- Groovy

### Shell Scripting DevOps Interview Questions

Shell scripting DevOps interview questions differ from company to company.

For example, a service-based company would be just interested in your basic Linux and shell scripting knowledge. However, a product-based company might expect a good level of

