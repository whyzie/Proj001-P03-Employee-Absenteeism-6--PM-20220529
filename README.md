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
