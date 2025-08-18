# Hotel Room Allotment

A simple, browser-based module for hotel room assignment using HTML, CSS, and JavaScript. Allows staff to assign rooms automatically with guest details, check-in dates, and room types.

---

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [Demo](#demo)  
- [Usage](#usage)  
- [Code Structure](#code-structure)  
- [Styling](#styling)  
- [Extending the Module](#extending-the-module)  
- [Contributing](#contributing)  
- [License](#license)  

---

## Overview

This lightweight web module enables quick room allotment. Users fill out a form with a guest’s name, check-in date, and room type. Upon submission, the module auto-generates a room number, displays the assigned room in a dynamic table, and resets the form for new entries.

---

## Features

- **Guest Details Capture**: Input guest name, check-in date, and select room type (Single, Double, Suite).  
- **Automated Room Numbering**: Auto-incrementing room numbers starting from 101.  
- **Dynamic Room Table**: Displays all allotted rooms in a responsive table.  
- **Form Validation**: Alerts are triggered if any field is incomplete.  
- **Navigation Links**: Quick access to related pages—Check-in Details and Contact Page.

---

## Demo

To try it locally:

1. Save the HTML code as `room-allotment.html`.
2. Open it in your preferred web browser.
3. Fill in the form and click **Allot Room** to see it in action!

---

## Usage

1. Enter the **Guest Name**.
2. Select the **Check-In Date**.
3. Choose a **Room Type** from the dropdown.
4. Click **Allot Room**.
5. Observe the new entry appear in the **Allotted Rooms** list.
6. The form resets automatically for the next entry.

---

## Code Structure

```text
./room-allotment.html
