
#  **CS-465 Full Stack Development I**

![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white) ![Express.js](https://img.shields.io/badge/express.js-%23404d59.svg?style=for-the-badge&logo=express&logoColor=%2361DAFB) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white) ![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white) ![jQuery](https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white) ![Licence](https://img.shields.io/github/license/Ileriayo/markdown-badges?style=for-the-badge)

![logo](https://github.com/harshilkumar-jayswal/CS465-FullStack/assets/87956398/fb63922f-ecfe-4281-b9ed-5f42123295b3)


### Architecture

In my full stack project, I used different types of frontend development, including Express HTML, JavaScript, and a single-page application (SPA) built with Angular.

- Express HTML and JavaScript: Initially, I used Express to serve HTML pages along with JavaScript for client-side interactivity. This approach is straightforward and works well for server-side rendering where the server sends complete HTML pages to the client. It is simpler but can be less efficient as it requires full page reloads for navigation and updates.

- Single-Page Application (SPA): Later, I moved to an Angular-based SPA. SPAs load a single HTML page and dynamically update content as the user interacts with the app. This approach offers a smoother and faster user experience since only the necessary data is fetched and the page is updated without a full reload. SPAs are highly modular and maintainable, with clear separation between components and services.

For the backend, I used a NoSQL MongoDB database. MongoDB is a flexible, document-oriented database that allows for easy scaling and efficient handling of large amounts of unstructured data. It’s particularly suitable for applications with evolving schemas, where the data structure can change over time. The JSON-like documents in MongoDB also align well with the data exchange format used in modern web applications.

### Functionality

JSON (JavaScript Object Notation) is a lightweight data-interchange format that is easy for humans to read and write and easy for machines to parse and generate. Unlike JavaScript, which is a programming language used to create dynamic content on the web, JSON is simply a format for structuring data. JSON is language-independent but uses conventions familiar to programmers of the C family of languages.

In my full stack project, JSON played an important role in tying together the frontend and backend. The Angular frontend would send HTTP requests to the Express backend, and the backend would respond with JSON data. This data interchange allowed the frontend to dynamically update the UI based on the responses from the backend.

Throughout the development process, I refactored code to improve functionality and efficiency. For example, I created reusable UI components in Angular. These components encapsulated specific functionalities, such as displaying a list of trips or a navbar, making the code more modular and easier to maintain. The benefits of reusable UI components include reduced code duplication, easier debugging and testing, and improved consistency across the application.

### Testing

Testing a full stack application involves various methods, especially when dealing with API endpoints and security layers. Here’s what I learned:

- API Testing: Ensuring that the endpoints work as expected is critical. This involves sending requests to the API and verifying that the responses are correct. Tools like Postman can be used for manual testing.

- Endpoints: Each endpoint needs to be tested for correct handling of different HTTP methods (GET, POST, PUT, DELETE) and correct data validation. It’s important to test for edge cases and error handling to ensure robustness.

- Security Testing: With added layers of security, such as authentication and authorization, testing becomes more complex. It’s essential to verify that only authorized users can access certain endpoints and that sensitive data is protected. This involves testing with various user roles and ensuring that token-based authentication works correctly.

### Reflection

This course has been instrumental in helping me achieve my professional goals. It provided hands-on experience with building a full stack application, which is a highly valuable skill in today’s job market. I learned to effectively use Angular for frontend development and Express with MongoDB for backend development, understanding how to integrate these technologies to create a cohesive application.

The skills I’ve developed include:

- Frontend Development: Mastering Angular for building dynamic and responsive SPAs.
- Backend Development: Using Express and MongoDB to handle server-side logic and database interactions.
- API Development: Creating and testing RESTful APIs to connect the frontend and backend.
- Problem-Solving: Debugging and refactoring code to improve performance and maintainability.

These skills make me a more marketable candidate in the tech industry, where full stack development is a highly sought-after skill. The ability to develop and integrate both frontend and backend components will allow me to contribute effectively to any development team.

#### Credits
Programming by Harshilkumar Jayswal

Professor Brian West

Module 8-1 Portfolio Journal 

CS-465 Full Stack Development I @ SNHU
