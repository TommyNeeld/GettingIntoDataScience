# Getting into Data Science

As much as people say there are loads of DS jobs out there, it is still difficult to get hired with little to no experience. I have seen many applicants turned away for positions which teams are desperate to fill. Also, when I have searched for articles or videos on 'how to get into data science' I often disagree with the advice or I find it is too prescriptive. Every DS role is unique, and every Data Scientist has a unique set of strengths/interests. I hope to develop this page over time as a valuable resource for people looking to get a role in DS and develop their career.

I tend to think of Data Science (DS) as a combination of Machine Learning (ML) theory/practice and Engineering or software development skills/practice. Some Data Scientists are stronger Engineers, others are stronger ML nerds. You can get away with being one or the other or a bit in-between. I was hired as a Junior Data Scientist as someone with little Engineering background but with a relatively strong ML background - I also applied to work in a consultancy role, which I knew would work in my favour as I had some experience as a consultant. I also find that there are two broad DS personalities, one which is more suited to the nerdy ML side and one which is more suited to building stuff. I have thought of these personality types as the empiricists and the rationalists, an empiricist is the experimental type who would rather build, test and observe the outcome, the rationalist is the theorist who will spend more time thinking what may or may not work and why. I would consider myself as the empiricist, who is at risk of doing stupid things occasionally but is good at getting stuff done. I have worked with many rationalists, these can be thought leaders in their field or very detail orientated academic level precision. Junior DS roles in small DS teams will typically suit more the Engineer/Empiricist, DS roles in established DS teams will typically suit more the ML theorist/rationalist.

A note on progression... when I started in DS in a junior role, my salary was way below average. However, with a lot of hard work, within 2 years I was able to double my salary to what is now considered average in my area. 

