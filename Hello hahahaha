<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Date Request</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f9f9f9;
            color: #333;
        }
        h1 {
            text-align: center;
            color: #444;
        }
        form {
            max-width: 400px;
            margin: 0 auto;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            background-color: #fff;
        }
        label {
            display: block;
            margin-bottom: 8px;
            font-weight: bold;
        }
        input, select, textarea {
            width: 100%;
            padding: 8px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            width: 100%;
            padding: 10px;
            background-color: #28a745;
            color: white;
            font-size: 16px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
    <h1>Would You Go On a Date with Me?</h1>
    <form action="submit_date.php" method="POST">
        <label for="date">Date and Time You're Free</label>
        <input type="datetime-local" id="date" name="date" required>

        <label for="places">Places You Want to Go</label>
        <textarea id="places" name="places" placeholder="e.g., Enchanted Kingdom, parks, cafes..." rows="3" required></textarea>

        <label for="restaurant">Places You Want to Eat</label>
        <textarea id="restaurant" name="restaurant" placeholder="e.g., Bistro Charlemagne, local street food..." rows="3" required></textarea>

        <label for="movie">Movie You Want to Watch</label>
        <textarea id="movie" name="movie" placeholder="e.g., The Marvels, a rom-com, or any specific movie..." rows="2" required></textarea>

        <button type="submit">Submit</button>
    </form>
</body>
</html>
