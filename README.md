# CRUD-2024091-
Projeto CRUD com HTML e CSS
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <title>CRUD Número da Turma</title>
  <style>
    body {
      font-family: sans-serif;
      margin: 0;
      padding: 0;
      background-color: #fff;
      display: flex;
      flex-direction: column;
      align-items: center;
    }

    /* Cabeçalho */
    .header {
      width: 100%;
      background-color: #fbbc04;
      padding: 15px 0;
      text-align: center;
    }

    .header h1 {
      color: #d32f2f;
      margin: 0;
      font-weight: bold;
      font-size: 24px;
    }

    /* Container do conteúdo abaixo do cabeçalho */
    .container {
      width: 80%;
      max-width: 800px;
      margin-top: 30px;
      text-align: left;
    }

    h2 {
      font-family: Georgia, serif;
      font-size: 26px;
      margin-bottom: 10px;
    }

    .add-btn {
      background-color: #4a90e2;
      color: white;
      border: none;
      padding: 10px 20px;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
      box-shadow: 0 4px #357ABD;
    }

    .add-btn:hover {
      background-color: #357ABD;
    }

    table {
      border-collapse: collapse;
      width: 100%;
      margin-top: 20px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }

    th, td {
      border: 1px solid #ddd;
      padding: 12px;
      text-align: left;
    }

    th {
      background-color: #f9f9f9;
      font-weight: bold;
    }

    .btn-edit {
      background-color: #007bff;
      color: white;
      border: none;
      padding: 6px 12px;
      border-radius: 4px;
      cursor: pointer;
      margin-right: 5px;
    }

    .btn-delete {
      background-color: #dc3545;
      color: white;
      border: none;
      padding: 6px 12px;
      border-radius: 4px;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <!-- Cabeçalho -->
  <div class="header">
    <h1>CRUD &lt;Número da Turma&gt;</h1>
  </div>

  <!-- Conteúdo alinhado à esquerda -->
  <div class="container">
    <h2>Registro de Empregados</h2>
    <button class="add-btn" onclick="alert('Adicionar novo empregado')">
      Adicionar Novo Empregado
    </button>

    <table>
      <thead>
        <tr>
          <th>ID</th>
          <th>Name</th>
          <th>Salary</th>
          <th>Department</th>
          <th>Action</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>1</td>
          <td>Rakesh</td>
          <td>2345</td>
          <td>IT</td>
          <td>
            <button class="btn-edit">Edit</button>
            <button class="btn-delete">Delete</button>
          </td>
        </tr>
        <tr>
          <td>2</td>
          <td>Priyanka</td>
          <td>2500</td>
          <td>HR</td>
          <td>
            <button class="btn-edit">Edit</button>
            <button class="btn-delete">Delete</button>
          </td>
        </tr>
        <tr>
          <td>3</td>
          <td>Anurag</td>
          <td>4500</td>
          <td>Sales</td>
          <td>
            <button class="btn-edit">Edit</button>
            <button class="btn-delete">Delete</button>
          </td>
        </tr>
      </tbody>
    </table>
  </div>

</body>
</html>
