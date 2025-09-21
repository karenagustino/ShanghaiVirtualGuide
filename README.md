## Shanghai Virtual Guide

# The Scenario (problem):  
Being a 7-day boarding prefect is not an easy job. As a prefect, I have to help the Head of 7-day boarding, Mr. Cheong, give him some inputs on the fun activities that the boarders can do during the weekend and ask for feedback from the boarders about the previous weekend activities. Brainstorming for ideas and asking for suggestions from people might sometimes be frustrating, and we often end up doing repetitive activities every several weeks. That’s when I started thinking about making a program to fix this. 
 
# Rationale of Solution: 
The goal of this project is to ease my job, as a prefect, and my client’s job, that is Mr. Cheong, by offering a list of activities and food destinations in each of the MRT stations in Shanghai. My client can not only get ideas on the places to visit in Shanghai but also know how much percentage of Shanghai they have covered or visited by accumulating their checked-boxes. As Mr. Cheong’s job is to take students to a variety of cultural and action places, the project will help differentiate the destinations into cultural or action.  
 
I have contacted my client previously through email and he said that he would be interested in this project. We also had a 30-minute video call through WeChat and discussed the possible features that he would expect in this project. One of the things that we discussed was to only put the top three activities or restaurants for each of the MRT stations to ease the client’s options. Furthermore, this won’t only benefit my client, Mr. Cheong, but also foreign tourists who want to explore every part of Shanghai. The project will be in a local desktop application and will use MySQL database to store user’s data. 
 
I will use Python as my programming language because: 
It is very flexible and has a simpler syntax compared to other programming languages. 
I am a beginner in coding, and so I think it is very easy to learn and use. 
After I graduate, someone else can easily update and improve the project with Python as it is globally recognized and easy to understand.  
 
# Success Criteria:  
The client can tick on a checkbox to know which MRT stations that they’ve visited. 
The project can display Shanghai’s MRT lines and stations. 
The project can differentiate whether the destinations are cultural or action-based. 
The client can add comments to the places (MRT station/restaurant/activity location). 
The project can display the costs and opening hours of each place (the MRT station, restaurants, activity location). 
The project can display several pictures of the MRT stations and/or the places of activities or food destinations. 
The project can have a login page for the client to access and hold their own information. 
 

# MEETING THE SUCCESS CRITERIA
Following my discussion with my client, my initial success criteria are shown as follow:
The client can tick on checkboxes to know which MRT stations that they’ve visited. 
Evaluation: Works well. All checkboxes can be saved to the database when the client clicks ‘Submit’. The client said that the number of accumulated checked checkboxes written as a percentage for every time the client clicks on the “Submit” button makes the program more interesting and fun.
 
The project can display Shanghai’s MRT lines and stations. 
Evaluation: Works well. All lines and stations are clearly shown and are identified as available or non-available with the color-coding (red: unavailable; blue: hyperlink/available). All hyperlinks are directed to their appropriate pages with no error found.

The project can differentiate whether the destinations are cultural or action-based. 
Evaluation: Works well. All destinations are written with bolded texts on whether they are cultural or action-based. 

The client can add comments to the places (restaurant/activity location). 
Evaluation: Works well. Not only can the clients input comments onto each destination, but also see their previous comments that they’ve written. All comments are saved and displayed after clicking ‘Submit’.

The project can display several pictures of the MRT stations and/or the places of activities or food destinations. 
Evaluation: Works well. All destinations are filled with two to three pictures that describe their location and environment, with a zoomed-in MRT map. The client says that this is very helpful in getting a brief picture of the destination before visiting it. 

The project can have a login page for the client to access and hold their own information.
Evaluation: Works well. The client can successfully sign-up and login into their account. After the client enters their username and password on the login page, their name will appear as they are directed to the main page.  


# RECOMMENDATIONS FOR FUTURE IMPROVEMENTS
After testing, my client suggested that there are many aspects of the program that can be improved. As the client would like to choose from a greater variety of destination options, I can improve the program to cover details and functions for all 18 MRT lines and each MRT station within those lines. 

Because my client would like to have easier access to the program on his local desktop, he suggested transforming this website into a local desktop application that can be accessed without the Internet. This allows him to access the program more easily and quickly. Since my program uses Python and Flask, I can do this by simply importing WebUI. 

Additionally, with the login and register function, my client expects that there will be other users (students) using the program. Hence, in the comment section of each destination, he would like to also the comments made by other users. This allows him to have a better judgment of each destination before having to visit them. 

Finally, I believe adding a sorting algorithm to the comments arrangement would make the program more interesting, as my client can compare the up-to-date comments with the outdated comments. 
