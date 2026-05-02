---
title: api-reference
date: 2026-04-21
tags: [API overview, Theme]
layout: post
---

This API allows users to customize their display theme based on their preference, with options for light, dark, or system mode.

For authentication, a bearer token is required.

The endpoint should follow this format: POST /api/v2/users/preferences

If it was successful the response should provide a "timestamp" and "status", if there is a problem it should provide a return error: "Invalid theme selected."

If status is successful the JSON block should look like:
{
  "status": "success",
  "message": "Resource created successfully",
  "data": {
    "id": "12345",
    "name": "Sample Item",
    "created_at": "2026-04-29T12:34:56Z"
  }
}

If there is an error the JSON will look like: 
{
  "status": "error",
  "message": "Invalid request data",
  "errors": [
    {
      "field": "name",
      "issue": "Name is required"
    },
    {
      "field": "email",
      "issue": "Invalid email format"
    }
  ]
}


<img width="1172" height="1215" alt="image" src="https://github.com/user-attachments/assets/fea6ef41-ff66-4292-b28f-f95c6d6ffb92" />

  
