# CIA-2
The code base contains pso,ga and aco implementastions for the optimization of weights in the neural network.

the pso algo gave a final accuracy of 70.60 but had a best accuracy of 83.60.
the ga algo gave a final accuracy of 70.60 too and didnt change since the second iteration proving that ga doesnt give the best solution always and may get stuck.
the aco algorithm performed porrly overall but some ants gave high local maxima of even 80-90percent accuracy for weight optimisation.

the images have been attatched in the gitlink for the outputs of the codes.

# allignment-matrix
The code takes 2 input strings of a.g.t.c protiens
and it checks if they are equal in length and the starts filling the allignment matrix.
the allignment matrix filler uses 2 functions which check if the characters are a match then checks diagnol else 
takes max of nieghbouring 3 elements.
This is all ive completed for now
ive also had errors when passing the 2d array in to the function which is causing a slightly faulty matrix.
