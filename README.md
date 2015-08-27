# uGIF
uGIF is an animated GIF encoder for Unity.

It use a single global color table and frame differencing
to optimize size of the output file. Encoding occurs in 
a separate thread which avoids any lag in the main Unity
thread.

See the Example Scene, Main Camera for an example of usage.

