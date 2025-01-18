---
layout: page
---
<style>
    body {
        text-align: justify;
        color: #4a5044;
    }
    h1 {
        color: #4a5044;
        text-decoration: underline;
        text-underline-offset: 10px
        /* border: 1px solid red; */
    }
    .subheading-split{
        display:flex;
        justify-content: space-between;
        color: #4a5044;
        font-size: 18px;
    }
    .subheading-split-left-first {
        font-size: 23px;
        font-weight: 700;
        margin: 0px;
        padding: 0px;
        /* border:1px solid black; */
    }
    .subheading-split-right-first {
        font-size: 23px;
        font-weight: 400;
        margin: 0px;
        padding: 0px;
    }
    .content-list {
        margin-left:40px;
    }
    .courses-list {
        margin-left: 20px;
        font-size: 18px;
        color: #4a5044;
    }
    .bold-skills-content {
        color: #4a5044;
        font-weight: 400;
    }
    .bold-skills-content b {
        font-weight: 700;
    }
    .multiple-img-container {
        display: flex;
        justify-content: space-around;
    }
    .single-img-container {
        text-align: center;
        font-size: 13px;
    }
    .light-bold {
        font-weight: 660;
        color: #4a5044;
    }
</style>
<!-- ### Projects -->
<h1>Projects</h1>

  <div class="subheading-split">
    <div>
      <span><p class="subheading-split-left-first">Machine Learning Based Event Extraction from
        Unstructured Data</p>
      <i>Bachelor's Thesis</i></span>
    </div>
  </div>
  <p>Supervisors: <a href="https://www.bits-pilani.ac.in/pilani/surekha-bhanot/">Prof. Surekha Bhanot</a>, <a href="https://personalpages.manchester.ac.uk/staff/riza.batista/">Dr. Riza Batista-Navarro</a></p>
  <div class="multiple-img-container">
    <div class="single-img-container">
        <img src="images/thesis_example.png" alt="Thesis Example" height="400"/>
        <p><i>Fig. Event Extraction Example</i></p>
    </div>
    <div class="single-img-container">
        <img src="images/thesis_full_model.png" alt="Example Image" height="400"/>
        <p><i>Fig. Model Architecture</i></p>
    </div>
  </div>
  <p>This project explored the extraction of cooking-related events from unstructured data, such as online recipes, using advanced machine learning and natural language processing techniques. Recipes are a rich source of information, detailing food preparation steps and methods. The goal was to transform these unstructured texts into structured, machine-readable event templates with minimal reliance on annotated datasets. By combining clustering, interactive machine learning, and transformer-based models, the thesis delivered a robust system for semi-automated event detection.</p>
  
  <p>
    The approach integrates:<br>
    <b class="light-bold">Clustering Algorithms:</b> HDBScan for identifying patterns in unstructured recipe data.<br>
    <b class="light-bold">Interactive Machine Learning:</b> Semi-supervised training with minimal human intervention.<br>
    <b class="light-bold">Transformer Models:</b> Fine-tuned BERT and T5 for question generation, answering, and machine reading comprehension.<br>
    <b class="light-bold">Linguistic Analysis:</b> Incorporation of POS tagging to improve system precision.
  </p>

<h4>Key Contributions:</h4>
<ul class="content-list">
    <li>Innovative Carbon Emission Model: Applied interactive machine learning and machine reading comprehension to create a model that calculates carbon emissions in recipes based on the extracted event templates</li>
    <li>Semi-Supervised Event Extraction: Designed a system that uses HDBScan clustering and human-in-the-loop training to extract events from unstructured data without pre-existing annotations.</li>
    <li>Transformer-Based Question Generation: Fine-tuned BERT and T5 models to generate relevant questions and refine event details. Incorporated POS tagging to improve accuracy in event detection.</li>
    <li>Research Excellence: Demonstrated strong problem-solving, critical thinking, and communication skills through collaborative work with academic mentors and experts. Enhanced teamwork and model design abilities throughout the project.</li>
</ul>