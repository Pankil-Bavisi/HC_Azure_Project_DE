# Azure Healthcare End-to-End Data Engineering Project
<html>
  <h2 tabindex="-1"><a aria-hidden="true"></a>  
<!--     tabindex="-1"><a aria-hidden="true" -->
    Introduction:
  </h2>
  <p dir="auto">
    <br style="display: block; margin:10px 0; content=''; ">
    <p style="margin-top: 0px; text-size: 50px;" dir="auto">The goal of this Healthcare Data Engineering project is to serve a 'Fact & Dimension' Tables to the Reporting Team to run BI workloads and reports and perform advanced data analytics to gether insights on large-scale Healthcare Data using a wide range of Big Data tools, technologies and Azure cloud services. </p>
    <p>This repository provides a complete end-to-end workflow of the project, offering a clear understanding of the overall architecture, implementation steps, and all the required Azure services and resources.</p>
  <p>By following this project, you will gain hands-on experience with real-world Data Engineering practices and strengthen your journey toward becoming a proficient Big Data Engineer.</p>
  </p>
  
  <h2>Architecture:</h2>
  <p dir="auto">
    <a href="https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/images/Architecture.png">
      <img id="architecture" src="https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/images/Architecture.png" style="margin-top: 0px; text-size: 50px;"> </img>
    </a>
  </p>
  
  <h2>Technnology Used</h2>
    <ul>
      <li>Programming Language - Python</li>
      <li>SQL</li>
      <li>Spark</li>
      <li>PySpark</li>
    </ul>
    <p>==) Azure Cloud Services:</p>
      <ol>
        <li>Azure DataLake Gen2</li>
        <li>Azure Databricks</li>
        <li>Azure Data Factory</li>
        <li>Azure Blob Storage</li>
        <li>Azure Key Vault</li>
        <li>Azure SQL Database</li>
        <li>Linked Service</li>
      </ol>
    <p>==) Other Functionalities:</p>
      <ol>
        <li>Implemented Medallion Architecture</li>
        <li>Implemented Common Data Model(CDM)</li>
        <li>Implemented SCD-2</li>
        <li>Implemented Surrogate Key</li>
        <li>Implemented naming conventions & folder structure</li>
        <li>Made the Pipeline from 'Sequential --> Parallel'</li>
        <li>Implemented 'is_active / is_inactive' (0/1) Flag.</li>
        <li>Added 'is_quarantined' feature to quarantine the bad records. (True: Bad records/False: Good records)</li>
      </ol>
      
  <h2>Dataset Used</h2>
    <p dir="auto">Healthcare Data includes various fields of records such as EMR Data(Patients Data, Providers Data(Doctors), Departments Data, Encounters Data, Transactions Data), Claims Data, CPT Codes Data, NPI & ICD Codes Data.</p>
    <p>Here is the dataset used in the video - <a href="https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/datasets">https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/datasets</a></p>
    <p>Links to understand the KPI's & understand more on Accounts Receivable (AR)</p>
    <ol>
      <li>Website : <a href="https://mdmanagementgroup.com/healthcare-accounts-receivable-management/">https://mdmanagementgroup.com/healthcare-accounts-receivable-management/</a></li>
      <li>Difference between ICD codes CPT codes : <a href="https://www.simplepractice.com/blog/icd-codes-and-cpt-codes/
">https://www.simplepractice.com/blog/icd-codes-and-cpt-codes/
</a></li>
    </ol>
    <p>More info about Healthcare Dataset can be found here: </p>
    <ul>
      <li>1) EMR Data (from 'Azure SQL DB' --> 'Bronze layer' --> 'Silver layer' --> 'Gold layer')</li>
      <li>2) NPI & ICD Data (from 'APIs' --> 'Bronze layer' --> 'Silver layer' --> 'Gold layer')</li>
      <li>3) Claims & CPT Data ('landing' --> 'Bronze layer' --> 'Silver layer' --> 'Gold layer')</li>
      <!-- <li><b>*Notes: </b>The transformation of 'Silver layer' --> 'Gold layer' of 'Encounters Data (part of EMR Data) & Claims Data' work in progress.</li> -->
      <li><b>Work in Progress: </b>The transformation of 'Silver layer' --> 'Gold layer' of 'Encounters Data (part of EMR Data) & Claims Data' is under development and will be updated in upcoming commits.</li>
    </ul> 
    
  <h2>Data Model</h2>
  <p>
    <a href="https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/images/DataModel.png">
      <img id="architecture" src="https://github.com/Pankil-Bavisi/HC_Azure_Project_DE/blob/main/images/DataModel.png"></img>
    </a>
  </p>
  
  <h2 tabindex="-1" dir="auto">End of Project</h2>
  <p dir="auto">Keep Learning, Keep Going | Be Strong | Never Give Up</p>
  
</html>

