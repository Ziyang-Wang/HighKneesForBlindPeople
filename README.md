# High knees for people with visual impairment

### Click on the picture to watch a demo:

[![](https://raw.githubusercontent.com/Ziyang-Wang/AccessibilityKinectProject/master/high%20knees%20for%20people%20with%20visual%20impairment.png)](https://youtu.be/9lMRoM6PMYU)

This is a demo that I did in my Research and Development of Accessible Computing Technologies class. Learning the fact that visually impaired students often have delyed performance with their locomotor skill (see [Teaching two critical locomotor skills to children who are blind or have low vision](https://www.researchgate.net/publication/283103782)) and also inspired by the course instructor's [Eyes-Free Yoga paper](http://homepage.cs.uiowa.edu/~krector/files/kinect_yoga_paper.pdf), I would like to see if it is possible to instruct people with visual impairment doing high knees with only a Kinect and a computer (possibly be a small interactive device in the future). For the demo, I used Microsoft KinectV2 to track the participant's joint. I wrote a C# program to calculate critical angles and provide basic audio feedback if necessary, which is relatively accurate. However, I found it exceedingly hard to find a way of providing simultaneous audio feedback for different body parts since the potential overlaps are messy. For now, I could only provide simultaneous textual feedback. I would love it if someone could offer some suggestions to the development of the project.
