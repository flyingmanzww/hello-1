export default {
    async fetch(request) {
        const html = `<!DOCTYPE html>
<html lang="zh">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> - NGO</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            width: 80%;
            max-width: 900px;
            margin: 40px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #2c3e50;
        }
        .header {
            text-align: center;
            padding-bottom: 20px;
            border-bottom: 2px solid #ddd;
        }
        .section {
            margin: 20px 0;
        }
        .project {
            background: #ecf0f1;
            padding: 15px;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        .contact {
            background: #3498db;
            color: white;
            padding: 15px;
            text-align: center;
            border-radius: 5px;
        }
        .contact a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        .contact a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="container">
        <div class="header">
            <h1>W H O</h1>
            <p>致力于环境可持续发展的专业人士</p>
        </div>

        <div class="header">
            <h1>关于我</h1>
            <p>我在环境可持续发展领域拥有丰富经验，曾参与多个国际环境项目，包括联合国环境项目。</p>
        </div>

        <div class="header">
            <h1>项目展示</h1>
            <div class="project">
                <h3>联合国环境项目</h3>
                <p>该项目致力于推动全球环境保护与可持续发展，涵盖气候变化、生物多样性、污染控制等多个方面。</p>
        
            </div>
            <div class="project">
                <h3>链接列表</h3>
                <p><a href="https://987.threem.ggff.net" target="_blank">987.threem.ggff.net</a></p>
                <p><a href="https://9870.threem.ggff.net" target="_blank">9870.threem.ggff.net</a></p>
                <p><a href="https://555.threem.ggff.net" target="_blank">555.threem.ggff.net</a></p>
                <p><a href="https://789.threem.ggff.net" target="_blank">789.threem.ggff.net</a></p>
                <p><a href="https://a.liyong.ggff.net" target="_blank">a.liyong.ggff.net</a></p>
                <p><a href="https://b.liyong.ggff.net" target="_blank">b.liyong.ggff.net</a></p>
                <p><a href="https://c.liyong.ggff.net" target="_blank">c.liyong.ggff.net</a></p>
                <p><a href="https://sub.cmliussss.net" target="_blank">sub.cmliussss.net</a></p>
            </div>
        </div>

        <div class="contact">
            <p> 联系我: <a href="mailto:20181203@gmail.com">20181203@gmail.com</a></p>
            
</div>
    </div>

</body>
</html>`;

        return new Response(html, {
            headers: {
                "Content-Type": "text/html;charset=UTF-8",
            },
        });
    },
};
