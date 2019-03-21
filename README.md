# PAPER REVIEW
![Paper](images/1.png)

<b>Title</b> : Implementing Virtual 3D Model and Augmented Reality Navigation for Library in University

<b>Author</b> : P. Jomsri

<b>Publication</b> : International Journal of Modeling and Optimization

<b>Year</b> : 2018

<b>Vol / No</b> : 8 / 6

## INTRODUCTION
The university libraries are an important data storage place for students, teachers, and other staff. Currently, to retrieve information in the library, most users only searched for details of books including categories, names, authors, and borrowing status. Not only finding those data, users must locate books such as buildings and shelves where books were kept. Thus, 3D and AR technology are considered as an alternative ways to find books which is more efficient.

By applied proper and high quality technology in the library both normal and online services, researcher believed that developing 3D library and AR navigation help users to locate books accurately and quickly. Users can see where the books locate, as well as system working on websites is convenient for any users who are not familiar with the library. Thus, users can see the whole services of libraries through the simulation which imitate the environment of the library in form of 3D which works together with current searching systems. When users can find books, the system will present in 3D, and work with AR technology so the system can bring users to book shelves quickly.

## METHOD
### Study and Gathering Data
This research studied carefully in the library’s services, bookshelf management, inquiring about the type of work required by the library, as well as related document and researches.

### Desiging 3D Model and Augmented Reality Technology for the Library
The process of Designing 3D model and Augmented Reality technology for the library is divided into two parts:

#### System designing by drafting 3D virtual library system

1. Augmented Reality system designing for Indoor navigation by using Unity and Vuforia SDK.
2. Taking pictures in the building, adjusting regarding the requirement, and uploaded to Vuforia website.
![Library](images/2.png)
3. Developing in-building navigation system which determined the current location of the users according to the turn of users by pointing the camera to the marker point in the area such as signpost and room number. When users specified the desired destination, the system calculated the shortest part with Dijkstra Shortest Path Algorithm and displayed the arrow on the image taken from the camera, displayed at the marker location as if it were an actual object. The arrow head pointed to the calculated path. This allowed users to walk in the right direction.
4. Map structure design by using basic information that was needed, which was the top-level diagram of each floor in the library building. In the development process, from the map of the node to the location of the node which could be classified as turn node or intersection, signpost node, and book node.
#### Mobile application design
This step was to design the database system and design a mobile screen which linked to 3D model and Augmented Reality navigation for university libraries by designing the user interface and the functionality of each part.

### System Development

This research divided into two parts: 3D library by using Google Sketchup program and library navigation by using C# in developing the application. To develop the system, a researcher took pictures from Library in Suan Sunandha Rajabhat University. The Vuforia SDK plugin was used to help identify the markers that appear in the camera and used the Unity 3D engine to create realistic arrow images. This was inserted into the image where detected the markers and user Dijkstra’s Algorithm for navigation.

![Library](images/3.png)

### System Testing and Implementation

This research was conducted in two parts: system validation and measure the level of user satisfaction with the developed system. A researcher asked 50 system experts including students and other people to volunteer in assessment. The subjects were asked to rate the relevancy of the search results on a five-point scale:
-	Score 1 is the level of satisfaction improvement
-	Score 2 is minimum level of satisfaction
-	Score 3 is medium level of satisfaction
-	Score 4 is good
-	Score 5 is very good satisfaction

## RESULT AND DISCUSSION

![Library](images/4.png)

## CONCLUSION

The results show that the developed system was a tool to reduce the time spent searching books from the library. Providing users with an overview of library and navigation areas within the library, AR technology can display the user's location and direction of movement when the user navigated.