# Can i improve my tennis serve using machine learning?


INTRODUCTION 

The serve is a crucial element in tennis, often described as the most important shot in the game. It's the only shot where players have complete control of the ball. A powerful and accurate serve can provide a significant advantage. Top players invest considerable time in perfecting their serve, as it can be the difference between winning and losing tight matches.
My science fair project explores how machine learning and artificial intelligence can analyse and improve my tennis serve. I chose to compare my serve to Jannik Sinner's because his serve improvement has been a key factor in his rise to one of the best men’s tennis players in the world. His serve power, accuracy and consistency played a major role in helping him get his first Grand Slam title at the 2024 Australian Open. By analysing his technique and comparing it to mine, I aim to identify how to enhance my serve.
I did this by:
Data Collection: I recorded videos of my serve (from both the side and back) and found similar videos of Jannik Sinner's serve on YouTube for comparison.
Pose Detection: Used a pose detection software to extract body positioning data from the videos.
Comparative Analysis: I compared my serve to Sinner's, focusing on 4 main points of the serve: the preparation, trophy pose, contact point, and follow-through stages.
Performance Measurement: I measured serve speed and accuracy with a speed gun.
Machine Learning Analysis: I analysed the data with an AI/ML analysis tool
Practice Implementation: I applied the suggestions the tool made during training, along with visualizing correct movements.
Post-Analysis Assessment: Recorded new serve videos, re-measured speed and accuracy, and compared the results to see if I improved.




AIM / Question
Question:
Can I use AI/ML to improve my tennis serve based off a pro tennis serve, and if so is it effective?

Aim:
I aim to use machine learning and artificial intelligence to analyse and improve my tennis serve by comparing my technique to the technique of the professional tennis player Jannik Sinner. I will split my serve into 4 main parts (the preparation, trophy pose, contact point and follow through) and let the analysis tool suggest ways of improving my serve. I then will apply the suggestions the analysis tool gave me to see if it is effective or not. 
Hypothesis
I believe that by using machine learning and AI to analyse my tennis serve and following the improvements they suggest, my serve will get faster and more accurate, making it more like Jannik Sinner's. 

Equipment used + METHOD
Equipment:
•	Tennis racket and balls 
•	Smartphone or camera for video recording 
•	Speed gun
•	Computer with pose detection software (I recommend openpose) 
•	Access to a AI/ML analysis tool
Method:
Data Collection:
•	Captured video footage of both the user's and Jannik Sinner's tennis serves (from both behind and side)
•	Capture speed and accuracy with a speed gun
•	Extracted joint angles from videos using pose detection software like openpose
Data Organization:
•	Imported pose detection data into CSV files for both users, separated by view.
•	Combined data into a single dataset
Data Analysis:
•	Identified key phases: Preparation, Loading, Hitting, Follow-through.
•	Analyse the data with an AI/ML analysis tool
Practicing:
•	Implementing suggestions given by the analysis tool into practices
•	Visualising correct movements
Post-Analysis Assessment:
•	Captured video footage of the users serve after the analysis
•	Capture speed and accuracy with a speed gun
•	Compare with previous results to see If you improved your serve
FAIR TEST
Through the test, I made sure I kept everything fair. I did this by:
•	Using the same equipment for each test (tennis racket, tennis balls, speed gun, shoes,  ect)
•	Making sure I do the test on the same type of tennis court in the same type of weather
•	Making sure I account for speed gun errors (+/- 1.60934kph)
•	Making sure the video is recorded from the same angle


Results 

•	Speed increase: 74.45%
•	Accuracy improvement: 30% 
•	[insert like 69 graphs]


































Conclusion
To conclude, this science fair project shows just how effective machine learning and artificial intelligence can be in improving a tennis serve by analysing and comparing it to a professional player's technique. By breaking my serve down into the key stages (preparation, trophy pose, contact point, and follow-through) and using an analysis tool to figure out what I need to work on, I was able to achieve an average overall serve speed increase of 74.45% and a 30% improvement in accuracy. This brings my average serve speed from 59.3kph to a solid 103.5kph and brings my accuracy score from 50% to 80%.  
These results support my hypothesis that AI and ML can be used to enhance a tennis serve, making it faster and more accurate. This project demonstrates that AI and ML have the potential to bring professional-level analysis and improvement to athletes at all levels. By using these tools, players can make changes to their technique based on the analysis and see measurable results, proving that AI can be a powerful tool when looking to get a better technique in many sports, not just tennis.







