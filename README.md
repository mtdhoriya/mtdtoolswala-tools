
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Online Free Tools | mtdtoolswala</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f9f9f9;
    }
    .tool-card {
      border: 1px solid #ddd;
      border-radius: 10px;
      padding: 20px;
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      transition: transform 0.2s;
    }
    .tool-card:hover {
      transform: scale(1.03);
    }
    .dropdown-menu-columns {
      display: flex;
      flex-wrap: wrap;
      max-height: 400px;
      overflow-y: auto;
    }
    .dropdown-menu-columns > div {
      flex: 1 1 200px;
      padding: 0 10px;
    }
  </style>
</head>
<body>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
    <div class="container-fluid">
      <a class="navbar-brand" href="#">mtdtoolswala</a>
      <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav me-auto mb-2 mb-lg-0">
          <li class="nav-item dropdown">
            <a class="nav-link dropdown-toggle" href="#" id="toolsDropdown" role="button" data-bs-toggle="dropdown" aria-expanded="false">
              All Tools
            </a>
            <div class="dropdown-menu dropdown-menu-columns p-3 bg-light" aria-labelledby="toolsDropdown">
              <div>
                <h6>Text Tools</h6>
                <a class="dropdown-item" href="#">Text Counter</a>
                <a class="dropdown-item" href="#">Remove Line Breaks</a>
                <a class="dropdown-item" href="#">Case Converter</a>
              </div>
              <div>
                <h6>Image Tools</h6>
                <a class="dropdown-item" href="#">Image Resizer</a>
                <a class="dropdown-item" href="#">Image Compressor</a>
                <a class="dropdown-item" href="#">PNG to JPG</a>
              </div>
              <div>
                <h6>PDF Tools</h6>
                <a class="dropdown-item" href="#">PDF to Word</a>
                <a class="dropdown-item" href="#">Word to PDF</a>
                <a class="dropdown-item" href="#">Merge PDFs</a>
              </div>
              <div>
                <h6>Code Tools</h6>
                <a class="dropdown-item" href="#">JSON Formatter</a>
                <a class="dropdown-item" href="#">Base64 Encoder</a>
                <a class="dropdown-item" href="#">HTML Minifier</a>
              </div>
              <div>
                <h6>Other Tools</h6>
                <a class="dropdown-item" href="#">QR Code Generator</a>
                <a class="dropdown-item" href="#">YouTube Thumbnail Downloader</a>
                <a class="dropdown-item" href="#">UPI QR Generator</a>
              </div>
            </div>
          </li>
        </ul>
        <button class="btn btn-outline-light">Dark Mode</button>
      </div>
    </div>
  </nav>

  <header class="container text-center my-5">
    <h1>Welcome to Online Free Tools</h1>
    <p class="lead">All your daily online tools in one place — fast, free, and without ads.</p>
  </header>

  <main class="container">
    <div class="row g-4">
      <div class="col-md-4">
        <div class="tool-card text-center">
          <h5>Text Counter</h5>
          <p>Count words, characters, and lines in your text.</p>
          <a href="#" class="btn btn-primary">Open Tool</a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="tool-card text-center">
          <h5>Image Resizer</h5>
          <p>Resize images directly in your browser.</p>
          <a href="#" class="btn btn-primary">Open Tool</a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="tool-card text-center">
          <h5>PDF to Word</h5>
          <p>Convert your PDF files into editable Word docs.</p>
          <a href="#" class="btn btn-primary">Open Tool</a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="tool-card text-center">
          <h5>QR Code Generator</h5>
          <p>Create QR codes for links, UPI, or text.</p>
          <a href="#" class="btn btn-primary">Open Tool</a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="tool-card text-center">
          <h5>Base64 Encoder</h5>
          <p>Encode or decode text in Base64 format.</p>
          <a href="#" class="btn btn-primary">Open Tool</a>
        </div>
      </div>
      <div class="col-md-4">
        <div class="tool-card text-center">
          <h5>YouTube Thumbnail Downloader</h5>
          <p>Download thumbnails from YouTube videos.</p>
          <a href="#" class="btn btn-primary">Open Tool</a>
        </div>
      </div>
    </div>
  </main>

  <footer class="text-center py-4 mt-5 bg-light">
    <p class="mb-0">&copy; 2025 mtdtoolswala.com – All rights reserved.</p>
  </footer>

  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
