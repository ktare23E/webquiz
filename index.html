<?php
$questions = [
    1 => [
        "question" => "What does HTML stand for?",
        "choices" => ["Hyperlinks and Text Markup Language", "Home Tool Markup Language", "HyperText Markup Language", "Hyper Transfer Markup Language"],
        "answer" => 2
    ],
    2 => [
        "question" => "Which language is used for styling web pages?",
        "choices" => ["HTML", "PHP", "CSS", "MySQL"],
        "answer" => 2
    ],
    3 => [
        "question" => "Which is a server-side scripting language?",
        "choices" => ["JavaScript", "PHP", "HTML", "CSS"],
        "answer" => 1
    ],
    4 => [
        "question" => "What does CSS stand for?",
        "choices" => ["Computer Style Sheets", "Creative Style Sheets", "Cascading Style Sheets", "Colorful Style Sheets"],
        "answer" => 2
    ],
    5 => [
        "question" => "Which database is commonly used with PHP?",
        "choices" => ["MongoDB", "Oracle", "MySQL", "PostgreSQL"],
        "answer" => 2
    ],
    6 => [
        "question" => "Which HTML tag is used to create a hyperlink?",
        "choices" => ["<a>", "<link>", "<href>", "<url>"],
        "answer" => 0
    ],
    7 => [
        "question" => "Which protocol is used to transfer web pages?",
        "choices" => ["FTP", "HTTP", "SMTP", "TCP"],
        "answer" => 1
    ],
    8 => [
        "question" => "Which CSS property controls text size?",
        "choices" => ["font-style", "text-size", "font-size", "text-style"],
        "answer" => 2
    ],
    9 => [
        "question" => "Which HTML element is used for the largest heading?",
        "choices" => ["<h6>", "<h4>", "<h1>", "<head>"],
        "answer" => 2
    ],
    10 => [
        "question" => "Which symbol is used for variables in PHP?",
        "choices" => ["#", "$", "%", "&"],
        "answer" => 1
    ],
    11 => [
        "question" => "Which HTML tag is used to display images?",
        "choices" => ["<img>", "<image>", "<pic>", "<src>"],
        "answer" => 0
    ],
    12 => [
        "question" => "Which CSS property is used to change text color?",
        "choices" => ["background-color", "font-color", "color", "text-color"],
        "answer" => 2
    ],
    13 => [
        "question" => "Which PHP function is used to output text?",
        "choices" => ["print()", "echo()", "write()", "display()"],
        "answer" => 1
    ],
    14 => [
        "question" => "Which HTML tag is used for unordered lists?",
        "choices" => ["<ol>", "<ul>", "<li>", "<list>"],
        "answer" => 1
    ],
    15 => [
        "question" => "Which HTTP method is used to submit forms?",
        "choices" => ["GET", "POST", "SEND", "PUSH"],
        "answer" => 1
    ],
    16 => [
        "question" => "Which CSS property is used for layout (flexbox)?",
        "choices" => ["display", "float", "position", "align"],
        "answer" => 0
    ],
    17 => [
        "question" => "Which tag is used to create a table row?",
        "choices" => ["<td>", "<th>", "<tr>", "<table>"],
        "answer" => 2
    ],
    18 => [
        "question" => "Which language runs in the browser?",
        "choices" => ["PHP", "Python", "JavaScript", "MySQL"],
        "answer" => 2
    ],
    19 => [
        "question" => "Which file extension is used for PHP files?",
        "choices" => [".html", ".css", ".js", ".php"],
        "answer" => 3
    ],
    20 => [
        "question" => "Which tool is used to style responsive layouts?",
        "choices" => ["HTML", "CSS", "PHP", "MySQL"],
        "answer" => 1
    ],
];

$score = 0;
$submitted = isset($_POST['submit']);
?>

<!DOCTYPE html>
<html>
<head>
    <title>Web Dev Quiz</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/x-icon" href="./nmsc.png">

    <style>
        body {
            font-family: Arial, sans-serif;
            background: #f4f6f9;
            margin: 0;
            padding: 0;
        }

        .container {
            max-width: 800px;
            background: white;
            margin: 20px auto;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        h2 {
            text-align: center;
        }

        .question {
            margin-bottom: 15px;
            padding: 10px;
            border-bottom: 1px solid #ddd;
        }

        label {
            display: block;
            margin: 5px 0;
        }

        .correct { color: green; font-weight: bold; }
        .wrong { color: red; font-weight: bold; }

        .btn {
            width: 100%;
            padding: 12px;
            background: #3498db;
            border: none;
            color: white;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }

        .btn:hover {
            background: #2980b9;
        }

        @media (max-width: 600px) {
            body { padding: 10px; }
            .container { padding: 15px; }
        }
    </style>
</head>
<body>

<div class="container">
<h2>🧠 Web Development Quiz</h2>

<form method="post">

<?php foreach ($questions as $num => $q): ?>
    <div class="question">
        <p><strong><?= $num ?>. <?= $q['question'] ?></strong></p>
        
        <?php foreach ($q['choices'] as $index => $choice): ?>
            <label>
                <input type="radio" name="q<?= $num ?>" value="<?= $index ?>"
                <?= (isset($_POST["q$num"]) && $_POST["q$num"] == $index) ? "checked" : "" ?>>
                <?= htmlspecialchars($choice) ?>
            </label>
        <?php endforeach; ?>

        <?php
        if ($submitted) {
            if (isset($_POST["q$num"]) && $_POST["q$num"] == $q['answer']) {
                echo "<span class='correct'>✔ Correct</span>";
                $score++;
            } else {
                echo "<span class='wrong'>✘ Wrong</span>";
            }
        }
        ?>
    </div>
<?php endforeach; ?>

<br>
<button type="submit" name="submit" class="btn">Submit Quiz</button>

</form>

<?php if ($submitted): ?>
    <h3 style="text-align:center;">Your Score: <?= $score ?> / <?= count($questions) ?></h3>
<?php endif; ?>

</div>
</body>
</html>
