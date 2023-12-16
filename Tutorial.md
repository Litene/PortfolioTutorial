# The why and how of portfolio making
Companies are looking for an investment; therefore, we must showcase that we are one.  
One of the best ways to achieve this is to showcase what we already know while we display  
that we are capable of improving and willing to learn. An easy way to showcase this  
is to show that we are pragmatic, organized individuals who reflect on our decisions before and after.  
Therefore, we want to create a cohesive story about problem-solving. It makes us look like people  
with a plan, someone who is thinking about what we are doing,
which is a great way to learn. To achieve this, follow the steps listed below;
this will also help create a red line throughout our portfolio.

There is another part to it which will not be presented here, about being a good teammate,
not complicated, fun and so on.

### General writing/presentation tips
* Vary sentence lengths
* Avoid big chunks of text
* Keep it relevant and the subject
* Mark relevant keywords in bold or underlined
* Vary the material text, images, media (gif or video)
* Use technical terms and keywords

### part 1 (Overview)
* Here, we present technical specifications and information relevant to the project.
  such as; team size, engine, duration, your role, trailer, and a short description of the game.

[//]: # (Tip)
    Tip

    This should take large portion of the size some space in a bigger font size, and spend time on the 
    presentation, this is the first thing the intersted party will see when they click a game page. This 
    is important information. 

Example: (Use some sort of visual presentation of things described above)

### part 2 (Theory/Pillars)
* We start by presenting the challenges that come with the constraints mentioned in the overview.
  Then break them down into pillars/goals, these are the focus points of the presentation  
  and will serve as a red line throughout the presentation. These will look similar to design pillars
  but but for programming, they will act as anchors for the rest of the gamepage to refer back to.

[//]: # (Tip)
    Tip

    This is great opportunity to showcase that you grasp programming on a broader scale, how limitations
    affect the project as a whole and that you can plan accordingly. 

Example: Our team only had two programmers and five designers therefore we focused creating simple tools the designers could use so that the designers could take a bigger
workload when it comes to implementation.

### Part 3 (Implementation, 1.0)
* We present the border between theory and our project, patterns used and why. This should tie back
  to the goals/pillar created in the theory section.

[//]: # (Tip)
    Tip
  
    A UML chart or flowchart of the architecture helps with overview of the project, it also helps in 
    the later steps when isolated scripts are shown, because its easy to reference back to it. 

Example: Since we had to focus on tool creation we deployed the factory pattern to facility quicker creation
of scriptable object, we kept the architecture simple due to the time constraints of the project.

### Part 4 (Implementation, 2.0)
* This is were we start presenting code, here we want to showcase relevant code, code that is
  related to our created pillars. Tying to explain how we achieved the pillars. This is done in small iterations
  and if its related to gameplay or gameplay loop, a small video or gif on the side is great.
  I would argue that the text in this section is more important than code itself, here you have an opportunity to showcase that you understand the code,
  that you were a central part in creating it, this is an important factor since most
  projects are group projects.
  
[//]: # (Tip)
    Tip

    * Video should be clickable when the text is seen, so that the reader can get context 
    while reading.
    * Easily accesible code foldout are preferred since it won't distract by default but is
    still accesible for context. 
    * Try to find a logical order for your project to present so that it doesn't feel
    random, a random order will create will make it hard to follow and will cause the reader
    to focus on the wrong things.

Example: We started by creating abstraction through Interfaces (see IFactory in UML).  
Access was managed through the abstract class to keep the encapsulation. This made it easy   
to create more factories for other types of objectives in the game.

(Code foldout)

Party 5 (Post Mortem)

* A detailed but short post mortem describing what went wrong, what went right,
  did you achieve the pillars of the project and so on.


[//]: # (Tip)
    Tip

    Please be honest here, if things went bad, explain what and explain why, this is is an
    opportunity to show that you learn from mistakes, a vital part of being an productive employee. 
    A nice touch is to describe what you would have done differently if you remade the project again.

Example: The project overall went well, but all the programmers had to both crunch and do suboptimal  
solutions in order to meet the deadline, this created a sort of spiderweb. If we did it again we could probably  
voice our concerns earlier about the amount of features. Additionally we should have tried not to give into the stress.  
In our case a builder pattern could have helped with some of the issues caused toward the end of the project.