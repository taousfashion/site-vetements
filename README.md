
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Boutique Mode Moderne</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f9f9f9;
      color: #333;
    }
    header {
      background: url('https://source.unsplash.com/1600x600/?fashion,model') center/cover no-repeat;
      height: 90vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      color: white;
      position: relative;
    }
    header::before {
      content: "";
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      background-color: rgba(0, 0, 0, 0.4);
    }
    header h1 {
      font-size: 3em;
      z-index: 1;
    }
    header a {
      display: inline-block;
      margin-top: 20px;
      background-color: #ff3366;
      color: white;
      padding: 12px 24px;
      border-radius: 25px;
      text-decoration: none;
      z-index: 1;
    }
    section {
      padding: 60px 20px;
      max-width: 1100px;
      margin: auto;
    }
