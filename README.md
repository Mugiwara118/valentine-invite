# valentine-invite
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Valentine's Invitation</title>
    <meta name="viewport" content="width=device-width, initial-scale=1">

    <style>
        /* ==== Reset & Base ==== */
        *, *::before, *::after { box-sizing: border-box; margin:0; padding:0; }
        body {
            font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
            background: linear-gradient(135deg, #ff9a9e 0%, #fad0c4 100%);
            color: #444;
            min-height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 2rem;
        }

        /* ==== Card ==== */
        .card {
            background: #fff;
            border-radius: 1rem;
            box-shadow: 0 12px 24px rgba(0,0,0,0.15);
            max-width: 500px;
            width: 100%;
            overflow: hidden;
            text-align: center;
            padding: 2rem 1.5rem;
        }

        .card img {
            max-width: 100%;
            border-radius: .5rem;
        }

        h1 {
            font-size: 2.2rem;
            margin-top: 1rem;
            color: #d63384;
        }

        p {
            margin: 1rem 0;
            line-height: 1.6;
        }

        /* ==== Details ==== */
        .details {
            margin-top: 1.5rem;
            background: #ffe5e9;
            padding: 1rem;
            border-radius: .5rem;
        }

        .details strong {
            color: #c2185b;
        }

        /* ==== Button ==== */
        .rsvp-btn {
            margin-top: 1.5rem;
            display: inline-block;
            background: #d63384;
            color: #fff;
            text-decoration: none;
            padding: .8rem 1.5rem;
            border-radius: .4rem;
            transition: background .3s ease;
        }

        .rsvp-btn:hover {
            background: #b31b6b;
        }

        /* ==== Responsive ==== */
        @media (max-width: 480px) {
            h1 { font-size: 1.8rem; }
        }
    </style>
</head>

<body>
    <section class="card">
        <!-- Replace the src with your own romantic image -->
        <img src="https://images.unsplash.com/photo-1513708929399-47ec7d6aaf9f?auto=format&fit=crop&w=800&q=80" alt="Valentine hearts">

        <h1>You're Invited!</h1>

        <p>
            Join us for a cozy Valentine's celebration filled with love, laughter, and sweet treats.
        </p>

        <div class="details">
            <p><strong>Date:</strong> February 14, 2026</p>
            <p><strong>Time:</strong> 7:00 PM – 10:00 PM</p>
            <p><strong>Location:</strong> 123 Romance Avenue, Heartville</p>
        </div>

        <a href="mailto:you@example.com?subject=RSVP%20-%20Valentine%27s%20Celebration" class="rsvp-btn">RSVP via Email</a>
    </section>
</body>
</html>
