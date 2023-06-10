# TikTok- Backend Assignment - 2023

![Tests](https://github.com/TikTokTechImmersion/assignment_demo_2023/actions/workflows/test.yml/badge.svg)

## Backend Instant Messaging System of 2023 TikTok Tech Immersion.
This README file provides an overview of the project setup, system architecture design, and project requirements for the "Backend Instant Messaging System" project.

## Project Setup
Install Golang on your system following the step-by-step guide provided for MacOS or Windows.

## System Architecture Design
The system architecture consists of the following components:

HTTP server: Handles HTTP requests and responses.

RPC server: Implements business logic in microservices.

Redis: High-performance in-memory store for message storage.


## Project Requirements
The project requires implementing the following API specifications:

Send Request: POST request to /api/send to send a message with sender, receiver, and text parameters.

Pull Request: GET request to /api/pull to retrieve messages from a chat room with chat, cursor, limit, and reverse parameters.


