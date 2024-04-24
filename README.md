**Project Title: Family & Friends Chronicle**

**Description:**
The Family & Friends Chronicle is a dynamic web application developed using Spring MVC, Thymeleaf, MongoDB, Google Charts, Spring Security, JSON Web Token (JWT), Swagger, and JavaScript. It serves as a comprehensive platform for users to record and keep track of family and friend history, events, travels, bucket list experiences, and more. While not a social networking platform, it provides a centralized repository for storing and sharing memories, photos, videos, and comments among family and friends.

**Key Components:**
- **User Registration:** Users can create accounts with unique credentials and access rights (e.g., coordinator or regular member).
- **User Login:** Secure login functionality with options for password recovery in case of forgotten credentials.
- **Access Rights Management:** Coordinators can manage access rights, adding new members or adjusting permissions as needed.
- **Family Ancestry:** Organizes family members' pictures and hierarchy, allowing for the addition of branches and sub-branches.
- **Friend History:** Records past and current friends' information, including text, video, or pictures.
- **Events:** Allows users to post pictures, comments, and videos from various events such as weddings or graduations.
- **Travel Memories:** Enables users to share pictures, comments, and videos from different trips and adventures.
- **Just Happened:** Provides a space to share current events with text, video, photos, and links.
- **Bucket List:** Allows users to list experiences or achievements they hope to accomplish, marking them as complete, in progress, or to be completed.
- **Dynamic Content Update:** Authorized users can easily post new content (videos, text, or photos) without requiring coding knowledge.

**Technologies Used:**
- Spring MVC: Web application framework for building Java-based web applications.
- Thymeleaf: Server-side Java template engine for dynamic content generation.
- MongoDB: NoSQL database for flexible and scalable data storage.
- Google Charts: Visualization library for creating interactive charts and graphs.
- Spring Security: Framework for securing Java applications.
- JSON Web Token (JWT): Secure method for transmitting information between parties.
- Swagger: API documentation tool for documenting and testing APIs.
- JavaScript: Programming language for adding interactivity and dynamic content to web pages.


**Execution Process:**

make sure java 17, maven is installed and set up. Enter into the project directory and run the spring application.
```bash
  mvn spring-boot:run
  ```
Open browser window and in each one go to the below url for exploring the project.

http://localhost:8080/homePage 

- try register, login and explore features of project