Things that help if you have little to no experience:
- play to your strengths - if you have a background in a field, apply for DS roles in that subject area if possible, this will bolster your application relative to those with a purely technical background;
- create a portfolio - in an ideal world you can link to your GitHub page on your CV and show off about some of the cool applications of DS related work you have done or built. Even if it is small it gives a recruiter confidence that you know what you are talking about;
- create your own experience - regardless of if you share what you have done on GitHub or not, you should certainly start gaining experience by working on some DS type problems. [Kaggle](https://www.kaggle.com/) is a great resource for this.


## Resources

### Podcasts:
- [Data Skeptic](https://dataskeptic.com/) - mixture of interviews and introductions to ML concepts from a good Data Scientist called Kyle Polich. The introductions to ML concepts are done one2one with his wife, who knows nothing about ML. I haven't listed to many of the interviews, the one2one explanations are very good though and work as a nice introduction to the subject. I listed to these a lot at the start of my career, I think they are now less relevant to me. 
- [Linear Digressions](http://lineardigressions.com/) - this  works very well as an introduction to concepts in ML from a good Data Scientist. Again, this is in a one2one format with someone who doesn't know much on the topic.
- [Talk Python to Me](https://talkpython.fm/) - this is more Engineering focussed, I find that this podcast is more useful as I grow in my career. 


## General setup:

It is important to start looking and behaving like a developer - depending on your role, you may spend most of your time developing. If you are on Mac I am not going to be able to help, however if you are on Windows I have a few suggestions. My suggestion is to use Windows Subsystem for Linux (WSL), or if you really want to add a Linux partition to your machine. To get started with WSL use the [windows guidence](https://docs.microsoft.com/en-us/windows/wsl/install-win10) and [this video](https://www.youtube.com/watch?v=Cvrqmq9A3tA&t=384s) for a nice walk-through with terminal installation suggestions.  

Independent on what computer you have, I advise to use pip as your Python package manager and virtual environments for projects - covered [here](https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/) or just follow [this video](https://www.youtube.com/watch?v=YYXdXT2l-Gg&list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU&index=2&t=0s). For engineering/application type projects use an IDE such as Visual Studio Code or PyCharm, for data analysis projects use Jupyter Notebooks or JupyterLab. Get used to interacting with the terminal using [bash commands](https://www.youtube.com/watch?v=oxuRxtrO2Ag). 


### High level path: 

This provides some high-level path and resources; however, you do not need to follow the ordering and can dip in and out once you know what you are interested in doing / learning about. 

#### 1.	Python fundamentals for data science / Engineering:
- Complete the Udemy [Python bootcamp course](https://www.udemy.com/course/complete-python-bootcamp/) or most of this [YouTube series](https://www.youtube.com/playlist?list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU)
- Review and use core Python Data Science libraries. These are covered in the [Udemy Pandas bootcamp](https://www.udemy.com/course/the-pandas-bootcamp/), this [YouTube Matplotlib series](https://www.youtube.com/playlist?list=PL-osiE80TeTvipOqomVEeZ1HRrcEvtZB_) and this [YouTube Seaborn series](https://www.youtube.com/playlist?list=PLE50-dh6JzC7X8VFX40yoIXnhctF2bR8F). Libraries to cover include: NumPy - Numeric Computation; Pandas – Data Analysis - learn before NumPy; Matplotlib – Data Viz, just a little then move to seaborn; Seaborn.
- Complete some python projects, can use [this article](https://realpython.com/intermediate-python-project-ideas/) as inspiration

#### 2.	Machine learning fundamentals:
- Learn some basic theory, use a combination of:
    - This [ML course on YouTube](https://www.youtube.com/watch?v=yDLKJtOVx5c&list=PLD0F06AA0D2E8FFBA) - this is a huge series and **does not** need completing (many first 10-20 lectures are enough)
    - This [MIT, intro to ML course on YouTube](https://www.youtube.com/playlist?list=PLnvKubj2-I2LhIibS8TOGC42xsD3-liux) – slightly dated but a good introduction
    - This [ML course by Andrew Ng]((https://www.coursera.org/learn/machine-learning?action=enroll&adgroupid=80109820241&adpostion=1t1&campaignid=2070742271&creativeid=369041663186&device=c&devicemodel=&gclid=CjwKCAiAuqHwBRAQEiwAD-zr3W9VKrRzBsD6AEXLSzijyd0QwIl0GNKRqggwGN1mXhR_MRQ2I5PJ8BoC8pAQAvD_BwE&hide_mobile_promo&keyword=machine+learning+mooc&matchtype=b&network=g&utm_content=07-StanfordML-ROW&utm_medium=sem&utm_source=gg)) comes highly recommended although I have never completed it myself.
- Go into some detailed ML topics, for example this [NLP course](https://www.youtube.com/playlist?list=PLoROMvodv4rOhcuXMZkNm7j3fVwBBY42z) - this will also get you into Neural Nets and 'deep learning'.
- Learn how to apply the theory by completing the [Python for Data Science Udemy course](https://www.udemy.com/course/python-for-data-science-and-machine-learning-bootcamp/) - gives an intro to scikit-learn and neural nets (ignore sections on Spark)
- More advanced reading:
    - Recommend 2nd edition of [Hands-On Machine Learning with Scikit-Learn, Keras and Tensorflow](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/)  
    - ...

*Bring it all together by Practise with [Kaggle data sets](https://www.kaggle.com/datasets) and submit one complete piece of analysis to Kaggle - Purpose: Get used to working with data, practise applying Data Science to real data and compare with others.*

#### 3. Git

`git` is the standard tool used within DS teams and software dev teams globally to manage code versioning. It is essential for any technical role -  although `git` is boring, I cannot stress how useful it is, you don't need a lot of experience but being able to do the basics and google your way through the rest is essential. There are many resources available for git, I would recommend reading the first few chapters of the [official documentation](https://git-scm.com/doc) and supplementing it with the odd video such as [this](https://www.youtube.com/watch?v=SWYqp7iY_Tc&t=348s).

#### 4. Cloud computing:

A large portion of the job of a Data Scientist is around cloud computing. This isn't covered by many DS or ML courses but is necessary once you get into a role - depending on the type of role you may be heavily involved in using or managing cloud resources. The most popular compute resources are Amazon Web Servers (AWS) and Microsoft Azure. Because AWS has been around longer it is more popular amongst DS practitioners however Azure has caught up. Google Cloud Platform (GCP) is gaining in popularity however is a little behind. Typically, I have found AWS or Azure are used as the platform of choice and GCP services will be used such as the speech-to-text API, maps API etc. Azure and AWS are comparable to a large extent - not one is better than the other. Personally, I find the UI in Azure much simpler and therefore easier to get started with. Regardless, the documentation on AWS is vast and therefore, although it appears more complex on the surface, the amount of advice online is extensive. 

To get comfortable using cloud environments  it is necessary to get comfortable using the command line interface to 'do things' on a computer. Sometimes this just needs to be as simple as navigating the file systems and making simple changes. Therefore, being comfortable with basic Bash commands and the basics of interacting with a Linux distribution can be very powerful. The simplest way of getting comfortable using Bash and interacting with a Linux distro is to do it on your own machine and get used to it that way. I give advice on how to do this in the 'Laptop setup' section for Windows users. In terms of lectures on bash, this [video is a good start for bash](https://www.youtube.com/watch?v=oxuRxtrO2Ag). In terms of cloud computing, it is a case of starting to do some things, starting an ec2 instance (basic Linux server) is covered [here](https://www.youtube.com/watch?v=Xs0g_ZEv2bw), doing the equivalent in Azure, known as a virtual machine in Microsoft lingo, is covered [here](https://www.youtube.com/watch?v=rOiSRkxtTeU)  
