# big-data-project-solved
**TO GET THIS SOLUTION VISIT:** [Big-Data Project Solved](https://www.ankitcodinghub.com/product/big-data-project-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;94213&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;Big-Data Project Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
This project assignment is to be executed in groups of three students. All students must contribute to the final outcome somehow (although they may have different tasks). Please notice that in the last page of the report you are expected to list the contributions of each group member, together with it’s relevance to the final result in percentage (the percentages given to the group members must add up to 100%).

1 The Data Set

Hazardous air pollutants, also known as toxic air pollutants or air toxics, are those pollu- tants that are known or suspected to cause cancer or other serious health effects, such as re- productive effects or birth defects, or adverse environmental effects. The USA Environmen- tal Protection Agency (EPA) tracks 187 air pollutants. See https://www.epa.gov/haps/ for more information.

1.1 The Main Data Set

The Data Set is a 2.6GB CSV file (epa_hap_daily_summary.csv) that contains data for every monitor (sampled parameter) in the Environmental Protection Agency (EPA) database for each day (available from Kaggle1). Each entry contains a daily summary record that is:

1. The aggregation of all sub-daily measurements taken at the monitor; or

2. A single sample value, if the monitor takes a single, daily sample (e.g., there is only one sample with a 24-hour duration). In this case, the mean and max daily sample will have the same value.

For development purposes, you may use the smaller version of the Data File with only 117 MB (epa_hap_daily_summary-small.csv)! See below for the links.

1.1.1 The Main Data Set Structure

The main Data Set contains 29 columns with the following contents:

1. State Code: The Federal Information Processing Standards (FIPS) code of the state in which the monitor resides.

</div>
</div>
<div class="layoutArea">
<div class="column">
1 https://www.kaggle.com/epa/hazardous- air- pollutants

</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>County Code: The FIPS code of the county in which the monitor resides.</li>
<li>Site Num: A unique number within the county identifying the site.</li>
<li>Parameter Code: The AQS code corresponding to the parameter measured by the monitor.</li>
<li>POC: This is the “Parameter Occurrence Code” used to distinguish different instru- ments that measure the same parameter at the same site.</li>
<li>Latitude: The monitoring site’s angular distance north of the equator measured in decimal degrees.</li>
<li>Longitude: The monitoring site’s angular distance east of the prime meridian mea- sured in decimal degrees.</li>
<li>Datum: The Datum associated with the Latitude and Longitude measures.</li>
<li>Parameter Name: The name or description assigned in AQS to the parameter
measured by the monitor. Parameters may be pollutants or non-pollutants.
</li>
<li>Sample Duration: The length of time that air passes through the monitoring device before it is analyzed (measured). So, it represents an averaging period in the atmosphere (for example, a 24-hour sample duration draws ambient air over a collection filter for 24 straight hours). For continuous monitors, it can represent an averaging time of many samples (for example, a 1-hour value may be the average of four one-minute samples collected during each quarter of the hour).</li>
<li>Pollutant Standard: A description of the ambient air quality standard rules used to aggregate statistics.</li>
<li>Date Local: The calendar date for the summary. All daily summaries are for the local standard day (midnight to midnight) at the monitor.</li>
<li>Units of Measure: The unit of measure for the parameter.</li>
<li>Event Type: Indicates whether data measured during exceptional events are in- cluded in the summary. A wildfire is an example of an exceptional event; it is something that affects air quality, but the local agency has no control over. None means no events occurred. Included means events occurred and the data from them is included in the summary. Excluded means that events occurred but data form them is excluded from the summary. Concurred Events Excluded means that events occurred but only EPA concurred exclusions are removed from the summary. If an event occurred for the parameter in question, the data will have multiple records for each monitor.</li>
<li>Observation Count: The number of observations (samples) taken during the day.</li>
<li>Observation Percent: The percent representing the number of observations taken with respect to the number scheduled to be taken during the day. This is only calcu- lated for monitors where measurements are required (e.g., only certain parameters).</li>
<li>Arithmetic Mean: The average (arithmetic mean) value for the day.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column"></div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
<ol start="18">
<li>1st Max Value: The highest value for the day.</li>
<li>1st Max Hour: The hour (on a 24-hour clock) when the highest value for the day
(the previous field) was taken.
</li>
<li>AQI: The Air Quality Index for the day for the pollutant, if applicable.</li>
<li>Method Code: An internal system code indicating the method (processes, equip- ment, and protocols) used in gathering and measuring the sample. The method name is in the next column.</li>
<li>Method Name: A short description of the processes, equipment, and protocols used in gathering and measuring the sample.</li>
<li>Local Site Name: The name of the site (if any) given by the State, local, or tribal air pollution control agency that operates it.</li>
<li>Address: The approximate street address of the monitoring site.</li>
<li>State Name: The name of the state where the monitoring site is located.</li>
<li>County Name: The name of the county where the monitoring site is located.</li>
<li>City Name: The name of the city where the monitoring site is located. This represents the legal incorporated boundaries of cities and not urban areas.</li>
<li>CBSA Name: The name of the core bases statistical area (metropolitan area) where the monitoring site is located.</li>
<li>Date of Last Change: The date the last time any numeric values in this record were updated in the AQS data system.</li>
</ol>
1.1.2 Downloading the Data Set

The three Data Sets (the main data set, the reduced data set, the secondary data set) are available as a 579 MB ZIP file from

<pre>   https://tinyurl.com/drnfupyb
</pre>
1.2 The Secondary Data Set

There is an additional auxiliary CSV file (usa_states.csv) that contains an approximation of the limits (latitude and longitude) of all the USA states, e.g.,

State Name MinLat MaxLat MinLon MaxLon

</div>
</div>
<div class="layoutArea">
<div class="column">
AK AL .

</div>
<div class="column">
Alaska Alabama

</div>
<div class="column">
52.5964 30.1463

</div>
<div class="column">
71.5232 -169.9146 35.0041 -88.4743

</div>
<div class="column">
-129.9930 -84.8927

</div>
</div>
<div class="layoutArea">
<div class="column">
.

This data set will be necessary for answering some of the questions.

</div>
</div>
<div class="layoutArea">
<div class="column">
.

</div>
<div class="column">
. .

</div>
<div class="column">
.

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
2 Project Assignment

You are asked to use the technologies we studied in this course, namely, 1. Map-Reduce;

2. Spark (plain Spark);

3. SparkDF (Spark with Dataframes);

4. SparkSql (Spark with SQL); and

5. Hive;

</div>
</div>
<div class="layoutArea">
<div class="column">
to prepare a set of indexes that will help answering the following questions:

<ol>
<li>Q.1) &nbsp;Which states have more/less monitors? (Rank states!)</li>
<li>Q.2) &nbsp;Which counties have the best/worst air quality? (Rank counties considering pollu- tants’ level!)</li>
<li>Q.3) &nbsp;Which states have the best/worst air quality in each year? (Rank states per year considering pollutants’ level!)</li>
<li>Q.4) &nbsp;For each state, what is the average distance (in km) of the monitors in that state to the state center? For simplicity, assume that 1 degree of latitude or logitude equals to 111 km. (Monitor dispersion per state!)</li>
<li>Q.5) &nbsp;How many sensors there are per quadrant (NW, NE, SE, SW) in each state? To answer this question, you should approximate each state’s area to a rectangle as defined in the file “usa_satates.csv”, and divide that area in 4 quadrants (NW, NE, SE, SW). (Count monitors per sate qudrant!)</li>
</ol>
2.1 Experimental Work

