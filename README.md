# Exploring and Visualizing Hate Crimes Across the United States

## Group Members:
	Our team consists of two members: Preethi and Lucius. Given that we have only two members, we decided that having
	strictly defined roles would not benefit our project. Instead, we will have equal ownership over the Project
	Manager/Director of Research/Director of Computation/Reporter roles. Preethi will lead in the Project Manager 
	and Director of Computation roles, and Lucius will lead in the Director of Research and Reporter roles. 

## Purpose:
	Our project will explore the COMPAS dataset provided by the investigative news organization ProPublica, published as part of their series on machine bias. They have done some analysis on this dataset to reveal that COMPAS scores contain several problematic biases (particularly against black defendants). We hope to leverage their existing work as a means of assessing bias while performing our own additional exploratory analysis and building our own model. More specifically, we will do the following:
	Exploratory Data Analysis: Perform clustering (using partitional and/or hierarchical clustering techniques) to 		understand the structure of the COMPAS data and see if any interesting features drive the clusters or if we can 	visually see different ‘levels of risk’ (in terms of recidivism) in the clustered data.
	Building Our Own Model: ProPublica’s analysis (1) creates a logistic regression to analyze which features contribute 	     most to the COMPAS score, and (2) uses a Cox proportional hazards model to measure how accurate the COMPAS predictions 	    are (i.e. how often did people actually recidivate after receiving a score). We want to build our own model that uses 	  the existing features from a profile to predict the likelihood of recidivating (a model that is not created in 		ProPublica’s analysis). After developing our own model, we want to (1) compare the predictive accuracy of our model to 	       the COMPAS model and (2) explore what kinds of bias exist in our model using the approach outlined by ProPublica and 	    see if we can minimize our own algorithmic bias.


## Data:
	The data was released along with the article and methodology. It contains information regarding the defendant’s COMPAS 	       score, race, age, criminal history, future recidivism, charge degree, gender and age.

## Variables:
	The dataset contains the following list of features:
	Id, name, first, last, compas_screening_date, sex, dob, age, age_cat, race, juv_fel_count, decile_score, 		juv_misd_count, juv_other_count, priors_count, days_b_screening_arrest, c_jail_in, c_jail_out, c_case_number, 		c_offense_date, c_arrest_date, c_days_from_compas, c_charge_degree, c_charge_desc, is_recid, r_case_number, 		r_charge_degree, r_days_from_arrest, r_offense_date, r_charge_desc, r_jail_in, r_jail_out, violent_recid, 		is_violent_recid, vr_case_number, vr_charge_degree, vr_offense_date, vr_charge_desc, type_of_assessment, decile_score, 	       score_text, screening_date, v_type_of_assessment, v_decile_score, v_score_text, v_screening_date, in_custody, 		out_custody, priors_count, start, end, event, two_year_recid


## End Product:
	Our end product will be a set of visualizations/graphs relating to our exploratory data analysis as well as a 		statistical model (we’re tentatively thinking logistic regression). Along with our visualizations and model, we will 	     provide a narrative to explain our process and findings, particularly in regards to how our predictive performance 	relates to the COMPAS score and potential bias in our model. Having access to the model (instead of it being a black 	     box, as with the COMPAS model) might also allow us to gain insight into different sources of bias related to this 		problem. Potential topics to investigate include the frequency of hate crimes over time, the distribution of hate 	  crimes geographically, and the types of hate crimes that have occurred over this period (using semantic analysis 		approaches on the summaries). 

