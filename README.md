<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <svg fill="none" viewBox="0 0 600 300" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
    <foreignObject width="100%" height="100%">
      <div xmlns="http://www.w3.org/1999/xhtml">
        <style>
          @keyframes hi  {
              0% { transform: rotate( 0.0deg) }
             10% { transform: rotate(14.0deg) }
             20% { transform: rotate(-8.0deg) }
             30% { transform: rotate(14.0deg) }
             40% { transform: rotate(-4.0deg) }
             50% { transform: rotate(10.0deg) }
             60% { transform: rotate( 0.0deg) }
            100% { transform: rotate( 0.0deg) }
          }
  
          .container {
            background-color: black;
  
            width: 100%;
            height: 300px;
            padding: 10px 20px;
            display: flex;
            flex-direction: column;
            justify-content: start;
            align-items: start;
            color: white;
  
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
          }
  
          .hi {
            animation: hi 1.5s linear -0.5s infinite;
            display: inline-block;
            transform-origin: 70% 70%;
          }
  
          @media (prefers-reduced-motion) {
            .hi {
              animation: none;
            }
          }
        </style>
  
        <div class="container">
          <h1>Hi I'm Sheersh <div class="hi">👋</div></h1>
          
          <p>An aspiring fullstack developer from India.</p>
          
          <ul>
            <li>🔭 I’m currently working on MERN STACK</li>
            <li>🌱 I’m currently learning MERN STACK</li>
            <li>💬 My other skills : Figma | Blender </li>
            <li>📫 How to reach me saxenasheersh1@gmail.com</li>
          </ul>
        </div>
      </div>
    </foreignObject>
  </svg>
</body>
</html>