Please create a Jupyter Notebook for each technology, where the questions are answered in the same order as listed above. Each Jupyter file should be named as:

<pre>    &lt;Gnn&gt;-&lt;TECHNOLOGY&gt;.ipynb
</pre>
where &lt;Gnn&gt; is the group numer, e.g., G05, and &lt;TECHNOLOGY&gt; is one of: mapreduce, spark, sparkDF, sparkSQL, hive.

Start by developing your solution in your personal computer with the small data set. Once you believe your solutions are ok, then you may try them in the Department’s Cluster. Additional instructions on how to access and use the Department’s Cluster will be given later.

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
2.2 Project Report

</div>
</div>
<div class="layoutArea">
<div class="column">
Prepare a project report in PDF format with name “Gnn-report.pdf” (where “Gnn” is the group number), with the look and feel of a research paper, with a maximum of 4 pages. If necessary a 5th page may be added only for “acknowledgments”, “description of the individual contributions”, and “references”. It is mandatory to follow the IEEE template for Computer Society Journals using either Word or LaTeX. Please remember to show, for each exercise, a small sample of the produced index and the corresponding execution time.

To get the IEEE template site at https://goo.gl/Xtjdh4 and

Select Publication Type → Transactions, Journals and Letters;

Select Publication → IEEE Transactions on Parallel and Distributed Systems; Select Article Type → Original Research;

Select Format → LaTeX or Word;

Download Template → Download Template;

Remember the Bloom’s Pyramid… the report should have a stronger emphasis on the upper layers of the pyramid (evaluate, analyze, create) rather than on the lower layers (remember, understand, apply). This means that, although How did you do your work? is important to me, What you learned with your work (and how did you learned it)? is much more important!

Please remember that in the last page of the report you are expected to have three sections:

<ol>
<li>List all the documentation relevant to your work in the “Bibliography/References”. The entries listed in this section must be cited somewhere in the main text.</li>
<li>List the contributions of each group member, together with it’s relevance to the final result in percentage (the percentages given to the group members must add up to 100%).</li>
<li>Acknowledgments to other colleagues (non-group members) that somehow were rel- evant to your work. Please be sure you identify the colleagues clearly (if possible include their student number) and how they helped you.</li>
</ol>
</div>
</div>
</div>
