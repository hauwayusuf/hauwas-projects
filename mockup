<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- displays site properly based on user's device -->
  
  <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
  
  <title>Frontend Mentor | Four card feature section</title>

  <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
  <style>
    .attribution { 
      font-size: 11px; 
      text-align: center; 
    }

    .attribution a { 
      color: hsl(228, 45%, 44%); 
    }

    body {
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f0f0f0;
    }

    .container {
      text-align: center;
      max-width: 800px;
      margin: auto;
    }

    .light-heading {
      font-weight: lighter;
      margin: 0;
    }

    .bold-heading {
      font-weight: bold;
      margin: 0;
    }

    .description {
      margin: 20px 0;
    }

    .box-container {
      display: grid;
      grid-template-columns: 1fr 1fr;
      grid-template-rows: auto auto;
      gap: 10px;
      justify-items: center;
      align-items: center;
    }

    .box {
      width: 200px;
      padding: 30px;
      background-color: white;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
      text-align: left;
      position: relative;
    }

    .box p {
      margin: 10px 0 0;
    }

    .blue {
      border-top: 5px solid blue;
      grid-column: 1 / span 2;
      grid-row: 1;
      height: 110px;
    }

    .brown {
      border-top: 5px solid brown;
      grid-column: 1;
      grid-row: 2;
      height: 110px;
    }

    .orange {
      border-top: 5px solid orange;
      grid-column: 2;
      grid-row: 2;
      height: 110px;
    }

    .navy {
      border-top: 5px solid navy;
      grid-column: 1 / span 3;
      grid-row: 3;
      height: 110px;
    }

    .icon {
      position: absolute;
      right: 10px;
      bottom: 10px;
      width: 24px;
      height: 24px;
    }

    footer {
      margin-top: auto;
      text-align: center;
    }

    /* Media Query for Mobile Devices */
    @media (max-width: 768px) {
      .box-container {
        grid-template-columns: 1fr;
        grid-template-rows: repeat(4, auto);
        gap: 10px;
      }

      .box {
        width: 100%; /* Make boxes full width */
        max-width: 100%;
        padding: 20px; /* Adjust padding for mobile */
      }

      .blue {
        grid-column: 1;
        grid-row: 1;
      }

      .brown {
        grid-column: 1;
        grid-row: 2;
      }

      .orange {
        grid-column: 1;
        grid-row: 3;
      }

      .navy {
        grid-column: 1;
        grid-row: 4;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <h1 class="light-heading">Reliable, Efficient Delivery</h1>
    <h2 class="bold-heading">Powered by Technology</h2>
    <p class="description">Our artificial intelligence powered tools use millions of project data points to ensure that your project is successful.</p>
    <div class="box-container">
      <div class="box blue">
        <strong>Supervisor</strong>
        <p>Monitors activity to identify project roadblocks.</p>
        <div class="icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24"><g fill="none"><path fill="#676E74" d="M56.842 7.158c-9.526-9.563-24.902-9.525-34.428 0-8.025 8.026-9.45 20.44-3.525 30.003l-2.513 2.55-1.356 6.144 4.214 4.214 5.093-2.408 2.512-2.55a24.254 24.254 0 0030.003-3.525c9.563-9.526 9.525-24.902 0-34.428z"/><path fill="#474F54" d="M24.327 47.661l2.512-2.55a24.254 24.254 0 0030.003-3.525c9.563-9.526 9.525-24.902 0-34.428l-40.26 40.26 2.652 2.651 5.093-2.408z"/><path fill="#64E1DC" d="M54.213 9.787a20.56 20.56 0 00-14.585-6.041C28.236 3.746 19 12.98 19 24.372a20.564 20.564 0 006.041 14.586 20.564 20.564 0 0014.586 6.04c11.392 0 20.626-9.234 20.626-20.626a20.56 20.56 0 00-6.041-14.585z"/><path fill="#00C8C8" d="M60.254 24.372a20.56 20.56 0 00-6.041-14.585l-29.17 29.17A20.564 20.564 0 0039.627 45c11.392 0 20.626-9.235 20.626-20.627z"/><path fill="#EFEFF4" d="M56.239 23.41c-.184-.307-2.98-4.914-7.281-8.368-2.63-2.113-5.822-3.796-9.33-3.796-9.242 0-16.314 11.669-16.61 12.165l-.576.961.575.961c.184.309 2.98 4.916 7.28 8.37 2.631 2.112 5.823 3.795 9.33 3.795 9.243 0 16.315-11.668 16.612-12.165l.574-.96-.574-.962z"/><path fill="#DADAE5" d="M56.239 25.333l.574-.96-.574-.962c-.184-.308-2.98-4.915-7.281-8.369l-18.66 18.66c2.63 2.113 5.822 3.796 9.33 3.796 9.242 0 16.314-11.668 16.61-12.165z"/><path fill="#64E1DC" d="M43.604 20.396a5.607 5.607 0 00-3.976-1.65 5.632 5.632 0 00-5.626 5.626c0 1.551.631 2.958 1.65 3.976a5.609 5.609 0 003.976 1.65 5.632 5.632 0 005.625-5.626c0-1.55-.63-2.957-1.649-3.976z"/><path fill="#00C8C8" d="M45.253 24.372c0-1.55-.63-2.957-1.649-3.976l-7.952 7.952a5.608 5.608 0 003.976 1.65 5.632 5.632 0 005.625-5.626z"/></g></svg>
        </div>
      </div>
      <div class="box brown">
        <strong>Team Builder</strong>
        <p>Scans our talent network to create the optimal team for your project.</p>
        <div class="icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26"><path fill="#F45B69" d="M40.546 20.917c0 8.086-6.56 14.646-14.646 14.646S11.254 29.003 11.254 20.917c0-8.085 6.56-14.645 14.646-14.645s14.646 6.56 14.646 14.645"/><path fill="#FF708D" d="M25.9 6.272c-.338 0-.673.017-1.005.045 7.782.508 13.895 7.011 13.895 14.6 0 7.588-6.113 14.092-13.895 14.6.332.028.667.045 1.005.045 8.085 0 14.645-6.56 14.645-14.645 0-8.085-6.56-14.645-14.645-14.645"/><path fill="#F45B69" d="M36.334 35.885c-.716-3.178-3.078-4.003-5.297-4.003-.38 0-.777.045-1.187.138-1.195.267-2.428.403-3.666.403s-2.471-.136-3.666-.403c-.41-.093-.807-.138-1.187-.138-2.219 0-4.581.825-5.297 4.003-.072.318-.118.682-.145 1.093 2.605 1.981 5.817 3.158 9.295 3.158 3.478 0 6.69-1.177 9.295-3.158-.027-.41-.073-.775-.145-1.093"/><path fill="#FF708D" d="M24.895 6.316c-7.785 0-14.6 6.815-14.6 14.6 0 7.784 6.815 14.6 14.6 14.6.34 0 .675-.017 1.008-.045-7.782-.508-13.895-7.012-13.895-14.6 0-7.589 6.113-14.092 13.895-14.6-.333-.028-.668-.045-1.008-.045"/><path fill="#F45B69" d="M18.126 28.52c-1.648 0-2.98-1.332-2.98-2.98s1.332-2.98 2.98-2.98 2.98 1.332 2.98 2.98-1.332 2.98-2.98 2.98"/><path fill="#FF708D" d="M33.673 28.52c-1.648 0-2.98-1.332-2.98-2.98s1.332-2.98 2.98-2.98 2.98 1.332 2.98 2.98-1.332 2.98-2.98 2.98"/></svg>
        </div>
      </div>
      <div class="box orange">
        <strong>Karma</strong>
        <p>Regularly evaluates our talent to ensure quality.</p>
        <div class="icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26"><path fill="#FFD52E" d="M22.436 43.44c-.826-3.577-3.553-4.502-6.11-4.502-.438 0-.897.053-1.37.162-1.379.308-2.799.465-4.222.465-1.424 0-2.844-.157-4.222-.465a6.324 6.324 0 00-1.37-.162c-2.557 0-5.284.925-6.11 4.502-.084.364-.134.782-.164 1.253 2.953 2.248 6.597 3.591 10.566 3.591 3.969 0 7.613-1.343 10.566-3.591-.03-.471-.08-.89-.164-1.253"/><path fill="#FFEB7B" d="M8.27 40.351a7.82 7.82 0 011.188-.138c1.195.267 2.428.403 3.666.403s2.471-.136 3.666-.403c.41-.093.807-.138 1.187-.138 2.22 0 4.582.825 5.298 4.003.071.318.118.682.144 1.093 2.244-1.706 4.163-3.847 5.584-6.305-5.937-3.157-9.453-9.341-9.453-16.087 0-3.473.903-6.805 2.616-9.75A19.54 19.54 0 0025 6.49a19.54 19.54 0 00-4.064-.424c-10.813 0-19.6 8.788-19.6 19.6 0 7.217 3.96 13.509 10.023 16.912.337-.278.752-.47 1.311-.47 1.167 0 2.301.702 3.017 2.243M35.224 23.33c0 6.773-5.507 12.28-12.28 12.28-6.772 0-12.28-5.507-12.28-12.28 0-6.772 5.508-12.28 12.28-12.28 6.773 0 12.28 5.508 12.28 12.28"/><path fill="#FFD52E" d="M35.224 22.34c-3.476 0-6.302-2.826-6.302-6.302S31.748 9.736 35.224 9.736c3.476 0 6.302 2.826 6.302 6.302s-2.826 6.302-6.302 6.302"/><path fill="#FFEB7B" d="M25 22.84c.833 0 1.51-4.772 1.51-10.655C26.51 6.772 25.833 2 25 2c-.832 0-1.51 4.772-1.51 10.185 0 5.883.678 10.655 1.51 10.655"/></svg>
        </div>
      </div>
      <div class="box navy">
        <strong>Calculator</strong>
        <p>Uses data from past projects to provide better delivery estimates.</p>
        <div class="icon">
          <svg xmlns="http://www.w3.org/2000/svg" width="26" height="26"><g fill="none"><path fill="#484A4D" d="M37.69 5.328H12.31c-3.556 0-6.482 2.925-6.482 6.482v27.38c0 3.557 2.926 6.482 6.482 6.482h25.38c3.557 0 6.482-2.925 6.482-6.482V11.81c0-3.557-2.925-6.482-6.482-6.482z"/><path fill="#6C6E71" d="M24.218 3.846c-.38 0-.753.045-1.123.121h14.595c3.556 0 6.482 2.925 6.482 6.482v27.38c0 3.557-2.926 6.482-6.482 6.482H23.096c.37.076.743.121 1.123.121h14.595c3.556 0 6.482-2.925 6.482-6.482V11.81c0-3.557-2.926-6.482-6.482-6.482H24.218z"/><path fill="#73777F" d="M38.345 5.328H13.655c-3.557 0-6.482 2.925-6.482 6.482v27.38c0 3.557 2.925 6.482 6.482 6.482h24.69c3.557 0 6.482-2.925 6.482-6.482V11.81c0-3.557-2.925-6.482-6.482-6.482z"/><path fill="#94989F" d="M25.263 3.846c-.38 0-.755.045-1.124.121h14.206c3.556 0 6.482 2.925 6.482 6.482v27.38c0 3.557-2.926 6.482-6.482 6.482H23.994c.37.076.743.121 1.124.121h14.206c3.556 0 6.482-2.925 6.482-6.482V11.81c0-3.557-2.926-6.482-6.482-6.482H25.263z"/><path fill="#73777F" d="M43.573 13.46H7.427c-1.074 0-1.944-.87-1.944-1.944V8.91c0-1.075.87-1.944 1.944-1.944h36.146c1.074 0 1.944.869 1.944 1.944v2.605c0 1.074-.87 1.944-1.944 1.944z"/><path fill="#94989F" d="M43.573 11.974H7.427c-1.074 0-1.944-.87-1.944-1.944V7.424c0-1.074.87-1.944 1.944-1.944h36.146c1.074 0 1.944.87 1.944 1.944v2.605c0 1.075-.87 1.945-1.944 1.945z"/><path fill="#484A4D" d="M26.172 5.14h-8.344a2.021 2.021 0 110-4.041h8.344a2.021 2.021 0 110 4.04"/><path fill="#94989F" d="M29.172 38.391H21.83a1.01 1.01 0 110-2.02h7.344a1.01 1.01 0 010 2.02M35.172 38.391h-2.344a1.01 1.01 0 110-2.02h2.344a1.01 1.01 0 110 2.02M35.172 32.391h-2.344a1.01 1.01 0 110-2.02h2.344a1.01 1.01 0 110 2.02M35.172 26.391h-2.344a1.01 1.01 0 110-2.02h2.344a1.01 1.01 0 110 2.02M29.172 32.391H21.83a1.01 1.01 0 110-2.02h7.344a1.01 1.01 0 110 2.02M29.172 26.391H21.83a1.01 1.01 0 110-2.02h7.344a1.01 1.01 0 110 2.02M23.172 20.391h-2.344a1.01 1.01 0 110-2.02h2.344a1.01 1.01 0 110 2.02M17.172 20.391h-2.344a1.01 1.01 0 110-2.02h2.344a1.01 1.01 0 110 2.02M11.172 20.391h-2.344a1.01 1.01 0 110-2.02h2.344a1.01 1.01 0 110 2.02"/></g></svg>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
