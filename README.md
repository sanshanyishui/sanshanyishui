<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>我的家乡——天津</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif;
            background: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }

        /* Header */
        header {
            background: #1a365d;
            padding: 1.5rem;
            text-align: center;
        }

        header h1 {
            color: #fff;
            font-size: 2rem;
            margin-bottom: 1rem;
        }

        nav ul {
            display: flex;
            justify-content: center;
            gap: 1rem;
            list-style: none;
            flex-wrap: wrap;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            padding: 0.5rem 1rem;
            border-radius: 4px;
            transition: background 0.2s;
        }

        nav a:hover {
            background: rgba(255,255,255,0.2);
        }

        /* Main */
        main {
            max-width: 900px;
            margin: 0 auto;
            padding: 2rem 1rem;
        }

        article {
            background: #fff;
            border-radius: 8px;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        article h2 {
            color: #1a365d;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #ed8936;
        }

        article img {
            width: 100%;
            height: auto;
            border-radius: 4px;
            margin-bottom: 1rem;
        }

        article p {
            color: #666;
        }

        article iframe {
            width: 100%;
            height: 315px;
            border: none;
            border-radius: 4px;
        }

        /* Aside */
        aside {
            background: #fff;
            border-radius: 8px;
            padding: 1.5rem;
            margin-bottom: 1.5rem;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }

        aside h3 {
            color: #1a365d;
            margin-bottom: 1rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #ed8936;
        }

        aside p {
            margin-bottom: 0.5rem;
        }

        aside ul {
            list-style: none;
        }

        aside li {
            padding: 0.5rem 0;
            border-bottom: 1px solid #eee;
        }

        aside li:last-child {
            border-bottom: none;
        }

        /* Form */
        form {
            display: flex;
            flex-direction: column;
            gap: 0.75rem;
        }

        input, textarea {
            padding: 0.75rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1rem;
        }

        input:focus, textarea:focus {
            outline: none;
            border-color: #1a365d;
        }

        input[type="submit"] {
            background: #ed8936;
            color: #fff;
            border: none;
            cursor: pointer;
            transition: background 0.2s;
        }

        input[type="submit"]:hover {
            background: #dd6b20;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 1.5rem;
            color: #666;
            border-top: 1px solid #ddd;
        }

        /* Responsive */
        @media (max-width: 640px) {
            header h1 {
                font-size: 1.5rem;
            }

            nav ul {
                gap: 0.5rem;
            }

            nav a {
                padding: 0.4rem 0.8rem;
                font-size: 0.9rem;
            }
        }
    </style>
</head>

<body>

<header>
    <h1>我的家乡——天津</h1>
    <nav>
        <ul>
            <li><a href="#">首页</a></li>
            <li><a href="#">天津风景</a></li>
            <li><a href="#">天津美食</a></li>
            <li><a href="#">天津文化</a></li>
        </ul>
    </nav>
</header>

<main>

    <article>
        <h2>海河风景</h2>
        <img src="../图片/天津海河.jpg" alt="海河风景">
        <p>海河是天津最重要的河流之一，贯穿天津市区，两岸拥有众多桥梁和现代建筑，夜景十分迷人。</p>
    </article>

    <article>
        <h2>天津城市风光</h2>
        <img src="../图片/城市风光.jpg" alt="天津城市风光">
        <p>天津是一座历史与现代结合的城市，既有现代化高楼，也有许多历史文化建筑，如五大道、古文化街等。</p>
    </article>

    <article>
        <h2>天津城市宣传视频</h2>
        <iframe src="//player.bilibili.com/player.html?bvid=BV1XW411C78j&page=1" allowfullscreen></iframe>
    </article>

    <aside>
        <h3>博主信息</h3>
        <p>姓名：XXX</p>
        <p>家乡：中国天津</p>
        <p>爱好：摄影 旅行</p>
    </aside>

    <aside>
        <h3>热门景点</h3>
        <ul>
            <li>天津之眼</li>
            <li>五大道</li>
            <li>古文化街</li>
            <li>海河夜景</li>
        </ul>
    </aside>

    <aside>
        <h3>留言</h3>
        <form>
            <input type="text" placeholder="姓名">
            <input type="email" placeholder="邮箱">
            <textarea rows="4" placeholder="留言"></textarea>
            <input type="submit" value="提交">
        </form>
    </aside>

</main>

<footer>
    <p>© 2026 我的家乡 天津</p>
</footer>

</body>
</html>
