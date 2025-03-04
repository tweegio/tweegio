<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Perfil</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(135deg, #1e3a1e, #3a5a3a);
            color: white;
            text-align: center;
        }
        .container {
            padding: 50px;
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid white;
            animation: fadeIn 1.5s ease-in-out;
        }
        h1 {
            margin-top: 20px;
            font-size: 2.5rem;
            animation: slideIn 1s ease-in-out;
        }
        .social-icons {
            margin-top: 20px;
        }
        .social-icons a {
            margin: 10px;
            color: white;
            font-size: 1.5rem;
            transition: transform 0.3s ease-in-out;
        }
        .social-icons a:hover {
            transform: scale(1.2);
            color: #00aaff;
        }
        @keyframes fadeIn {
            from { opacity: 0; }
            to { opacity: 1; }
        }
        @keyframes slideIn {
            from { transform: translateY(-20px); opacity: 0; }
            to { transform: translateY(0); opacity: 1; }
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="https://via.placeholder.com/150" alt="Foto de perfil" class="profile-img">
        <h1>¡Hola, soy Sergio Pereira 👋!</h1>
        <p>Desarrollador Web | Backend | Frontend | Técnico Informático</p>
       <h2>About me:</h2>
<!--Intro start-->
<p align="left">

- I'm a Junior developer, computer technician and student of Computer Engineering.
- I'm currently working on some freelance and personal projects.
- 🌱 I'm currently learning computer security.
- 📫 How to reach me: **sergio.pereira.proyect@gmail.com**
- 😄 Pronouns: tweegio

</p>
<h2 >Tecnologías conocidas👨🏻‍💻</h2>
<!--tech stack icons-->
<p align="left">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=java,python,javascript,css,html,bootstrap,nodejs,mysql,sqlite,git,github,vscode,linux,ai,ps&perline=12" />
  </a>
</p>
<br>
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"> 
      <div class="social-icons">
            <a href="https://github.com/tuusuario" target="_blank"><i class="fab fa-github"></i></a>
            <a href="https://www.linkedin.com/in/tuusuario" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="mailto:tuemail@gmail.com" target="_blank"><i class="fas fa-envelope"></i></a>
        </div>
    </div>
</body>
</html>
Credit: [tweegio](https://github.com/tweegio)

Last Edited on: 03/08/2024
