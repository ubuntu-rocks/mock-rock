If you have content that needs to go into the ROCK, then your 
Dockerfile should have access to it.

You can have folders alongside your ROCK recipe files, just make 
sure `.dockerignore` is excluding the contents the ROCK does not need.