REFRENCES

Medium blog post: 
https://medium.com/@daniel_c_barker/simple-web-app-for-human-pose-detection-using-docker-and-openpose-56f698ca68bd
Openpose github: 
https://github.com/CMU-Perceptual-Computing-Lab/openpose
windows portable demo version of openpose: 
https://github.com/CMU-Perceptual-Computing-Lab/openpose/blob/master/doc/installation/0_index.md#windows-portable-demo
windows portable releases: 
https://github.com/CMU-Perceptual-Computing-Lab/openpose/releases
missing model file (server where the missing file was hosted got shutdown, so I found the file using a github thread) 
https://drive.google.com/file/d/1QCSxJZpnWvM00hx49CJ2zky7PWGzpcEh/edit
Github thread used: 
https://github.com/CMU-Perceptual-Computing-Lab/openpose/issues/1602
Openpose website: (with installation guides and demo features)
https://cmu-perceptual-computing-lab.github.io/openpose/web/html/doc/md_doc_installation_0_index.html#windows-portable-demo
flags for run command (e.g. --write_json):
https://github.com/CMU-Perceptual-Computing-Lab/openpose/blob/master/include/openpose/flags.hpp
Googe Cloud AI VIdeo:
https://www.youtube.com/watch?v=yLrOy2Xedgk
Tennis game analysis system:
https://www.youtube.com/watch?v=L23oIHZE14w
Website on tennis serve analysis with PDF included:
https://emerginginvestigators.org/articles/21-168
Google Cloud AI blog on using AI to analyze tennis serve:
https://daleonai.com/machine-learning-for-sports
Tennis Analysis using machine learning:
https://medium.com/@kosolapov.aetp/tennis-analysis-using-deep-learning-and-machine-learning-a5a74db7e2ee





LOG BOOK:
11 May
Came up with idea to use machine learning for my tennis serve
Started research

https://daleonai.com/machine-learning-for-sports
https://emerginginvestigators.org/articles/21-168
https://github.com/adeeteya/Tennis-Serve-Analysis
https://www.youtube.com/watch?v=L23oIHZE14w

Found Google Machine Learning development library
Machine Learning Projects 
Google provides a wide range of technologies and products for developers to use and develop for their machine learning and AI projects. These include TensorFlow, TensorFlow.js, TensorFlow Lite, TensorFlow Extended, JAX, Keras and Mediapipe. Dev Library has a curated collection of Machine Learning and AI blogs, open source projects, and tutorials contributed by developers around the world. 
https://devlibrary.withgoogle.com/products/ml?sort=added

12 May
Analysis on Sinner serve
https://www.youtube.com/watch?v=XILA_mMMeRo
https://www.youtube.com/watch?v=NzapT3RxvFs

12 May
16:00 to 17:00
Court 7
Before video for pose detection
Before readings for speed and accuracy - speed gun

13 May
Video analysis research
https://cloud.google.com/video-intelligence/docs
https://cloud.google.com/video-intelligence/docs/annotate-video-command-line
TensorFlow
https://www.tensorflow.org/hub/tutorials/movenet

14 May
Gathered training data from my serve and Sinner from back and side angle to analyse

24 Jun
https://cloud.google.com/blog/topics/developers-practitioners/can-machine-learning-make-you-better-athlete

13 Jul
Research Random Forest Algorithm in Machine Learning
https://www.geeksforgeeks.org/random-forest-algorithm-in-machine-learning/

14 Jul
Developed script to load the CSV files, combine the data, identify the serve phases, calculate the average angles, and save the comparison data to a new CSV file called comparison_serve_phases.csv

22 July
Private lesson 1 hr

25 July 2024
11:30 to 12:30
Court 7
Practice

28 July 2024
16:00 to 17:00
Court 2
After readings video for pose detection

28 July
Ran comparison pose detection Before / After / Sinner

04 August 2024
15:00 to 16:00
Court 3
After readings Serve speed and accuracy - speed gun (Asher)



















