<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>AIS 64Kbps (V2ray)</title>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
    body {
        margin: 0;
        font-family: Arial, Helvetica, sans-serif;
        background: linear-gradient(180deg, #0f2027, #203a43, #2c5364);
        color: #fff;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    .card {
        width: 90%;
        max-width: 420px;
        background: #0b1c22;
        border-radius: 18px;
        padding: 25px;
        box-shadow: 0 0 25px rgba(0, 255, 255, 0.25);
    }

    .status {
        text-align: center;
        margin-bottom: 25px;
    }

    .status h2 {
        margin: 0;
        font-size: 24px;
        letter-spacing: 1px;
    }

    .status p {
        margin: 6px 0 0;
        font-size: 14px;
        color: #9ee7f0;
    }

    .server-box {
        background: #0f2a33;
        border-radius: 16px;
        padding: 20px;
    }

    .server-title {
        font-size: 18px;
        margin-bottom: 15px;
    }

    .copy-btn {
        width: 100%;
        padding: 15px;
        border: none;
        border-radius: 30px;
        font-size: 16px;
        font-weight: bold;
        color: #003c44;
        background: linear-gradient(90deg, #00f5ff, #00c9d6);
        cursor: pointer;
    }

    .copy-btn:active {
        transform: scale(0.98);
    }
</style>
</head>
<body>

<div class="card">
    <div class="status">
        <h2>SERVER ONLINE</h2>
        <p>Premium Network Active</p>
    </div>

    <div class="server-box">
        <div class="server-title">Ais 64Kbps (V2ray)</div>
        <button class="copy-btn" onclick="copyKey()">COPY KEY</button>
    </div>
</div>

<script>
function copyKey() {
    const key = "YOUR_V2RAY_KEY_HERE";
    navigator.clipboard.writeText(key);
    alert("Key Copied!");
}
</script>

</body>
</html>
