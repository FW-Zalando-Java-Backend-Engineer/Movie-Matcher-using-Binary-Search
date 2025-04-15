## 🎓 **Java Assignment: Movie Matcher using Binary Search**

### 📝 Assignment Title:
**🎬 "Movie Matcher": Find All Movies with a Given Rating Using Binary Search**

---

### 🧑‍🏫 **Objective**

Students will:
- Practice **arrays** and **binary search** in Java.
- Work with **custom objects** (`Movie` class).
- Use **Scanner** for user input.
- Learn how to find **multiple matches** efficiently using **Binary Search + Expansion**.
- Implement clean, reusable code with **methods**.

---

### 🎯 **The Scenario**

You are building a mini tool for a movie recommendation system.

The platform has a **sorted list of movies** by **rating** (e.g., 1 to 5 stars).

A user enters their **preferred rating** (e.g., 4), and your system will return **all movies** with that exact rating.

---

### 🛠️ **Requirements**

1. Create a `Movie` class with:
   - `String title`
   - `int rating` (1 to 5)

2. Create a sorted array of `Movie` objects (sorted by rating).

3. Accept user input via `Scanner`:
   - Prompt: `"Enter desired movie rating (1 to 5):"`

4. Use **Binary Search** to find one movie with that rating.

5. Then use **left and right expansion** to find **all other matches**.

6. Display all matched movie titles or a message if none found.

---

### ✅ Sample Output

```
Enter desired movie rating (1 to 5): 4

🎬 Movies with 4-star rating:
 - The Prestige
 - Interstellar
 - Inception
```

---

### 🔍 Bonus Challenge (Optional)

- Ask user for **minimum rating**, and return all movies **with rating >= input**.
- Sort unsorted movie list with **Bubble Sort**, then apply search.

---

### 📦 Deliverables

- Java file: `MovieMatcher.java`
- Method: `List<Movie> findMoviesByRating(Movie[] movies, int rating)`
- Output clearly listing matches or "No results found"

---

### 🧠 Concepts Practiced

- Arrays and custom classes
- Binary search
- Expansion for multiple matches
- Scanner for user input
- Clean code with modular methods

---

### ✏️ Teacher Note:

This reinforces what we covered in the **Health Diagnosis Simulator**, while using a **fun and modern theme** (movies). Great for engagement and retention.


