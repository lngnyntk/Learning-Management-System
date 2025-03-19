# OpenCourse
## Struktur Website
### Index / Home
- Login

### Header 
- h3 OpenCourse
- input-text Searh
- a
    - Dashboard
    - Lesson
    - Forum
    - Profile
    - Notification
    - Logout

### Dashboard
- Mini-profile
- Lesson
- Forum
- Progress

### Search
- Filter

### Lesson
- Register
- My Lesson
- Progress

### Forum
- Redirect to discord

### Profile
- Name
- Status
- Social Media
- Progress

## Color
    :root {
    --Background: rgb(246, 248, 213);
    --Primary: rgb(33, 133, 213);
    --Secondary: rgb(52, 140, 212);
    --Text: Black;
    }

## Font
### Menggunakan Google Font dari https://fonts.google.com/
### Poppins (taruh di header) 
    <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');
    </style>

## Cara Penggunaan Dasar
        .poppins-regular {
    font-family: "Poppins", sans-serif;
    font-weight: 400;
    font-style: normal;
    }

## Icon
### Menggunakan Feather Icon dari https://feathericons.com
### Cara Penggunaan:
### 1. Tulis di head
    <script src="/src/feather.js"></script> 
### 2. Tulis ditempat yang mau digunakan
    <i data-feather="github"></i>
### 3. Tulis di body
    <script>feather.replace();</script>
