# Lab6Web
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bootstrap Layout</title>
    <!-- Bootstrap CSS -->
    <link
      href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      body {
        background-image: url("img/lamborghini-3840x2160-19504.jpg");
        border: 5px solid #ddd;
        border-radius: 5px;
        padding: 5px;
        width: 100%;
      }
      /* Tambahkan CSS custom di sini */
      .sidebar {
        background-color: #f8f9fa;
        padding: 20px;
      }
      .content {
        padding: 20px;
      }
    </style>
  </head>
  <body>
    <!-- Navbar -->
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
      <a class="navbar-brand" href="#">Spezial Casual</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav ml-auto">
          <li class="nav-item active">
            <a class="nav-link" href="#">Home</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">Contact</a>
          </li>
        </ul>
        <ul class="navbar-nav">
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdown"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Username
            </a>
            <div
              class="dropdown-menu dropdown-menu-right"
              aria-labelledby="navbarDropdown"
            >
              <a class="dropdown-item" href="#">Profile</a>
              <a class="dropdown-item" href="#">Sign Out</a>
            </div>
          </li>
        </ul>
      </div>
    </nav>

    <div class="container-fluid">
      <div class="row">
        <!-- Sidebar -->
        <nav class="col-md-3 col-lg-2 sidebar">
          <h5>FORUM</h5>
          <ul class="nav flex-column">
            <li class="nav-item">
              <a class="nav-link active" href="#">Kaos</a>
            </li>
            <li class="nav-item"><a class="nav-link" href="#">Sepatu</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Jaket</a></li>
            <li class="nav-item"><a class="nav-link" href="#">Polo</a></li>
          </ul>
        </nav>

        <!-- Main content -->
        <main class="col-md-9 col-lg-10 content">
          <div class="jumbotron">
            <h1 class="display-4">Selamat Datang</h1>
            <p>Toko kami mempunyai perlengkapan pakaian casual original</p>
            <a class="btn btn-primary btn-lg" href="#" role="button"
              >Learn more »</a
            >
          </div>

          <div class="row">
            <div class="col-md-4">
              <h2>Sepatu</h2>
              <img { border: 5px solid #ddd; border-radius: 5px; padding: 5px;
              width="250px" src="img/product 1.jpg"}/>
              <p>Casual cocok untuk kegiatan olahraga apapun</p>
              <p><a class="btn btn-secondary" href="#" role="button">BUY</a></p>
            </div>
            <div class="col-md-4">
              <h2>Polo</h2>
              <img { border: 5px solid #ddd; border-radius: 5px; padding: 5px;
              width="200px" src="img/polo 3.jpg"}/>
              <p>Pakain anak Gen Z</p>
              <p><a class="btn btn-secondary" href="#" role="button">BUY</a></p>
            </div>
            <div class="col-md-4">
              <h2>Jaket</h2>
              <img { border: 5px solid #ddd; border-radius: 5px; padding: 5px;
              width="300px" src="img/dddd.jpg"}/>
              <p>
                Tebal lembut enak dipakai dicuaca dingin dan panas fleksibel
              </p>
              <p><a class="btn btn-secondary" href="#" role="button">BUY</a></p>
            </div>
          </div>
        </main>
      </div>
    </div>

    <!-- Bootstrap JavaScript -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.5.2/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
  </body>
</html>


# penjelasan
![Cuplikan layar 2024-11-05 141737](https://github.com/user-attachments/assets/0d57ece1-49b0-45d5-af14-3a22f0a75719)
Pada tampilan ini menunjukan tampilan awal
![Cuplikan layar 2024-11-05 141818](https://github.com/user-attachments/assets/95a189fe-a419-4493-ab56-a88456ea9f47)
Pada tampilan ini menggantikan nama project (Spezial Casual)
![Cuplikan layar 2024-11-05 141924](https://github.com/user-attachments/assets/4f8e4228-3d3d-4788-98c5-5ec2142542fc)
Pada tampilan ini menggantikan nama SI DEBAR Dengan(Forum)
![Cuplikan layar 2024-11-05 141924](https://github.com/user-attachments/assets/67e115b9-f290-4b67-8854-0bf20c420c13)
Pada tampilan ini menggantikan nama LINK dengan nama Project
![Cuplikan layar 2024-11-05 142213](https://github.com/user-attachments/assets/7f1a4e00-9eef-4ecd-9c26-19c33248569a)
Pada tampilan ini menggantikan card yang berisi gambar dengan Text Produk
![Cuplikan layar 2024-11-05 142441](https://github.com/user-attachments/assets/a7a91cb0-d07d-4e9d-97bb-768707664c7b)
Pada tampilan ini menggantikan nama hello word menjadi(Selamat Datang)
![Cuplikan layar 2024-11-05 142441](https://github.com/user-attachments/assets/a237f58d-641b-4af6-b3f6-21914ed2fa29)
Pada tampilan ini menggantikan text menjadi deskripsi toko
![Cuplikan layar 2024-11-05 142937](https://github.com/user-attachments/assets/be296424-8b7f-4bb2-8c86-f24ebc0259e5)
Pada tampilan ini menggantikan deskripsi produk dan button produk
![Cuplikan layar 2024-11-07 222330](https://github.com/user-attachments/assets/8cdf0ee5-ba53-4691-86df-d37d7a92187a)
Pada tampilan ini hasil yang sudah jadi
![Screenshot (63)](https://github.com/user-attachments/assets/548db7e7-9bd2-41aa-833f-4bab096bb2a8)











