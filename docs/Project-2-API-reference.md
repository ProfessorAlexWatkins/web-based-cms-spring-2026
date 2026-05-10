---
title: API overview and authentication
status: draft
audience: Development team
tags: [design, development]
---

<h2>API Overview:</h2>
This is a new feature that let's users change their profile settings to dark mode, light mode, or system, and save this preference to the users profile. The user will recceive a notification that their update has been sucessfully or unsucessfully saved. 

Endpoint: `POST /api/users/preferences`
User can sucessfully save their profile settings as dark, light, or system mode. 

<h2>Authentication:</h2>

Authentication required: Yes
Authorization: Bearer <your_token>

<h2>Request Details: </h2>

| Request       | User experience |
| ------------- | ------------- |
| Slider button option 1  | Dark mode (boolean: true/fasle)  |
| Slider button option 2  | Light mode (boolean: true/false)  |
| Slider button option 3  | System mode (boolean:true/false)  |

<h2>Code Samples:</h2>


<h2>Visual Logic:</h2>
