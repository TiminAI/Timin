<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>一键点名签到</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #f4f4f9;
            margin: 0;
        }
        .container {
            text-align: center;
            background-color: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            background-color: #007bff;
            color: white;
            margin-top: 10px;
        }
        button:hover {
            background-color: #0056b3;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            background-color: #e9ecef;
            margin: 5px 0;
            padding: 10px;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>一键点名签到</h1>
        <button id="checkinButton">签到</button>
        <ul id="checkinList"></ul>
        <button id="downloadButton" style="margin-top: 20px;">下载签到数据</button>
    </div>

    <script>
        const checkinButton = document.getElementById('checkinButton');
        const downloadButton = document.getElementById('downloadButton');
        const checkinList = document.getElementById('checkinList');
        let signIns = [];

        checkinButton.addEventListener('click', () => {
            const now = new Date();
            const formattedTime = `${now.getFullYear()}-${String(now.getMonth() + 1).padStart(2, '0')}-${String(now.getDate()).padStart(2, '0')} ${String(now.getHours()).padStart(2, '0')}:${String(now.getMinutes()).padStart(2, '0')}:${String(now.getSeconds()).padStart(2, '0')}`;
            signIns.push(formattedTime);

            const listItem = document.createElement('li');
            listItem.textContent = formattedTime;
            checkinList.appendChild(listItem);
        });

        downloadButton.addEventListener('click', () => {
            if (signIns.length === 0) {
                alert('没有签到记录可供下载');
                return;
            }

            const csvContent = "data:text/csv;charset=utf-8," 
                             + signIns.map(time => time).join("\n");
            const encodedUri = encodeURI(csvContent);
            const link = document.createElement("a");
            link.setAttribute("href", encodedUri);
            link.setAttribute("download", "签到记录.csv");
            document.body.appendChild(link); // Required for FF

            link.click(); // This will download the data file named "签到记录.csv".
            document.body.removeChild(link);
        });
    </script>
</body>
</html>


