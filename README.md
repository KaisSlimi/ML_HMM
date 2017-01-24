# ML_Project
This file show the implementation of Gaussian HMM using hmmlearn
It is used for the unsupervised learning for the human activities recognition.

For the MHMMR file:
Dor each activity, I see how it was preducted by he algorithm.

For exmample, the activity one is easy to predict, because it is a simple activity: " Working at PC".
Activité  1
[0, 30601, 76, 1974, 307, 540, 179]
So, we can be sure that the activity 1 is the cluster 2 in the prediction.

In the contrast, for the actvities, whih are not a simple, but a complicate ones: combination of actions, the algorithm divide it between the other activities and the activity itself.
For axemple, activity 2: "Standing Up, Walking and Going updown stairs", is a combination of other 3 activities and itself.
And for that, we obtain: 
Activité  2
[0, 0, 94, 388, 0, 252, 194]
So, we can say that the non null componenet make refrence to thses for activities: "activity 2", "Standing",  "Walking" and "Going updown stairs".

And the same way, for the others.
