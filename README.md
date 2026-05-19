

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DE-HUDY’S-SALOON</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: url('WhatsApp Image 2026-05-19 at 9.48.16 AM.jpeg') center/cover no-repeat;
        }
        header {
            background:url(WhatsApp Image 2026-05-19 at 9.48.16 AM.jpeg) 
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
        header h1 {
            margin: 0 0 10px;
            font-size: 2.8rem;
        }
        header p {
            margin: 10px 0;
            font-size: 1.1rem;
        }
        .container {
            max-width: 1100px;
            margin: 0 auto;
            padding: 25px 20px;
        }
        .grid {
            display: grid;
            gap: 25px;
        }
        .card {
            background: white;
            border-radius: 18px;
            box-shadow: 0 12px 30px rgba(0,0,0,0.08);
            padding: 25px;
        }
        h2 {
            margin-top: 0;
            color: #3a1f4a;
        }
        .contact-list,
        .features-list {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        .contact-list li,
        .features-list li {
            margin-bottom: 12px;
            line-height: 1.6;
        }
        .feature-item {
            display: flex;
            align-items: flex-start;
            gap: 12px;
        }
        .feature-item::before {
            content: '•';
            color: #f18f01;
            font-weight: bold;
            margin-top: 2px;
        }
        .hero {
            display: grid;
            grid-template-columns: 1.4fr 1fr;
            gap: 30px;
            align-items: center;
        }
        .hero-image {
            border-radius: 20px;
            overflow: hidden;
            min-height: 260px;
            background: url('WhatsApp Image 2026-05-19 at 9.51.58 AM.jpeg') center/cover no-repeat;
        }
        .button-primary {
            display: inline-block;
            background: #7b4b9f;
            color: white;
            padding: 14px 24px;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: transform .2s ease, box-shadow .2s ease;
        }
        .button-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 12px 25px rgba(123,75,159,0.25);
        }
        .section-split {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 30px;
        }
        .section-split img {
            width: 100%;
            border-radius: 18px;
            object-fit: cover;
        }
        form {
            display: grid;
            gap: 18px;
        }
        label {
            font-weight: 600;
        }
        input, select, textarea {
            width: 100%;
            padding: 14px 16px;
            border: 1px solid #dcd3d0;
            border-radius: 14px;
            font-size: 1rem;
            resize: vertical;
        }
        textarea {
            min-height: 120px;
        }
        .form-row {
            display: grid;
            grid-template-columns: repeat(2, minmax(0, 1fr));
            gap: 18px;
        }
        .form-row .full-width {
            grid-column: 1 / -1;
        }
        .submit-btn {
            background: #f18f01;
            border: none;
            color: white;
            padding: 16px 20px;
            font-size: 1rem;
            border-radius: 999px;
            cursor: pointer;
            transition: background .2s ease;
        }
        .submit-btn:hover {
            background: #d07600;
        }
        .note {
            font-size: 0.95rem;
            color: #5a4b57;
        }
        footer {
            text-align: center;
            padding: 24px 20px;
            color: #5a4b57;
            font-size: 0.95rem;
        }
        @media (max-width: 860px) {
            .hero, .section-split {
                grid-template-columns: 1fr;
            }
            .form-row {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>DE HUDY’S SALOON <style>font-color: #7b4b9f;</style></h1>
            <p>Quality hair styling, beauty services, wigs and hair products in Nungua Kanta.</p>
            <p>Call: <strong>050 935 6744</strong> · <strong>024 405 8208</strong></p>
            <a href="#booking" class="button-primary">Book an Appointment</a>
        </div>
    </header>

    <main class="container">
        <section class="hero card">
            <div>
                <h2>Welcome to DE HUDY’S SALOON</h2>
                <p>At DE HUDY’S SALOON, we offer beautiful hair styling, expert treatment, braiding, weaving, wig installation, and premium beauty grooming services. Shop top-quality wigs, bundles and hair care products while you relax in our friendly salon space.</p>
                <ul class="contact-list">
                    <li><strong>Location:</strong> Maritime ACADEMY RD, Nungua Kanta</li>
                    <li><strong>GPS:</strong> G-042-6160</li>
                    <li><strong>Email:</strong> <a href="mailto:hudysde@gmail.com">hudysde@gmail.com</a></li>
                </ul>
            </div>
            <div class="hero-image" aria-label="Salon service image"></div>
        </section>

        <section class="section-split">
            <div class="card">
                <h2>Salon Services</h2>
                <div class="features-list">
                    <div class="feature-item">Hair styling</div>
                    <div class="feature-item">Hair treatment</div>
                    <div class="feature-item">Braiding and weaving</div>
                    <div class="feature-item">Wig installation</div>
                    <div class="feature-item">Beauty and grooming services</div>
                    <div class="feature-item">Makeup, lashes, manicure and pedicure</div>
                </div>
            </div>
            <div class="card">
                <h2>Products for Sale</h2>
                <div class="features-list">
                    <div class="feature-item">High-quality wigs</div>
                    <div class="feature-item">Hair bundles</div>
                    <div class="feature-item">Hair care products</div>
                    <div class="feature-item">Beauty accessories</div>
                </div>
            </div>
        </section>

        <section id="booking" class="card">
            <h2>Book an Appointment</h2>
            <p class="note">Complete the form below and our team will contact you to confirm your appointment.</p>
            <form id="bookingForm">
                <div class="form-row">
                    <label for="name">Full Name</label>
                    <input type="text" id="name" name="name" placeholder="Your name" required>
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" name="phone" placeholder="050 935 6744" required>
                </div>
                <div class="form-row">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" name="email" placeholder="you@example.com" required>
                    <label for="service">Preferred Service</label>
                    <select id="service" name="service" required>
                        <option value="">Select a service</option>
                        <option>Hair styling</option>
                        <option>Hair treatment</option>
                        <option>Braiding and weaving</option>
                        <option>Wig installation</option>
                        <option>Makeup, nails, lashes</option>
                    </select>
                </div>
                <div class="form-row">
                    <label for="date">Preferred Date</label>
                    <input type="date" id="date" name="date" required>
                    <label for="time">Preferred Time</label>
                    <input type="time" id="time" name="time" required>
                </div>
                <div>
                    <label for="message">Additional Details</label>
                    <textarea id="message" name="message" placeholder="Describe your booking request..." required></textarea>
                </div>
                <button type="submit" class="submit-btn">Submit Booking Request</button>
                <p id="responseMessage" class="note" style="display:none; margin-top: 12px;"></p>
            </form>
        </section>
    </main>

    <footer>
        <p>DE HUDY’S SALOON · Maritime ACADEMY RD · Nungua Kanta · Call 050 935 6744 or 024 405 8208</p>
    </footer>

    <script>
        document.getElementById('bookingForm').addEventListener('submit', function(event) {
            event.preventDefault();
            const responseMessage = document.getElementById('responseMessage');
            responseMessage.style.display = 'block';
            responseMessage.textContent = 'Thank you! Your booking request has been captured. We will contact you shortly to confirm your appointment.';
            this.reset();
        });
    </script>
</body>
</html>
