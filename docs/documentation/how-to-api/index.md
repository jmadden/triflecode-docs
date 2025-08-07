---
title: How To API
excerpt: >-
  This page will help you get started with Triflecode Docs. You'll be up and
  running in a jiffy!
hidden: false
link:
  new_tab: false
---

# Understanding REST APIs: A Basic Instruction Manual

This guide will help you understand the fundamentals of REST APIs and how to interact with them.

## What is a REST API?

A REST (Representational State Transfer) API is a set of rules that allows different software applications to communicate with each other over the internet. It's a way for a client (like your web browser or a mobile app) to request information or perform actions on a server.

## How Do REST APIs Work?

REST APIs use standard HTTP methods to perform operations on resources. A "resource" can be any piece of information or data that the API provides or manipulates. Each resource is identified by a unique URL (Uniform Resource Locator).

When you interact with a REST API, you are essentially sending a request to a specific URL, telling the server what you want to do with the resource at that URL, and then receiving a response from the server.

## Common HTTP Methods

Here are some of the most common HTTP methods used in REST APIs:

*   **GET**: Used to retrieve data from a server. It should not have any side effects on the server's data.
*   **POST**: Used to send new data to the server to create a new resource.
*   **PUT**: Used to update an existing resource with new data. It replaces the entire resource.
*   **PATCH**: Used to partially update an existing resource. It applies partial modifications to a resource.
*   **DELETE**: Used to remove a resource from the server.

## Anatomy of a REST API Call

A typical REST API call consists of:

1.  **Endpoint URL**: The unique address of the resource you want to interact with.
2.  **HTTP Method**: The action you want to perform (GET, POST, PUT, DELETE, etc.).
3.  **Headers**: Additional information sent with the request, such as authentication tokens, content type, etc.
4.  **Body (optional)**: Data sent to the server, typically used with POST, PUT, or PATCH requests.

## Example: Retrieving Data

Let's say you want to get a list of products from an e-commerce API. You might use a `GET` request to an endpoint like `https://api.example.com/products`.

**Request:**

```
GET /products HTTP/1.1
Host: api.example.com
Authorization: Bearer YOUR_API_KEY
```

**Response (simplified):**

```json
HTTP/1.1 200 OK
Content-Type: application/json

[
  {
    "id": 1,
    "name": "Laptop",
    "price": 1200
  },
  {
    "id": 2,
    "name": "Mouse",
    "price": 25
  }
]
```

In this example:

*   We used the `GET` method to retrieve data.
*   The endpoint was `/products`.
*   We included an `Authorization` header with an API key for authentication.
*   The server responded with a `200 OK` status and a JSON array of product objects.

This is just a basic introduction. REST APIs can be much more complex, involving various authentication methods, error handling, and advanced data structures. However, understanding these core concepts will provide a strong foundation for working with them.
