<!DOCTYPE html>
<html lang="hi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Line Copper Orange App</title>
  <style>
    /* Theme Variables */
    :root {
      --copper: #b87333;
      --copper-dark: #8b5a2b;
      --orange: #ff7f00;
      --orange-bright: #ff5500;
      --bg-dark: #1a1512;
      --card-bg: #261f1b;
      --text-light: #f5e6d3;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body {
      background-color: var(--bg-dark);
      color: var(--text-light);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      padding: 20px;
    }

    /* Container with Line & Copper Border */
    .app-card {
      background: var(--card-bg);
      border: 2px solid var(--copper);
      border-radius: 16px;
      padding: 30px;
      width: 100%;
      max-width: 400px;
      text-align: center;
      box-shadow: 0 10px 30px rgba(184, 115, 51, 0.2);
      position: relative;
    }

    .app-card h1 {
      color: var(--orange);
      font-size: 24px;
      margin-bottom: 10px;
      text-transform: uppercase;
      letter-spacing:
