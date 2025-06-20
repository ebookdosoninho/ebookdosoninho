## Hi there 👋

<!--
**ebookdosoninho/ebookdosoninho** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>10 Histórias para Crianças Dormirem - ÚLTIMAS HORAS!</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #2c3e50;
            overflow-x: hidden;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Countdown Banner */
        .countdown-banner {
            background: linear-gradient(45deg, #e74c3c, #c0392b);
            color: white;
            text-align: center;
            padding: 15px 0;
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            z-index: 1000;
            box-shadow: 0 2px 10px rgba(0,0,0,0.3);
            animation: pulse-red 2s infinite;
        }

        @keyframes pulse-red {
            0%, 100% { background: linear-gradient(45deg, #e74c3c, #c0392b); }
            50% { background: linear-gradient(45deg, #c0392b, #e74c3c); }
        }

        .countdown-text {
            font-weight: bold;
            font-size: 1.1em;
            margin-bottom: 5px;
        }

        .countdown-timer {
            font-size: 1.8em;
            font-weight: bold;
            font-family: 'Courier New', monospace;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        /* Header */
        .header {
            background: linear-gradient(135deg, #1a1a2e 0%, #16213e 50%, #0f3460 100%);
            color: white;
            text-align: center;
            padding: 120px 0 80px 0;
            margin-top: 80px;
            position: relative;
            overflow: hidden;
        }

        .header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: radial-gradient(circle at 30% 70%, rgba(255,215,0,0.1) 0%, transparent 50%),
                        radial-gradient(circle at 70% 30%, rgba(255,69,0,0.1) 0%, transparent 50%);
        }

        .header h1 {
            font-size: 3.8em;
            margin-bottom: 20px;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.5);
            position: relative;
            z-index: 2;
            background: linear-gradient(45deg, #ffd700, #ff6b35);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        .header .subtitle {
            font-size: 1.8em;
            margin-bottom: 30px;
            position: relative;
            z-index: 2;
            color: #ecf0f1;
        }

        .urgency-badge {
            background: linear-gradient(45deg, #ff4757, #ff3742);
            color: white;
            padding: 20px 40px;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.4em;
            display: inline-block;
            animation: shake 1s infinite;
            position: relative;
            z-index: 2;
            box-shadow: 0 10px 30px rgba(255, 71, 87, 0.4);
            border: 3px solid #fff;
        }

        @keyframes shake {
            0%, 100% { transform: translateX(0); }
            25% { transform: translateX(-5px); }
            75% { transform: translateX(5px); }
        }

        /* Social Proof Popups */
        .social-proof {
            position: fixed;
            bottom: 20px;
            left: 20px;
            background: white;
            padding: 15px 20px;
            border-radius: 10px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.2);
            z-index: 999;
            transform: translateX(-400px);
            transition: transform 0.5s ease;
            border-left: 5px solid #27ae60;
            max-width: 300px;
        }

        .social-proof.show {
            transform: translateX(0);
        }

        .social-proof-content {
            display: flex;
            align-items: center;
            gap: 15px;
        }

        .social-proof-avatar {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            background: linear-gradient(45deg, #3498db, #2980b9);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            flex-shrink: 0;
        }

        .social-proof-text {
            font-size: 0.9em;
            line-height: 1.4;
        }

        .social-proof-name {
            font-weight: bold;
            color: #2c3e50;
        }

        .social-proof-action {
            color: #27ae60;
            font-size: 0.85em;
        }

        /* Problem Section */
        .problem-section {
            background: linear-gradient(135deg, #ff6b6b 0%, #ee5a52 100%);
            color: white;
            padding: 100px 0;
            text-align: center;
            position: relative;
        }

        .problem-section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><circle cx="20" cy="20" r="2" fill="rgba(255,255,255,0.1)"/><circle cx="80" cy="40" r="3" fill="rgba(255,255,255,0.1)"/><circle cx="40" cy="80" r="2" fill="rgba(255,255,255,0.1)"/></svg>');
        }

        .problem-section h2 {
            font-size: 3.2em;
            margin-bottom: 40px;
            position: relative;
            z-index: 2;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .problem-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin: 50px 0;
            position: relative;
            z-index: 2;
        }

        .problem-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 15px;
            border: 1px solid rgba(255,255,255,0.2);
            transition: transform 0.3s ease;
        }

        .problem-card:hover {
            transform: translateY(-5px);
        }

        .problem-icon {
            font-size: 3em;
            margin-bottom: 20px;
        }

        .problem-card h4 {
            font-size: 1.4em;
            margin-bottom: 15px;
        }

        /* Solution Section */
        .solution-section {
            background: linear-gradient(135deg, #27ae60 0%, #2ecc71 100%);
            color: white;
            padding: 100px 0;
            text-align: center;
            position: relative;
        }

        .solution-section h2 {
            font-size: 3.2em;
            margin-bottom: 40px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .solution-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 30px;
            margin: 50px 0;
        }

        .solution-card {
            background: rgba(255,255,255,0.15);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 15px;
            border: 1px solid rgba(255,255,255,0.3);
            transition: transform 0.3s ease;
        }

        .solution-card:hover {
            transform: scale(1.05);
        }

        .solution-icon {
            font-size: 3em;
            margin-bottom: 20px;
        }

        /* Product Section */
        .product-section {
            padding: 100px 0;
            background: #f8f9fa;
            position: relative;
        }

        .product-showcase {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 60px;
            align-items: center;
            margin: 50px 0;
        }

        .product-mockup {
            position: relative;
            text-align: center;
        }

        .book-3d {
            width: 300px;
            height: 400px;
            background: linear-gradient(145deg, #667eea 0%, #764ba2 100%);
            border-radius: 15px;
            margin: 0 auto;
            position: relative;
            transform: perspective(1000px) rotateY(-15deg) rotateX(5deg);
            box-shadow: 
                20px 20px 60px rgba(0,0,0,0.3),
                inset 5px 5px 10px rgba(255,255,255,0.2);
            display: flex;
            align-items: center;
            justify-content: center;
            color: white;
            font-weight: bold;
            font-size: 1.5em;
            text-align: center;
            line-height: 1.4;
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: perspective(1000px) rotateY(-15deg) rotateX(5deg) translateY(0px); }
            50% { transform: perspective(1000px) rotateY(-15deg) rotateX(5deg) translateY(-10px); }
        }

        .product-details h3 {
            font-size: 2.8em;
            color: #2c3e50;
            margin-bottom: 30px;
            text-align: center;
        }

        .stories-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin: 40px 0;
        }

        .story-item {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            border-left: 4px solid #667eea;
            transition: transform 0.3s ease;
        }

        .story-item:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }

        .story-icon {
            font-size: 2em;
            margin-bottom: 10px;
        }

        /* Pricing Section */
        .pricing-section {
            background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
            color: white;
            padding: 100px 0;
            text-align: center;
            position: relative;
        }

        .pricing-container {
            max-width: 600px;
            margin: 0 auto;
        }

        .pricing-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(20px);
            padding: 60px 40px;
            border-radius: 20px;
            border: 2px solid rgba(255,255,255,0.2);
            position: relative;
            overflow: hidden;
        }

        .pricing-card::before {
            content: '';
            position: absolute;
            top: -50%;
            left: -50%;
            width: 200%;
            height: 200%;
            background: linear-gradient(45deg, transparent, rgba(255,215,0,0.1), transparent);
            animation: shine 3s infinite;
        }

        @keyframes shine {
            0% { transform: translateX(-100%) translateY(-100%) rotate(45deg); }
            100% { transform: translateX(100%) translateY(100%) rotate(45deg); }
        }

        .discount-badge {
            background: linear-gradient(45deg, #e74c3c, #c0392b);
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.2em;
            display: inline-block;
            margin-bottom: 30px;
            animation: pulse 2s infinite;
            position: relative;
            z-index: 2;
        }

        .old-price {
            font-size: 1.8em;
            text-decoration: line-through;
            opacity: 0.7;
            margin-bottom: 15px;
            position: relative;
            z-index: 2;
        }

        .new-price {
            font-size: 4.5em;
            font-weight: bold;
            margin: 20px 0;
            text-shadow: 3px 3px 6px rgba(0,0,0,0.3);
            background: linear-gradient(45deg, #ffd700, #ff6b35);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
            position: relative;
            z-index: 2;
        }

        .installments {
            font-size: 1.3em;
            margin-bottom: 40px;
            position: relative;
            z-index: 2;
        }

        /* CTA Button */
        .cta-button {
            background: linear-gradient(45deg, #ff4757, #ff3742);
            color: white;
            padding: 25px 60px;
            font-size: 1.8em;
            font-weight: bold;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            text-decoration: none;
            display: inline-block;
            margin: 30px 0;
            transition: all 0.3s ease;
            box-shadow: 0 15px 35px rgba(255, 71, 87, 0.4);
            text-transform: uppercase;
            letter-spacing: 1px;
            position: relative;
            z-index: 2;
            animation: pulse-button 2s infinite;
        }

        @keyframes pulse-button {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.05); }
        }

        .cta-button:hover {
            transform: translateY(-3px) scale(1.05);
            box-shadow: 0 20px 40px rgba(255, 71, 87, 0.6);
        }

        .cta-features {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin-top: 30px;
            flex-wrap: wrap;
            position: relative;
            z-index: 2;
        }

        .cta-feature {
            display: flex;
            align-items: center;
            gap: 10px;
            font-size: 1.1em;
        }

        /* Guarantee Section */
        .guarantee-section {
            background: #ecf0f1;
            padding: 80px 0;
            text-align: center;
        }

        .guarantee-box {
            background: white;
            padding: 50px;
            border-radius: 20px;
            max-width: 700px;
            margin: 0 auto;
            box-shadow: 0 20px 60px rgba(0,0,0,0.1);
            border: 3px solid #27ae60;
            position: relative;
        }

        .guarantee-badge {
            position: absolute;
            top: -30px;
            left: 50%;
            transform: translateX(-50%);
            background: #27ae60;
            color: white;
            padding: 15px 30px;
            border-radius: 50px;
            font-weight: bold;
            font-size: 1.2em;
        }

        /* Testimonials */
        .testimonials-section {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 100px 0;
        }

        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin: 50px 0;
        }

        .testimonial-card {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(10px);
            padding: 30px;
            border-radius: 15px;
            border: 1px solid rgba(255,255,255,0.2);
        }

        .testimonial-stars {
            color: #ffd700;
            font-size: 1.5em;
            margin-bottom: 15px;
        }

        .testimonial-text {
            font-style: italic;
            margin-bottom: 20px;
            font-size: 1.1em;
            line-height: 1.6;
        }

        .testimonial-author {
            font-weight: bold;
            text-align: right;
        }

        /* FAQ Section */
        .faq-section {
            padding: 100px 0;
            background: white;
        }

        .faq-container {
            max-width: 800px;
            margin: 0 auto;
        }

        .faq-item {
            background: #f8f9fa;
            margin: 20px 0;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }

        .faq-question {
            background: #2c3e50;
            color: white;
            padding: 25px;
            cursor: pointer;
            font-weight: bold;
            font-size: 1.2em;
            transition: background 0.3s ease;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .faq-question:hover {
            background: #34495e;
        }

        .faq-question::after {
            content: '+';
            font-size: 1.5em;
            transition: transform 0.3s ease;
        }

        .faq-question.active::after {
            transform: rotate(45deg);
        }

        .faq-answer {
            padding: 0 25px;
            max-height: 0;
            overflow: hidden;
            transition: all 0.3s ease;
            background: white;
        }

        .faq-answer.active {
            padding: 25px;
            max-height: 200px;
        }

        /* Footer CTA */
        .footer-cta {
            background: linear-gradient(135deg, #ff4757 0%, #ff3742 100%);
            color: white;
            padding: 80px 0;
            text-align: center;
        }

        .footer-cta h2 {
            font-size: 3em;
            margin-bottom: 30px;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .footer-cta p {
            font-size: 1.3em;
            margin-bottom: 40px;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
        }

        /* Footer */
        .footer {
            background: #2c3e50;
            color: white;
            padding: 40px 0;
            text-align: center;
        }

        .footer p {
            margin: 10px 0;
            opacity: 0.8;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            .countdown-timer {
                font-size: 1.4em;
            }
            
            .header h1 {
                font-size: 2.5em;
            }
            
            .header .subtitle {
                font-size: 1.3em;
            }
            
            .urgency-badge {
                font-size: 1.1em;
                padding: 15px 25px;
            }
            
            .problem-section h2,
            .solution-section h2 {
                font-size: 2.2em;
            }
            
            .product-showcase {
                grid-template-columns: 1fr;
                gap: 40px;
            }
            
            .book-3d {
                width: 250px;
                height: 350px;
            }
            
            .stories-grid {
                grid-template-columns: 1fr;
            }
            
            .new-price {
                font-size: 3em;
            }
            
            .cta-button {
                font-size: 1.4em;
                padding: 20px 40px;
            }
            
            .cta-features {
                flex-direction: column;
                gap: 15px;
            }
            
            .social-proof {
                left: 10px;
                right: 10px;
                max-width: none;
            }
            
            .problem-grid,
            .solution-grid {
                grid-template-columns: 1fr;
            }
            
            .testimonials-grid {
                grid-template-columns: 1fr;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 0 15px;
            }
            
            .header h1 {
                font-size: 2em;
            }
            
            .countdown-text {
                font-size: 0.9em;
            }
            
            .countdown-timer {
                font-si
