# vision-model-development
I am making a end to end pipline foor computer vision model 


step 1: 
i am open a image and converting it to 'RGB' for matrix uniformity
then i am resizing and coverting it into a 32 bit float and using /255 to create a uniform scale of [0,1], using to tensor from transformers libarry from pytorch.
then i am permuting it from 'HWC' TO 'CHW' and add a dimension by using unsquezes(0)
