<h1> Service Level Analytics </h1>
<p> This is a resume project challenge from <a href="https://codebasics.io/challenge/codebasics-resume-project-challenge/5">code basics</a>.</p>
<h2>Problem Statement</h2>
<p>AtliQ Mart is a growing FMCG manufacturer headquartered in Gujarat, India. It is currently operational in three cities Surat, Ahmedabad and Vadodara. They want to expand to other metros/Tier 1 cities in the next 2 years.

AtliQ Mart is currently facing a problem where a few key customers did not extend their annual contracts due to service issues. It is speculated that some of the essential products were either not delivered on time or not delivered in full over a continued period, which could have resulted in bad customer service. Management wants to fix this issue before expanding to other cities and requested their supply chain analytics team to track the ’On time’ and ‘In Full’ delivery service level for all the customers daily basis so that they can respond swiftly to these issues.

The Supply Chain team decided to use a standard approach to measure the service level in which they will measure ‘On-time delivery (OT) %’, ‘In-full delivery (IF) %’, and OnTime in full (OTIF) %’ of the customer orders daily basis against the target service level set for each customer.</p>

<h2>Objectives</h2>
<ol>
  <li>Create the metrics according to the metrics list.</li>
  <li>Create a dashboard according to the requirements provided by stakeholders in the business review meeting. You will be provided with the transcript of this business review meeting in comic form.</li>
  <li>Create relevant insights not provided in the metric list/stakeholder meeting.</li>
</ol>

<h2>Files</h2>
<p>My solution to the project is <strong>Service Level Analytics.pbix</strong> file</p>
<p>I used python to create the metrics in the <strong>data_preprocessing.ipynb</strong> file in the <strong>C2 Input for participants</strong> folder</p> 
<p><strong> C2 Stakeholder Chat_Business Review Meeting.pdf</strong> contains information on the requirements of the dashboard </p>
<p><strong> C2 Business Knowledge.pdf</strong> contains information of how to calculate the metrics</p>
<p><strong> C2 Peter Pandey's Note.pdf</strong> contains information of how the dashboard should look like </p>
<p>All other files in the <strong>C2 Input for participants</strong> folder represents datasets and requirements of the project.</p>
<p><strong>meta_data.txt</strong> contains all the information about the data provided by the company. These include:</p>
<ol>
  <li>dim_customers.csv</li>
  <li>dim_date.csv</li>
  <li>dim_products.csv</li>
  <li>dim_targets_order.csv</li>
  <li>fact_orders_aggregate.csv</li>
</ol>
<p> <strong>lifr_vofr_metrics</strong> contains the LIFR (Line FIll Rate) and VOFR (Volume Fill Rate) metrics </p>
<p> <strong>metrics_vs_targets.csv</strong> contains the On Time%, In Full% an On Time In Full% metrics compared to the their expected targets.</p>







