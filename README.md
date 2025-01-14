# kiet<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Giới Thiệu - Focus10</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      /* Body and layout setup */
      body {
        font-family: "Roboto", sans-serif;
        background-color: #fafafa;
        color: #2e2e2e;
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: column;
        min-height: 100vh; /* Ensure the body takes at least the full height of the viewport */
      }

      /* Header styling */
      header {
        background-color: #ffffff;
        color: #2e2e2e;
        padding: 20px 40px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      header .logo {
        font-size: 28px;
        font-weight: 700;
        color: #4a90e2;
      }

      header nav a {
        color: #2e2e2e;
        margin: 0 20px;
        font-size: 16px;
        text-decoration: none;
      }

      header nav a:hover {
        color: #4a90e2;
      }

      /* Container setup */
      .container {
        padding-top: 50px;
        padding-bottom: 50px;
        flex-grow: 1; /* Allow content to take remaining space */
      }

      /* Section Title styling */
      .section-title {
        font-size: 32px;
        font-weight: 600;
        margin-bottom: 30px;
        color: #2e2e2e;
      }

      /* Section content styling */
      .section-content {
        font-size: 18px;
        line-height: 1.6;
        color: #333;
      }

      /* Footer styling */
      footer {
        background-color: #ffffff;
        color: #2e2e2e;
        text-align: center;
        padding: 20px;
        font-size: 14px;
        box-shadow: none;
        position: relative;
        bottom: 0;
        width: 100%;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">Focus10</div>
      <nav>
        <a href="index.html">Trang Chủ</a>
        <a href="dang-nhap.html">Đăng Nhập</a>
      </nav>
    </header>

    <div class="container">
      <div class="section-title">Giới Thiệu Về Focus10</div>
      <div class="section-content">
        <p>
          Focus10 là nền tảng hỗ trợ học sinh ôn thi hiệu quả với bộ đề thi, tài
          liệu ôn tập, và các bộ đề thi thử đa dạng. Chúng tôi cung cấp cho các
          bạn học sinh các công cụ để ôn luyện, cải thiện kỹ năng và chuẩn bị
          tốt nhất cho các kỳ thi quan trọng.
        </p>
        <p>
          Chúng tôi cam kết cung cấp những tài liệu, đề thi, và bộ đề thi thử
          chất lượng, giúp các bạn tự tin hơn khi bước vào phòng thi. Tại
          Focus10, chúng tôi luôn đồng hành cùng bạn trong suốt hành trình học
          tập của bạn.
        </p>
        <p>
          Mục Tiêu: Website Focus10 được thiết kế để cung cấp tài liệu ôn thi
          tuyển sinh lớp 10 chất lượng, giúp học sinh ôn tập hiệu quả, đặc biệt
          là môn Tiếng Anh. Website cung cấp các tài liệu phong phú và các công
          cụ hỗ trợ học tập để học sinh dễ dàng tiếp cận và nâng cao kỹ năng của
          mình. Điểm Nhấn: Đề Thi: Cung cấp các bộ đề thi thử với đa dạng chủ đề
          và cấu trúc bài thi, giúp học sinh làm quen với định dạng đề thi và
          luyện tập hiệu quả. Bài Giải Chi Tiết: Các bài giải chi tiết giúp học
          sinh hiểu rõ từng bước giải quyết vấn đề và nắm bắt phương pháp làm
          bài thi chính xác. Mẹo Học Tập: Các mẹo học tập và chiến lược ôn thi
          sẽ giúp học sinh tối ưu hóa thời gian học, tăng cường sự tự tin khi
          đối mặt với các kỳ thi. Tài Liệu Tham Khảo: Cung cấp tài liệu tham
          khảo đa dạng, bao gồm sách, bài giảng, và video học để học sinh có
          thêm nguồn tài liệu phong phú phục vụ cho quá trình ôn tập.
        </p>
        <p>
          Cảm ơn bạn đã tin tưởng và lựa chọn Focus10 làm người bạn đồng hành
          trong việc chuẩn bị cho kỳ thi sắp tới!
        </p>
      </div>
    </div>

    <footer>
      <p>&copy; 2025 Focus10. All rights reserved.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
  </body>
</html>
<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Danh Mục Đề Thi - Focus10</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      /* Layout setup for the body */
      body {
        font-family: "Roboto", sans-serif;
        background-color: #fafafa;
        color: #2e2e2e;
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: column;
        min-height: 100vh; /* Ensures the body takes at least the full height of the viewport */
      }

      header {
        background-color: #ffffff;
        color: #2e2e2e;
        padding: 20px 40px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      header .logo {
        font-size: 28px;
        font-weight: 700;
        color: #4a90e2;
      }

      header nav a {
        color: #2e2e2e;
        margin: 0 20px;
        font-size: 16px;
        text-decoration: none;
        font-weight: 500;
      }

      header nav a:hover {
        color: #4a90e2;
      }

      #logoutLink {
        display: none;
        cursor: pointer;
        font-weight: 500;
      }

      #accountName {
        display: none;
        margin-left: 10px;
        font-weight: 500;
        color: #4a90e2;
      }

      /* Container for the page content */
      .container {
        padding-top: 50px;
        padding-bottom: 50px;
        flex-grow: 1; /* Allow content to grow and take available space */
      }

      .upload-section {
        background-color: white;
        padding: 30px;
        border-radius: 8px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        margin-bottom: 30px;
      }

      .upload-section h3 {
        font-size: 24px;
        margin-bottom: 20px;
        font-weight: 600;
        color: #2e2e2e;
      }

      .upload-section form input[type="file"] {
        margin-bottom: 20px;
      }

      .upload-section form button {
        background-color: #4a90e2;
        color: white;
        padding: 12px 20px;
        border: none;
        border-radius: 6px;
        cursor: pointer;
        font-size: 16px;
        transition: background-color 0.3s ease;
      }

      .upload-section form button:hover {
        background-color: #357ab7;
      }

      footer {
        background-color: #ffffff;
        color: #2e2e2e;
        text-align: center;
        padding: 20px;
        font-size: 14px;
        box-shadow: none;
        position: relative;
        bottom: 0;
        width: 100%;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">Focus10</div>
      <nav>
        <a href="index.html" id="homeLink">Trang Chủ</a>
        <a href="gioi-thieu.html">Giới Thiệu</a>
        <a href="bo-de-thi-thu.html">Bộ Đề Thi Thử</a>
        <a href="tai-lieu-on-tap.html">Tài Liệu Ôn Tập</a>
        <a href="dang-ky.html" id="registerLink">Đăng Ký</a>
        <a href="dang-nhap.html" id="loginLink">Đăng Nhập</a>
        <span id="accountName"></span>
        <span id="logoutLink">Đăng Xuất</span>
      </nav>
    </header>

    <div class="container">
      <h1>Danh Mục Đề Thi</h1>
      <div class="upload-section">
        <h3>Tải File Lên - Danh Mục Đề Thi</h3>
        <form
          action="http://localhost:3000/upload/danh-muc"
          method="post"
          enctype="multipart/form-data"
        >
          <input type="file" name="files" class="form-control" multiple />
          <button type="submit" class="btn btn-primary mt-3">Tải Lên</button>
        </form>
      </div>
    </div>

    <footer>
      <p>&copy; 2025 Focus10. All rights reserved.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
    <script>
      function checkLoginStatus() {
        const currentUser = localStorage.getItem("currentUser");
        const accountName = document.getElementById("accountName");
        const logoutLink = document.getElementById("logoutLink");
        const loginLink = document.getElementById("loginLink");
        const registerLink = document.getElementById("registerLink");

        if (!currentUser) {
          alert("Bạn cần đăng nhập để truy cập trang này.");
          window.location.href = "dang-nhap.html";
          return;
        }

        accountName.textContent = `(${currentUser})`;
        accountName.style.display = "inline";
        logoutLink.style.display = "inline";
        loginLink.style.display = "none";
        registerLink.style.display = "none";

        logoutLink.addEventListener("click", function () {
          localStorage.removeItem("currentUser");
          window.location.href = "index.html";
        });
      }

      checkLoginStatus();
    </script>
  </body>
</html>
<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Đăng Nhập - Focus10</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      body {
        font-family: "Roboto", sans-serif;
        background-color: #fafafa;
        color: #2e2e2e;
        margin: 0;
        padding: 0;
      }

      header {
        background-color: #ffffff;
        color: #2e2e2e;
        padding: 20px 40px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      header .logo {
        font-size: 28px;
        font-weight: 700;
        color: #4a90e2;
      }

      header nav a {
        color: #2e2e2e;
        margin: 0 20px;
        font-size: 16px;
        text-decoration: none;
        font-weight: 500;
      }

      header nav a:hover {
        color: #4a90e2;
      }

      .container {
        padding-top: 50px;
        padding-bottom: 50px;
      }

      .form-container {
        max-width: 500px;
        margin: auto;
        background-color: white;
        padding: 40px;
        border-radius: 8px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      }

      .form-container h3 {
        font-size: 24px;
        font-weight: 700;
        margin-bottom: 20px;
        color: #4a90e2;
      }

      .form-group input {
        padding: 12px;
        border-radius: 6px;
        border: 1px solid #ddd;
        width: 100%;
        font-size: 16px;
        margin-bottom: 20px;
      }

      .form-group button {
        background-color: #4a90e2;
        color: white;
        padding: 12px;
        border: none;
        border-radius: 6px;
        font-size: 16px;
        width: 100%;
        cursor: pointer;
        transition: background-color 0.3s ease;
      }

      .form-group button:hover {
        background-color: #357ab7;
      }

      .register-link-container {
        background-color: #f9f9f9;
        padding: 15px;
        border-radius: 8px;
        margin-top: 20px;
        text-align: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      .register-link-container a {
        color: #4a90e2;
        text-decoration: none;
        font-weight: 500;
      }

      .register-link-container a:hover {
        text-decoration: underline;
      }

      footer {
        background-color: #ffffff;
        color: #2e2e2e;
        text-align: center;
        padding: 20px;
        font-size: 14px;
        box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.1);
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">Focus10</div>
      <nav>
        <a href="index.html">Trang Chủ</a>
        <a href="dang-ky.html">Đăng Ký</a>
      </nav>
    </header>

    <div class="container">
      <div class="form-container">
        <h3>Đăng Nhập</h3>
        <form action="#" method="post" onsubmit="loginUser(event)">
          <div class="form-group">
            <input
              type="text"
              id="login-username"
              class="form-control"
              placeholder="Tên đăng nhập"
              required
            />
          </div>
          <div class="form-group">
            <input
              type="password"
              id="login-password"
              class="form-control"
              placeholder="Mật khẩu"
              required
            />
          </div>
          <div class="form-group">
            <button type="submit">Đăng Nhập</button>
          </div>
        </form>

        <!-- Link to register page if user doesn't have an account -->
        <div class="register-link-container">
          <p>
            Nếu bạn chưa có tài khoản, <a href="dang-ky.html">đăng ký ngay!</a>
          </p>
        </div>
      </div>
    </div>

    <footer>
      <p>&copy; 2025 Focus10. All rights reserved.</p>
    </footer>

    <script>
      // Function to get stored users from localStorage
      function getUsers() {
        const users = localStorage.getItem("users");
        return users ? JSON.parse(users) : [];
      }

      // Function to handle login
      function loginUser(event) {
        event.preventDefault();
        const username = document.getElementById("login-username").value.trim();
        const password = document.getElementById("login-password").value.trim();
        const users = getUsers();

        const user = users.find(
          (user) => user.username === username && user.password === password
        );

        if (user) {
          localStorage.setItem("currentUser", username);
          alert("Đăng nhập thành công! Chuyển hướng đến trang người dùng.");
          window.location.href = "logged-in.html";
        } else {
          alert("Sai tên đăng nhập hoặc mật khẩu. Vui lòng thử lại.");
        }
      }

      // Check if already logged in and redirect
      function checkAlreadyLoggedIn() {
        const currentUser = localStorage.getItem("currentUser");
        if (currentUser) {
          alert("Bạn đã đăng nhập, chuyển hướng đến trang người dùng.");
          window.location.href = "logged-in.html";
        }
      }

      // Call the check function on page load
      checkAlreadyLoggedIn();
    </script>

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
  </body>
</html>
<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Đăng Ký - Focus10</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      body {
        font-family: "Roboto", sans-serif;
        background-color: #fafafa;
        color: #2e2e2e;
        margin: 0;
        padding: 0;
      }
      header {
        background-color: #ffffff;
        color: #2e2e2e;
        padding: 20px 40px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }
      header .logo {
        font-size: 28px;
        font-weight: 700;
        color: #4a90e2;
      }
      header nav a {
        color: #2e2e2e;
        margin: 0 20px;
        font-size: 16px;
        text-decoration: none;
        font-weight: 500;
      }
      header nav a:hover {
        color: #4a90e2;
      }
      .container {
        padding-top: 50px;
        padding-bottom: 50px;
      }
      .form-container {
        max-width: 500px;
        margin: auto;
        background-color: white;
        padding: 40px;
        border-radius: 8px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      }
      .form-container h3 {
        font-size: 24px;
        font-weight: 700;
        margin-bottom: 20px;
        color: #4a90e2;
      }
      .form-group input {
        padding: 12px;
        border-radius: 6px;
        border: 1px solid #ddd;
        width: 100%;
        font-size: 16px;
        margin-bottom: 20px;
      }
      .form-group button {
        background-color: #4a90e2;
        color: white;
        padding: 12px;
        border: none;
        border-radius: 6px;
        font-size: 16px;
        width: 100%;
        cursor: pointer;
        transition: background-color 0.3s ease;
      }
      .form-group button:hover {
        background-color: #357ab7;
      }
      footer {
        background-color: #ffffff;
        color: #2e2e2e;
        text-align: center;
        padding: 20px;
        font-size: 14px;
        box-shadow: 0 -4px 8px rgba(0, 0, 0, 0.1);
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">Focus10</div>
      <nav>
        <a href="index.html">Trang Chủ</a>
        <a href="dang-nhap.html">Đăng Nhập</a>
      </nav>
    </header>

    <div class="container">
      <div class="form-container">
        <h3>Đăng Ký Tài Khoản</h3>
        <form action="#" method="post" onsubmit="registerUser(event)">
          <div class="form-group">
            <input
              type="text"
              id="register-username"
              class="form-control"
              placeholder="Tên đăng nhập"
              required
            />
          </div>
          <div class="form-group">
            <input
              type="password"
              id="register-password"
              class="form-control"
              placeholder="Mật khẩu"
              required
            />
          </div>
          <div class="form-group">
            <input
              type="password"
              id="confirm-password"
              class="form-control"
              placeholder="Xác nhận mật khẩu"
              required
            />
          </div>
          <button type="submit" class="btn btn-primary">Đăng Ký</button>
        </form>
      </div>
    </div>

    <footer>
      <p>&copy; 2025 Focus10. All rights reserved.</p>
    </footer>

    <script>
      function getUsers() {
        const users = localStorage.getItem("users");
        return users ? JSON.parse(users) : [];
      }

      function saveUsers(users) {
        localStorage.setItem("users", JSON.stringify(users));
      }

      function registerUser(event) {
        event.preventDefault();
        const username = document.getElementById("register-username").value;
        const password = document.getElementById("register-password").value;
        const confirmPassword =
          document.getElementById("confirm-password").value;

        if (password !== confirmPassword) {
          alert("Mật khẩu xác nhận không khớp. Vui lòng thử lại.");
          return;
        }

        const users = getUsers();
        const userExists = users.some((user) => user.username === username);

        if (userExists) {
          alert("Tên đăng nhập đã tồn tại. Vui lòng chọn tên khác.");
        } else {
          users.push({ username, password });
          saveUsers(users);
          alert("Đăng ký thành công! Chuyển hướng đến trang đăng nhập.");
          window.location.href = "dang-nhap.html";
        }
      }
    </script>

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
  </body>
</html>
<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Bộ Đề Thi Thử - Focus10</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      /* Ensure the body takes at least the full height of the viewport */
      body {
        font-family: "Roboto", sans-serif;
        background-color: #fafafa;
        color: #2e2e2e;
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: column;
        min-height: 100vh; /* Ensures full height for the page */
      }

      header {
        background-color: #ffffff;
        color: #2e2e2e;
        padding: 20px 40px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      header .logo {
        font-size: 28px;
        font-weight: 700;
        color: #4a90e2;
      }

      header nav a {
        color: #2e2e2e;
        margin: 0 20px;
        font-size: 16px;
        text-decoration: none;
        font-weight: 500;
      }

      header nav a:hover {
        color: #4a90e2;
      }

      #logoutLink {
        display: none;
        cursor: pointer;
        font-weight: 500;
      }

      #accountName {
        display: none;
        margin-left: 10px;
        font-weight: 500;
        color: #4a90e2;
      }

      /* Container for page content */
      .container {
        padding-top: 50px;
        padding-bottom: 50px;
        flex-grow: 1; /* This allows the content area to take available space */
      }

      .upload-section {
        background-color: white;
        padding: 30px;
        border-radius: 8px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        margin-bottom: 30px;
      }

      .upload-section h3 {
        font-size: 24px;
        margin-bottom: 20px;
        font-weight: 600;
        color: #2e2e2e;
      }

      .upload-section form input[type="file"] {
        margin-bottom: 20px;
      }

      .upload-section form button {
        background-color: #4a90e2;
        color: white;
        padding: 12px 20px;
        border: none;
        border-radius: 6px;
        cursor: pointer;
        font-size: 16px;
        transition: background-color 0.3s ease;
      }

      .upload-section form button:hover {
        background-color: #357ab7;
      }

      footer {
        background-color: #ffffff;
        color: #2e2e2e;
        text-align: center;
        padding: 20px;
        font-size: 14px;
        box-shadow: none;
        position: relative;
        bottom: 0;
        width: 100%;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">Focus10</div>
      <nav>
        <a href="index.html" id="homeLink">Trang Chủ</a>
        <a href="gioi-thieu.html">Giới Thiệu</a>
        <a href="danh-muc.html">Danh Mục Đề Thi</a>
        <a href="tai-lieu-on-tap.html">Tài Liệu Ôn Tập</a>
        <a href="dang-ky.html" id="registerLink">Đăng Ký</a>
        <a href="dang-nhap.html" id="loginLink">Đăng Nhập</a>
        <span id="accountName"></span>
        <span id="logoutLink">Đăng Xuất</span>
      </nav>
    </header>

    <div class="container">
      <h1>Bộ Đề Thi Thử</h1>
      <div class="upload-section">
        <h3>Tải File Lên - Bộ Đề Thi Thử</h3>
        <form
          action="http://localhost:3000/upload/bo-de-thi-thu"
          method="post"
          enctype="multipart/form-data"
        >
          <input type="file" name="files" class="form-control" multiple />
          <button type="submit" class="btn btn-primary mt-3">Tải Lên</button>
        </form>
      </div>
    </div>

    <footer>
      <p>&copy; 2025 Focus10. All rights reserved.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
    <script>
      function checkLoginStatus() {
        const currentUser = localStorage.getItem("currentUser");
        const accountName = document.getElementById("accountName");
        const logoutLink = document.getElementById("logoutLink");
        const loginLink = document.getElementById("loginLink");
        const registerLink = document.getElementById("registerLink");

        if (!currentUser) {
          alert("Bạn cần đăng nhập để truy cập trang này.");
          window.location.href = "dang-nhap.html";
          return;
        }

        accountName.textContent = `(${currentUser})`;
        accountName.style.display = "inline";
        logoutLink.style.display = "inline";
        loginLink.style.display = "none";
        registerLink.style.display = "none";

        logoutLink.addEventListener("click", function () {
          localStorage.removeItem("currentUser");
          window.location.href = "index.html";
        });
      }

      checkLoginStatus();
    </script>
  </body>
</html>
<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Tài Liệu Ôn Tập - Focus10</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      html,
      body {
        height: 100%;
        margin: 0;
      }

      body {
        font-family: "Roboto", sans-serif;
        background-color: #fafafa;
        color: #2e2e2e;
        display: flex;
        flex-direction: column;
      }

      header {
        background-color: #ffffff;
        color: #2e2e2e;
        padding: 20px 40px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      header .logo {
        font-size: 28px;
        font-weight: 700;
        color: #4a90e2;
      }

      header nav a {
        color: #2e2e2e;
        margin: 0 20px;
        font-size: 16px;
        text-decoration: none;
        font-weight: 500;
      }

      header nav a:hover {
        color: #4a90e2;
      }

      #logoutLink {
        display: none;
        cursor: pointer;
        font-weight: 500;
      }

      #accountName {
        display: none;
        margin-left: 10px;
        font-weight: 500;
        color: #4a90e2;
      }

      .container {
        padding-top: 50px;
        padding-bottom: 50px;
        flex-grow: 1;
      }

      .upload-section {
        background-color: white;
        padding: 30px;
        border-radius: 8px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        margin-bottom: 30px;
      }

      .upload-section h3 {
        font-size: 24px;
        margin-bottom: 20px;
        font-weight: 600;
        color: #2e2e2e;
      }

      .upload-section form input[type="file"] {
        margin-bottom: 20px;
      }

      .upload-section form button {
        background-color: #4a90e2;
        color: white;
        padding: 12px 20px;
        border: none;
        border-radius: 6px;
        cursor: pointer;
        font-size: 16px;
        transition: background-color 0.3s ease;
      }

      .upload-section form button:hover {
        background-color: #357ab7;
      }

      footer {
        background-color: #ffffff;
        color: #2e2e2e;
        text-align: center;
        padding: 20px;
        font-size: 14px;
        box-shadow: none;
        position: relative;
        bottom: 0;
        width: 100%;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">Focus10</div>
      <nav>
        <a href="index.html">Trang Chủ</a>
        <a href="gioi-thieu.html">Giới Thiệu</a>
        <a href="danh-muc.html">Danh Mục Đề Thi</a>
        <a href="bo-de-thi-thu.html">Bộ Đề Thi Thử</a>
        <a href="dang-ky.html" id="registerLink">Đăng Ký</a>
        <a href="dang-nhap.html" id="loginLink">Đăng Nhập</a>
        <span id="accountName"></span>
        <span id="logoutLink">Đăng Xuất</span>
      </nav>
    </header>

    <div class="container">
      <h1>Tài Liệu Ôn Tập</h1>
      <div class="upload-section">
        <h3>Tải File Lên - Tài Liệu Ôn Tập</h3>
        <form
          action="http://localhost:3000/upload/tai-lieu-on-tap"
          method="post"
          enctype="multipart/form-data"
        >
          <input type="file" name="files" class="form-control" multiple />
          <button type="submit" class="btn btn-primary mt-3">Tải Lên</button>
        </form>
      </div>
    </div>

    <footer>
      <p>&copy; 2025 Focus10. All rights reserved.</p>
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.11.6/dist/umd/popper.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.min.js"></script>
    <script>
      function checkLoginStatus() {
        const currentUser = localStorage.getItem("currentUser");
        const accountName = document.getElementById("accountName");
        const logoutLink = document.getElementById("logoutLink");
        const loginLink = document.getElementById("loginLink");
        const registerLink = document.getElementById("registerLink");

        if (!currentUser) {
          alert("Bạn cần đăng nhập để truy cập trang này.");
          window.location.href = "dang-nhap.html";
          return;
        }

        accountName.textContent = `(${currentUser})`;
        accountName.style.display = "inline";
        logoutLink.style.display = "inline";
        loginLink.style.display = "none";
        registerLink.style.display = "none";

        logoutLink.addEventListener("click", function () {
          localStorage.removeItem("currentUser");
          window.location.href = "index.html";
        });
      }

      checkLoginStatus();
    </script>
  </body>
</html>
<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Search Results - Focus10</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      body {
        font-family: "Roboto", sans-serif;
        background-color: #fafafa;
        color: #2e2e2e;
        margin: 0;
        padding: 0;
      }

      header {
        background-color: #ffffff;
        padding: 20px 40px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      .container {
        padding: 50px 20px;
      }

      h1 {
        font-size: 28px;
        margin-bottom: 20px;
      }

      .search-term {
        color: #4a90e2;
        font-weight: bold;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">Focus10</div>
      <nav>
        <a href="index.html">Home</a>
      </nav>
    </header>

    <div class="container">
      <h1>Search Results</h1>
      <p>
        Showing results for: <span class="search-term" id="searchTerm"></span>
      </p>
      <div id="results"></div>
    </div>

    <script>
      // Get the search term from the URL query parameter
      const urlParams = new URLSearchParams(window.location.search);
      const searchTerm = urlParams.get("query");

      // Display the search term
      document.getElementById("searchTerm").textContent = searchTerm;

      // Dummy data for demonstration
      const data = [
        {
          title: "Giới Thiệu",
          content: "Welcome to the introduction page of Focus10.",
        },
        {
          title: "Danh Mục Đề Thi",
          content: "Here is the list of all exam categories.",
        },
        {
          title: "Bộ Đề Thi Thử",
          content: "Browse all trial exam sets available here.",
        },
        {
          title: "Tài Liệu Ôn Tập",
          content: "Find all study materials in this section.",
        },
      ];

      // Filter the data based on the search term
      const results = data.filter(
        (item) =>
          item.title.toLowerCase().includes(searchTerm.toLowerCase()) ||
          item.content.toLowerCase().includes(searchTerm.toLowerCase())
      );

      // Display the results
      const resultsContainer = document.getElementById("results");
      if (results.length > 0) {
        results.forEach((item) => {
          const resultElement = document.createElement("div");
          resultElement.innerHTML = `<h3>${item.title}</h3><p>${item.content}</p>`;
          resultsContainer.appendChild(resultElement);
        });
      } else {
        resultsContainer.innerHTML = "<p>No results found.</p>";
      }
    </script>
  </body>
</html>
<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Focus10 - User Dashboard</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      body {
        font-family: "Roboto", sans-serif;
        background-color: #fafafa;
        color: #2e2e2e;
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: column;
        min-height: 100vh;
      }

      header {
        background-color: #ffffff;
        padding: 20px 40px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      .logo {
        font-size: 28px;
        font-weight: 700;
        color: #4a90e2;
      }

      nav a {
        color: #2e2e2e;
        margin: 0 20px;
        font-size: 16px;
        text-decoration: none;
        font-weight: 500;
      }

      nav a:hover {
        color: #4a90e2;
      }

      #logoutLink {
        cursor: pointer;
        font-weight: 500;
      }

      #accountName {
        margin-left: 10px;
        font-weight: 500;
        color: #4a90e2;
      }

      .container {
        padding-top: 50px;
        padding-bottom: 50px;
        flex-grow: 1;
        text-align: center;
      }

      footer {
        background-color: #ffffff;
        padding: 20px;
        text-align: center;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">Focus10</div>
      <nav>
        <span id="accountName"></span>
        <span id="logoutLink">Đăng Xuất</span>
      </nav>
    </header>

    <div class="container">
      <h1>Welcome to Your Dashboard</h1>
      <p>You are successfully logged in.</p>
    </div>

    <footer>
      <p>&copy; 2025 Focus10. All rights reserved.</p>
    </footer>

    <script>
      function checkAccess() {
        const currentUser = localStorage.getItem("currentUser");
        const accountName = document.getElementById("accountName");
        const logoutLink = document.getElementById("logoutLink");

        if (!currentUser) {
          alert("You need to log in to access this page.");
          window.location.href = "index.html";
          return;
        }

        accountName.textContent = `(${currentUser})`;

        logoutLink.addEventListener("click", function () {
          localStorage.removeItem("currentUser");
          window.location.href = "index.html";
        });

        // Automatic redirection to homepage after 3 seconds
        setTimeout(() => {
          window.location.href = "index.html";
        }, 1000);
      }

      checkAccess();
    </script>
  </body>
</html>
<!DOCTYPE html>
<html lang="vi">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Focus10 Thi</title>
    <link
      href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css"
      rel="stylesheet"
    />
    <style>
      /* Basic body setup */
      body {
        font-family: "Roboto", sans-serif;
        background-color: #fafafa;
        color: #2e2e2e;
        margin: 0;
        padding: 0;
        display: flex;
        flex-direction: column;
        min-height: 100vh;
      }

      header {
        background-color: #ffffff;
        padding: 20px 40px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      .logo {
        font-size: 28px;
        font-weight: 700;
        color: #4a90e2;
      }

      nav a {
        color: #2e2e2e;
        margin: 0 20px;
        font-size: 16px;
        text-decoration: none;
        font-weight: 500;
      }

      nav a:hover {
        color: #4a90e2;
      }

      .search-bar {
        display: flex;
        align-items: center;
        gap: 10px;
      }

      .search-bar input {
        padding: 8px 12px;
        border: 1px solid #ccc;
        border-radius: 4px;
        font-size: 14px;
      }

      .search-bar button {
        padding: 8px 12px;
        background-color: #4a90e2;
        color: white;
        border: none;
        border-radius: 4px;
        cursor: pointer;
      }

      .container {
        padding-top: 50px;
        padding-bottom: 50px;
        flex-grow: 1;
      }

      .upload-sections-wrapper {
        display: flex;
        flex-wrap: wrap;
        gap: 30px;
      }

      .upload-section-wrapper {
        flex: 1 1 300px;
      }

      .upload-section {
        background-color: white;
        padding: 30px;
        border-radius: 8px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        margin-bottom: 30px;
      }

      .upload-section h3 {
        font-size: 24px;
        margin-bottom: 20px;
        font-weight: 600;
        color: #2e2e2e;
      }

      footer {
        background-color: #ffffff;
        padding: 20px;
        text-align: center;
      }

      #logoutLink {
        display: none;
        cursor: pointer;
        font-weight: 500;
      }

      #accountName {
        display: none;
        margin-left: 10px;
        font-weight: 500;
        color: #4a90e2;
      }
    </style>
  </head>
  <body>
    <header>
      <div class="logo">Focus10</div>
      <nav>
        <a href="gioi-thieu.html">Giới Thiệu</a>
        <a href="danh-muc.html">Danh Mục Đề Thi</a>
        <a href="bo-de-thi-thu.html">Bộ Đề Thi Thử</a>
        <a href="tai-lieu-on-tap.html">Tài Liệu Ôn Tập</a>
        <a href="dang-ky.html" id="registerLink">Đăng Ký</a>
        <a href="dang-nhap.html" id="loginLink">Đăng Nhập</a>
        <span id="logoutLink">Đăng Xuất</span>
        <span id="accountName"></span>
      </nav>
      <div class="search-bar">
        <input
          type="text"
          id="searchInput"
          placeholder="Search..."
          aria-label="Search"
        />
        <button id="searchButton">Search</button>
      </div>
    </header>

    <div class="container">
      <h1>Welcome to Focus10</h1>
      <p>This is the homepage of the Focus10 platform.</p>
      <div class="upload-sections-wrapper">
        <div class="upload-section-wrapper">
          <div class="upload-section">
            <h3>Danh Mục Đề Thi</h3>
            <p>Click here to upload or view all categories of exam papers.</p>
            <a href="danh-muc.html" class="btn btn-primary">Go to Danh Mục</a>
          </div>
        </div>

        <div class="upload-section-wrapper">
          <div class="upload-section">
            <h3>Bộ Đề Thi Thử</h3>
            <p>Click here to upload or view all the trial exam sets.</p>
            <a href="bo-de-thi-thu.html" class="btn btn-primary"
              >Go to Bộ Đề Thi Thử</a
            >
          </div>
        </div>

        <div class="upload-section-wrapper">
          <div class="upload-section">
            <h3>Tài Liệu Ôn Tập</h3>
            <p>Click here to upload or view all the study materials.</p>
            <a href="tai-lieu-on-tap.html" class="btn btn-primary"
              >Go to Tài Liệu Ôn Tập</a
            >
          </div>
        </div>
      </div>
    </div>

    <footer>
      <p>&copy; 2025 Focus10. All rights reserved.</p>
    </footer>

    <script>
      document
        .getElementById("searchButton")
        .addEventListener("click", function () {
          const searchTerm = document
            .getElementById("searchInput")
            .value.trim();
          if (searchTerm) {
            window.location.href = `search-results.html?query=${encodeURIComponent(
              searchTerm
            )}`;
          }
        });

      function getUsers() {
        const users = localStorage.getItem("users");
        return users ? JSON.parse(users) : [];
      }

      function saveUsers(users) {
        localStorage.setItem("users", JSON.stringify(users));
      }

      function registerUser(event) {
        event.preventDefault();
        const username = document.getElementById("register-username").value;
        const password = document.getElementById("register-password").value;
        const confirmPassword =
          document.getElementById("confirm-password").value;

        if (password !== confirmPassword) {
          alert("Mật khẩu xác nhận không khớp. Vui lòng thử lại.");
          return;
        }

        const users = getUsers();
        const userExists = users.some((user) => user.username === username);

        if (userExists) {
          alert("Tên đăng nhập đã tồn tại. Vui lòng chọn tên khác.");
        } else {
          users.push({ username, password });
          saveUsers(users);
          alert("Đăng ký thành công! Chuyển hướng đến trang đăng nhập.");
          window.location.href = "dang-nhap.html";
        }
      }

      function loginUser(event) {
        event.preventDefault();
        const username = document.getElementById("login-username").value;
        const password = document.getElementById("login-password").value;
        const users = getUsers();
        const user = users.find(
          (user) => user.username === username && user.password === password
        );

        if (user) {
          localStorage.setItem("currentUser", username);
          alert("Đăng nhập thành công! Chuyển hướng đến trang chủ.");
          window.location.href = "index.html";
        } else {
          alert("Sai tên đăng nhập hoặc mật khẩu. Vui lòng thử lại.");
        }
      }

      function checkLoginStatus() {
        const currentUser = localStorage.getItem("currentUser");
        const logoutLink = document.getElementById("logoutLink");
        const loginLink = document.getElementById("loginLink");
        const registerLink = document.getElementById("registerLink");
        const accountName = document.getElementById("accountName");

        if (currentUser) {
          loginLink.style.display = "none";
          registerLink.style.display = "none";
          logoutLink.style.display = "inline";
          accountName.style.display = "inline";
          accountName.textContent = `(${currentUser})`;
          logoutLink.addEventListener("click", function () {
            localStorage.removeItem("currentUser");
            window.location.href = "dang-nhap.html";
          });
        } else {
          loginLink.style.display = "inline";
          registerLink.style.display = "inline";
          logoutLink.style.display = "none";
          accountName.style.display = "none";
        }
      }

      checkLoginStatus();
    </script>
  </body>
</html>
