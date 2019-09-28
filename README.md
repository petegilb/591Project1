# 591Project1

I started off my project without much of an idea of what I wanted to do so I looked up different python libraries and ended up finding pendulum which is a datetime python library. I wanted to use it and compare it with the built-in datetime features in python, and actually found that the built-in one is pretty good. I did some tests parsing strings and finding the current time and found that when pendulum used its own functions it was much faster. So I decided to make an example where whenever we see datetime.strptime we will instead use pendulum.parse and only the first argument. I changed it using the NodeTransformer that we discussed in class by visiting Call in the Ast and making a new node. I also created a BNF notation and visitor class that checks the validity of the syntax using NodeVisitor. This was definitely an interesting first project.

Peter Gilbert
