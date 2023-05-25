---
title: API Documentation
date: 2023-05-29
eleventyNavigation:
  key: API 
  order: 4
  title: API
---

# API Documentation

ViiM.world's functionality is exposed through a collection of APIs that allow users to interact with ViiM Objects and Events, manipulate their personal lockers, and navigate the platform. This section provides a high-level overview of our API endpoints and what they offer. Detailed technical documentation will be provided separately.

## ViiM Object API

The ViiM Object API allows users to create, read, update, and delete (CRUD) their ViiM Objects. Here's a brief description of the core endpoints:

- **POST /objects**: Creates a new ViiM Object associated with the user's Locker ID.
- **GET /objects/{id}**: Retrieves the details of a specified ViiM Object.
- **PUT /objects/{id}**: Updates the details of a specified ViiM Object.
- **DELETE /objects/{id}**: Deletes a specified ViiM Object.

## ViiM Event API

The ViiM Event API provides users with the tools to manage the events associated with their ViiM Objects:

- **POST /events**: Creates a new ViiM Event associated with a ViiM Object.
- **GET /events/{id}**: Retrieves the details of a specified ViiM Event.
- **PUT /events/{id}**: Updates the details of a specified ViiM Event.
- **DELETE /events/{id}**: Deletes a specified ViiM Event.

## Future API Developments

As ViiM.world continues to grow, we plan to introduce more APIs to improve user interaction and platform functionality. Here are a few ideas:

- **ViiM Path API**: This API would allow users to create and manage ViiM Paths, potentially enabling guided tours or navigational aids in the virtual overlay of the real world.
  
- **ViiM Transaction API**: As ViiM.world integrates peer-to-peer payments, a Transaction API would allow users to initiate and manage these transactions securely.
  
- **ViiM Challenge API**: To add a gamification aspect to the platform, a Challenge API could manage user-created challenges and keep track of user progress and achievements.

Our API design philosophy revolves around providing users with the tools they need to fully explore and interact with the ViiM.world, and we're excited to see how these tools will evolve as the platform grows.
