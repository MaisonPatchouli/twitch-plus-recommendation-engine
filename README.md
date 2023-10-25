# Twitch+ Project

**Demo**: [Twitch demo](https://ysnrh2mxp3.us-east-2.awsapprunner.com)

In the domain of live streaming and video content, the significance of recommendation systems is growing rapidly. To address this demand and enhance my skills, I initiated the "Twitch+" project, aiming to optimize the recommendation experience on Twitch-related platforms.

## Backend
- Developed using **Spring Boot** as the backend framework.
- Designed multiple APIs including user authentication, content recommendation, and search functions.
- The three APIs work in synergy, prioritizing results that match a logged-in user's history and interests.
- All APIs are RESTful in design and interact with the Twitch API to ensure real-time accuracy of data.

## Frontend
- Built the user interface using **React**.
- Used **Ant Design** as the UI library.
- Created an intuitive and user-friendly interface, designed to offer users a seamless browsing experience. This allows users to effortlessly register, log in, view recommended streams, and search for streams.

## Database
- Implemented using **MySQL** to ensure efficient big data processing and query speeds.
- The main tables include users, browsing history, and live streams.
- Although the data currently processed is in the thousands, the design considers future expansion needs of up to millions of records.

By integrating **Spring Security** and a self-developed recommendation algorithm, I ensured data security and provided users with highly relevant content recommendations.

## Future Plans
- Continuously refine the recommendation algorithm.
- Enhance the user interface.
- Introduce features like reviews and subscriptions to further enrich the functionality and user experience of Twitch+.
