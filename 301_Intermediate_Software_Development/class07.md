# What Google Learned About Teams

## Summation
------------
> **A lot of employers are starting to realize that analyzing and improving individual workers isn't enough. A lot of work these days are becoming reliant on team-based output. This is supported by studies that show people working in teams tend to achieve better results and report higher job satisfaction. Silicon Valley takes studies like that and adopts it into the workplace where companies encourage their software engineers to work together because these same studies show that groups tend to innovate faster, see mistakes more quickly and find better solutions to problems.** 

> **In the last decade Google has focused on building the perfect team. Google created Project Aristotle to find the answer to questions about what made the perfect team. Was it common interests? Shared goals? Similar backgrounds? Personalities? A lot of research became directed toward group culture norms as this seemed to point toward instances where groups described aspects of their team in regards to "unspoken rules" or "team culture". Researchers eventually concluded that what distinguished the "good" teams from the dysfunctional groups was how teammates treated one another. The right ones could raise a groups collective intelligence.**

## Some common themes among successful teams:

1. Everyone got a chance to talk(equality in distribution of converasational turn-taking.

2. Good teams had high "average social sensitivity".

3. Pychological safety - teammembers feeling as if they could take risks without being ridiculed.
-------------

Who is Roy Fielding?

 > computer scientist. one of the principal authors of the HTTP specificaiton and the originator of the Representational State Transfer achitectural style(Wikipedia)

Why don’t the techniques that we use today work well when we need to be able to talk to all of the machines in the world?

 > Bc they weren't designed to be used like that. Fielding and his colleagues had that originally as a goal but developers much later didn't have those requirements. You only needed to talk to a small group of machines. 

What is the HTTP protocol that Fielding and his friends created?

 > General purpose protocal for applying verbs to nouns. Example used it when you go to a web page the browser does an HTTP GET on the URL you tpe in a then you get back a web page. 

What does a GET do?

 > Read: Used to "read" (or retrieve) arepresentation of a resource. Returns a representation in XML or JSON. Considered safe. [Using HTTP Methods for RESTful Services](https://www.restapitutorial.com/lessons/httpmethods.html) 

What does a POST do?

 > Create: Often used to "create" new resources. [Using HTTP Methods for RESTful Services](https://www.restapitutorial.com/lessons/httpmethods.html) 

What does PUT do?

 > Update/Replace: Often used to "update" capabilities. No safe, bc it modifies(or creates) state on the server. [Using HTTP Methods for RESTful Services](https://www.restapitutorial.com/lessons/httpmethods.html) 

What does PATCH do?

 > Update/Modify: Used for "modify" capabilities. Only needs to contain the changes to the resource, not the complete resource. [Using HTTP Methods for RESTful Services](https://www.restapitutorial.com/lessons/httpmethods.html) 

 API Keys request completed. 

  ## Things I want to know more about
    The difference between PUT and PATCH. Would like to see some examples. 