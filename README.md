<img width="100%" src="BookStore/React-Native/bookstore/bookstore-3.png">

<h1> BookStoreApp - A book sharing social media app. </h1>

BookstoreApp is a modern mobile application developed using React Native and Expo, designed to offer users a seamless experience in discovering, managing, and interacting with a collection of books. Built with JavaScript on the frontend, it leverages Zustand for efficient and lightweight state management. The backend is powered by Express.js, with MongoDB serving as the database for storing and retrieving book data. The books are stored in a pdf links and is shared throughout the app where multiple users can access the resources of the books.

<!-- README.md Badge -->


<div align="center">
  <img src="https://cdn.iconscout.com/icon/free/png-256/free-react-logo-icon-download-in-svg-png-gif-file-formats--company-brand-world-logos-vol-4-pack-icons-282599.png?f=webp&w=256" style="width: 50px;"/>
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR9LjgzCpES-ZQDftN8oxb_7fe1xvpgnnzOND0STDv0B0Zq6cRK5pZu7wdUnn_6h-J5Jx0&usqp=CAU" style="width: 50px;" alt="Node.js Logo" />
  <img src="https://cdn-icons-png.freepik.com/512/5968/5968292.png" style="width: 50px;" alt="JavaScript Logo" />
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSITHn_TgjDyhdWvePNw0mveDrTUr00GLfv_Q&s" style="width: 50px;" alt="MongoDB Logo" />
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT5d-YG1OqK53sDiYDYTyrWOrJUOXgkm8ZJ_Q&s" style="width: 50px;" alt="Zustand Logo (assumed)" />
  <img width="50px" src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRgcmKD370zZ_gDhMVzMYuwJQfG_bndLTG-BQ&s" alt="Express.js Logo" />
</div>

<br>



<!-- Source Code Badge -->
<div align="center">

<!-- README.txt Badge -->
<a href="BookStore/React-Native/bookstore/readme.txt" target="_blank">
  <img src="https://img.shields.io/badge/README.txt-View-grey?style=for-the-badge&logo=markdown&logoColor=white" alt="README.txt Badge"></a>
  
  <a align="center" href="BookStore" target="_blank">
    <img src="https://img.shields.io/badge/Source%20Code-grey?style=for-the-badge&logo=github" alt="Source Code"></a>
  


<!-- PDF Badge -->
<a href="BookStore/React-Native/bookstore/New Doc 05-31-2025 20.25.pdf" target="_blank">
  <img src="https://img.shields.io/badge/PDF-View-grey?style=for-the-badge&logo=adobeacrobatreader&logoColor=white" alt="PDF Badge"></a>
  
</div>

## ✨ Features

- 📖 Browse an extensive list of books with detailed information  
- 🔎 Search and filter books by title, author, or genre  
- ⭐ Mark favorite books for easy access  
- 📝 Add personal notes for any book  
- 🗂️ Global state handling using Zustand  
- 🌐 Backend API integration for dynamic data  
- 📱 Cross-platform (Android + iOS) via Expo  
- ⚡ Smooth performance and clean UI


<table>
  <tr>
    <td valign="top">

  <h2>🔗 API Endpoints</h2>
      <table>
        <tr>
          <th>Method</th>
          <th>Endpoint</th>
          <th>Description</th>
        </tr>
        <tr>
          <td>GET</td>
          <td><code>/books</code></td>
          <td>Get all books</td>
        </tr>
        <tr>
          <td>GET</td>
          <td><code>/books/:id</code></td>
          <td>Get a specific book</td>
        </tr>
        <tr>
          <td>POST</td>
          <td><code>/books</code></td>
          <td>Add a new book</td>
        </tr>
        <tr>
          <td>PUT</td>
          <td><code>/books/:id</code></td>
          <td>Update a book</td>
        </tr>
        <tr>
          <td>DELETE</td>
          <td><code>/books/:id</code></td>
          <td>Delete a book</td>
        </tr>
      </table>

  </td>


  <td valign="top" style="padding-left: 30px;">
      <h2>🛠️ Tech Stack</h2>
      <table>
        <tr>
          <th>Frontend</th>
          <th>Backend</th>
        </tr>
        <tr>
          <td>React Native</td>
          <td>Express.js</td>
        </tr>
        <tr>
          <td>Expo</td>
          <td>Node.js</td>
        </tr>
        <tr>
          <td>JavaScript</td>
          <td>MongoDB</td>
        </tr>
        <tr>
          <td>Zustand</td>
          <td>Mongoose</td>
        </tr>
        <tr>
          <td>React Navigation</td>
          <td></td>
        </tr>
      </table>

   </td>
  </tr>
</table>


> [!IMPORTANT]
>
> **Error:**  
> - PDFs sometimes fail to load inside the mobile viewer with a **Network / CORS error**.
>
> **Cause:**  
> - Some book links were served over **HTTP** instead of **HTTPS**,  
> - or the server did not include proper CORS headers (`Access-Control-Allow-Origin`).
>
> **Solution:**  
> - Enforced **HTTPS links** for all book resources.  
> - Updated the Express server to include:
>   - `Access-Control-Allow-Origin: *`
>   - `Access-Control-Allow-Methods: GET`
> - Added validation to reject insecure PDF URLs in the database.


## Project Overview

<img width="100%" src="BookStore/React-Native/bookstore/bookstore-1.png">
<img width="100%" src="https://github.com/Jostar-Foundation/BookStore/blob/main/assets/bs-1.png">
<img width="100%" src="assets/bs-2.png">

---

<div align="center">
  ⚠️ This Repository is uniquely designed by <b>@JoshuaThadi.</b> 
</div>
