---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
    /* Container optimization */
    .page__content {
        max-width: 100%;
    }

    /* About section styling */
    .about-section {
        animation: fadeInUp 0.8s ease-out;
    }

    .section-title {
        font-size: 2em;
        font-weight: 700;
        color: var(--global-text-color);
        margin-bottom: 20px;
        padding-bottom: 12px;
        border-bottom: 3px solid #4285f4;
        display: inline-block;
        letter-spacing: -0.5px;
    }

    .about-content {
        font-size: 1.1em;
        line-height: 1.8;
        color: var(--global-text-color);
        margin-bottom: 40px;
    }

    .about-content p {
        margin-bottom: 20px;
        text-align: justify;
    }

    .highlight-box {
        background: linear-gradient(135deg, rgba(66, 133, 244, 0.05) 0%, rgba(66, 133, 244, 0.02) 100%);
        border-left: 4px solid #4285f4;
        padding: 20px 25px;
        border-radius: 8px;
        margin: 25px 0;
        box-shadow: 0 2px 8px rgba(0, 0, 0, 0.05);
    }

    /* News section styling */
    .news-section {
        margin-top: 50px;
        animation: fadeInUp 0.8s ease-out 0.2s backwards;
    }

    .news-container {
        max-width: 100%;
        margin-top: 30px;
    }

    .news-item {
        display: flex;
        margin-bottom: 25px;
        padding: 20px;
        background: var(--global-bg-color);
        border: 2px solid var(--global-border-color);
        border-radius: 10px;
        box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
        transition: all 0.3s ease;
        position: relative;
        overflow: hidden;
    }

    .news-item::before {
        content: "";
        position: absolute;
        left: 0;
        top: 0;
        bottom: 0;
        width: 5px;
        background: linear-gradient(180deg, #4285f4 0%, #3367d6 100%);
        transition: width 0.3s ease;
    }

    .news-item:hover {
        transform: translateX(5px);
        box-shadow: 0 5px 20px rgba(66, 133, 244, 0.15);
        border-color: rgba(66, 133, 244, 0.3);
    }

    .news-item:hover::before {
        width: 8px;
    }

    .news-date {
        flex: 0 0 160px;
        font-weight: 700;
        font-size: 1em;
        color: #4285f4;
        padding-right: 25px;
        display: flex;
        align-items: flex-start;
        padding-top: 2px;
    }

    .news-date::before {
        content: "📅";
        margin-right: 8px;
        font-size: 1.1em;
    }

    .news-content {
        flex: 1;
        font-size: 1.05em;
        line-height: 1.6;
        color: var(--global-text-color);
    }

    .news-content strong {
        color: #3367d6;
        font-weight: 600;
    }

    .achievement-badge {
        display: inline-block;
        background: linear-gradient(135deg, #4285f4 0%, #3367d6 100%);
        color: white;
        padding: 3px 10px;
        border-radius: 12px;
        font-size: 0.85em;
        font-weight: 600;
        margin-left: 5px;
        box-shadow: 0 2px 5px rgba(66, 133, 244, 0.3);
    }

    /* Divider */
    .section-divider {
        height: 2px;
        background: linear-gradient(to right, transparent, var(--global-border-color), transparent);
        margin: 45px 0;
    }

    /* Animations */
    @keyframes fadeInUp {
        from {
            opacity: 0;
            transform: translateY(30px);
        }
        to {
            opacity: 1;
            transform: translateY(0);
        }
    }

    /* Responsive design */
    @media (max-width: 768px) {
        .section-title {
            font-size: 1.6em;
        }

        .about-content {
            font-size: 1em;
        }

        .news-item {
            flex-direction: column;
            padding: 15px;
        }

        .news-date {
            flex: none;
            padding-right: 0;
            margin-bottom: 10px;
            padding-bottom: 10px;
            border-bottom: 1px solid var(--global-border-color);
        }

        .news-content {
            font-size: 0.95em;
        }

        .highlight-box {
            padding: 15px 18px;
        }
    }
</style>

<div class="about-section">
    <h1 class="section-title">About Me</h1>
    
    <div class="about-content">
        <p>
            I am a first-year PhD student at Southern Illinois University Carbondale, where my research focuses on <strong>computer vision</strong> and its applications in the medical field. I am particularly interested in deriving meaningful insights from medical, biomedical, and microscopy images to address critical clinical challenges and improve diagnostic accuracy.
        </p>
         <p>
            Before commencing my doctoral studies, I served as a <strong>Research Assistant</strong> at SUST Research Center, Sylhet, Bangladesh, where I gained valuable experience in applied research and computational methods. I received my Bachelor's degree from the Shahjalal University of Science & Technology (SUST) in 2023, majoring in Computer Science & Engineering.
        </p>
        
        <div class="highlight-box">
            <strong>Research Interests:</strong> Medical Image Analysis • Computer Vision • Generative AI • AI for Healthcare • Natural Language Processing
        </div>
  
    </div>
</div>

<div class="section-divider"></div>

<div class="news-section">
    <h1 class="section-title">News</h1>
    
    <div class="news-container">
        <div class="news-item">
            <div class="news-date">October 2025</div>
            <div class="news-content">
                Our paper titled <em>"Contrastive-inspired feature optimization for generative diffusion-augmented learning in digital breast tomosynthesis"</em> has been accepted at <strong>SPIE Medical Imaging 2026</strong> (Computer-Aided Diagnosis).
                <span class="achievement-badge">Paper Accepted</span>
            </div>
        </div>

        <div class="news-item">
            <div class="news-date">October 2025</div>
            <div class="news-content">
                Virtually attended and presented my research on <em>Generative AI for lesion synthesis in DBT</em> at the <strong>IEEE SMC 2025</strong> conference, Vienna, Austria.
            </div>
        </div>

        <div class="news-item">
            <div class="news-date">June 2025</div>
            <div class="news-content">
                Our paper titled <em>"Generative diffusion-augmented learning for lesion detection in digital breast tomosynthesis: A proof-of-concept study"</em> has been accepted at <strong>IEEE SMC 2025</strong>.
                <span class="achievement-badge">Paper Accepted</span>
            </div>
        </div>

        <div class="news-item">
            <div class="news-date">May 2025</div>
            <div class="news-content">
                Serving as a reviewer for <strong>IEEE SMC 2025</strong>.
            </div>
        </div>

        <div class="news-item">
            <div class="news-date">January 2025</div>
            <div class="news-content">
                🎓 Joined as a PhD student at <strong>Southern Illinois University Carbondale</strong>, beginning my doctoral journey in computer vision and medical imaging.
            </div>
        </div>
    </div>
</div>


<!--
# Education
--------------------
<div style="display: flex; justify-content: space-between;">
    <div><strong>Shahjalal University of Science & Technology (SUST)</strong></div>
    <div>Sylhet, Bangladesh</div>
</div>
<div style="display: flex; justify-content: space-between;">
    <div>B.S. in Computer Science & Engineering </div>
    <div>May 2023</div>
</div>
<div style="display: flex; justify-content: space-between;">
    <div>GPA: 3.51/4.00 (<b>3.73</b> in the last two years)</div>
    <div></div>
</div><br>
-->
<!--
# Research Experience
---------------------
<div style="display: flex; justify-content: space-between;">
    <div style="font-size: 20px;"><strong>Reasearch Assistant</strong></div>
    <div>Jul 2022 - Jun 2023</div>
</div> 
Supervisor: <a href="https://www.sust.edu/d/cse/faculty-profile-detail/44" target="_blank"> Dr. Sadia Sultana</a> <br>
<div>
  In the final year of my undergrad studies, I had the privilege of working part-time as a research assistant on a university research project titled "<strong>SUFEDB: A facial expression database for emotion recognition</strong>". I collected consent from participants and annotated expression images via OpenCV. I had also done preprocessing of images to ensure data uniformity of the dataset. In addition, I had evaluated and analyzed the performance of current state-of-the-art CNN models on the dataset.
</div> <br>

<div style="display: flex; justify-content: space-between;">
    <div style="font-size: 20px;"><strong>Undergraduate Thesis</strong></div>
    <div>Jan 2022 - Mar 2023</div>
</div>
<span style="opacity: 0.8;"> **Development of an Ensemble Learning system for Facial Expression Recognition using smaller CNN models with Transfer
Learning** </span> <br/>
Supervisor: <a href="https://www.sust.edu/d/cse/faculty-profile-detail/44" target="_blank"> Dr. Sadia Sultana</a> <br>
<div>
<ul style="opacity: 0.8;">
  <li>Developed and trained an efficient Facial Expression Recognition ensemble learning system using smaller CNN models with transfer learning, which achieved 97.55% accuracy on the benchmark dataset KDEF.</li>
  <li>Used transfer learning and advanced data augmentation to deal with overfitting problems and assessed the performance of Mixup and CutMix data augmentation on our benchmark datasets. </li>
  <li> Validated the effectiveness of our ensemble model with other existing state-of-the-art methods.</li>
</ul> <br>

<div style="display: flex; justify-content: space-between;">
    <div style="font-size: 20px;"><strong>Collaborative Research</strong></div>
    <div>Ongoing</div>
</div>
Supervisor: <strong>Prof. Moqsadur Rahman</strong> <br>
<div>
In recent years, there has been an increasing interest in expressing thoughts and feelings on social media rather than in face-to-face conversation. Social networks, especially Reddit, have emerged as powerful platforms for sharing depression, which can be utilized to analyze the trends of depression. For this, we collected a bulk amount of depression-related data (1M posts) crawling from Reddit and utilized NLTK for text processing and custom functions for text cleaning. We preprocessed the data in a time-based approach: Incremental Window and Sliding Window. We used pre-trained word embeddings like Skip-gram and GloVe for analyzing trends related to depression, leveraging the semantic relationships encoded in word vectors.
-->
<!--
<h2>  Publications </h2>
<div>
  <strong>SUFEDB: A facial expression database for emotion recognition</strong> <br/>
  <span style="opacity: 0.9;">Sadia Sultana, Saiful Sagor, <strong>Golam Jilani</strong>, Al Masum, Samara Paul </span> <br/>
<span style="opacity: 0.5;">(under review)</span>
</div> <br>

<div>
  <strong>An efficient ensemble learning model integrating multi-branch sub-networks for facial expression recognition.</strong> <br/>
<span style="opacity: 0.9;"><strong>Golam Jilani</strong>, Samara Paul, Sadia Sultana </span> <br/>
<span style="opacity: 0.5;">(under review)</span> 
</div>
-->


<!--
<h2> Technical Skills </h2>
<ul>
  <li>Languages & Databases: Python, C, Java, JavaScript, MySQL, MongoDB. </li>
  <li>Frameworks: MERN Stack (MongoDB, Express.js, React.js, Node.js), Django, LaTeX. </li>
  <li>ML Frameworks: PyTorch, Keras, Tensorflow, Numpy, Pandas, scikit-learn, OpenCV, NLTK, Gensim.</li>
</ul>


<h3> Misc </h3>

Outside of research, I enjoy reading non-fiction, playing cricket and badminton, outdoor activities (hiking, cycling, and running), and gardening. I am a DIY enthusiast and love building DIY products like desk organizers, photo frames, planters, etc.

<h3>Contact</h3>
golam.jilani1656@gmail.com
-->


