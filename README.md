<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Orgonite Online Store</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <h1>Orgonite Online Store</h1>
    <p>Harnessing quantum and life force energy with infinite potential</p>
  </header>

  <!-- Introductory Video -->
  <section id="intro-video">
    <h2>What is Anandamide?</h2>
    <iframe src="https://www.youtube.com/embed/9nD1s4VPKk8" 
            title="Anandamide video" 
            frameborder="0" 
            allowfullscreen></iframe>
  </section>

  <!-- Accordion Sections -->
  <div id="accordion">
    <!-- Products -->
    <div class="accordion-item">
      <button class="accordion-header">Products</button>
      <div class="accordion-content">
        <div class="sub-section">
          <button class="sub-header">Pyramids</button>
          <div class="sub-content">
            <div class="product">
              <img src="pyramid1.jpg" alt="Pyramid 1">
              <p>Pyramid 1: Description. Price: $50</p>
            </div>
            <div class="product">
              <img src="pyramid2.jpg" alt="Pyramid 2">
              <p>Pyramid 2: Description. Price: $60</p>
            </div>
            <div class="product">
              <img src="pyramid3.jpg" alt="Pyramid 3">
              <p>Pyramid 3: Description. Price: $70</p>
            </div>
            <button class="view-all">View All</button>
          </div>
        </div>
        <!-- Jewelry -->
        <div class="sub-section">
          <button class="sub-header">Jewelry</button>
          <div class="sub-content">
            <div class="product">
              <img src="necklace1.jpg" alt="Necklace 1">
              <p>Necklace 1: Description. Price: $40</p>
            </div>
            <div class="product">
              <img src="bracelet1.jpg" alt="Bracelet 1">
              <p>Bracelet 1: Description. Price: $30</p>
            </div>
            <div class="product">
              <img src="ring1.jpg" alt="Ring 1">
              <p>Ring 1: Description. Price: $20</p>
            </div>
            <button class="view-all">View All</button>
          </div>
        </div>
        <!-- Handhelds -->
        <div class="sub-section">
          <button class="sub-header">Handhelds</button>
          <div class="sub-content">
            <div class="product">
              <img src="handheld1.jpg" alt="Handheld 1">
              <p>Handheld 1: Description. Price: $30</p>
            </div>
            <div class="product">
              <img src="handheld2.jpg" alt="Handheld 2">
              <p>Handheld 2: Description. Price: $35</p>
            </div>
            <div class="product">
              <img src="handheld3.jpg" alt="Handheld 3">
              <p>Handheld 3: Description. Price: $40</p>
            </div>
            <button class="view-all">View All</button>
          </div>
        </div>
      </div>
    </div>

    <!-- Personalized Guidance -->
    <div class="accordion-item">
      <button class="accordion-header">Your Personalized Guidance</button>
      <div class="accordion-content">
        <form id="guidance-form">
          <label>What do you need? <input type="text" id="need"></label>
          <label>What do you want for yourself? <input type="text" id="want"></label>
          <label>What do you fear? <input type="text" id="fear"></label>
          <label>What have you tried in the past that did not work? <input type="text" id="failure"></label>
          <label>What is your desired outcome? <input type="text" id="outcome"></label>
          <button type="button" id="get-results">Get Your Results</button>
        </form>
        <div id="results"></div>
      </div>
    </div>

    <!-- What is Orgonite -->
    <div class="accordion-item">
      <button class="accordion-header">What is Orgonite and How Does it Work?</button>
      <div class="accordion-content">
        <p>Orgonite transduces energy into organized form...</p>
      </div>
    </div>

    <!-- Reference Material -->
    <div class="accordion-item">
      <button class="accordion-header">Reference Material</button>
      <div class="accordion-content">
        <p>Example reference materials...</p>
        <iframe src="https://m.youtube.com/watch?v=KN3PBFxV3Xw&t=10s&pp=ygUPV2hhdHMgaW4gYSBkcm9w" 
                title="Whats is a Drop? We are water so what is the unconscious effect of vibrations on us." 
                frameborder="0" 
                allowfullscreen></iframe>
        <iframe src="https://m.youtube.com/watch?v=R8VyUsVOic0&pp=ygUVTm9iZWwgcHJvemUgZG5hIHdhdGVy" 
                title="Water Memory. Here a Nobel prize laureate measures the emf of extremely diluted water that once touched a strand of hiv infected dna and sends the audio to germany where they play the recording for a vial of water that contains 4 amino acids and one rna for an hour and the exact strand of infected dna is replicated exactly. We can do this with stem cells , cures, preventions, anything " 
                frameborder="0" 
                allowfullscreen></iframe>
      </div>
    </div>

    <!-- Add other sections... -->
  </div>

  <!-- Footer -->
  <footer>
    <p>Thank you! Not FDA-approved, no patents—make/share/sell freely.</p>
    <iframe src="https://www.youtube.com/embed/HIGHLIGHTS_VIDEO_ID" 
            title="Highlights video" frameborder="0" allowfullscreen></iframe>
  </footer>

  <script src="scripts.js"></script>
</body>
</html>