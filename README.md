# Draw-It-or-Lose-It-Software-Design-Doc
A document outlining the design of the Draw It or Lose It application designed for client: The Gaming Room

My client The Gaming Room requested a web-based version of their application Draw IT or Lose It. This design document was helpful in developing the code for the project as it outlined the requirements and design constraints to adhere to, provided a helpful visual in the form of a UML diagram, and helped to organize my thoughts on which platform to host the game on. My analysis of the UML diagram in the documents was detailed and broke down exactly why each class was structured the way that it was, and how each class was related to the other classes, which in turn helped me to understand the code I had to write. If I could go back and revise this document I'd give more thought to hosting the application on a cloud-based platform. Overall I feel that I met the client's requirements well within the code I wrote. I employed a singleton pattern to make sure that there was only ever one instance of the gameService() class and employed an iterator pattern to make sure that mutiple games could be playing at once with indivisual IDs, names, players, and teams. I also used the iterator pattern to make sure that no duplicate game, team, or player names or IDs existed. 
