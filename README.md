# Brain-Brawl

## Problem Statement:
In an era where educational institutions seek advanced and seamless methods for academic assessments, a challenge persists in providing user-friendly, real-time evaluation platforms for universities and colleges. The current systems often lack interactive features and fail to deliver an engaging 1v1 contest-based assessment experience. The absence of such an effective evaluation platform hinders the enhancement of learning experiences and the achievement of academic excellence within educational institutions. This prompts the need to address the deficiency by developing an innovative, comprehensive solution that facilitates real-time, user-friendly evaluations while fostering interactive 1v1 contest-based assessments, aligning with the project's vision to empower educational institutions and promote enhanced learning experiences.

## Solution : 
Welcome to the Brain-Brawl Django REST application repository! This backend application is designed to support the Flutter-based "Brain-Brawl" application, where students from different universities can compete in knockout competitions involving assessments that challenge both accuracy and speed.

## About the Project : 
We provide a 1-on-1 learning experience in knockout series form, whereas, when you start a game you are matched with a player who also joined under the same subject as you did, and from there you both get to battle each other by answering assessments that require both accuracy and speed to win. Winners will rise on the leaderboard until there is only one winner among all the universities participating in the knockout competition.

## Application Overview

The Brain-Brawl application's main functionality is to facilitate knockout competitions among students from different universities. Here's a brief overview of how it works:

- When you start a knockout competition, you are matched with a student from another university who also joined under the same subject.
- You and your opponent get to battle each other by answering assessments within 30-45 seconds, depending on the question's complexity.
- The competition requires both accuracy and speed to win.
- The winners will rise on the leaderboard, and the competition continues until there is only one winner among all the universities participating in the knockout competition.

## Backend Deployment

The backend of Brain-Brawl is deployed on the Render platform. You can access it at [Backend Base URL](https://hackcbs-backend.onrender.com/).

## Frontend Deployment

The frontend of Brain-Brawl is deployed on the Firebase platform. You can access it at [Live Web App](https://brainbrawl-3268e.web.app).

## Figma Design Document

The design of BrainBrawl is published at Figma. You can access it at [Figma Link](https://www.figma.com/design/hWSQ276GrtnrQfDn5Nguof/HackCbs-7-Brain_Brawl?node-id=0-1&t=NYwA9EoAVE8uoiBC-1).

## Presentation for BrainBrawl is available at [Canva Link](https://www.canva.com/design/DAGV-0z1-Vs/Ijt0aEiSeATno8YV02Mm8w/view?utm_content=DAGV-0z1-Vs&utm_campaign=designshare&utm_medium=link&utm_source=editor).

## API Endpoints

The following are the available API endpoints of the Brain-Brawl application:

1. **admin**: Panel to manage the entire application.
2. **competition**: Allows you to add, modify, or delete competitions.
3. **admin/question/question**: Used to manage questions, including adding, deleting, or modifying them.
4. **participantsview**: Displays all participants with their IDs and levels.
5. **users**: Provides functionality to add, modify, or delete users on the platform.
6. **register recruiters**: Allows contest hosting organizations to register on the platform.


## Getting Started

To set up the Brain-Brawl application locally, follow these steps:

```bash
# Clone the repository to your local machine:
git clone https://github.com/Dhruv-IGI/BrainBrawl-Backend
cd Brain-Brawl

# Create a virtual environment and install the required dependencies:
python -m venv venv
source venv/bin/activate  # On Windows, use: venv\Scripts\activate
pip install -r requirements.txt

# Migrate the database:
python manage.py migrate

# Create a superuser for admin access:
python manage.py createsuperuser

# Start the development server:
python manage.py runserver
```
## Frontend Repo Link: 
