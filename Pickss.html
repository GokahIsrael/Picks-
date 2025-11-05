<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Picks</title>
  <link rel="stylesheet" href="style.css" />
  <style>
    body {
  font-family: Arial, sans-serif;
  background: #f3f4f6;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

.search-container {
  background: #fff;
  padding: 30px;
  border-radius: 10px;
  box-shadow: 0 0 15px rgba(0,0,0,0.1);
  text-align: center;
  width: 400px;
}

.search-box {
  display: flex;
  margin-top: 20px;
}

.search-box input {
  flex: 1;
  padding: 10px;
  font-size: 16px;
  border: 1px solid #ccc;
  border-radius: 6px 0 0 6px;
  outline: none;
}

.search-box button {
  padding: 10px 20px;
  background: #007bff;
  color: white;
  border: none;
  border-radius: 0 6px 6px 0;
  cursor: pointer;
  transition: background 0.3s ease;
}

.search-box button:hover {
  background: #0056b3;
}

#results {
  margin-top: 20px;
  text-align: left;
}
  </style>
</head>
<body>
  <div class="search-container">
    <h2>Welcome dear User</h2>
    <div class="search-box">
      <input type="text" id="searchInput" placeholder="Type your query..." />
      <button id="searchBtn">Search</button>
    </div>
    <div id="results"></div>
  </div>

  <script>
    document.getElementById('searchBtn').addEventListener('click', function() {
  const query = document.getElementById('searchInput').value.trim();
  const resultsDiv = document.getElementById('results');
  
  if (query === '') {
    resultsDiv.innerHTML = '<p>Please enter a search term.</p>';
    return;
  }

  resultsDiv.innerHTML = '<p>Loading...</p>';

  // Send request to PHP backend
  fetch(`search.php?q=${encodeURIComponent(query)}`)
    .then(response => response.json())
    .then(data => {
      if (data.error) {
        resultsDiv.innerHTML = `<p>${data.error}</p>`;
      } else {
        // Display formatted results
        let html = '<ul>';
        data.results.forEach(item => {
          html += `<li>${item}</li>`;
        });
        html += '</ul>';
        resultsDiv.innerHTML = html;
      }
    })
    .catch(err => {
      resultsDiv.innerHTML = `<p>Error: ${err.message}</p>`;
    });
});
  </script>
</body>
</html>
