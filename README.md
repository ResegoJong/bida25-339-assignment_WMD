# bida25-339-assignment_WMD<!DOCTYPE html>
<html>
<head>
    <title>Student Study Hub</title>
    <style>
        body { font-family: Arial; margin: 0; }
        header { background: purple; color: white; padding: 15px; text-align: center; }
        nav { background: #333; padding: 10px; text-align: center; }
        nav a { color: white; margin: 10px; text-decoration: none; }
        section { padding: 20px; }
    </style>
</head>

<body>

<header>
    <h1>Student Study Hub</h1>
</header>

<nav>
    <a href="index.html">Home</a>
    <a href="timetable.html">Timetable</a>
    <a href="flashcards.html">Flashcards</a>
    <a href="contact.html">Contact</a>
</nav>

<section>
    <h2>Welcome</h2>
    <p>This website helps students study, plan, and revise effectively.</p>

</section>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Timetable</title>
</head>
<body>

<h1>Study Timetable</h1>

<a href="index.html">Back Home</a>

<table border="1">
    <tr>
        <th>Day</th>
        <th>Subject</th>
    </tr>
    <tr>
        <td>Monday</td>
        <td>Mathematics</td>
    </tr>
    <tr>
        <td>Tuesday</td>
        <td>Computer Studies</td>
    </tr>
    <tr>
        <td>Wednesday</td>
        <td>Business Studies</td>
    </tr>
</table>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Flashcards</title>
    <style>
        body { font-family: Arial; text-align: center; }
        .card {
            width: 300px;
            margin: 50px auto;
            padding: 20px;
            background: #f4f4f4;
        }
    </style>
</head>
<body>

<h1>Flashcards</h1>

<a href="index.html">Back Home</a>

<div class="card">
    <h2>What is a computer?</h2>
    <p id="answer" style="display:none;">
        An electronic device that processes data.
    </p>

    <button onclick="showAnswer()">Show Answer</button>
</div>

<script>
function showAnswer() {
    document.getElementById("answer").style.display = "block";
}
</script>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
    <title>Contact</title>
</head>
<body>

<h1>Contact Us</h1>

<a href="index.html">Back Home</a>

<form>
    Name:<br>
    <input type="text"><br><br>

    Email:<br>
    <input type="email"><br><br>

    Message:<br>
    <textarea></textarea><br><br>

    <input type="submit" value="Send">
</form>

</body>
</html>

