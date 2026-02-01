<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Will You Be My Valentine, Kemyia?</title>
  <style>
    body {
      background: pink;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Comic Sans MS', cursive;
    }

    .card {
      background: white;
      padding: 40px;
      border-radius: 20px;
      text-align: center;
      box-shadow: 0 10px 25px rgba(0,0,0,0.2);
      position: relative;
      width: 350px;
    }

    .heart {
      width: 100px;
      height: 90px;
      position: relative;
      margin: 0 auto 20px;
      transform: rotate(-45deg);
      background: red;
      animation: pulse 1.2s infinite;
    }

    .heart::before,
    .heart::after {
      content: "";
      width: 100px;
      height: 90px;
      background: red;
      border-radius: 50%;
      position: absolute;
    }

    .heart::before {
      top: -50px;
      left: 0;
    }

    .heart::after {
      left: 50px;
      top: 0;
    }

    @keyfr
