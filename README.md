<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Date Request</title>
    <style>
        body {
            font-family: 'Comic Sans MS', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffe6f7;
            color: #333;
        }
        .container {
            max-width: 500px;
            margin: 50px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
        }
        h1 {
            color: #ff66cc;
        }
        form label {
            display: block;
            margin: 15px 0 5px;
            font-weight: bold;
        }
        select, input, button {
            width: 90%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 14px;
        }
        button {
            background-color: #ff66cc;
            color: white;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }
        button:hover {
            background-color: #e055aa;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🌸 Date Invitation 🌸</h1>
        <p>Would you go on a date with me? 😊</p>
        <form action="submit_date.php" method="POST">
            <!-- Date and Time -->
            <label for="date">Date and Time You're Free</label>
            <input type="datetime-local" id="date" name="date" required>

            <!-- Places to Go -->
            <label for="places">Where Do You Want to Go?</label>
            <select id="places" name="places" required>
                <option value="" disabled selected>Choose a place...</option>
                <option value="SM">SM Mall</option>
                <option value="Manila">Manila City</option>
                <option value="Park">Parks</option>
                <option value="Enchanted Kingdom">Enchanted Kingdom</option>
                <option value="Beach">Beach</option>
            </select>

            <!-- Places to Eat -->
            <label for="restaurant">What Do You Want to Eat?</label>
            <select id="restaurant" name="restaurant" required>
                <option value="" disabled selected>Choose a restaurant...</option>
                <option value="McDonald's">McDonald's</option>
                <option value="KFC">KFC</option>
                <option value="Jollibee">Jollibee</option>
                <option value="Ramen">Ramen</option>
                <option value="Bistro Charlemagne">Bistro Charlemagne</option>
            </select>

            <!-- Movies -->
            <label for="movie">Which Movie Do You Want to Watch?</label>
            <select id="movie" name="movie" required>
                <option value="" disabled selected>Choose a movie...</option>
                <option value="The Marvels">The Marvels</option>
                <option value="Five Nights at Freddy's">Five Nights at Freddy's</option>
                <option value="Wish">Wish</option>
                <option value="Napoleon">Napoleon</option>
                <option value="Wish Dragon">Wish Dragon</option>
            </select>

            <!-- Submit -->
            <button type="submit">Submit 💖</button>
        </form>
    </div>
</body>
</html>
