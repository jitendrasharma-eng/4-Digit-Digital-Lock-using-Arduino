<h1 align="center">🔐 4-Digit Digital Lock using Arduino</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Arduino-Project-blue?style=flat-square" alt="Arduino Badge">
  <img src="https://img.shields.io/badge/Status-Working-green?style=flat-square" alt="Status Badge">
</p>

<p>This project is a <strong>4-digit digital lock</strong> implemented using an <strong>Arduino Uno</strong>, <strong>4x4 keypad</strong>, <strong>16x2 LCD</strong>, and <strong>servo motor</strong>. The lock system allows users to enter a predefined PIN using the keypad. If the correct PIN is entered, the servo motor unlocks the system; otherwise, a buzzer alerts for incorrect attempts.</p>

<hr>

<h2>🔧 Components Used</h2>
<ul>
  <li>Arduino Uno (Microcontroller)</li>
  <li>4x4 Keypad (for PIN entry)</li>
  <li>16x2 LCD Display (to show input and status)</li>
  <li>Servo Motor (for locking/unlocking)</li>
  <li>Buzzer (for incorrect PIN alert)</li>
  <li>NPN Transistor (to drive the buzzer)</li>
  <li>Resistors & Wires (for connections)</li>
  <li>Breadboard (for circuit assembly)</li>
</ul>

<h2>⚙️ Working Principle</h2>
<ol>
  <li>The user enters a 4-digit PIN using the keypad.</li>
  <li>The LCD display shows the entered PIN.</li>
  <li>If the entered PIN matches the pre-defined PIN:
    <ul>
      <li>✅ The servo motor rotates, unlocking the system.</li>
      <li>✅ The LCD displays a success message.</li>
    </ul>
  </li>
  <li>If the PIN is incorrect:
    <ul>
      <li>❌ The buzzer sounds as an alert.</li>
      <li>❌ The LCD displays an error message.</li>
    </ul>
  </li>
  <li>The system allows multiple attempts and can be reset.</li>
</ol>

<h2>🔌 Circuit Connections</h2>
<ul>
  <li><strong>Keypad:</strong> Connected to Arduino D1-D7 pins</li>
  <li><strong>LCD Display:</strong> Connected via Arduino A0-A5 pins</li>
  <li><strong>Servo Motor:</strong> Signal wire connected to D9</li>
  <li><strong>Buzzer:</strong> Controlled using an NPN transistor, connected to D8</li>
</ul>

<h2>📝 How to Use</h2>
<ol>
  <li>Power the system using USB or external power supply.</li>
  <li>Enter the 4-digit PIN using the keypad (default is <strong>4 5 6 7</strong> – you can change this in code).</li>
  <li>If the PIN is correct, the servo unlocks the system.</li>
  <li>If the PIN is incorrect, the buzzer sounds an alert.</li>
  <li>Reset or re-enter the PIN to try again.</li>
</ol>

<h2>💡 Applications</h2>
<ul>
  <li>✅ Home & office digital door locks</li>
  <li>✅ Safe security systems</li>
  <li>✅ Industrial equipment locking</li>
</ul>

<hr>

<h3>Simulation link:<h6>https://www.tinkercad.com/things/0UV1DYWhlVg-copy-of-password-door-lock-security-system/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard%2Fdesigns%2Fcircuits</h6></h3>
<hr>
📬 Author: Jitendra Sharma 📧 Email: jitendrasharma7409@gmail.com 🔗 Follow for more: https://github.com/jitendrasharma-eng?tab=repositories | www.youtube.com/@ECodeLab-mv4jm | linkedin.com/in/jitendra-sharma-484072248 [https://www.linkedin.com/in/jitendra-sharma-484072248?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BdRzhEpUKQSqQh6%2Fm6UayRw%3D%3D]
