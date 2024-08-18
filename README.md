# Can I Improve My Tennis Serve Using Machine Learning?

## Introduction

The serve is a crucial element in tennis, often described as the most important shot in the game. It's the only shot where players have complete control of the ball. A powerful and accurate serve can provide a significant advantage. Top players invest considerable time in perfecting their serve, as it can be the difference between winning and losing tight matches.

My science fair project explores how machine learning and artificial intelligence can analyze and improve my tennis serve. I chose to compare my serve to Jannik Sinner's because his serve improvement has been a key factor in his rise to one of the best men’s tennis players in the world. His serve power, accuracy, and consistency played a major role in helping him get his first Grand Slam title at the 2024 Australian Open. By analyzing his technique and comparing it to mine, I aim to identify how to enhance my serve.

### I Did This By:

1. **Data Collection**: 
   - Recorded videos of my serve (from both the side and back) and found similar videos of Jannik Sinner's serve on YouTube for comparison.
   
2. **Pose Detection**: 
   - Used pose detection software to extract body positioning data from the videos.
   
3. **Comparative Analysis**: 
   - Compared my serve to Sinner's, focusing on 4 main points of the serve: the preparation, trophy pose, contact point, and follow-through stages.
   
4. **Performance Measurement**: 
   - Measured serve speed and accuracy with a speed gun.
   
5. **Machine Learning Analysis**: 
   - Analyzed the data with an AI/ML analysis tool.
   
6. **Practice Implementation**: 
   - Applied the suggestions the tool made during training, along with visualizing correct movements.
   
7. **Post-Analysis Assessment**: 
   - Recorded new serve videos, re-measured speed and accuracy, and compared the results to see if I improved.

## Aim / Question

**Question**:  
Can I use AI/ML to improve my tennis serve based on a pro tennis serve, and if so, is it effective?

**Aim**:  
I aim to use machine learning and artificial intelligence to analyze and improve my tennis serve by comparing my technique to the professional tennis player Jannik Sinner. I will split my serve into 4 main parts (the preparation, trophy pose, contact point, and follow-through) and let the analysis tool suggest ways of improving my serve. I will then apply the suggestions the analysis tool gave me to see if it is effective or not.

**Hypothesis**:  
I believe that by using machine learning and AI to analyze my tennis serve and following the improvements they suggest, my serve will get faster and more accurate, making it more like Jannik Sinner's.

## Equipment Used + Method

### Equipment:

- Tennis racket and balls 
- Smartphone or camera for video recording 
- Speed gun
- Computer with pose detection software (e.g., OpenPose) 
- Access to an AI/ML analysis tool

### Method:

1. **Data Collection**:
   - Captured video footage of both the user's and Jannik Sinner's tennis serves (from both behind and side).
   - Captured speed and accuracy with a speed gun.
   - Extracted joint angles from videos using pose detection software like OpenPose.
   
2. **Data Organization**:
   - Imported pose detection data into CSV files for both users, separated by view.
   - Combined data into a single dataset.
   
3. **Data Analysis**:
   - Identified key phases: Preparation, Loading, Hitting, Follow-through.
   - Analyzed the data with an AI/ML analysis tool.
   
4. **Practicing**:
   - Implemented suggestions given by the analysis tool into practices.
   - Visualized correct movements.
   
5. **Post-Analysis Assessment**:
   - Captured video footage of the user's serve after the analysis.
   - Captured speed and accuracy with a speed gun.
   - Compared with previous results to see if you improved your serve.

## Fair Test

Through the test, I made sure I kept everything fair by:

- Using the same equipment for each test (tennis racket, tennis balls, speed gun, shoes, etc.).
- Performing the test on the same type of tennis court in the same type of weather.
- Accounting for speed gun errors (+/- 1.60934 kph).
- Recording the video from the same angle.

## Results

