<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Montañas y Ríos</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0;
            background-color: #eef2f3;
            color: #333;
        }

        header {
            background: linear-gradient(to right, #4facfe, #00f2fe);
            color: white;
            text-align: center;
            padding: 2rem 1rem;
        }

        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }

        .galeria {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            padding: 40px;
        }

        .imagen {
            position: relative;
            overflow: hidden;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0,0,0,0.2);
            transition: transform 0.3s ease;
        }

        .imagen:hover {
            transform: scale(1.03);
        }

        .imagen img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        .imagen p {
            position: absolute;
            bottom: 0;
            background: rgba(0, 0, 0, 0.5);
            color: white;
            width: 100%;
            padding: 10px;
            text-align: center;
            margin: 0;
            font-size: 1.1rem;
        }

        fo
