<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Open Source Business Solutions</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        header {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            text-align: center;
            padding: 3rem 2rem;
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
        }
        
        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        section {
            max-width: 1100px;
            margin: 0 auto;
            padding: 4rem 2rem;
        }
        
        section:nth-child(even) {
            background-color: #f8f9fa;
        }
        
        h2 {
            color: #2c3e50;
            font-size: 2rem;
            margin-bottom: 1.5rem;
            text-align: center;
        }
        
        p {
            font-size: 1.1rem;
            margin-bottom: 1rem;
            text-align: justify;
        }
        
        .benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        
        .benefit-card {
            background: white;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .benefit-card h3 {
            color: #2980b9;
            margin-bottom: 0.5rem;
        }
        
        .contact-form {
            max-width: 600px;
            margin: 2rem auto;
            background: white;
            padding: 2rem;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: #2c3e50;
        }
        
        input, textarea {
            width: 100%;
            padding: 0.75rem;
            border: 1px solid #ddd;
            border-radius: 4px;
            font-size: 1rem;
            font-family: inherit;
        }
        
        textarea {
            resize: vertical;
            min-height: 120px;
        }
        
        button {
            background: #2980b9;
            color: white;
            padding: 1rem 2rem;
            border: none;
            border-radius: 4px;
            font-size: 1.1rem;
            cursor: pointer;
            width: 100%;
            transition: background 0.3s;
        }
        
        button:hover {
            background: #21618c;
        }
        
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
            padding: 2rem;
        }
    </style>
</head>
<body>
    <header>
        <h1>Open Source Business Solutions</h1>
        <p>Affordable, Sustainable Technology for Small Business</p>
    </header>

    <section id="benefits">
        <h2>Switching to Open Source Solutions</h2>
        <p>Switching to open-source business solutions and Linux operating systems can transform your small business's bottom line while enhancing security and flexibility. By eliminating expensive licensing fees for proprietary software like Windows and Microsoft Office, you can redirect thousands of dollars annually toward growth initiatives, marketing, or hiring. Open-source alternatives like LibreOffice, Linux distributions, and tools such as Nextcloud or Odoo deliver enterprise-grade functionality without the recurring costs, while giving you complete control over your data and systems.</p>
        
        <div class="benefits">
            <div class="benefit-card">
                <h3>💰 Cost Savings</h3>
                <p>Eliminate expensive licensing fees and redirect funds toward business growth.</p>
            </div>
            <div class="benefit-card">
                <h3>🔒 Enhanced Security</h3>
                <p>Linux systems are renowned for stability, security, and resistance to malware.</p>
            </div>
            <div class="benefit-card">
                <h3>♻️ Hardware Revival</h3>
                <p>Restore life to outdated machinery made obsolete by Windows 11 requirements.</p>
            </div>
            <div class="benefit-card">
                <h3>🚀 Complete Control</h3>
                <p>Avoid vendor lock-in and customize software to fit your exact workflow.</p>
            </div>
        </div>
    </section>

    <section id="mission">
        <h2>Our Mission</h2>
        <p>We empower small businesses to break free from costly technology constraints by delivering accessible, sustainable open-source solutions that maximize existing resources and minimize expenses. Through hands-on migration services, hardware revitalization, comprehensive training, and AI-enhanced internal support development, we transform outdated equipment into productive assets and convert recurring software costs into long-term savings.</p>
        
        <p>Our commitment is to provide personalized, on-site expertise that not only transitions businesses to Linux and open-source platforms, but equips their teams with the knowledge and tools to maintain technological independence. We believe every small business deserves enterprise-level capability without enterprise-level costs, and we're dedicated to proving that sustainable, secure, and cost-effective technology isn't just possible—it's practical.</p>
        
        <p>By breathing new life into existing hardware, eliminating vendor lock-in, and fostering internal technical competency, we help our clients redirect their resources from IT overhead to business growth, creating a foundation for resilient, future-proof operations.</p>
    </section>

    <section id="contact">
        <h2>Get Started Today</h2>
        <div class="contact-form">
            <form id="contactForm">
                <div class="form-group">
                    <label for="name">Name *</label>
                    <input type="text" id="name" name="name" required>
                </div>
                
                <div class="form-group">
                    <label for="email">Email *</label>
                    <input type="email" id="email" name="email" required>
                </div>
                
                <div class="form-group">
                    <label for="company">Company Name</label>
                    <input type="text" id="company" name="company">
                </div>
                
                <div class="form-group">
                    <label for="message">How can we help? *</label>
                    <textarea id="message" name="message" required></textarea>
                </div>
                
                <button type="submit">Send Message</button>
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2025 Open Source Business Solutions. All rights reserved.</p>
    </footer>

    <script>
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message! We will contact you soon.');
            this.reset();
        });
    </script>
</body>
</html>
