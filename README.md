## What is MRR
MRR specializes in industrial drone technology that eliminates the need for specialized drone operators. Their sophisticated software enables drones to autonomously follow user-designated flight paths. The primary function of these drones is to capture extensive imagery for 3D modeling applications, which supports various services such as precise distance measurements and detailed inspections of structures like rooftops and roadways.


Figure 1<img width="571" alt="Screenshot 2025-03-02 at 14 15 44" src="https://github.com/user-attachments/assets/4a9edd66-bc22-40e5-a707-ad211f1987d3" /> 

Figure 2<img width="571" alt="Screenshot 2025-03-02 at 14 15 44" src="https://github.com/user-attachments/assets/917b2c57-8f7d-409c-9f1b-0716b613cbe7" />


## My role in the project 

During the seventh semester of my ICT studies, I contributed to the development of MRR's drone platform, which serves as the central hub for drone data management and control. The platform utilizes C# .NET for backend operations and React.js for the frontend interface. My responsibilities included resolving existing technical issues and implementing new features to enhance user experience and mission performance.

### Task 1 - Marketplace
 
The objective of this assignment was to improve the "Marketpalce" functionality by implementing the ability to add new applications. These applications provide supplementary functionality during operations, when initiating a mission, users can select specific applications to augment drone capabilities. The applications can include for example specialized AI models designed for particular detection tasks, such as identifying waste materials or corrosion during inspection missions.
My task involved developing a user-friendly interface where admins can enter an app's name, description, and upload an image. This data is then passed to the back-end, which manages the process of storing the new app information in the database. The end goal was to ensure that new app entries could be seamlessly integrated into the marketplace with minimal user effort.
In figure 3 you can see the final working version of first task



https://github.com/user-attachments/assets/b9310575-ed35-4343-a447-0a231fea8411



###Task 2 - Progressbar


The project addresses a critical gap in mission management where users have no way to monitor the progress and current stage of ongoing missions. Additionally, there is no mechanism to verify whether mission-related images had been successfully uploaded to cloud storage, creating uncertainty around data completeness and availability.

The solution needed to provide real-time visibility into both mission progression and data management aspects, enabling stakeholders to track mission stages and confirm the successful storage of all mission-related assets. That is how the progress bar is going to solve this problem. By providing stages of the mission which are going to be dynamically updated based on the progress of the drone.  

In the video you can see the platform on the left with the progressbar on the bottom of the map and on the left there is a minecraft environment where we tested the dornes performance since the phisical drona was not always available for us to test new code implementations


https://github.com/user-attachments/assets/b19f348b-31d0-44b1-8af3-5fbd76bcbb41


