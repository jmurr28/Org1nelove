# Org1nelove
A tool for exploring our own potential
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Quantum Orgonite Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .intro-video, .footer-video {
            text-align: center;
            margin: 20px 0;
        }
        .accordion {
            margin: 20px 0;
        }
        .accordion-item {
            border-bottom: 1px solid #ccc;
        }
        .accordion-header {
            background-color: #2c3e50;
            color: white;
            padding: 15px;
            cursor: pointer;
            font-size: 18px;
            transition: background-color 0.3s;
        }
        .accordion-header:hover {
            background-color: #34495e;
        }
        .accordion-content {
            display: none;
            padding: 15px;
            background-color: white;
        }
        .sub-accordion-header {
            background-color: #ecf0f1;
            padding: 10px;
            cursor: pointer;
            font-size: 16px;
            margin: 10px 0;
        }
        .sub-accordion-content {
            display: none;
            padding: 10px 20px;
        }
        .product-grid {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .product-item {
            flex: 1 1 30%;
            background-color: #f9f9f9;
            padding: 10px;
            text-align: center;
        }
        .product-item img {
            max-width: 100%;
            height: auto;
        }
        .view-all {
            display: block;
            text-align: center;
            margin: 10px 0;
            color: #2980b9;
            cursor: pointer;
        }
        .form-container {
            margin: 20px 0;
        }
        .form-container input, .form-container textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
        }
        .form-container button {
            background-color: #2c3e50;
            color: white;
            padding: 10px 20px;
            border: none;
            cursor: pointer;
        }
        .social-icons a {
            margin: 0 10px;
            color: #2c3e50;
            font-size: 24px;
        }
        .instagram-feed {
            text-align: center;
            margin: 20px 0;
        }
        @media (max-width: 768px) {
            .product-item {
                flex: 1 1 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Intro Video -->
        <div class="intro-video">
            <h2>Welcome to Quantum Orgonite</h2>
            <iframe width="560" height="315" src="https://m.youtube.com/watch?v=9nD1s4VPKk8&pp=0gcJCccJAYcqIYzv" frameborder="0" allowfullscreen></iframe>
            <p>Discover the power of anandamide, the bliss molecule, and our quantum orgonite products.</p>
        </div>

        <!-- Accordion Sections -->
        <div class="accordion">
            <!-- Products -->
            <div class="accordion-item">
                <div class="accordion-header">Products</div>
                <div class="accordion-content">
                    <!-- Pyramids -->
                    <div class="sub-accordion-header">Pyramids</div>
                    <div class="sub-accordion-content">
                        <div class="product-grid">
                            <div class="product-item">
                                <img src="pyramid1.jpg" alt="Pyramid 1">
                                <p>Quantum Pyramid: Crafted with monoatomic gold for enhanced energy alignment.</p>
                            </div>
                            <div class="product-item">
                                <img src="pyramid2.jpg" alt="Pyramid 2">
                                <p>Healing Pyramid: Infused with colloidal silver for quantum coherence.</p>
                            </div>
                            <div class="product-item">
                                <img src="pyramid3.jpg" alt="Pyramid 3">
                                <p>Balance Pyramid: Uses nascent iodine for vibrational harmony.</p>
                            </div>
                        </div>
                        <div class="view-all">View All Pyramids</div>
                        <div class="sub-accordion-content hidden">
                            <div class="product-grid">
                                <div class="product-item">
                                    <img src="pyramid4.jpg" alt="Pyramid 4">
                                    <p>Energy Pyramid: Boosts prana flow with quantum materials.</p>
                                </div>
                                <!-- Add more pyramid products as needed -->
                            </div>
                        </div>
                        <div class="product-grid">
                            <div class="product-item">
                                <p>Price: $49.99</p>
                            </div>
                            <div class="product-item">
                                <p>Price: $59.99</p>
                            </div>
                            <div class="product-item">
                                <p>Price: $69.99</p>
                            </div>
                        </div>
                    </div>
                    <!-- Jewelry -->
                    <div class="sub-accordion-header">Jewelry</div>
                    <div class="sub-accordion-content">
                        <!-- Necklaces -->
                        <div class="sub-accordion-header">Necklaces</div>
                        <div class="sub-accordion-content">
                            <div class="product-grid">
                                <div class="product-item">
                                    <img src="necklace1.jpg" alt="Necklace 1">
                                    <p>Quantum Necklace: Enhances energy flow with monoatomic gold.</p>
                                </div>
                                <!-- Add more necklaces -->
                            </div>
                            <div class="view-all">View All Necklaces</div>
                        </div>
                        <!-- Bracelets -->
                        <div class="sub-accordion-header">Bracelets</div>
                        <div class="sub-accordion-content">
                            <div class="product-grid">
                                <div class="product-item">
                                    <img src="bracelet1.jpg" alt="Bracelet 1">
                                    <p>Healing Bracelet: Balances chi with colloidal silver.</p>
                                </div>
                                <!-- Add more bracelets -->
                            </div>
                            <div class="view-all">View All Bracelets</div>
                        </div>
                        <!-- Rings -->
                        <div class="sub-accordion-header">Rings</div>
                        <div class="sub-accordion-content">
                            <div class="product-grid">
                                <div class="product-item">
                                    <img src="ring1.jpg" alt="Ring 1">
                                    <p>Energy Ring: Aligns prana with nascent iodine.</p>
                                </div>
                                <!-- Add more rings -->
                            </div>
                            <div class="view-all">View All Rings</div>
                        </div>
                    </div>
                    <!-- Handhelds -->
                    <div class="sub-accordion-header">Handhelds</div>
                    <div class="sub-accordion-content">
                        <div class="product-grid">
                            <div class="product-item">
                                <img src="handheld1.jpg" alt="Handheld 1">
                                <p>Quantum Wand: Channels life force energy for meditation.</p>
                            </div>
                            <!-- Add more handhelds -->
                        </div>
                        <div class="view-all">View All Handhelds</div>
                    </div>
                </div>
            </div>

            <!-- Personalized Guidance -->
            <div class="accordion-item">
                <div class="accordion-header">Your Personalized Guidance</div>
                <div class="accordion-content">
                    <div class="form-container">
                        <form id="guidance-form">
                            <label>What do you need?</label>
                            <textarea name="need" required></textarea>
                            <label>What do you want for yourself?</label>
                            <textarea name="want" required></textarea>
                            <label>What do you fear?</label>
                            <textarea name="fear" required></textarea>
                            <label>What have you tried in the past that did not work?</label>
                            <textarea name="past" required></textarea>
                            <label>What is your desired outcome from this site or product?</label>
                            <textarea name="outcome" required></textarea>
                            <button type="submit">Get Your Results</button>
                        </form>
                        <div id="guidance-result" style="display: none;"></div>
                    </div>
                </div>
            </div>

            <!-- What is Orgonite -->
            <div class="accordion-item">
                <div class="accordion-header">What is Orgonite and How Does it Work?</div>
                <div class="accordion-content">
                    <p>Orgonite transduces available energy into organized energy, aligning subtle and major energy systems like a crystal. This facilitates efficient information transfer in the human system, promoting ease, balance, and preventative health. As Jesus said, “It is not what goes into the body that defiles a man but what comes out.” Seek peace, righteousness, and joy in the Holy Spirit to achieve a state of health where no dis-ease can thrive.</p>
                </div>
            </div>

            <!-- Reference Material -->
            <div class="accordion-item">
                <div class="accordion-header">Reference Material</div>
                <div class="accordion-content">
                    <div class="product-grid">
                        <div class="product-item">
                            <iframe width="100%" height="200" src="https://www.youtube.com/embed/VIDEO_ID1" frameborder="0" allowfullscreen></iframe>
                            <p>Video on Wilhelm Reich’s orgone energy discoveries.</p>
                        </div>
                        <!-- Add more videos -->
                    </div>
                    <div class="view-all">View All Videos</div>
                </div>
            </div>

            <!-- Home Experiments -->
            <div class="accordion-item">
                <div class="accordion-header">Home Experiments</div>
                <div class="accordion-content">
                    <p>These are simple, duplicable experiments anyone can do at home to replicate peer-reviewed university studies.</p>
                    <div class="product-grid">
                        <div class="product-item">
                            <p>Experiment 1: Test orgonite’s effect on plant growth.</p>
                        </div>
                        <!-- Add more experiments -->
                    </div>
                    <div class="view-all">View All Experiments</div>
                </div>
            </div>

            <!-- Create Your Own -->
            <div class="accordion-item">
                <div class="accordion-header">Create Your Own at Home</div>
                <div class="accordion-content">
                    <div class="product-grid">
                        <div class="product-item">
                            <iframe width="100%" height="200" src="https://www.youtube.com/embed/VIDEO_ID4" frameborder="0" allowfullscreen></iframe>
                            <p>Basic orgonite creation tutorial.</p>
                        </div>
                        <!-- Add more videos -->
                    </div>
                    <div class="view-all">View All Tutorials</div>
                    <div class="sub-accordion-content hidden">
                        <p><a href="orgonite-guide.pdf" download>Download PDF Guide</a></p>
                        <p>Paid detailed tutorials available for in-depth understanding.</p>
                    </div>
                </div>
            </div>

            <!-- Testimonials -->
            <div class="accordion-item">
                <div class="accordion-header">Testimonials</div>
                <div class="accordion-content">
                    <div class="product-grid">
                        <div class="product-item">
                            <img src="user1.jpg" alt="User 1">
                            <p>John Doe: "This pyramid transformed my meditation practice!"</p>
                        </div>
                        <!-- Add more testimonials -->
                    </div>
                    <div class="view-all">View All Testimonials</div>
                </div>
            </div>

            <!-- Feedback -->
            <div class="accordion-item">
                <div class="accordion-header">Feedback</div>
                <div class="accordion-content">
                    <p>We are in extreme need of critiques, ideas, or any feedback. This is a community effort for the greater good, and all contributions are appreciated.</p>
                    <div class="form-container">
                        <form action="mailto:Org1nelove@gmail.com" method="post" enctype="text/plain">
                            <label>Name</label>
                            <input type="text" name="name" required>
                            <label>Feedback</label>
                            <textarea name="feedback" required></textarea>
                            <button type="submit">Submit Feedback</button>
                        </form>
                    </div>
                </div>
            </div>

            <!-- Collaborators -->
            <div class="accordion-item">
                <div class="accordion-header">Collaborators or Institutions</div>
                <div class="accordion-content">
                    <p>We welcome anyone with experience in any field to prove or disprove this technology to improve its efficiency or gain recognition. All support or opposition is met with gratitude.</p>
                    <div class="form-container">
                        <form action="mailto:Org1nelove@gmail.com" method="post" enctype="text/plain">
                            <label>Name</label>
                            <input type="text" name="name" required>
                            <label>Contact Info</label>
                            <input type="text" name="contact" required>
                            <label>Message</label>
                            <textarea name="message" required></textarea>
                            <button type="submit">Submit</button>
                        </form>
                    </div>
                </div>
            </div>

            <!-- About/Follow/Contact -->
            <div class="accordion-item">
                <div class="accordion-header">About/Follow/Contact Us</div>
                <div class="accordion-content">
                    <p>We are a community dedicated to harnessing quantum energy for health and balance, inspired by pioneers like Wilhelm Reich, Nikola Tesla, and others.</p>
                    <div class="social-icons">
                        <a href="https://instagram.com/yourprofile"><i class="fab fa-instagram"></i></a>
                        <a href="https://twitter.com/yourprofile"><i class="fab fa-twitter"></i></a>
                        <a href="https://facebook.com/yourprofile"><i class="fab fa-facebook"></i></a>
                    </div>
                    <p>Contact: Org1nelove@gmail.com</p>
                </div>
            </div>
        </div>

        <!-- Footer Video and Instagram Feed -->
        <div class="footer-video">
            <h2>Highlights</h2>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/HIGHLIGHTS_VIDEO_ID" frameborder="0" allowfullscreen></iframe>
        </div>
        <div class="instagram-feed">
            <h2>Our Instagram Feed</h2>
            <p>[Embedded Instagram feed placeholder]</p>
        </div>
        <div class="footer-note">
            <p>Thank you for visiting! None of this is FDA-approved, and there are no patents. Feel free to make your own orgonite, share with friends, or sell them—it's free for all!</p>
        </div>
    </div>

    <script>
        // Accordion Functionality
        document.querySelectorAll('.accordion-header').forEach(header => {
            header.addEventListener('click', () => {
                const content = header.nextElementSibling;
                content.style.display = content.style.display === 'block' ? 'none' : 'block';
            });
        });

        document.querySelectorAll('.sub-accordion-header').forEach(header => {
            header.addEventListener('click', () => {
                const content = header.nextElementSibling;
                content.style.display = content.style.display === 'block' ? 'none' : 'block';
            });
        });

        document.querySelectorAll('.view-all').forEach(button => {
            button.addEventListener('click', () => {
                const extraContent = button.nextElementSibling;
                extraContent.style.display = extraContent.style.display === 'block' ? 'none' : 'block';
                button.textContent = extraContent.style.display === 'block' ? 'Hide All' : 'View All';
            });
        });

        // Guidance Form AI Simulation
        document.getElementById('guidance-form').addEventListener('submit', (e) => {
            e.preventDefault();
            const formData = new FormData(e.target);
            const resultDiv = document.getElementById('guidance-result');
            resultDiv.style.display = 'block';
            resultDiv.innerHTML = `
                <p><strong>Need:</strong> Based on your input, we recommend a Quantum Pyramid to address ${formData.get('need')}.</p>
                <p><strong>Want:</strong> To achieve ${formData.get('want')}, try our Healing Necklace.</p>
                <p><strong>Fear:</strong> To overcome ${formData.get('fear')}, use the Balance Handheld daily.</p>
                <p><strong>Past Failures:</strong> Since ${formData.get('past')} didn’t work, our products offer a quantum approach.</p>
                <p><strong>Desired Outcome:</strong> For ${formData.get('outcome')}, we suggest starting with a Quantum Pyramid.</p>
            `;
        });
    </script>
</body>
</html>