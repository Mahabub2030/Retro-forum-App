# Retro Forum

A modern yet retro-themed forum built with **JavaScript, Tailwind CSS, and ES6 APIs**. This project provides a fully functional discussion platform with an old-school aesthetic, utilizing modern web technologies.

## Features

- 🎨 **Retro UI Design** - Styled with Tailwind CSS for a nostalgic look and feel.
- ⚡ **ES6 Modules** - Uses modern JavaScript features for clean, efficient code.
- 🔄 **API Integration** - Fetch and display forum posts dynamically.
- 🔍 **Search Functionality** - Easily find discussions using a built-in search feature.
- ✍️ **Post & Comment System** - Users can create posts and leave comments.
- 📱 **Responsive Design** - Optimized for desktop and mobile devices.

## Tech Stack

- **Frontend:** JavaScript (ES6+), Tailwind CSS
- **Backend API:** Mock API (JSONPlaceholder or Custom API)

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/retro-forum.git
   cd retro-forum
   ```
2. **Open `index.html` in a browser** or use a local server:
   ```bash
   npx live-server
   ```
3. **Modify API endpoints** in `config.js` if needed.

## API Usage

- Fetch posts:
  ```javascript
  fetch('https://jsonplaceholder.typicode.com/posts')
    .then(response => response.json())
    .then(data => console.log(data));
  ```
- Submit a new post:
  ```javascript
  fetch('https://jsonplaceholder.typicode.com/posts', {
    method: 'POST',
    body: JSON.stringify({ title: 'New Post', body: 'This is a retro post!' }),
    headers: { 'Content-Type': 'application/json' }
  });
  ```

## Contributing

1. Fork the repository 🍴
2. Create a new branch (`feature-branch`) 🌿
3. Commit changes (`git commit -m 'Added new feature'`) 🔥
4. Push to the branch (`git push origin feature-branch`) 🚀
5. Open a **Pull Request** 🛠️

## License

This project is licensed under the **MIT License**.

---

Happy Coding! 🚀