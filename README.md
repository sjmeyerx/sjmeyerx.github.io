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
            font-family: 'Inter', 'Segoe UI', sans-serif;
            line-height: 1.7;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 3rem 1.5rem;
            color: #333;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            gap: 2rem;
        }
        
        .box {
            background: white;
            border-radius: 20px;
            padding: 3rem;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.3);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        
        .box:hover {
            transform: translateY(-5px);
            box-shadow: 0 25px 70px rgba(0, 0, 0, 0.4);
        }
        
        h2 {
            color: #667eea;
            font-size: 2.2rem;
            margin-bottom: 1.5rem;
            text-align: center;
            font-weight: 700;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }
        
        p {
            font-size: 1.1rem;
            margin-bottom: 1rem;
            color: #555;
            line-height: 1.8;
        }
        
        .highlight-boxes {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }
        
        .highlight {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1.5rem;
            border-radius: 12px;
            text-align: center;
            box-shadow: 0 8px 20px rgba(102, 126, 234, 0.3);
        }
        
        .highlight h3 {
            font-size: 1.3rem;
            margin-bottom: 0.5rem;
        }
        
        .highlight p {
            color: rgba(255, 255, 255, 0.95);
            font-size: 0.95rem;
        }
        
        .form-group {
            margin-bottom: 1.5rem;
        }
        
        label {
            display: block;
            margin-bottom: 0.5rem;
            font-weight: 600;
            color: #333;
            font-size: 1rem;
        }
        
        input, textarea {
            width: 100%;
            padding: 0.9rem;
            border: 2px solid #e0e0e0;
            border-radius: 10px;
            font-size: 1rem;
            font-family: inherit;
            transition: border-color 0.3s ease;
        }
        
        input:focus, textarea:focus {
            outline: none;
            border-color: #667eea;
        }
        
        textarea {
            resize: vertical;
            min-height: 130px;
        }
        
        button {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1.1rem 2.5rem;
            border: none;
            border-radius: 10px;
            font-size: 1.1rem;
            font-weight: 600;
            cursor: pointer;
            width: 100%;
            transition: transform 0.2s ease, box-shadow 0.3s ease;
            box-shadow: 0 8px 20px rgba(102, 126, 234, 0.3);
        }
        
        button:hover {
            transform: translateY(-2px);
            box-shadow: 0 12px 30px rgba(102, 126, 234, 0.4);
        }
        
        button:active {
            transform: translateY(0);
        }
        
        header {
            text-align: center;
            color: white;
            margin-bottom: 2rem;
        }
        
        header h1 {
            font-size: 3rem;
            font-weight: 800;
            text-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
            margin-bottom: 0.5rem;
        }
        
        header p {
            font-size: 1.3rem;
            color: rgba(255, 255, 255, 0.95);
            text-shadow: 0 2px 10px rgba(0, 0, 0, 0.2);
        }
        
        @media (max-width: 768px) {
            body {
                padding: 2rem 1rem;
            }
            
            .box {
                padding: 2rem;
            }
            
            header h1 {
                font-size: 2.2rem;
            }
            
            h2 {
                font-size: 1.8rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Open Source Business Solutions</h1>
        <p>Affordable, Sustainable Technology for Small Business</p>
    </header>

    <div class="container">
        <div class="box">
            <h2>Switching to Open Source Solutions</h2>
            <p>Switching to open-source business solutions and Linux operating systems can transform your small business's bottom line while enhancing security and flexibility. By eliminating expensive licensing fees for proprietary software like Windows and Microsoft Office, you can redirect thousands of dollars annually toward growth initiatives, marketing, or hiring.</p>
            
            <p>Open-source alternatives like LibreOffice, Linux distributions, and tools such as Nextcloud or Odoo deliver enterprise-grade functionality without the recurring costs, while giving you complete control over your data and systems. Linux systems are renowned for their stability, security, and resistance to malware—meaning less downtime, fewer IT headaches, and reduced need for costly antivirus subscriptions.</p>
            
            <div class="highlight-boxes">
                <div class="highlight">
                    <h3>💰 Cost Savings</h3>
                    <p>Eliminate licensing fees</p>
                </div>
                <div class="highlight">
                    <h3>🔒 Security</h3>
                    <p>Enhanced protection</p>
                </div>
                <div class="highlight">
                    <h3>♻️ Revive Hardware</h3>
                    <p>Extend equipment life</p>
                </div>
                <div class="highlight">
                    <h3>🚀 Independence</h3>
                    <p>No vendor lock-in</p>
                </div>
            </div>
        </div>

        <div class="box">
            <h2>Our Mission</h2>
            <p>We empower small businesses to break free from costly technology constraints by delivering accessible, sustainable open-source solutions that maximize existing resources and minimize expenses. Through hands-on migration services, hardware revitalization, comprehensive training, and AI-enhanced internal support development, we transform outdated equipment into productive assets and convert recurring software costs into long-term savings.</p>
            
            <p>Our commitment is to provide personalized, on-site expertise that not only transitions businesses to Linux and open-source platforms, but equips their teams with the knowledge and tools to maintain technological independence. We believe every small business deserves enterprise-level capability without enterprise-level costs, and we're dedicated to proving that sustainable, secure, and cost-effective technology isn't just possible—it's practical.</p>
            
            <p>By breathing new life into existing hardware, eliminating vendor lock-in, and fostering internal technical competency, we help our clients redirect their resources from IT overhead to business growth, creating a foundation for resilient, future-proof operations.</p>
        </div>

        <div class="box">
            <h2>Get Started Today</h2>
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
    </div>

    <script>
        document.getElementById('contactForm').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Thank you for your message! We will contact you soon.');
            this.reset();
        });
    </script>
</body>
</html>
