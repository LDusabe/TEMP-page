# TEMP-page
web page
 /* Global Styles */
 * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: 'Roboto', sans-serif;
    color: #1F2937;
    background-color: #E5E7EB;
}

/* Header */
header {
    background-color: #1F2937;
    color: #F9FAF8;
    display: flex;
    justify-content: space-between;
    padding: 20px;
    align-items: center;
}

header .logo {
    font-size: 24px;
    font-weight: bold;
}

header .nav-links {
    display: flex;
    gap: 20px;
}

header .nav-links p {
    color: #E5E7EB;
    margin: 0;
    font-size: 14px;
}

/* Hero Section */
.hero {
    background-color: #1F2937;
    color: #F9FAF8;
    padding: 60px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.hero-content h1 {
    font-size: 48px;
    font-weight: 900;
    margin-bottom: 10px;
}

.hero-content p {
    font-size: 18px;
    color: #A1A9B8;
    margin-bottom: 20px;
}

.hero-content button {
    padding: 10px 20px;
    font-size: 16px;
    background-color: #3882F6;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.hero-image {
    width: 300px;
    height: 200px;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 5px;
    overflow: hidden;
}

.hero-image img {
    max-width: 100%;
    height: auto;
    object-fit: cover;
}

/* Info Section */
.info-section {
    background-color: #F9FAF8;
    padding: 60px 20px;
    text-align: center;
}

.info-section h2 {
    font-size: 24px;
    font-weight: 900;
    margin-bottom: 20px;
}

.info-cards {
    display: flex;
    justify-content: center;
    gap: 20px;
    flex-wrap: wrap;
}

.card {
    width: 150px;
    border: 2px solid #3882F6;
    border-radius: 5px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    padding: 10px;
}

.card img {
    width: 100%;
    height: 100px;
    object-fit: cover;
    border-radius: 5px;
}

/* Quote Section */
.quote-section {
    background-color: #D1D5DB;
    padding: 60px 20px;
    text-align: center;
    font-style: italic;
    color: #1F2937;
}

.quote-section p {
    font-size: 24px;
    margin-bottom: 10px;
}

.quote-section .author {
    font-size: 18px;
    font-style: normal;
}

/* Call to Action Section */
.call-to-action {
    background-color: #3882F6;
    color: #ffffff;
    padding: 50px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-radius: 10px;
    max-width: 900px;
    margin: 90px auto;
}

.call-to-action p {
    font-size: 18px;
}

.call-to-action .cta-button {
    padding: 10px 20px;
    font-size: 16px;
    background-color: transparent;
    color: #fff;
    border: 2px solid #fff;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s ease, color 0.3s ease;
}

.call-to-action .cta-button:hover {
    background-color: #fff;
    color: #3882F6;
}

/* Footer */
footer {
    background-color: #1F2937;
    color: #F9FAF8;
    padding: 20px;
    text-align: center;
    font-size: 14px;
}
