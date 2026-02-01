/* Premium Interior Section Styles */
.interior-process {
    padding: 80px 20px;
    background-color: #f9f9f9; /* Light, clean background */
    font-family: 'Helvetica Neue', Arial, sans-serif;
    color: #333;
    text-align: center;
}

.section-title {
    font-size: 2.5rem;
    font-weight: 300;
    letter-spacing: 2px;
    margin-bottom: 10px;
    text-transform: uppercase;
}

.section-subtitle {
    font-style: italic;
    color: #777;
    margin-bottom: 50px;
}

.process-grid {
    display: flex;
    justify-content: center;
    gap: 30px;
    flex-wrap: wrap;
    max-width: 1100px;
    margin: 0 auto;
}

.process-card {
    background: #fff;
    padding: 40px;
    flex: 1;
    min-width: 280px;
    border: 1px solid #eee;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.process-card:hover {
    transform: translateY(-10px);
    box-shadow: 0 10px 30px rgba(0,0,0,0.05);
}

.step-number {
    font-size: 3rem;
    font-weight: 100;
    color: #d4af37; /* Elegant Gold color */
    display: block;
    margin-bottom: 20px;
}

.process-card h3 {
    margin-bottom: 15px;
    font-weight: 500;
}

.process-card p {
    line-height: 1.6;
    color: #666;
    font-size: 0.95rem;
}

.cta-wrapper {
    margin-top: 50px;
}

.main-btn {
    display: inline-block;
    padding: 15px 40px;
    background-color: #333;
    color: #fff;
    text-decoration: none;
    letter-spacing: 1px;
    transition: background 0.3s ease;
}

.main-btn:hover {
    background-color: #d4af37; /* Turns gold on hover */
}
