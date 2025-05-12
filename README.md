<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Learn C Programming</title>
  <link rel="stylesheet" href="style.css">
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #fff8f0;
      color: #333;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #ffcbcb;
      text-align: center;
      padding: 20px;
      color: #2d2d2d;
    }

    header h1 {
      margin: 0;
    }

    main {
      max-width: 800px;
      margin: auto;
      padding: 20px;
    }

    h2 {
      color: #444;
    }

    pre {
      background-color: #f0f8ff;
      padding: 15px;
      border-left: 4px solid #a0d8ef;
      overflow-x: auto;
    }

    form {
      background-color: #f9f9f9;
      padding: 20px;
      margin-top: 30px;
      border-radius: 10px;
    }

    input, textarea {
      width: 100%;
      padding: 10px;
      margin-top: 8px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    button {
      background-color: #ff85a1;
      color: white;
      padding: 10px 20px;
      margin-top: 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    button:hover {
      background-color: #ff6f8c;
    }

    footer {
      background-color: #ffcbcb;
      text-align: center;
      padding: 10px;
      color: #444;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <header>
    <h1>Learn C Programming</h1>
    <p>Easy guide for beginners</p>
  </header>

  <main>
    <section>
      <h2>What is C?</h2>
      <p>C is a programming language used for creating software. It's great for beginners because it's easy to learn and very powerful.</p>
      <ul>
        <li><b>int</b> — used for numbers</li>
        <li><b>char</b> — used for characters</li>
        <li><b>printf()</b> — used to print text to the screen</li>
      </ul>
    </section>

    <section>
      <h2>Example: Hello World</h2>
      <pre>
#include &lt;stdio.h&gt;

int main() {
    printf("Hello, World!");
    return 0;
}
      </pre>

      <h2>Example: Adding Two Numbers</h2>
      <pre>
#include &lt;stdio.h&gt;

int main() {
    int a = 5, b = 10;
    int sum = a + b;
    printf("Sum is %d", sum);
    return 0;
}
      </pre>
    </section>

    <section>
      <h2>Contact Us</h2>
      <form>
        <label for="name">Name:</label>
        <input type="text" id="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" required>

        <label for="message">Message:</label>
        <textarea id="message" rows="4" required></textarea>

        <button type="submit">Send</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Learn C Programming</p>
  </footer>

</body>
</html># Aakriti-pokhrel
Project for cs
