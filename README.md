<style>
  .page-container {
    display: flex;
    min-height: 100vh;
    font-family: Arial, sans-serif;
  }

  .sidebar {
    width: 280px;
    padding: 40px 24px;
    border-right: 1px solid #e5e5e5;
    text-align: center;
  }

  .profile-img {
    width: 180px;
    height: 180px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 20px;
  }

  .name {
    font-size: 26px;
    font-weight: 700;
    margin: 10px 0 6px;
  }

  .status {
    font-size: 16px;
    color: #666;
    margin: 0;
  }

  .main-content {
    flex: 1;
    padding: 50px 60px;
  }

  .main-content h1 {
    margin-top: 0;
  }

  @media (max-width: 768px) {
    .page-container {
      flex-direction: column;
    }

    .sidebar {
      width: auto;
      border-right: none;
      border-bottom: 1px solid #e5e5e5;
    }

    .main-content {
      padding: 32px 24px;
    }
  }
</style>

<div class="page-container">

  <aside class="sidebar">
    <img src="assets/profile.jpg" alt="Profile photo" class="profile-img">

```
<h2 class="name">Seungchae Na</h2>
<p class="status">Ajou University</p>
```

  </aside>

  <main class="main-content">

# Welcome

Hello, I am Seungchae Na.

This is my personal homepage.

## About Me

Write a short introduction here.

## Research Interests

* Interest 1
* Interest 2
* Interest 3

## Contact

* Email: [your-email@example.com](mailto:your-email@example.com)
* GitHub: [seungchae](https://github.com/seungchae)

  </main>

</div>
