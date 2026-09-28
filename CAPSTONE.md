# Capstone Proposal — IT Help Desk Ticket Manager

## Problem

IT support teams often receive multiple technical issues at the same time. Without an organized system, requests can be forgotten, handled out of order, or difficult to track. My capstone project will create an **IT Help Desk Ticket Manager** that allows support requests to be entered, organized, processed, and tracked until they are completed.

## Data Structure

The main data structure used in this project will be a **Queue**.

A queue follows the **FIFO — First In, First Out** principle. When a new support ticket is submitted, it is added to the end of the queue. The oldest unresolved ticket is handled first.

This matches how a basic help desk normally processes requests in the order they are received.

## Why a Queue?

An obvious alternative would be a **Stack**, which follows the LIFO — Last In, First Out principle.

A stack would not be appropriate because the newest support request would be handled before older requests. This could cause older tickets to remain unresolved for a long time.

A queue is a better choice because it maintains the order in which tickets were submitted and provides a predictable workflow for processing support requests.

## Features to Deliver by Module 8

By Module 8, the application will include four main features:

1. **Create Ticket** — Users can enter a technical issue with information such as ticket ID, user name, issue description, and priority.

2. **View Ticket Queue** — Display all unresolved tickets in the order they are waiting to be handled.

3. **Process Next Ticket** — Remove the ticket at the front of the queue when an IT technician begins or completes the request.

4. **Ticket Status Tracking** — Track whether each ticket is waiting, in progress, or completed.

The final project will demonstrate how a queue can be used in a practical IT support environment while providing a simple system for managing technical support requests.
