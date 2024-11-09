# URL Shortener Project

Welcome to my URL shortener project! This is my first backend project built using **Node.js**, **Express**, and **MongoDB**.

## Overview

This project provides a simple and efficient way to shorten long URLs into more manageable and shareable links. With this application, you can easily generate short URLs for any long URL, making it easier to share links, especially on platforms with character limits like Twitter.

## Features

- **Shorten URLs**: Quickly shorten long URLs into shorter, more manageable links.
- **Customizable URLs**: Optionally provide a custom alias for your shortened URL.
- **Statistics**: Track basic statistics, such as the number of times a shortened URL has been accessed.
- **Secure**: Uses MongoDB for data storage and Express for handling HTTP requests, ensuring security and reliability.

## Usage

1. Send a **POST request** to the `/shorten` endpoint with a JSON payload containing the long URL you want to shorten.
   
2. Optionally, you can provide a custom alias for your shortened URL.

3. The server will respond with a shortened URL.

4. Use the shortened URL to access the original long URL.

## Tech Stack

- **Node.js**: JavaScript runtime for building scalable server-side applications.
- **Express**: Web framework for handling HTTP requests and routing.
- **MongoDB**: Database for storing URLs and statistics securely.

---


