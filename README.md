# podcast_embeddings
Kernel 1 - food podcasts 

The is made up of two main files. The helper file which contains all the functions, and the process_podcasts which contains code to send a podcast to gpt and recieve back cleaned up data.

The code currently takes txt files

# To do

- The prompt needs re-writing to produce better output, for example separated paragraphs. might be worth experimenting on a small bit of text and seeing how the api responds
- the current code only processes a single file at a time. This is impractical for many files. A for loop needs to be created that will loop through all the files send them to the api combine each podcast backtogther then save the resulting txt file.