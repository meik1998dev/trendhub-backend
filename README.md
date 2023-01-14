# Trend Hub

Trend Hub is a social network web app that allows users to create posts, comments, and chat with each other in real-time. It also includes features such as followers, hashtags, and photos.

## Services

Trend Hub is built using a microservices architecture, with the following services:

1. **User Authentication and Authorization Service**: This service handles user registration, login, and logout, as well as user roles and permissions. It uses MongoDB as its database.

2. **User Profile Service**: This service handles user profiles, including information about themselves and their interests. It also includes features such as friend lists and followers. It uses PostgresSQL as its database.

3. **Post and Comments Service**: This service handles the creation and management of posts and comments. It also includes features such as hashtags and tagging other users. It uses PostgresSQL as its database.

4. **Real-time Messaging Service**: This service handles real-time messaging between users. It uses WebSockets for real-time communication and MongoDB as its database.

5. **Notifications Service**: This service handles notifications for users when they receive a new message, are mentioned in a post, or receive a new friend request MongoDB as its database.

6. **Groups Service**: This service handles the creation and management of groups centered around a particular topic or interest. It also includes features such as group pages and the ability for users to post and comment on content within the group. It uses PostgresSQL as its database.

7. **API Gateway**: This service handles routing and proxying of requests to the different services. It uses NestJS as a framework.
