<!DOCTYPE html>
<html lang="zh-Hant">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>個人網站</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>我的個人網站</h1>
        <nav>
            <ul>
                <li><a href="#life">生活</a></li>
                <li><a href="#mood">心情</a></li>
                <li><a href="#work">工作</a></li>
                <li><a href="#present">當下</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section id="life">
            <h2>生活</h2>
            <div class="content">
                <!-- 在這裡插入生活內容 -->
            </div>
        </section>
        <section id="mood">
            <h2>心情</h2>
            <div class="content">
                <!-- 在這裡插入心情內容 -->
            </div>
        </section>
        <section id="work">
            <h2>工作</h2>
            <div class="content">
                <!-- 在這裡插入工作內容 -->
            </div>
        </section>
        <section id="present">
            <h2>當下</h2>
            <div class="content">
                <!-- 在這裡插入當下內容 -->
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 我的個人網站</p>
    </footer>

    <!-- 留言表單模態框 -->
    <div id="commentModal" class="modal">
        <div class="modal-content">
            <span class="close">&times;</span>
            <h2>留言</h2>
            <form id="commentForm">
                <label for="name">姓名:</label>
                <input type="text" id="name" name="name" required>
                <label for="comment">留言:</label>
                <textarea id="comment" name="comment" required></textarea>
                <button type="submit">提交</button>
            </form>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
