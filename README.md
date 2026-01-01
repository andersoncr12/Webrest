<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>web.ac</title>

  <style>
    body {
      margin: 0;
      background: #ffcbd3;
      font-family: Arial, sans-serif;
    }

    .container {
      padding: 15px;
    }

    h1, h2 {
      color: green;
      font-weight: bold;
      text-transform: lowercase;
    }

    hr {
      border: none;
      height: 1px;
      background: #e0aeb5;
      margin: 15px 0;
    }

    /* PRODUTOS */
    .produtos {
      display: flex;
      gap: 8px;
      overflow-x: auto;
      padding-bottom: 10px;
    }

    .produtos img {
      width: 90px;
      height: auto;
      border-radius: 6px;
      flex-shrink: 0;
    }

    /* CATEGORIAS */
    .categorias {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
    }

    .categorias button {
      padding: 6px 10px;
      border: 1px solid #999;
      background: #f5f5f5;
      border-radius: 4px;
      cursor: pointer;
    }

    /* BANNER */
    .banner {
      margin-top: 15px;
    }

    .banner img {
      width: 100%;
      border-radius: 6px;
    }
  </style>
</head>

<body>
  <div class="container">

    <h1>web.ac</h1>
    <hr>

    <h2>produtos em destaque</h2>

    <div class="produtos">
      <img src="https://aws-assets.kiwify.com.br/cdn-cgi/image/fit=scale-down,width=400/W4eo2d5xljz01Hw/FB-INI-2_7eec280bf0424215876fe89355eabf7f.jpg">
      <img src="https://aws-assets.kiwify.com.br/cdn-cgi/image/fit=scale-down,width=400/mndp5DLBHBxTUTr/foto-banner_8381998d362b4314ae9b9cdc385cfbd8.jpg">
      <img src="https://aws-assets.kiwify.com.br/cdn-cgi/image/fit=scale-down,width=400/gDlcLu7ddGy0lEV/FAFA3B2B-2006-47E4-809D-4A4617041B3E_e951e80a2f4e4f209056ce8e50132425.jpeg">
      <img src="https://aws-assets.kiwify.com.br/cdn-cgi/image/fit=scale-down,width=400/YPTCDffhwTH0gDl/5901A9C0-3A50-422E-955F-702AD06D5FE4_f4c41ebed7b04c3a9de4244e12a3d767_6ef70f71a4f64d6fa1fac3e26e5787fb.png">
    </div>

    <hr>

    <h2>categorias</h2>

    <div class="categorias">
      <button>cursos</button>
      <button>receitas</button>
      <button>ganhar dinheiro</button>
      <button>marketing</button>
      <button
