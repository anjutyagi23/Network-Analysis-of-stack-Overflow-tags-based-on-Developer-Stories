# Network-Analysis-of-stack-Overflow-tags-based-on-Developer-Stories
Network graph visualization using Python and Gephi

### Introduction:
StackOverflow is a platform where students and professionals post queries and answer questions about programming. It is a platform to showcase their knowledge. It is owned by the StackExchange Network. The answers are upvoted based on its usefulness to the community. Users can also use StackOverflow to advance their careers & enhance their skills. It is a community of more than seven million programmers.

Along with questions, students and professionals also creates their Developer Stories in Stack Overflow.They are designed to give a full picture of a students/professionals based on what they know and built. Stories gives insight into their proficiency in different technologies, open source contributions, blogs, applications and websites they’ve built, Stack Overflow activity, and much more. Technology tags is a part of their profile which highlight's their preferred tools and languages. Each tag represents a specific technology that the candidate has used, likes or dislikes. Thus technology tags on Developer Stroies is the great way to analyze the relation between various technologies.

### Objective:

Being in the IT company, we spend a lot of time and energy thinking about tech ecosystems and how technologies are related to each other. One way to get at this idea of relationships between technologies is tag correlations, how often technology tags at Stack Overflow appear together relative to how often they appear separately. One place we see developers using tags at Stack Overflow is on their Developer Stories, or professional profiles/CVs/resumes. It will be interesting to know how technologies are connected and how they are used together, developers' own descriptions of their work and careers is a great place to get that.

Our analysis will help the people from various background. For experienced person s it will help them to understand the technologies which is related or attached to there current field or area of expertise so they can develop new skills, Even if someone wants to change their domain in IT suppose from frontend to backend or full-stack, what are the popular technologies developers are using currently they can easily able to identify from this type of analysis and if will think this from fresh graduate perspective or someone who is new to IT world, This will help them to understand the fastest growing technologies, which they can learn in coming days to scale up their skills and full-fill requirement of the different companies.

Here, we carry out an analysis of the Stack Overflow tags viewed as a network, or a graph. Specifically,
we aim to get some insight about the user communities by representing tags and their cooccurrences as a graph, where the graph nodes are the tags themselves, and an edge between two nodes exists if the corresponding tags are found together in the same Stack Overflow Developer Stories. The resulting network edges are weighted, i.e., the more stories exist with two tags co-occurring, the higher the weight of the relevant edge between them will be.

In graph terminology, the resulting graph is a weighted undirected one.

### Problem Statements:

    1) How technologies relate to each other in the network.
    2) How often technology appears together.
    3) Analyzing the busiest node and try to identify the reason behind it.
    4) Which technology has the greatest number of centrality and which has least number of centrality.
    5) Analyzing different clusters for each programming language and family pattern like android with java or embedded systems with C and C++.
