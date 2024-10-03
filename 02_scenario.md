You are the newest member of Automatidata’s data analytics team. Your team is still in the early stages of their project for the New York City Taxi & Limousine Commission (TLC). 

Previously, you were asked to complete a project proposal by your supervisor, Deshawn Washington. You have received notice that your project proposal has been approved and that TLC has given the Automatidata team access to their data for research purposes. Congratulations! To get clear insights, TLC's data must be analyzed, key variables identified, and the dataset ensured it is ready for analysis.

You discover two new emails in your inbox: one from your supervisor, Deshawn Washington, and one from your teammate, Luana Rodriguez. Review the emails, then follow the provided instructions to complete the PACE strategy document, the code notebook, and the executive summary. 

**_Note:_** *Team member names used in this workplace scenario are fictional and are not representative of the New York City TLC.*

# 

**Email from Deshawn Washington, Data Analysis Manager**

**Subject:** Help with coding notebook?

**From:** “Deshawn Washington,” ```Deshawn@automatidata.com```

**Cc:** “Luana Rodriquez” ```Luana@automatidata.com```

Good morning team,

I have a couple of updates on the TLC project. The project proposal that you completed previously has been approved. Thanks for all of your great work so far.  Additionally, I just received an email from our Senior Project Manager, Uli King, that TLC has given our team access to their data.

Before we begin the process of Exploratory Data Analysis (EDA), we could really use your help with coding and prepping the data. During your interview you mentioned that you worked with Python during the Google Career Certificate program. That experience sounds applicable here. 

Luana (Cc’d) started a Jupyter notebook with the relevant dataset from TLC (attached). She is busy in the final stages of another project currently. I’m sure she could use your assistance in completing the coding and setting up the notebook for the TLC project. 

Luana, do you mind sharing the details? 

Humblest regards, 

Deshawn Washington

Data Analysis Manager

Automatidata

# 

Email from Luana Rodriquez, Senior Data Analyst

**Subject:** RE: Help with coding notebook?

**From:**  “Luana Rodriquez” ```Luana@automatidata.com```

**Cc:** “Deshawn Washington,” ```Deshawn@automatidata.com```

Nice to meet you (virtually)! 

Hope you have enjoyed your first few weeks! 

The project proposal you helped prepare covered the major points of this project, so I’ll get right to how you can assist the team. There are a number of us making adjustments to the machine learning developed for the last client, so your help is greatly appreciated!

Until we finish the prior project, there is no need to do a full EDA on this data. We will get to that soon. Do you mind reviewing the TLC data we received for the team? It would be fantastic if you could include a summary of the column Dtypes, data value nonnull counts, relevant and irrelevant columns, along with anything else code related you think is worth sharing in the notebook? It would be really helpful if you can create meaningful variables by combining or modifying the structures given. 

Thanks,

Luana Rodriquez

Senior Data Analyst

Automatidata

#

## Step-By-Step Instructions

Follow the instructions to complete the activity. Then, go to the next course item to compare your work to a completed exemplar.

### Step 1: Access the templates

To use the templates for this course item, click each link of the following links and select Use Template. 

Links to templates:  

- [PACE strategy document](https://github.com/pereisergio/Automatidata/tree/main/Templates/)

- [Executive summary templates](https://github.com/pereisergio/Automatidata/tree/main/Templates/)

### Step 2: Access the end-of-course project lab

**_Note_**: *The following lab is also the next course item. Once you complete and submit your end-of-course project activity, return to the lab instructions’ page and click Next to continue on to the exemplar reading.*

To access the end-of-course project lab, click the following link and select Open Lab. 

- [Automatidata project lab]()

Your Python notebook for this project includes a guided framework that will assist you with the required coding. Input the code and answer the questions in your Python notebook to inspect and organize your data. You’ll find helpful reminders for tasks like: 

- Importing data

- Loading necessary packages

- Identifying relevant data structures and summarizing data

- Extracting information from columns

- Combining or modifying data structures to create meaningful variables

You will also discover questions in this Python notebook designed to help you gather the relevant information you’ll need to write an executive summary for your team.

Use your completed PACE strategy document and Python notebook to help you prepare your executive summary.

### Data Dictionary

This project uses a dataset called 2017_Yellow_Taxi_Trip_Data. It contains data gathered by the New York City Taxi & Limousine Commission. For each trip, there are many different data variables gathered. Please find the attached dataset below. 

The dataset contains:

- [Data]()

**408,294 rows** – each row represents a different trip

**18 columns**

| **Column name** | **Description** |
|-----------|-----------|
| ID | Trip identification number |
| VendorID | A code indicating the TPEP provider that provided the record.<br>**1= Creative Mobile Technologies, LLC;**<br>**2= VeriFone Inc.**|
| tpep_pickup_datetime | The date and time when the meter was engaged. |
| tpep_dropoff_datetime |The date and time when the meter was disengaged. |
| Passenger_count | The number of passengers in the vehicle.<br>This is a driver-entered value. |
| Trip_distance |The elapsed trip distance in miles reported by the taximeter. |
| PULocationID | TLC Taxi Zone in which the taximeter was engaged |
| DOLocationID | TLC Taxi Zone in which the taximeter was disengaged |
| RateCodeID | The final rate code in effect at the end of the trip.<br>**1= Standard rate**<br>**2=JFK**<br>**3=Newark**<br>**4=Nassau or Westchester**<br>**5=Negotiated fare**<br>**6=Group ride** |
| Store_and_fwd_flag | |This flag indicates whether the trip record was held in vehicle memory before being sent to the vendor, aka “store and forward,”  because the vehicle did not have a connection to the server.<br>**Y= store and forward trip**<br>**N= not a store and forward trip** |
| Payment_type | A numeric code signifying how the passenger paid for the trip.<br>**1= Credit card**<br>**2= Cash**<br>**3= No charge**<br>**4= Dispute**<br>**5= Unknown**<br>**6= Voided trip** |
| Fare_amount |The time-and-distance fare calculated by the meter. |
| Extra | Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges. |
| MTA_tax | $0.50 MTA tax that is automatically triggered based on the metered rate in use. |
| Improvement_surcharge | $0.30 improvement surcharge assessed trips at the flag drop. The  improvement surcharge began being levied in 2015. |
| Tip_amount | Tip amount – This field is automatically populated for credit card tips. Cash tips are not included. |
| Tolls_amount | Total amount of all tolls paid in trip. |
| Total_amount | The total amount charged to passengers. Does not include cash tips. |

### Step 3: Complete your PACE strategy document

The PACE strategy document includes questions that will help guide you through the Automatidata workplace scenario project. Answer the questions in your PACE strategy document to prepare for using Python to inspect and organize your data. 

As a reminder, the PACE strategy document is designed to help you complete the contents for each of the templates provided. You might navigate back and forth between the PACE strategy document and the Python notebook. Make sure your PACE strategy document is complete before preparing your executive summary. 

### Step 4: Prepare an executive summary

Your executive summary will keep your teammates at Automatidata informed of your progress. The one-page format is designed to respect teammates and stakeholders who may not have time to read and understand an entire report. 

First, select one of the executive summary design layouts from the provided template. Then, add the relevant information. Your executive summary should include the following:

- A summary of your tasks

- Information regarding the results of your data variable assessment

- Identify recommended next steps in order to build a predictive model

- Complete your executive summary to effectively communicate your results to your teammates. 
