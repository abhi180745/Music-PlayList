# Music-PlayList
🎵 Music Playlist Manager Using Doubly Linked List

📌 Project Description

The Music Playlist Manager is a menu-driven C++ application developed using the concept of a Doubly Linked List.

It allows users to manage a music playlist by adding songs, deleting songs, displaying the playlist, and navigating between songs.

Each song contains a song title and artist name. The doubly linked list allows traversal in both forward and backward directions using "next" and "prev" pointers.

🎯 Objectives

- To understand the concept of Doubly Linked Lists.
- To perform insertion and deletion operations.
- To implement forward and backward traversal.
- To understand pointer manipulation and dynamic memory allocation.
- To develop a real-world application using Data Structures.

✨ Features

1. Add Song – Add a new song with its title and artist name.
2. Delete Song – Remove a song from the playlist using its title.
3. Display Playlist – Display all songs in forward order.
4. Display Playlist in Reverse – Display songs in reverse order.
5. Play Current Song – Play the currently selected song.
6. Play Next Song – Navigate to the next song.
7. Play Previous Song – Navigate to the previous song.
8. Play Complete Playlist – Display all songs as they are played.
9. Repeat All – Repeat the complete playlist a specified number of times.
10. Show Current Song – Display the currently selected song.
11. Exit – Exit the application.

🛠️ Technologies Used

- Programming Language: C++
- Data Structure: Doubly Linked List
- Concepts: Classes, Objects, Pointers, Dynamic Memory Allocation, Recursion-free Traversal
- Header Files: iostream, string

🧠 Data Structure Used

Doubly Linked List

A Doubly Linked List is a linear data structure in which each node contains three parts:

- Song title and artist name (data)
- Pointer to the next node ("next")
- Pointer to the previous node ("prev")

Node Structure:

+----------+----------+----------+
|   prev   |   Data   |   next   |
+----------+----------+----------+

Playlist Representation:

NULL <- [Song 1] <-> [Song 2] <-> [Song 3] -> NULL

This structure allows the user to navigate both forward and backward through the playlist.

📂 Project Structure

Music-Playlist-Manager/
│
├── MusicPlaylist.cpp
└── README.md

🚀 How to Run the Project

Step 1: Clone the Repository

git clone YOUR_REPOSITORY_URL

Step 2: Open the Project Folder

cd Music-Playlist-Manager

Step 3: Compile the Program

g++ MusicPlaylist.cpp -o playlist

Step 4: Run the Program

Windows:

playlist.exe

Linux / macOS:

./playlist

💻 Sample Output

===== MUSIC PLAYLIST MANAGER =====

1. Add Song
2. Delete Song
3. Display Playlist
4. Display Playlist in Reverse
5. Play Current Song
6. Play Next Song
7. Play Previous Song
8. Play Complete Playlist
9. Repeat All
10. Show Current Song
11. Exit

Enter your choice: 1

Enter Song Title: Kesariya
Enter Artist Name: Arijit Singh

Song added successfully

Sample Playlist

Playlist:

Give Me Some Sunshine - Suraj Jagan
Kesariya - Arijit Singh
Perfect - Ed Sheeran

⏱️ Time Complexity

Operation| Time Complexity
Add Song| O(n)
Delete Song| O(n)
Display Playlist| O(n)
Reverse Display| O(n)
Play Next Song| O(1)
Play Previous Song| O(1)
Show Current Song| O(1)
Play Complete Playlist| O(n)

Here, "n" represents the total number of songs in the playlist.

📚 Learning Outcomes

Through this project, I learned:

- How Doubly Linked Lists work.
- How to create and manage nodes dynamically.
- How to insert and delete nodes.
- How to perform forward and backward traversal.
- How to use pointers to navigate between songs.
- How data structures are applied in real-world applications.

👨‍💻 Author

Abhijit Bargal

B.Tech – Electronics and Computer Engineering

GitHub: "abhi180745" (https://github.com/abhi180745)

---

⭐ If you find this project useful, don't forget to give it a star!

Thank You! 🎵