# Proj001-P03-Employee-Absenteeism-PM-20220529
Predict Employee Absenteeism
<img style="float:left" src="https://i.imgur.com/DWQOJgU.png" width="1500">

<hr>
29 May 2022

<div>
<img style="float: left" src="https://i.postimg.cc/qvZpHzhk/002-Img-Objectives-Draft-2-20220819.png(https://postimg.cc/cvYpQ1Bj)" width="75">
<h2 id="Obj1">Objectives</h2>
<hr>

<h3 style="text-align:justify">In this project,with the high competitiveness of company today has led to an increased in pressure in the work place. The company expectation becoming high thus there is the probability that the target can not be attained and might raise stress level. The low performance will increase the possibility of the employee being laid off. These can lead to the deteriorate of health gradually or even suddenly.
<br><br>
by predicting employees absenteeism, it might be possible to identify factors that contribute. Because it is time-consuming and expensive to find, interview, and hire new employees, increasing employee retention will be beneficial to the company.</h3> 
<p style = "font-family: Arial; font-size: 18px">Note: This project's dataset was created for pedagogical purposes and may not be indicative of the data.</p>    
</div> 

<div class="alert alert-block alert-warning">
<img style="float: left" src="https://i.postimg.cc/kXz8cFqC/005-Img-Yellow-Notes-Draft-1-20220819.png" width="60">
<b style = "font-family: Arial; font-size: 16px">Remember:</b><p style = "font-family:Verdana; font-size:14px">We must be <b>objective</b> in analyzing the data in order to acquire valuable insights and understand it by collecting, fact checking or challenging the data and other sources. Go to where the data - Genchi Genbutsu attitudes. Data must be <b>Clear, Objective, Valuable, Focus, Agile, Scientific and Timeframe (COV-FAST)</b></p>
    <p style = "font-family:Verdana; font-size:14px">There are methodologies to be considered logistic regression, random forest or neural networking. We can use the same preprocessing dataset and try each options methodologies in seperate notebooks</p>
</div>
    <h3>Methodologies Overview</h3>
<h3>Data Analysis PACE Steps:</h3>
   <ol style="font-family:Verdana; font-size:16px">
    <li><img style="float:left" src="https://i.imgur.com/gIne5bH.png" width="50"> Define (Plan & Analyze - EDA) - PART 1</li> 
    <blockquote>
    <ol>Understand your data in the problem context
        <br>EDA - check model, assumption & select model
    </ol>
    </blockquote>
        <li><img style="float:left" src="https://i.imgur.com/rb8V6X5.png" width="50">Measure (Analyze - EDA)</li>
    <blockquote>
    <ol> EDA - check model, assumption & select model
     </ol>
    </blockquote>
    <li><img style="float:left" src="https://i.imgur.com/J4M3HKM.png" width="50">Analyze (Construct) </li>
    <blockquote>
    <ol>Contruct and evaluate model
     </ol>
    </blockquote>
    <li><img style="float:left" src="https://i.imgur.com/wpcEXQC.png" width="50">Improve (Execute) - interpret model and share the story</li>
    <br>
    <li>Control</li>  
       
