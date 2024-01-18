<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Howard Brown | Data Science Portfolio</title>
  <link rel="stylesheet" href="https://bootswatch.com/4/slate/bootstrap.min.css">
  <style>
    .banner {
      background-image: url("https://github.com/HowardBBrown/howardbbrown.github.io/blob/main/kenny-eliason-OjxsirfohHU-unsplash.jpg");
      background-size: cover;
      background-position: center;
      height: 400px;
    }

    .profile {
      width: 200px;
      height: 200px;
      border-radius: 50%;
      object-fit: cover;
      margin: -100px auto 0;
      border: 5px solid white;
    }

    .name {
      font-size: 36px;
      font-weight: bold;
      color: white;
      text-align: center;
      margin-top: 10px;
    }

    .bio {
      font-size: 18px;
      color: white;
      text-align: center;
      margin-top: 10px;
    }

    .contact {
      font-size: 18px;
      color: white;
      text-align: center;
      margin-top: 10px;
    }

    .contact a {
      color: white;
      text-decoration: none;
    }

    .section {
      padding: 20px;
    }

    .section-title {
      font-size: 24px;
      font-weight: bold;
      color: #17a2b8;
      margin-bottom: 20px;
    }

    .card {
      margin-bottom: 20px;
    }

    .card-img-top {
      height: 200px;
      object-fit: cover;
    }

    .card-title {
      font-size: 18px;
      font-weight: bold;
      color: #17a2b8;
    }

    .card-link {
      color: #17a2b8;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <div class="banner">
    <img src="profile.jpg" alt="Howard Brown" class="profile">
    <div class="name">Howard Brown</div>
    <div class="bio">I'm a computer science graduate with an interest in quantum computing and machine learning. During my final research science internship at Lockheed Martin, I taught myself quantum mechanics to better understand some research papers at the time. Upon returning to the university, I took quantum physics I and earned the second-highest grade (B) in the class. I'm the only non-physicist that has been allowed to take the course at my school. I've been hooked ever since.
    I like solving issues of a complicated manner and am available to solve problems.</div>
    <div class="contact"><a href="mailto:howard.brown@example.com">Email</a> | <a href="https://www.linkedin.com/in/howard-brown/">LinkedIn</a> | <a href="https://github.com/HowardBBrown">GitHub</a></div>
  </div>
  <div class="section">
    <div class="container">
      <div class="section-title">Education</div>
      <div class="row">
        <div class="col-md-12">
          <div class="card">
            <div class="card-body">
              <div class="card-title">BSc. Computer Science, Hampton University</div>
              <div class="card-text">Graduated in 2016 with a GPA of 3.8. Took courses in data structures, algorithms, databases, artificial intelligence, quantum computing, and machine learning.</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="section">
    <div class="container">
      <div class="section-title">Experience</div>
      <div class="row">
        <div class="col-md-12">
          <div class="card">
            <div class="card-body">
              <div class="card-title">Lockheed Martin 2015</div>
              <div class="card-subtitle">Research Science Intern</div>
              <div class="card-text">
                <ul>
                  <li>As one of three data scientists, we predicted shortages for each part used in the 2-year construction of F-35 aircraft worth $400M each, years in advance, as part of a large cross-functional team</li>
                  <li>Modeled how supply chain risks changed over time using R and SAP HANA (SQL based)</li>
                  <li>Predicted optimal order of plane variants to be built over next 50 years against uncertainty of non-committed customers in R</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="card-body">
              <div class="card-title">Lockheed Martin 2014 - 2015</div>
              <div class="card-subtitle">Research Science Intern</div>
              <div class="card-text">
                <ul>
                  <li>Part of a five person team working on a corporate R&D project to apply machine learning and natural
                  language processing techniques to predict schedule, budget and performance risks 6 months in advance for every program within Lockheed Martin.</li>
                  <li>Early predictions allowed enough time for corrective measures to be taken to save each identified program</li>
                  <li>Engineering Manager’s skip was the CTO of Lockheed Martin</li>
                  <li>Stakeholders were the heads of each Business Area (company) of Lockheed Martin</li>
                  <li>First intern in Lockheed Martin history to work on a corporate R&D project for the CTO</li>
                  <li>Acted as sole engineer for the GUI while principal research scientist was on sabbatical</li>
                  <li>Designed and implemented code to take raw predictions as input and developed data structures and methods to display reports and accuracy ROC curves in the Graphical User Interface</li>
                  <li>Restructured data, took features from earlier in the cleaning process to generate new features and provide more context</li>
                  <li>Took requirements and implemented data structures and API for external AI firms that needed to run experiments on our data. Extract, Transform, Load</li>
                  <li>Learned Python, Pandas, NumPy, HDF5, Scikit-Learn, Natural Language Tool Kit on the job</li>
                </ul>
              </div>
            </div>
          </div>
          <div class="card">
            <div class="card-body">
              <div class="card-title">Lockheed Martin 2014</div>
              <div class="card-subtitle">Software Engineering Intern</div>
              <div class="card-text">
                <ul>
                  <li>I implemented Lockheed T-50A in a videogame simulator for training pilots to fly F-35 aircraft as part of an R&D project that aimed to replace the US Air Force trainer jet and win a $9.2B award fee</li>
                  <li>Designed and implemented code to develop training simulations in Lockheed’s commercial flight simulator, Prepar3D in C++, XML</li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <div class="section">
    <div class="container">
      <div class="section-title">Data Science Projects</div>
      <div class="row">
        <div class="col-md-6">
          <div class="card">
            <img src="https://via.placeholder.com/300x200" alt="Random Forest Classifier Project" class="card-img-top">
            <div class="card-body">
              <div class="card-title"><a href="https://github.com/HowardBBrown/Data-Science-Projects/blob/main/Classification/randomForestClassifier.ipynb">Random Forest Classifier Project</a></div>
              <div class="card-text">An project using the scikit-learn implementation of the RandomForestClassifier placeholder</div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
