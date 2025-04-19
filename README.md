<!DOCTYPE html>
<html lang="el">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SynCreate</title>
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Raleway', sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            background-color: #f6f8fa;
            color: #3c3c3d;
        }
        nav {
            background-color: #ffffff;
            padding: 10px;
            text-align: center;
            position: sticky;
            top: 0;
            z-index: 1000;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        nav a {
            color: #3c3c3d;
            margin: 0 15px;
            text-decoration: none;
            font-weight: 600;
        }
        nav a:hover {
            color: #627eea;
        }
        .hero-section {
            background-image: url('./coppy.PNG'); /* Βεβαιωθείτε ότι η διαδρομή είναι σωστή */
            background-size: cover;
            background-position: center;
            height: 600px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            position: relative;
            color: white;
        }
        .hero-section::before {
            content: "";
            position: absolute;
            top: 0; left: 0; right: 0; bottom: 0;
            background: rgba(0, 0, 0, 0.4);
            z-index: 1;
        }
        .hero-content {
            position: relative;
            z-index: 2;
            max-width: 800px;
            padding: 20px;
        }
        .hero-content h1 {
            font-size: 2.8rem;
            font-weight: 700;
            margin-bottom: 20px;
        }
        .hero-content p {
            font-size: 1.2rem;
            font-weight: 400;
        }
        .button {
            display: inline-block;
            background-color: #627eea;
            color: white;
            padding: 12px 24px;
            text-decoration: none;
            border-radius: 6px;
            font-weight: 600;
            margin-top: 25px;
            cursor: pointer; /* Προσθέτουμε cursor για να δείξουμε ότι είναι κουμπί */
        }
        section {
            padding: 40px 20px;
            max-width: 900px;
            margin: auto;
        }
        h2 {
            color: #627eea;
            font-weight: 700;
        }
        ul, ol {
            margin-left: 20px;
        }
        .categories-list {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }
        .categories-list div {
            background-color: #fff;
            border: 1px solid #ddd;
            padding: 15px;
            border-radius: 8px;
            text-align: center;
            font-weight: 600;
            box-shadow: 0 1px 4px rgba(0,0,0,0.05);
        }
        footer {
            background-color: #3c3c3d;
            color: #aaa;
            text-align: center;
            padding: 20px;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>
    <nav>
        <a href="#home">Αρχική</a>
        <a href="#about">Τι είναι</a>
        <a href="#how">Πώς λειτουργεί</a>
        <a href="#join">Συμμετοχή</a>
        <a href="#contact">Επικοινωνία</a>
    </nav>

    <section class="hero-section" id="home">
        <div class="hero-content">
            <h1>SynCreate</h1>
            <p>Η πλατφόρμα που ενώνει ιδέες, ανθρώπους και δυνατότητες.</p>
            <a href="#" class="button" id="start-journey-button">Ξεκίνα το ταξίδι σου</a>
        </div>
    </section>

    <section id="about">
        <h2>Τι είναι το SynCreate;</h2>
        <p>Το SynCreate είναι μια διαδικτυακή πλατφόρμα συνεργασίας και κοινής χρηματοδότησης. Βοηθά ανθρώπους με οραματικές ιδέες να συνδεθούν με άλλους που πιστεύουν στο ίδιο όνειρο, να δημιουργήσουν ομάδες και να μετατρέψουν τις ιδέες τους σε πραγματικότητα – μαζί.</p>
    </section>

    <section id="how">
        <h2>Πώς λειτουργεί;</h2>
        <ol>
            <li><strong>Μοιράσου την ιδέα σου:</strong> Επέλεξε κατηγορία, γράψε περιγραφή και τι χρειάζεσαι.</li>
            <li><strong>Βρες συμμάχους:</strong> Μέσα από τη μηχανή αντιστοίχισης ή την αναζήτηση.</li>
            <li><strong>Υλοποιήστε μαζί:</strong> Οργάνωσε την ομάδα, εξασφάλισε κεφάλαιο και ξεκινήστε!</li>
        </ol>
    </section>

    <section id="categories">
        <h2>Κατηγορίες Επιχειρηματικών Ιδεών</h2>
        <div class="categories-list">
            <div>Τεχνολογία</div>
            <div>Εκπαίδευση</div>
            <div>Υγεία & Ευεξία</div>
            <div>Περιβάλλον & Βιωσιμότητα</div>
            <div>Καλλιτεχνικά & Πολιτισμός</div>
            <div>Κοινωνικές Επιχειρήσεις</div>
            <div>Αγροδιατροφή</div>
            <div>Τουρισμός & Φιλοξενία</div>
        </div>
    </section>

    <section id="join">
        <h2>Για ποιους είναι;</h2>
        <p>Το SynCreate είναι για δημιουργούς, οραματιστές, μικροεπενδυτές, φοιτητές, επαγγελματίες και κάθε άνθρωπο που θέλει να συνεργαστεί πάνω σε κάτι που τον εμπνέει.</p>
    </section>

    <section id="contact">
        <h2>Ξεκίνα τώρα</h2>
        <p>Θες να ξεκινήσεις το δικό σου project; Ψάχνεις μια ιδέα να συμμετέχεις;</p>
        <a href="#" class="button">Γράψου στη λίστα ενδιαφέροντος</a>
    </section>

    <footer>
        <p>© 2025 SynCreate. Με αγάπη και καινοτομία από ανθρώπους για ανθρώπους.</p>
    </footer>

    <script>
        const startJourneyButton = document.getElementById('start-journey-button');

        startJourneyButton.addEventListener('click', (event) => {
            event.preventDefault(); // Αποτρέπουμε την προεπιλεγμένη συμπεριφορά του συνδέσμου

            // Δημιουργούμε το HTML περιεχόμενο του πρώτου αρχείου
            const newContent = `
                <!DOCTYPE html>
                <html lang="el">
                <head>
                    <meta charset="UTF-8">
                    <meta name="viewport" content="width=device-width, initial-scale=1.0">
                    <title>SynCreate - Βρείτε Συνεργάτες &amp; Κεφάλαιο</title>
                    <style>
                        body {
                            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
                            margin: 0;
                            padding: 0;
                            background-color: #f8f9fa;
                            color: #343a40;
                            line-height: 1.6;
                        }
                        header {
                            background-color: #007bff;
                            color: white;
                            padding: 2em 0;
                            text-align: center;
                            margin-bottom: 2em;
                        }
                        header h1 {
                            font-size: 2.5em;
                            margin-bottom: 0.5em;
                        }
                        .tagline {
                            font-style: italic;
                            color: #eee;
                        }
                        .main-content {
                            padding: 20px;
                            text-align: center;
                        }
                        .start-section {
                            background-color: #e9ecef;
                            padding: 3em 20px;
                            border-radius: 8px;
                            margin-bottom: 2em;
                        }
                        .start-section h2 {
                            color: #007bff;
                            margin-bottom: 1em;
                        }
                        #start-button {
                            display: inline-block;
                            padding: 12px 24px;
                            background-color: #28a745;
                            color: white;
                            text-decoration: none;
                            border-radius: 5px;
                            font-weight: bold;
                            cursor: pointer;
                            transition: background-color 0.3s ease;
                            border: none;
                            font-size: 1em;
                        }
                        #start-button:hover {
                            background-color: #218838;
                        }
                        #options-container {
                            display: none; /* Initially hidden */
                            margin-top: 20px;
                        }
                        .option-button {
                            display: inline-block;
                            padding: 10px 20px;
                            background-color: #6c757d;
                            color: white;
                            text-decoration: none;
                            border-radius: 5px;
                            font-weight: bold;
                            cursor: pointer;
                            margin: 0 10px;
                            border: none;
                            font-size: 1em;
                            transition: background-color 0.3s ease;
                        }
                        .option-button:hover {
                            background-color: #5a6268;
                        }
                        .secondary-options-container {
                            display: none; /* Initially hidden */
                            margin-top: 20px;
                        }
                        .secondary-option {
                            display: block;
                            margin-bottom: 10px;
                        }
                        .secondary-option button {
                            display: inline-block;
                            padding: 10px 20px;
                            background-color: #007bff;
                            color: white;
                            text-decoration: none;
                            border-radius: 5px;
                            font-weight: bold;
                            cursor: pointer;
                            border: none;
                            font-size: 1em;
                            transition: background-color 0.3s ease;
                        }
                        .secondary-option button:hover {
                            background-color: #0056b3;
                        }
                        footer {
                            background-color: #343a40;
                            color: white;
                            text-align: center;
                            padding: 1em 0;
                            position: fixed;
                            bottom: 0;
                            width: 100%;
                        }
                    </style>
                </head>
                <body>

                    <header>
                        <h1>SynCreate</h1>
                        <p class="tagline">Συνεργαστείτε για να Καινοτομήσετε.</p>
                    </header>

                    <main class="main-content">
                        <section class="start-section">
                            <h2>Βρείτε τους Συνεργάτες και το Κεφάλαιο που Χρειάζεστε</h2>
                            <p>Κάντε το πρώτο βήμα για να μετατρέψετε την ιδέα σας σε πραγματικότητα.</p>
                            <button id="start-button-inner">Ξεκινήστε Τώρα</button>

                            <div id="options-container">
                                <h3>Έχετε μια Ιδέα;</h3>
                                <button class="option-button" id="idea-button">Έχω μια Ιδέα</button>
                                <button class="option-button" id="capital-button">Ψάχνω Κεφάλαιο</button>
                            </div>

                            <div id="idea-options" class="secondary-options-container">
                                <h3>Τι ψάχνετε;</h3>
                                <div class="secondary-option">
                                    <button id="find-partners-idea">Βρείτε Ανθρώπους με την Ίδια Ιδέα</button>
                                </div>
                                <div class="secondary-option">
                                    <button id="find-needs-idea">Βρείτε τους Ανθρώπους που Χρειάζεστε Τώρα</button>
                                </div>
                            </div>

                            <div id="capital-options" class="secondary-options-container">
                                <h3>Τι σας ενδιαφέρει;</h3>
                                <div class="secondary-option">
                                    <button id="invest-ideas-capital">Επενδύστε σε Έξυπνες Καινοτόμες Ιδέες</button>
                                </div>
                                <div class="secondary-option">
                                    <button id="find-capital-capital">Βρείτε Κεφάλαιο Τώρα</button>
                                </div>
                            </div>
                        </section>
                    </main>

                    <footer>
                        <p>&copy; 2025 SynCreate - Δημιουργήθηκε για Εσάς</p>
                    </footer>

                    <script>
                        const startButtonInner = document.getElementById('start-button-inner');
                        const optionsContainerInner = document.getElementById('options-container');
                        const ideaButtonInner = document.getElementById('idea-button');
                        const capitalButtonInner = document.getElementById('capital-button');
                        const ideaOptionsInner = document.getElementById('idea-options');
                        const capitalOptionsInner = document.getElementById('capital-options');
                        const findPartnersIdeaButtonInner = document.getElementById('find-partners-idea');
                        const findNeedsIdeaButtonInner = document.getElementById('find-needs-idea');
                        const investIdeasCapitalButtonInner = document.getElementById('invest-ideas-capital');
                        const findCapitalCapitalButtonInner = document.getElementById('find-capital-capital');

                        startButtonInner.addEventListener('click', () => {
                            startButtonInner.style.display = 'none';
                            optionsContainerInner.style.display = 'block';
                            ideaOptionsInner.style.display = 'none';
                            capitalOptionsInner.style.display = 'none';
                        });

                        ideaButtonInner.addEventListener('click', () => {
                            optionsContainerInner.style.display = 'none';
                            ideaOptionsInner.style.display = 'block';
                            capitalOptionsInner.style.display = 'none';
                        });

                        capitalButtonInner.addEventListener('click', () => {
                            optionsContainerInner.style.display = 'none';
                            capitalOptionsInner.style.display = 'block';
                            ideaOptionsInner.style.display = 'none';
                        });

                        findPartnersIdeaButtonInner.addEventListener('click', () => {
                            alert('Λειτουργία για εύρεση ανθρώπων με την ίδια ιδέα (θα υλοποιηθεί σύντομα).');
                            // Εδώ θα μπορούσε να υπάρχει κώδικας για μετάβαση σε μια σελίδα/λειτουργία εύρεσης συνεργατών με κοινές ιδέες.
                        });

                        findNeedsIdeaButtonInner.addEventListener('click', () => {
                            alert('Λειτουργία για εύρεση των ανθρώπων
