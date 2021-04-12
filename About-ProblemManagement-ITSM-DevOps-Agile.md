## Q. I am looking for Problem Management in DevOps with agile principles if any one has some idea, inputs or document please do share. Thanks.

This is a very dense question. Anything that includes *DevOps*, *Agile* and *ITIL* has to be. Let’s try to deconstruct the key concepts and then approach the answer piece by piece.

***Disclaimer:*** *I'm not an expert. What you are going to read below is my simplistic interpretation of these concepts. I will try to contrast/relate these concepts in a way that may help you approach the problem at hands with some more clarity.*


## Problem Management

For most practical purposes, you can see PM as an evolution of Incident Management (IM). It tries to get highly enriched insight from IM. This is true for most of the cases. There are situation where a Problem can come into existence without any history in IM. But let's keep it simple for now. In short, you can say PM is IM of Incidents.

> ### *"Problem Management is meta-Incident-Management"*

Where IM gives you a way of managing the Incidents on day to day basis, PM is about doing further analysis on IM, thereby maturing the IM, one problem at a time. In PM you analyse the volume of incidents over a period of time and draw new insights that may not be very obvious when you are busy solving day to day issues. 

> ### *"Sometimes you have to take a step back and look at problems from a different perspective to get a better view of the situation. PM is that perspective."* 

***Example:*** 
> *You have a leaking tap at home.* <- This is an **Incident**. 
 
Now, you know how to resolve this Incident. You have faced this issue in past. In fact you are now so good at solving this that solving such incident has now become a second nature. Even better, you are so good at this that you can even predict when the tap is going to break down next and so you now keep the plumbing supplies handy so that you can fix this whenever it happens. 

> Even though you have a solution to this incident. The tap still keeps breaking every 6 months. This is not ok.

Problem management in this case would be looking at your home repair projects time to time in hope of finding some patterns. You notice that tap breaks down every 6 months, which should run longer than that. You identify this as a "Problem". If you can fix this, you will have fewer incidents each months. You may even save some money. Or time. That's why it worth it. 

> *You have a leaking tap at home.* <- This is an **Incident**.     
> *Tap keeps breaking every 6 months.* <- This is an **Problem**. 

Possible solution could be. Invest in better quality spare parts. Or may be not. The point of PM is not to find a "better" solution but find an "acceptable" solution. Acceptable, within a given context. From your analysis you may come to a conclusion that replacing it every 6 months is still cheaper than investing in a better quality faucet. May be this is a holiday home and you only come here once in a while. May be you don't have the skills to set up the new tap. As long as you practice a ritual of:-  
	1. Analyse Incidents
	2. Identify patterns  
	2. Acknowledg Problems  
	3. Resolve

As long as you take a conscious decision to change (or not change), it's all good.


## Agile 

Is a set of principles. It tells us what to focus on and what should be ignored. It’s nothing more than that. You can read the menifesto [here](https://agilemanifesto.org/)

Read the manifesto and then read it again. Read it one more time and then read the principles. Make sure you not only understand them but also believe in them. Believe that collaborating with your customer will ensure a more successful journey than trying to negotiate a contract. So on a so forth. Once you start believing in these principles they will naturally reflect in your solutions. 

**Example:**  
> *"Individuals and interactions over processes and tools"*  

Tools and processes exist to enable interactions between individuals. Focus more on THIS outcome: "interactions" not the means of enabling it "tools and process"

> *"Responding to change over following a plan"*. 

Don't get annoyed if the requirements changes. Because they will. Instead, develop a workflow that can deliver something quickly. So the changing requirements can be accommodated in incremental fashion. Build something every couple of weeks will lead to customer delight. You and customer will come up with requirements that otherwise would not have been possible. That's the magic of collaboration. 

 
## DevOps 
Is an ecosystem. Ecosystem, because it is made up of right set of tools, people, mindset and rituals. It aims to solve just one single problem. Bridge the gap between Development and Operations. How does it differs or relates to from Agile and ITSM? I think it's an irrelevant question. Each of these concept evolved independently to solve some problem within their respective domains. It's like asking should I use a hammer, a brick or create a floor plan for construction? 

The right question should be how to make them work together. 


## What's the point?

All of this would be of no use if there aren't actionable. There might be to possible scenarios right now.

Try to understand what DevOps practices are already in place. If there are none there’s a bigger problem to solve. And how to solve it depends a lot on the factors. Are you are responsible for just PM or the over all DevOps transformation? In most case there has to be a dedicated DevOps transformation being led by different stakeholders in different capacity and you would leverage that to set up PM within that eco system.

You should as yourself this question. Am I working with a customer who already has DevOps in place with agile as a way of thinking in every solution they implement? Or you have a customer that is new to this and you are helping them in the overall transformation, along with ITSM?

I wish it's the first case because second one can become very messy very soon. Trying to drive two organisation level changes that too of such complex nature seldom works. Nevertheless, depending on which scenario applies to you, your approach can be one of the two:-

* **Approach 1:** Design and Implement a Problem Management process that "fits" within the existing ecosystem. What that means, if people already prefer a certain way of interacting...slack instead of emails...meet them half way down the road. Ex: Approvals and review on Slack instead of emails. 

	*If people write RCAs in Google docs or simple emails don't expect them to suddenly start publishing these RCA in an ITSM Knowledge Management System....instead leverage what you can immediately. ex: Put links of these documents with in your KM module. <- This is agile way of solving a problem. Instead of driving a change which would need you to communicate train and comply people to do thing certain way, which by the way may never happen, you decide to do the minimum viable version of it (just put the doc links) as the first version of solution and then improve from there on.*  
	
	These are just few examples but apply this idea of "fitting in" and "meeting them half way" and "incremental change" and "continues improvement" as a part of your overall solution. The end result will be an agile PM solution that enabled/solves some specific problem for DevOps*.

* **Approach 2:** You are driving a bigger transformation for them along with the ITSM (PM). In that case, since, and I am assuming, you won't have control or visibility of what tools or process they come to agree upon...you can still implement a PM solution that has agile principle embedded in it as a part of core design. just remember the points discussed about. Only caveat is since there's no guiding lights for you to follow, having a prior experience of working with different DevOps teams will help.