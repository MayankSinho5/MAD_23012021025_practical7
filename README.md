# MAD Practical 7 (Mobile Application Development)

This Android application (Practical 7) is part of the Mobile Application Development course.  
It demonstrates how to fetch data from a remote JSON API, parse the response, display the data in a `RecyclerView`, and store/retrieve it in a local SQLite database.

---

## 📌 AIM  
To build an Android app that retrieves data in JSON format from a web API, displays it, and persists it locally using SQLite.

---

## Features

- Fetch data from a remote JSON web service.  
- Parse JSON response into data objects.  
- Display the parsed data in a `RecyclerView`.  
- Save the fetched data into a local SQLite database.  
- Load data from the SQLite database on demand.  
- Delete individual items (records) from the local database.  
- Use of modern Android architecture patterns (if applicable).  

---

## How It Works / How to Use

1. **Launch the App**  
   When you open the app, it first loads data from the local SQLite database (if present).  

2. **Fetch from Network**  
   - Tap on the toolbar/menu icon (or button) labeled “Network” (or similar) to fetch fresh JSON data from the remote API.  
   - The app sends a network request, retrieves JSON, parses it, displays it in the `RecyclerView`, and stores the parsed data into SQLite.  

3. **Load from SQLite**  
   - Tap on the “Local DB” (or similar) icon/menu option to load data stored in your device’s SQLite database.  
   - This is useful to view previously fetched data offline.

4. **Delete a Record**  
   - Each item in the list has a delete (trash) icon.  
   - Tap the icon to remove that record from both the RecyclerView and the SQLite database.

---

## Output:
<table>
  <tr>
    <th>White Theme:</th>
    <th>Deleting Record:</th>
    <th>Fetch Details:</th>
  </tr>
  <tr>
    <td><img width="376" height="830" alt="image" src="https://github.com/user-attachments/assets/2d3f3bd0-f317-47cc-b527-85e020581226" />
</td>
    <td><img width="372" height="816" alt="image" src="https://github.com/user-attachments/assets/961a4650-f9eb-4b69-99fa-e4b5c446d6d2" />
</td>
    <td><img width="369" height="825" alt="image" src="https://github.com/user-attachments/assets/604a0718-a626-4480-b556-f671b0ca980a" />
</td>
  </tr>
</table>

