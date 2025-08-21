<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sean Callahan - Economics Research</title>
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
            background: linear-gradient(135deg, #f0f4ff 0%, #faf0ff 50%, #fff8f0 100%);
            position: relative;
            overflow-x: hidden;
        }

        /* Floating 3D objects in background */
        .floating-objects {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: -1;
        }

        .floating-object {
            position: absolute;
            border-radius: 8px;
            box-shadow: 0 8px 25px rgba(0, 0, 0, 0.15);
            transform-style: preserve-3d;
        }

        .floating-object::before {
            content: '';
            position: absolute;
            top: -6px;
            left: 6px;
            width: 100%;
            height: 100%;
            border-radius: inherit;
            transform: rotateX(25deg) rotateY(-20deg);
            z-index: -1;
            opacity: 0.6;
        }

        .floating-object::after {
            content: '';
            position: absolute;
            top: 6px;
            left: -6px;
            width: 100%;
            height: 100%;
            border-radius: inherit;
            transform: rotateX(-15deg) rotateY(25deg);
            z-index: -2;
            opacity: 0.3;
        }

        .floating-object.sphere {
            border-radius: 50%;
        }

        .floating-object.sphere::before,
        .floating-object.sphere::after {
            border-radius: 50%;
        }

        /* Fixed positioned objects with slow, wide movements */
        .object-1 {
            top: 8%;
            left: 5%;
            width: 70px;
            height: 50px;
            background: linear-gradient(135deg, rgba(102, 126, 234, 0.3), rgba(102, 126, 234, 0.1));
            animation: slowFloat1 25s ease-in-out infinite;
        }

        .object-1::before {
            background: linear-gradient(135deg, rgba(102, 126, 234, 0.2), rgba(102, 126, 234, 0.05));
        }

        .object-1::after {
            background: linear-gradient(135deg, rgba(102, 126, 234, 0.15), rgba(102, 126, 234, 0.03));
        }

        .object-2 {
            top: 20%;
            right: 8%;
            width: 60px;
            height: 60px;
            background: linear-gradient(135deg, rgba(253, 160, 133, 0.3), rgba(253, 160, 133, 0.1));
            animation: slowFloat2 30s ease-in-out infinite;
        }

        .object-2::before {
            background: linear-gradient(135deg, rgba(253, 160, 133, 0.2), rgba(253, 160, 133, 0.05));
        }

        .object-2::after {
            background: linear-gradient(135deg, rgba(253, 160, 133, 0.15), rgba(253, 160, 133, 0.03));
        }

        .object-3 {
            top: 35%;
            left: 75%;
            width: 45px;
            height: 45px;
            background: linear-gradient(135deg, rgba(240, 147, 251, 0.3), rgba(240, 147, 251, 0.1));
            border-radius: 50%;
            animation: slowFloat3 28s ease-in-out infinite;
        }

        .object-3::before {
            background: linear-gradient(135deg, rgba(240, 147, 251, 0.2), rgba(240, 147, 251, 0.05));
        }

        .object-3::after {
            background: linear-gradient(135deg, rgba(240, 147, 251, 0.15), rgba(240, 147, 251, 0.03));
        }

        .object-4 {
            top: 55%;
            left: 12%;
            width: 80px;
            height: 35px;
            background: linear-gradient(135deg, rgba(102, 126, 234, 0.25), rgba(102, 126, 234, 0.08));
            animation: slowFloat4 35s ease-in-out infinite;
        }

        .object-4::before {
            background: linear-gradient(135deg, rgba(102, 126, 234, 0.18), rgba(102, 126, 234, 0.04));
        }

        .object-4::after {
            background: linear-gradient(135deg, rgba(102, 126, 234, 0.12), rgba(102, 126, 234, 0.02));
        }

        .object-5 {
            top: 42%;
            left: 35%;
            width: 55px;
            height: 55px;
            background: linear-gradient(135deg, rgba(253, 160, 133, 0.25), rgba(253, 160, 133, 0.08));
            border-radius: 50%;
            animation: slowFloat5 22s ease-in-out infinite;
        }

        .object-5::before {
            background: linear-gradient(135deg, rgba(253, 160, 133, 0.18), rgba(253, 160, 133, 0.04));
        }

        .object-5::after {
            background: linear-gradient(135deg, rgba(253, 160, 133, 0.12), rgba(253, 160, 133, 0.02));
        }

        .object-6 {
            top: 68%;
            right: 20%;
            width: 65px;
            height: 40px;
            background: linear-gradient(135deg, rgba(240, 147, 251, 0.25), rgba(240, 147, 251, 0.08));
            animation: slowFloat6 32s ease-in-out infinite;
        }

        .object-6::before {
            background: linear-gradient(135deg, rgba(240, 147, 251, 0.18), rgba(240, 147, 251, 0.04));
        }

        .object-6::after {
            background: linear-gradient(135deg, rgba(240, 147, 251, 0.12), rgba(240, 147, 251, 0.02));
        }

        .object-7 {
            top: 15%;
            left: 50%;
            width: 40px;
            height: 70px;
            background: linear-gradient(135deg, rgba(99, 179, 237, 0.3), rgba(99, 179, 237, 0.1));
            animation: slowFloat7 26s ease-in-out infinite;
        }

        .object-7::before {
            background: linear-gradient(135deg, rgba(99, 179, 237, 0.2), rgba(99, 179, 237, 0.05));
        }

        .object-7::after {
            background: linear-gradient(135deg, rgba(99, 179, 237, 0.15), rgba(99, 179, 237, 0.03));
        }

        .object-8 {
            top: 80%;
            left: 60%;
            width: 50px;
            height: 50px;
            background: linear-gradient(135deg, rgba(168, 85, 247, 0.3), rgba(168, 85, 247, 0.1));
            border-radius: 50%;
            animation: slowFloat8 29s ease-in-out infinite;
        }

        .object-8::before {
            background: linear-gradient(135deg, rgba(168, 85, 247, 0.2), rgba(168, 85, 247, 0.05));
        }

        .object-8::after {
            background: linear-gradient(135deg, rgba(168, 85, 247, 0.15), rgba(168, 85, 247, 0.03));
        }

        /* Slow, wide movement animations */
        @keyframes slowFloat1 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            25% { transform: translateY(-60px) translateX(40px) rotate(3deg); }
            50% { transform: translateY(-30px) translateX(-25px) rotate(-2deg); }
            75% { transform: translateY(-80px) translateX(15px) rotate(4deg); }
        }

        @keyframes slowFloat2 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            33% { transform: translateY(-45px) translateX(-35px) rotate(-3deg); }
            66% { transform: translateY(-70px) translateX(20px) rotate(2deg); }
        }

        @keyframes slowFloat3 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            30% { transform: translateY(-55px) translateX(30px) rotate(5deg); }
            70% { transform: translateY(-85px) translateX(-20px) rotate(-4deg); }
        }

        @keyframes slowFloat4 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            20% { transform: translateY(-40px) translateX(-30px) rotate(-2deg); }
            50% { transform: translateY(-75px) translateX(35px) rotate(3deg); }
            80% { transform: translateY(-20px) translateX(-15px) rotate(-1deg); }
        }

        @keyframes slowFloat5 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            40% { transform: translateY(-65px) translateX(-40px) rotate(-4deg); }
            80% { transform: translateY(-35px) translateX(45px) rotate(3deg); }
        }

        @keyframes slowFloat6 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            25% { transform: translateY(-50px) translateX(25px) rotate(2deg); }
            75% { transform: translateY(-90px) translateX(-30px) rotate(-3deg); }
        }

        @keyframes slowFloat7 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            35% { transform: translateY(-70px) translateX(-25px) rotate(-5deg); }
            65% { transform: translateY(-40px) translateX(50px) rotate(4deg); }
        }

        @keyframes slowFloat8 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            50% { transform: translateY(-95px) translateX(-35px) rotate(-6deg); }
        }

        /* Slow, wide movement animations */
        @keyframes slowFloat1 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            25% { transform: translateY(-60px) translateX(40px) rotate(3deg); }
            50% { transform: translateY(-30px) translateX(-25px) rotate(-2deg); }
            75% { transform: translateY(-80px) translateX(15px) rotate(4deg); }
        }

        @keyframes slowFloat2 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            33% { transform: translateY(-45px) translateX(-35px) rotate(-3deg); }
            66% { transform: translateY(-70px) translateX(20px) rotate(2deg); }
        }

        @keyframes slowFloat3 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            30% { transform: translateY(-55px) translateX(30px) rotate(5deg); }
            70% { transform: translateY(-85px) translateX(-20px) rotate(-4deg); }
        }

        @keyframes slowFloat4 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            20% { transform: translateY(-40px) translateX(-30px) rotate(-2deg); }
            50% { transform: translateY(-75px) translateX(35px) rotate(3deg); }
            80% { transform: translateY(-20px) translateX(-15px) rotate(-1deg); }
        }

        @keyframes slowFloat5 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            40% { transform: translateY(-65px) translateX(-40px) rotate(-4deg); }
            80% { transform: translateY(-35px) translateX(45px) rotate(3deg); }
        }

        @keyframes slowFloat6 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            25% { transform: translateY(-50px) translateX(25px) rotate(2deg); }
            75% { transform: translateY(-90px) translateX(-30px) rotate(-3deg); }
        }

        @keyframes slowFloat7 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            35% { transform: translateY(-70px) translateX(-25px) rotate(-5deg); }
            65% { transform: translateY(-40px) translateX(50px) rotate(4deg); }
        }

        @keyframes slowFloat8 {
            0%, 100% { transform: translateY(0px) translateX(0px) rotate(0deg); }
            50% { transform: translateY(-95px) translateX(-35px) rotate(-6deg); }
        }

        @keyframes floatObject {
            0%, 100% { 
                transform: translateY(0px) translateX(0px) rotate(0deg);
            }
            25% { 
                transform: translateY(-20px) translateX(10px) rotate(2deg);
            }
            50% { 
                transform: translateY(-8px) translateX(-5px) rotate(-1deg);
            }
            75% { 
                transform: translateY(-25px) translateX(8px) rotate(3deg);
            }
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 2rem 0;
            position: relative;
            overflow: hidden;
        }

        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><rect width="20" height="20" x="0" y="0" fill="rgba(255,255,255,0.1)"/><rect width="15" height="15" x="30" y="10" fill="rgba(255,255,255,0.05)"/><rect width="25" height="10" x="60" y="20" fill="rgba(255,255,255,0.08)"/></svg>') repeat;
            opacity: 0.3;
        }

        .header-content {
            position: relative;
            z-index: 1;
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 1rem;
        }

        .headshot {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            object-position: center;
            border: 4px solid rgba(255, 255, 255, 0.3);
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.2);
            transition: transform 0.3s ease;
        }

        .headshot:hover {
            transform: scale(1.05);
        }

        h1 {
            font-size: 2.5rem;
            margin-bottom: 0.5rem;
            font-weight: 300;
        }

        .subtitle {
            font-size: 1.2rem;
            opacity: 0.9;
            font-weight: 300;
        }

        /* Navigation */
        nav {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            padding: 1rem 0;
            position: sticky;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 20px rgba(0,0,0,0.1);
        }

        nav ul {
            list-style: none;
            display: flex;
            justify-content: center;
            gap: 2rem;
        }

        nav a {
            text-decoration: none;
            color: #495057;
            font-weight: 500;
            padding: 0.5rem 1rem;
            border-radius: 25px;
            transition: all 0.4s cubic-bezier(0.25, 0.8, 0.25, 1);
        }

        nav a:hover {
            background: linear-gradient(135deg, #fda085 0%, #f093fb 100%);
            color: white;
            transform: translateY(-3px) scale(1.05);
            box-shadow: 0 8px 15px rgba(253, 160, 133, 0.3);
        }

        /* Main Content */
        main {
            padding: 3rem 0;
        }

        .section {
            margin-bottom: 4rem;
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(10px);
            padding: 2.5rem;
            border-radius: 15px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.1);
            position: relative;
            overflow: hidden;
            border: 1px solid rgba(255, 255, 255, 0.2);
            transition: all 0.3s ease;
        }

        .section:hover {
            transform: translateY(-3px);
            box-shadow: 0 15px 40px rgba(0,0,0,0.15);
            background: rgba(255, 255, 255, 0.95);
        }

        .section::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            height: 4px;
            background: linear-gradient(135deg, #fda085 0%, #f093fb 100%);
        }

        .section h2 {
            color: #495057;
            margin-bottom: 1.5rem;
            font-size: 2rem;
            font-weight: 300;
        }

        .section h3 {
            color: #667eea;
            margin-bottom: 1rem;
            font-size: 1.3rem;
        }

        /* Research Areas Grid */
        .research-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .research-card {
            background: linear-gradient(135deg, #f8f9fa 0%, #e9ecef 100%);
            padding: 2rem;
            border-radius: 10px;
            border-left: 4px solid #667eea;
            transition: all 0.4s cubic-bezier(0.25, 0.8, 0.25, 1);
            cursor: pointer;
        }

        .research-card:hover {
            transform: translateY(-15px) scale(1.02);
            box-shadow: 
                0 20px 40px rgba(0, 0, 0, 0.15),
                0 10px 20px rgba(102, 126, 234, 0.1);
            background: linear-gradient(135deg, #ffffff 0%, #f8f9fa 100%);
        }

        .research-card:nth-child(2) {
            border-left-color: #fda085;
        }

        .research-card:nth-child(2):hover {
            box-shadow: 
                0 20px 40px rgba(0, 0, 0, 0.15),
                0 10px 20px rgba(253, 160, 133, 0.1);
        }

        .research-card:nth-child(3) {
            border-left-color: #f093fb;
        }

        .research-tags {
            margin-top: 1rem;
        }

        .tag {
            display: inline-block;
            padding: 0.25rem 0.75rem;
            border-radius: 16px;
            background: rgba(102, 126, 234, 0.1);
            color: #667eea;
            font-size: 0.875rem;
            margin-right: 0.5rem;
            margin-bottom: 0.5rem;
            border: 1px solid rgba(102, 126, 234, 0.2);
            transition: all 0.3s ease;
        }

        .tag:hover {
            background: rgba(102, 126, 234, 0.2);
            transform: translateY(-1px);
        }

        .teaching-entry {
            background: #f8f9fa;
            padding: 1.5rem;
            margin-bottom: 1rem;
            border-radius: 8px;
            border-left: 3px solid #667eea;
            transition: all 0.4s cubic-bezier(0.25, 0.8, 0.25, 1);
            cursor: pointer;
        }

        .teaching-entry:hover {
            transform: translateY(-8px) scale(1.01);
            box-shadow: 
                0 15px 30px rgba(0, 0, 0, 0.12),
                0 8px 15px rgba(102, 126, 234, 0.08);
            background: #ffffff;
            border-left-width: 4px;
        }

        .teaching-entry h3 {
            color: #667eea;
            margin-bottom: 0.5rem;
            font-size: 1.2rem;
        }

        .teaching-entry p {
            margin-bottom: 0.5rem;
        }

        /* Publications */
        .publication {
            background: #f8f9fa;
            padding: 1.5rem;
            margin-bottom: 1rem;
            border-radius: 8px;
            border-left: 3px solid #667eea;
            transition: all 0.4s cubic-bezier(0.25, 0.8, 0.25, 1);
            cursor: pointer;
        }

        .publication:hover {
            transform: translateY(-8px) scale(1.01);
            box-shadow: 
                0 15px 30px rgba(0, 0, 0, 0.12),
                0 8px 15px rgba(102, 126, 234, 0.08);
            background: #ffffff;
            border-left-width: 4px;
        }

        .publication-title {
            font-weight: 600;
            color: #495057;
            margin-bottom: 0.5rem;
        }

        .publication-details {
            color: #6c757d;
            font-size: 0.9rem;
        }

        /* Contact */
        .contact-info {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
        }

        .contact-item {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            padding: 1.5rem;
            border-radius: 10px;
            text-align: center;
            transition: all 0.4s cubic-bezier(0.25, 0.8, 0.25, 1);
            cursor: pointer;
        }

        .contact-item:hover {
            transform: translateY(-12px) scale(1.03);
            box-shadow: 
                0 20px 40px rgba(0, 0, 0, 0.15),
                0 10px 20px rgba(102, 126, 234, 0.2);
            background: linear-gradient(135deg, #5a6fd8 0%, #6a4190 100%);
        }

        .contact-item h4 {
            margin-bottom: 0.5rem;
        }

        /* Footer */
        footer {
            background: #495057;
            color: white;
            text-align: center;
            padding: 2rem 0;
            margin-top: 3rem;
        }

        /* Responsive */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            nav ul {
                flex-direction: column;
                align-items: center;
                gap: 1rem;
            }
            
            .section {
                padding: 1.5rem;
            }
        }

        /* Decorative elements */
        .floating-element {
            position: absolute;
            background: rgba(102, 126, 234, 0.1);
            border-radius: 50%;
        }

        .floating-1 {
            width: 60px;
            height: 60px;
            top: 20%;
            right: 10%;
            animation: float 6s ease-in-out infinite;
        }

        .floating-2 {
            width: 40px;
            height: 40px;
            top: 60%;
            left: 5%;
            animation: float 8s ease-in-out infinite reverse;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="header-content">
                <img src="headshot.jpeg" alt="Sean Callahan" class="headshot">
                <h1>Sean Callahan</h1>
                <p class="subtitle">4th year PhD Student in Economics | Colorado State University</p>
            </div>
        </div>
        <div class="floating-element floating-1"></div>
        <div class="floating-element floating-2"></div>
    </header>

    <nav>
        <div class="container">
            <ul>
                <li><a href="#about">About</a></li>
                <li><a href="#research">Research</a></li>
                <li><a href="#publications">Publications</a></li>
                <li><a href="#teaching">Teaching</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </div>
    </nav>

    <!-- Floating 3D objects background -->
    <div class="floating-objects">
        <div class="floating-object object-1"></div>
        <div class="floating-object object-2"></div>
        <div class="floating-object object-3 sphere"></div>
        <div class="floating-object object-4"></div>
        <div class="floating-object object-5 sphere"></div>
        <div class="floating-object object-6"></div>
        <div class="floating-object object-7"></div>
        <div class="floating-object object-8 sphere"></div>
    </div>

    <main class="container">
        <section id="about" class="section">
            <h2>About</h2>
            <p>I describe myself as an international macroeconomist. I am interested in how the industrial composition of economies (developed and developing) change over time and what policies can be used to steer this change.</p>
            
            <p>My research bridges theoretical frameworks with empirical analysis to understand how institutions, policy interventions, and production networks shape economic development trajectories. I examine the complex relationships between structural transformation, income distribution, and sustainable growth in both advanced and emerging economies.</p>
        </section>

        <section id="research" class="section">
            <h2>Research Areas</h2>
            <div class="research-grid">
                <div class="research-card">
                    <h3>Economic Development</h3>
                    <p>Examining how policy interventions shape industrial composition, production linkages, and economic development. My work focuses on understanding the mechanisms through which strategic policies can guide structural transformation in both developed and developing economies.</p>
                    <div class="research-tags">
                        <span class="tag">Trade</span>
                        <span class="tag">Development</span>
                        <span class="tag">Networks</span>
                        <span class="tag">Industrial Policy</span>
                    </div>
                </div>
                <div class="research-card">
                    <h3>Macrodynamics of Income Distribution</h3>
                    <p>Studying the relationships between income distribution, economic growth, and structural change. This research explores how distributional dynamics influence and are influenced by broader macroeconomic trends and sectoral transformation.</p>
                    <div class="research-tags">
                        <span class="tag">Growth Theory</span>
                        <span class="tag">Distribution</span>
                        <span class="tag">Structural Change</span>
                    </div>
                </div>
                <div class="research-card">
                    <h3>Macroeconomics of the Green Transition</h3>
                    <p>Exploring demand-driven models and simulations of the energy transition. My research in this area focuses on understanding how economic systems can successfully navigate the transition to sustainable energy sources while maintaining growth and employment.</p>
                    <div class="research-tags">
                        <span class="tag">Sustainability</span>
                        <span class="tag">Green Growth</span>
                        <span class="tag">Demand-driven</span>
                    </div>
                </div>
            </div>
        </section>

        <section id="publications" class="section">
            <h2>Working Papers & Research in Progress</h2>
            
            <div class="publication">
                <div class="publication-title">Strategic Industry Policy and Production Networks: Evidence from China's Semiconductor Initiative</div>
                <div class="publication-details">Callahan, Sean (2024)</div>
            </div>
            
            <div class="publication">
                <div class="publication-title">The Collapse of the Social Partnership and Structural Change in the Celtic Tiger</div>
                <div class="publication-details">Callahan, Sean (2024)</div>
            </div>
            
            <div class="publication">
                <div class="publication-title">Demand-driven Model of Energy Capacity Investment</div>
                <div class="publication-details">Callahan, Sean (2024)</div>
            </div>
        </section>

        <section id="teaching" class="section">
            <h2>Teaching Experience</h2>
            
            <div class="teaching-entry">
                <h3>ECON 240: Issues in Environmental Economics</h3>
                <p><strong>Graduate Teaching Instructor</strong> | 2024-2025</p>
                <p>Lead instructor responsible for course design, lectures, and assessment for undergraduate environmental economics course.</p>
            </div>
            
            <div class="teaching-entry">
                <h3>ECON 204: Principles of Macroeconomics</h3>
                <p><strong>Graduate Teaching Assistant</strong> | 2023-2024</p>
                <p>Assisted with instruction, led recitation sections, and provided tutoring for introductory macroeconomics students.</p>
            </div>
            
            <div class="teaching-entry">
                <h3>ECON 202: Principles of Microeconomics</h3>
                <p><strong>Graduate Teaching Assistant</strong> | 2022-2023</p>
                <p>Supported course instruction and provided academic support for undergraduate microeconomics students.</p>
            </div>
            
            <h3>Technical Skills</h3>
            <p><strong>Statistical Software:</strong> R (primary), Stata, Python<br>
            <strong>Research Methods:</strong> Econometric analysis, Network analysis, Panel data methods, Input-output analysis<br>
            <strong>Specializations:</strong> Industrial policy analysis, Structural change modeling, Development economics</p>
        </section>

        <section id="contact" class="section">
            <h2>Contact</h2>
            <div class="contact-info">
                <div class="contact-item">
                    <h4>Email</h4>
                    <p>sean.callahan@colostate.edu</p>
                </div>
                <div class="contact-item">
                    <h4>Office</h4>
                    <p>Clark C309B<br>Department of Economics<br>Colorado State University</p>
                </div>
                <div class="contact-item">
                    <h4>Location</h4>
                    <p>Fort Collins, Colorado<br>United States</p>
                </div>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">
            <p>&copy; 2025 Sean Callahan. All rights reserved.</p>
        </div>
    </footer>

    <script>
        // Smooth scrolling for navigation links
        document.querySelectorAll('nav a').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const target = document.querySelector(this.getAttribute('href'));
                target.scrollIntoView({
                    behavior: 'smooth',
                    block: 'start'
                });
            });
        });

        // Add subtle parallax effect to floating objects
        window.addEventListener('scroll', () => {
            const scrolled = window.pageYOffset;
            const floatingObjects = document.querySelectorAll('.floating-object');
            
            floatingObjects.forEach((element, index) => {
                const speed = 0.1 + (index * 0.02); // Gentle parallax speeds
                element.style.transform = `translateY(${scrolled * speed}px)`;
            });
        });
    </script>
</body>
</html>