## SIPOC Analysis
<hr>
<table style="color:black;
           display:fill;
           border-colapse: colapse;
           width: 100%;
           border: 1px solid black;
           border-collapse: collapse;
           border-style: solid;
           border-radius:5px;
           background-color:#5642C5;
           font-size:110%;
           font-family:Verdana;
           letter-spacing:0.5px">
  <h3 style = "text-align:center">Table 1.1. SIPOC Analysis</h3>
  <tr>
    <th>Supplier (S)
    <th colspan="2">Input (I)</th>    
    <th colspan="4">Process (P)</th>
    <th colspan="2">Output (O)</th>
    <th colspan="2">Customer (C)</th>  
  </tr>
    <td>Employee
    <br>Dept Head
    <br>Employer</td>
    <td colspan="2">Employee
        <ul>
            <li>Time & attendance policies/rules
            <li>Time & attendance recording systems
            <li>Employee communication/on boarding
            <li>Line managers trained accountable 
            <li>Wellness policy/services
        </ul></td> 
    <td style="background:LightSkyBlue;text-align:center">Employee absent without notice, noted in time & attendance system </td>
    <td style="background:LightSkyBlue;text-align:center">Employee notifies or does not notify  employer</td>
    <td style="background:LightSkyBlue;text-align:center">Employee return to work & investigation to establish facts</td>
    <td style="background:LightSkyBlue">Reason accepted as valid & leave/time records adjusted</td>
    <td style="background:LightSkyBlue">Reason accepted or not accepted as valid & leave/time records adjusted</td>
    <td>   
    <ul>
            <li>Update time/attendance & leave records
            <li>Diciplinary process if appropriate  
            <li>Absenteeism tracking & trend analysis
        </ul>
    </td>
    <td colspan="2" style="margin: auto; display:fill; word-wrap: break-word">
        <ul>
            <li>Dept Head
            <li>HR
            <li>Employer
        </ul>
    </td>
 </table>
<div class="alert alert-block alert-warning">
<img style="float: left" src="https://i.postimg.cc/kXz8cFqC/005-Img-Yellow-Notes-Draft-1-20220819.png" width="60">
<b style = "font-family: Arial; font-size: 16px">Note:</b><p style = "font-family:Verdana; font-size:14px">Discussion should be conducted with the process' owner</p>
</div>

## Stakeholder Analysis
<hr>
<span style ="font-family:Verdana; font-size:16px; text-align:justify">In this project we will only be mapping the stakeholders that were mentioned in articles or sources with high impacts and major role to the Salifort Motors project.</span>

<h3 style = "text-align:center">Table 1.3. Stakeholder Analysis</h3>
<table style="color:black;
           display:fill;
           border-colapse: colapse;
           width: 100%;
           border: 1px solid black;
           border-collapse: collapse;
           border-style: solid;
           border-radius:5px;
           background-color:#5642C5;
           font-size:110%;
           font-family:Verdana;
           letter-spacing:0.5px">
  
  <tr>
    <th>Stakeholders</th>
    <th>Role</th>
    <th colspan="2">Involvement</th>    
    <th>Power or Influence (H/M/L)</th>
    <th>Interest (H/M/L)</th>
    <th colspan="2">Engagement</th>  
  </tr>
  <tr>
    <td>HR Director</td>
    <td style = "text-align:left">      
      Project sponsor 
    </td>
    <td colspan="2" style ="text-align:left">
    Makes high-level decisions; serves as team resource
    </td>
    <td style ="text-align:center">
      H 
    </td> 
    <td style ="text-align:center">
      L
    </td>
    <td colspan="2" style ="text-align:left">
      Communicate regularly, but not daily. Ask questions and give updates. 
    </td>
  </tr>
  <tr>
    <td>Dept Head</td>
    <td style = "text-align:left">      
      Project owner 
    </td>
    <td colspan="2" style ="text-align:left">
     <ul>
         <li>Advisory role and providing valid information
         <li>Implementation of preventive, diagnosis and treatment measures
         <li>Allow re-export of surplus imported data or any required items to support project
         <li>Formulation of the business requirements
        <li>Formulation and implementation of equitable distribution of execution
        </ul> 
    </td>
    <td style ="text-align:center">
      M 
    </td> 
    <td style ="text-align:center">
      H 
    </td>
    <td colspan="2" style ="text-align:left">
      <ul>
        <li>Informing, mentoring and coaching
        <li>Monitoring the proper implementation of interventions
        <li>Coordination in informing
        <li>Official information reference in the Human Resource Management and