- **Speed increase**: 74.45%
- **Accuracy improvement**: 30%
- ![Insert Graphs](#)

## Conclusion

To conclude, this science fair project shows just how effective machine learning and artificial intelligence can be in improving a tennis serve by analyzing and comparing it to a professional player's technique. By breaking my serve down into the key stages (preparation, trophy pose, contact point, and follow-through) and using an analysis tool to figure out what I need to work on, I was able to achieve an average overall serve speed increase of 74.45% and a 30% improvement in accuracy. This brings my average serve speed from 59.3 kph to a solid 103.5 kph and my accuracy score from 50% to 80%. 

These results support my hypothesis that AI and ML can be used to enhance a tennis serve, making it faster and more accurate. This project demonstrates that AI and ML have the potential to bring professional-level analysis and improvement to athletes at all levels. By using these tools, players can make changes to their technique based on the analysis and see measurable results, proving that AI can be a powerful tool when looking to improve technique in many sports, not just tennis.

## References

- Medium blog post: [Simple Web App for Human Pose Detection Using Docker and OpenPose](https://medium.com/@daniel_c_barker/simple-web-app-for-human-pose-detection-using-docker-and-openpose-56f698ca68bd)
- OpenPose GitHub: [CMU-Perceptual-Computing-Lab/OpenPose](https://github.com/CMU-Perceptual-Computing-Lab/openpose)
- Windows Portable Demo Version of OpenPose: [Installation Guide](https://github.com/CMU-Perceptual-Computing-Lab/openpose/blob/master/doc/installation/0_index.md#windows-portable-demo)
- Windows Portable Releases: [OpenPose Releases](https://github.com/CMU-Perceptual-Computing-Lab/openpose/releases)
- Missing Model File: [Google Drive Link](https://drive.google.com/file/d/1QCSxJZpnWvM00hx49CJ2zky7PWGzpcEh/edit)
- GitHub Thread Used: [CMU-Perceptual-Computing-Lab/openpose/issues/1602](https://github.com/CMU-Perceptual-Computing-Lab/openpose/issues/1602)
- OpenPose Website: [OpenPose Documentation](https://cmu-perceptual-computing-lab.github.io/openpose/web/html/doc/md_doc_installation_0_index.html#windows-portable-demo)
- Flags for Run Command: [OpenPose Flags](https://github.com/CMU-Perceptual-Computing-Lab/openpose/blob/master/include/openpose/flags.hpp)
- Google Cloud AI Video: [YouTube Video](https://www.youtube.com/watch?v=yLrOy2Xedgk)
- Tennis Game Analysis System: [YouTube Video](https://www.youtube.com/watch?v=L23oIHZE14w)
- Tennis Serve Analysis with PDF: [Emerging Investigators Article](https://emerginginvestigators.org/articles/21-168)
- Google Cloud AI Blog: [Machine Learning for Sports](https://daleonai.com/machine-learning-for-sports)
- Tennis Analysis Using Machine Learning: [Medium Article](https://medium.com/@kosolapov.aetp/tennis-analysis-using-deep-learning-and-machine-learning-a5a74db7e2ee)

## Log Book

- **11 May**: Came up with the idea to use machine learning for my tennis serve. Started research.  
  - [Machine Learning for Sports](https://daleonai.com/machine-learning-for-sports)
  - [Emerging Investigators Article](https://emerginginvestigators.org/articles/21-168)
  - [Tennis Serve Analysis GitHub Repo](https://github.com/adeeteya/Tennis-Serve-Analysis)
  - [Tennis Game Analysis YouTube Video](https://www.youtube.com/watch?v=L23oIHZE14w)
  - Found Google Machine Learning development library.  
  - Google provides a wide range of technologies and products for developers to use for machine learning and AI projects, including TensorFlow, TensorFlow.js, TensorFlow Lite, TensorFlow Extended, JAX, Keras, and Mediapipe.  
  - [Dev Library](https://devlibrary.withgoogle.com/products/ml?sort=added)

- **12 May**: Analysis on Sinner's serve  
  - [Serve Analysis Video](https://www.youtube.com/watch?v=XILA_mMMeRo)
  - [Serve Analysis Video 2](https://www.youtube.com/watch?v=NzapT3RxvFs)

- **12 May**: 16:00 to 17:00, Court 7  
  - Before video for pose detection.  
  - Before readings for speed and accuracy - speed gun.

- **13 May**: Video analysis research  
  - [Google Cloud Video Intelligence](https://cloud.google.com/video-intelligence/docs)
  - [Google Cloud Video Intelligence Annotate Video](https://cloud.google.com/video-intelligence/docs/annotate-video)
  - Used OpenPose for my video detection.

- **14 May**: Analysis on my serve - OpenPose  

- **14 May**: Re-record my serve after practicing (16:00 to 17:00 Court 7)

- **15 May**: AI/ML analysis on my serve  

- **15 May**: Upload before/after AI comparison results - Created graphs in Excel. 

- **16 May**: Completed conclusion. Created science board and printed out results.
