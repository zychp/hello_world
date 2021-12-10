# hello_world
This is according to a guide https://guides.github.com/activities/hello-world/

Pawel here, I like Python and the Heatmaps. I want to make sure that my tests are kept somewhere safe and I can get them from anywhere.
The first real Python Code file will be about reading in JASON file or a dataframe and creating the heatmap plot on it.
Heatmaps should contain (as a minimum), a record number and the values for it in two columns. Let's say that we have 10 rows of data and the values would specify what is the status in reality, so the second column (first was the record number) would be positive, negative, positive, begative and so on. In total, we would have 5 positive with indexes 1, 3, 5, 7, 9 and negative with indexes 2, 4, 6, 8, 10. The third column would contain the status labeled by predictive system. If the system is perfectly labeling as in relity, then the heatmap would have 1s on the diagonal and zeros off the diagonal.
Id real pred
1  pos  pos
2. neg  neg
3. pos  pos
... ...
10 neg  neg

If, however, the labeling system (predictions) will contain some mistakes, then the heatmap would show one value off the diagonal. It would be easy to see what was confused with what.