control
        <li>Training and consulting with other related organizations and institutions
        </ul> 
    </td>
  </tr>
  <tr>
    <td>HR Engagement and Retention</td>
    <td style = "text-align:left">      
      Project leader 
    </td>
    <td colspan="2" style ="text-align:left">
     <ul>
      <li>Project-rules making and planning
     <li>Facilitate and synergy in inter-sectorial cooperation
     <li>Identifying problems and providing solutions in the form of executive
       approvals
     </ul> 
    </td>
    <td style ="text-align:center">
      M 
    </td> 
    <td style ="text-align:center">
      H 
    </td>
    <td colspan="2" style ="text-align:left">
       <ul>
      <li>Synergy and strengthening of various capabilities across the team and organization,
       directing and Mobilizing all capacities within the team.
      <li>Lead project from the start to clossing.
      </ul> 
    </td>
  </tr>
  
 </table>

 ## Figure 1.1 Normal vs Excessive Absenteeism

![image](https://github.com/whyzie/Proj001-P03-Employee-Absenteeism-6--PM-20220529/assets/97485455/d0feb1ab-db25-46be-8e02-dc00146c8236)


 <h3 style = "text-align:center">Table 1.4. Project Charter</h3>
<table style="color:black;
           display:fill;
           border-colapse: colapse;
           width: 100%;
           border: 1px solid black;
           border-collapse: collapse;
           border-style: solid;
           border-radius:5px;
           background-color:#5642C5;
           font-size:110%;
           font-family:Verdana;
           letter-spacing:0.5px">
  
  <tr>
    <th colspan ="4" style="text-align:center">Project HR Employee Productivity</th>
  </tr>
    <tr>
    <th colspan ="4" style="text-align:center">31th May 2022</th>
  </tr>
  <tr>
      <th colspan ="4" style="text-align:center">Document Status: <del>Draft</del> | In Review | <del>Approved</del></th>
  </tr>
  <tr>
      <th colspan ="4" style="text-align:center">Executive Summary</th>
  </tr>
  <tr>
      <td colspan ="4" style="text-align:center">develop a model that predicts employee excessive absenteeism profile.</td>
  </tr>
  <tr style ="background:LightSkyBlue;text-align:center">
      <td colspan ="2">Business Case</td>
      <td colspan ="2">Problem/Opportunity Statement</td>
  </tr>
 <tr style="text-align:left">
      <td colspan ="2">Based on the data company X, from 2015 to 2018 has employees who are absent more than 3 hours or disengaged employee around 46%. It is equal to 4030 absenteeism hours or unproductive hours across 2015 to 2018 (we can't quantify the loss as limited information). The work from home and also work back to office also can be a challenge.
</td>
      <td colspan ="2"><em>In this project</em> we establish a model to find ways to<b> predict employee absenteeism profile. </b>
<br><br>The goal is to identify the people profile who are likely to have excessive absent and increase the hours to productive hours then absent hours,
     </td>
  </tr>

 <tr style ="background:LightSkyBlue;text-align:center">
      <td colspan ="2">Goal Statement</td>
      <td colspan ="2">Deliverables (Key Results)</td>
 </tr>
 <tr style="text-align:left">
      <td colspan ="2">Primary metric:
     <ul>
         <li>Reduce absenteeism hours
     </ul>
     Secondary Metric:
     <ul>
         <li>Average monthly hours
         <li>Evaluation
     </ul>
     </td>
      <td colspan ="2">Primary Key Results:
     <ul>
         <li>Increase retention rate - reduce 50% of people absent more than 3 hours (the data provide the employee who engaged or disengaged).
     </ul>
     Secondary Key Results:
     <ul>
         <li>Number of project
     </ul>
     </td>
  </tr>
 
 <tr style ="background:LightSkyBlue;text-align:center">
      <td colspan ="2">Benefits, Cost, and Budget</td>
      <td colspan ="2">Scope and Exclusion</td>
 </tr>
 <tr style="text-align:left">
      <td colspan ="2">Benefits:
     <ul>
         <li>Reducing 50% of employees (for below 50 employees) disengaged employee from unproductive hours $(No data provided) in avoidable costs.
     </ul>
     Costs:
     <ul>
         <li>Recruitment cost
         <li>Training cost   
     </ul>
     Budget Needed:
           <span>TBD</span>
     </td>
      <td colspan ="2">In-Scope:
     <ul>
         <li>All department
         <li>Full time
     </ul>
     Out-of-Scope:
     <ul>
         <li>Part Time or contract
     </ul>
     </td>
  </tr>   
 
 <tr style ="background:LightSkyBlue;text-align:center">
      <td colspan ="2">Project Team</td>
      <td colspan ="2">Measuring Success</td>
 </tr>
 <tr style="text-align:left">
      <td colspan ="2"> 
     <ul>
         <li>Sponsor: Laura, Director of HR
         <li>Owner: Washington, Operations Manager
         <li>Leader:Joko, Senior   
             HR Engagement and Retentioan
         <li>Member: Denzel, Data Analysis Manager, jennifer, Senior Data Analyst, Wahyu Senior Data Analyst   
     </ul>
     </td>
  
  <td colspan ="2">Deliverables after solutions implementation:
     <ul>
         <li>Increase productivity hours
     </ul>
  </td>
  </tr>
  </table>

  <hr>
<table style="color:black;
           display:fill;
           border-colapse: colapse;
           width: 100%;
           border: 1px solid black;
           border-collapse: collapse;
           border-style: solid;
           border-radius:5px;
           background-color:#5642C5;
           font-size:110%;
           font-family:Verdana;
           letter-spacing:0.5px">
            
  <h3 style = "text-align:center">Table 2. Machine Learning Model Feature Importance </h3>
  <tr>
    <th>XG Boost (1)</th>
    <th>Decision Tree (1)</th>
    <th>Random Forest (1)</th>    
  </tr>
  <tr style = "text-align:center">
      <td><img style= "margin:auto" src="https://i.imgur.com/fRCagnV.png" width = "600"></td>
      <td><img style= "margin:auto" src="https://i.imgur.com/r5NT76p.png" width = "600"></td>
      <td><img style= "margin:auto" src="https://i.imgur.com/kBpwsEl.png" width = "600"></td>
  </tr>
  </table>
  
## Conclussion
<hr>

<div class="alert alert-block alert-success" style="font-family:verdana; font-size:14px">

Logistic Regression
<br><br>
The logistic regression model achieved precision of 73%, recall of 73%, f1-score of 73% (all weighted averages), and accuracy of 72.86%, on the test set.
<br><br>
Tree-based Machine Learning
<br><br>
We only still in the level 01 (baseline) and has not done feature engineering, the xgboost model achieved AUC of 79.4%, precision of 75.4%, recall of 81.2%, f1-score of 78.2%, and accuracy of 19.3%, on the test set. The random forest and decision tree model slightly underperformed the decision tree model
<br>    
The models and the feature importances extracted from the models baseline shows that employees at the company are drive by the trasport expense. 
<br><br>
To preliminary reduce absenteeism, the following recommendations could be presented to the stakeholders:
<br><br>
<ol>
<li> Transportation expense between ~190 to 300 USD have the most employee with excessive absenteeism. We have to look to this further whether they can work from home,  as the distance with this range account of ~10 to 40 distance to work but not included as feature importance.
<li>  We can see that there are employees who are overworked increase in ~240-300 hours
<li> We can see the increase of children also decrease employee with excessive absenteeism. There are employees without children who are disengaged employees. We can also elaborate by separating to two groups without children (0) and with children (1).
<li>Ensure that employee has understood the overtime policy, check and if the employee has been given information accordingly.  Consider that employee can exchange their overtime with more paid leave of holiday or vacation.
<li>Ensure that employee has understood the absenteeism policy, check and if the employee has been given information accordingly.    
<li>Important to have team or department as well in company-wide discussion regarding the work culture.
<li> Body mass index and month value, provide gym or healthy programs.
<br><br>
Next Steps
<br>
It may be justified to still have some concern about data leakage and we only have small data of 700. Feture engineering is required to confirm the results further.
</div>
