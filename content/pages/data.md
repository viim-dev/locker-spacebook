---
title: ViiM Objects and Events
date: 2023-05-27
eleventyNavigation:
  key: Data 
  order: 2
  title: Data
---

# ViiM Objects and Events

At the heart of the ViiM.world platform are the ViiM Objects and Events. These entities are representative of the physical world, offering a seamless blend between reality and the digital realm. The data structure for these objects and events is flexible and scalable, allowing for future expansion of their properties and capabilities.

## ViiM Objects

ViiM Objects are virtual entities that correlate to real-world objects. The data structure for these objects includes:

- **Object ID**: A unique identifier for each object.
- **Name**: The name of the object.
- **Description**: A brief summary of the object.
- **Location**: The geographical location of the object in the real world.
- **Owner (Locker ID)**: The owner of the object, linked via the Locker ID.
- **Access Control List**: Defines the users who can interact with the object and how.

## ViiM Events

ViiM Events are interactions or occurrences associated with the objects. The data structure for these events includes:

- **Event ID**: A unique identifier for each event.
- **Name**: The name of the event.
- **Description**: A brief summary of the event.
- **Associated Object ID**: The ID of the object with which the event is associated.
- **Event Script**: The script or action that gets triggered when the event occurs.

## Future Data Types

As ViiM.world evolves, more data types could be introduced to enhance the functionality and user experience of the platform. Here are a few examples:

- **ViiM Paths**: Routes or trajectories in the mixed reality environment, potentially useful for creating tours or guides.
- **ViiM Actions**: Specific actions that users can perform on objects or events, such as initiating a peer-to-peer transaction.
- **ViiM Challenges**: Tasks or missions that users can complete in the ViiM.world, adding a gamification element to the platform.
- **ViiM Scenes**: Collections of objects and events that together form a larger narrative or setting, providing a more immersive experience.
