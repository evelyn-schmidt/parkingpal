# Parking Pal
Parking Lot Space Counter for TigerHacks 2022

## Website
https://eas4875.wixsite.com/hehe

## Inspiration
A major problem on our college campus is parking lot availability, especially for commuters. There are cameras that monitor the parking lots however the video feeds are hard to access and clicking through all of them is time-consuming. We were interested in computer vision and have heard of the concept of using it to analyze parking lots to see what spaces are available or not. We thought a great idea for a start-up would be to create a system that can analyze parking lots and easily share the data with both the organizations that use the parking lots and potential customers that want to find a place to park. For a customer or commuter, knowing if spaces are available and when the parking lot is the busiest would make going to a location less stressful. An organization can use this data to more fully understand when they are the busiest and if they have adequate parking available. Furthermore, this could be used to better community nfrastructure by showing where parking is in the highest demand or to encourage commuters to use other transportation on days when parking is the most scarce. 

## Our Goal
First, a photo of an empty parking lot will be analyzed by marking all the individual empty spaces. Then a live feed of a parking lot will be fed into a program and, using computer vision, we will determine which spots have a car in them and which spots remain empty. This data will be outputted to a website where a potential user of that parking lot could view it. Additionally, a report will be created that an organization would be given to better understand how their customers access their business. 

## How we built it
There were some resources using OpenCV that we referenced to both teach us about computer vision and test to see if our idea was possible. We used a few sample videos and projects from other sources, we then began to manipulate the output in a way that was applicable to our project. This included doing some calculations using the data to find the time when the parking lot is the busiest and also attempting to convert the output into a JSON object. This JSON object would be used by an API to be displayed by the Wix website. 

## Challenges we ran into
The first challenge was that computer vision is difficult to implement because pictures and videos of parking lots were often imperfect. The second challenge was getting the results from OpenCV into a format that was compatible with our website. Connecting our python program to a Wix website was difficult because our team was not super familiar with any of the languages and platforms that we choose to use. We also found that the concepts of connecting backend code to our website were difficult to understand.

## Accomplishments that we're proud of
We got OpenCV to detect whether parking spots are open or not. We also built a website using Wix Velo which none of us had experience with. Our team was mostly first-time hackathon attendees so we were pretty new at this. Finally, we are proud of our idea which we think is a practical business idea. 

## What's next for Parking Pal
We would like to connect the output from our python program to our website. After we connect the data we could display stats in more helpful ways. We would also like to implement both a commuter version and a business version of our website. The business version would use the parking lot data to better an organization while the commuter version would help drivers decide where and when to park.

## Resources Used
https://www.computervision.zone/courses/parking-space-counter/

