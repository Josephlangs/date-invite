<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Date Invitation</title>
    <style>
        body {
            font-family: 'Comic Sans MS', sans-serif;
            background-color: #ffebf7;
            margin: 0;
            padding: 0;
            color: #444;
        }
        .container {
            max-width: 600px;
            margin: 30px auto;
            padding: 20px;
            background: #fff;
            border-radius: 15px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
        }
        h1 {
            font-size: 24px;
            color: #ff66cc;
            margin-bottom: 10px;
        }
        p {
            font-size: 16px;
            color: #777;
        }
        form {
            margin-top: 20px;
        }
        label {
            font-weight: bold;
            display: block;
            margin: 15px 0 5px;
        }
        select, input, textarea, button {
            width: 90%;
            padding: 10px;
            margin-bottom: 15px;
            font-size: 14px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        select, textarea {
            resize: none;
        }
        button {
            background-color: #ff66cc;
            color: white;
            border: none;
            font-size: 16px;
            cursor: pointer;
        }
        button:hover {
            background-color: #e055aa;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>💖 Would You Go On a Date with Me? 💖</h1>
        <p>Please fill out the form below to plan our perfect day! 🥰</p>
        <form action="submit_date.php" method="POST">
            <!-- Date and Time -->
            <label for="date">When Are You Free?</label>
            <input type="datetime-local" id="date" name="date" required>

            <!-- Places to Go -->
            <label for="places">Where Would You Like to Go?</label>
            <select id="places" name="places" required>
                <option value="" disabled selected>Select a place...</option>
                <option value="SM San Pablo">SM San Pablo</option>
                <option value="SM Calamba">SM Calamba</option>
                <option value="SM Mall of Asia">SM Mall of Asia</option>
                <option value="Museums in SM Sta. Rosa">Museums in SM Sta. Rosa</option>
                <option value="Enchanted Kingdom">Enchanted Kingdom</option>
                <option value="Venice Grand Canal, Taguig">Venice Grand Canal, Taguig</option>
                <option value="Bonifacio Global City (BGC)">Bonifacio Global City (BGC)</option>
                <option value="Parks in Manila">Parks in Manila</option>
                <option value="Tagaytay City">Tagaytay City</option>
            </select>

            <!-- Restaurants -->
            <label for="restaurant">What Do You Want to Eat?</label>
            <select id="restaurant" name="restaurant" required>
                <option value="" disabled selected>Select a restaurant...</option>
                <option value="McDonald's">McDonald's</option>
                <option value="KFC">KFC</option>
                <option value="Jollibee">Jollibee</option>
                <option value="Ramen">Ramen</option>
                <option value="Sangyupsal">Sangyupsal</option>
                <option value="Fine Dining">Fine Dining</option>
                <option value="Local Street Food">Local Street Food</option>
            </select>

            <!-- Movie -->
            <label for="movie">What Movie Do You Want to Watch?</label>
            <textarea id="movie" name="movie" placeholder="Type the movie you'd like to see..." rows="2" required></textarea>

            <!-- Submit -->
            <button type="submit">Submit 💕</button>
        </form>
    </div>
</body>
</html>
