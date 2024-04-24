# Problem statement and literature review

The goal of the Insurance Company Benchmark (COIL 2000) dataset is to provide real-world data for predictive modeling and analysis in the context of an insurance company's customer base. The dataset contains information on 9,000 customers of an insurance company, with 86 variables that include product usage data and socio-demographic data derived from zip area codes.
The dataset was donated in July 2000 as part of the CoIL 2000 Challenge, a data mining competition organized by the Dutch company Sentient Machine Research. The challenge was to build models that could predict whether a customer has a caravan insurance policy based on the provided features.
The dataset is divided into a training set (TICDATA2000.txt) with 5,822 customer records and a test set (TICEVAL2000.txt) with 4,000 customer records. The target variable is the "CARAVAN:Number of mobile home policies" attribute, which indicates whether the customer has a caravan insurance policy or not.
The dataset includes a variety of socio-demographic variables, such as age, employment status, and household composition, as well as product ownership information for various insurance products. The socio-demographic data is derived from zip codes, meaning that customers living in the same zip code area share the same socio-demographic attributes.
The dataset is suitable for various tasks, such as regression, classification, and descriptive analysis, and can be used to explore the relationship between customer characteristics and insurance product ownership, as well as to develop predictive models for targeted marketing or risk assessment.


Citation: Putten, Peter. (2000). Insurance Company Benchmark (COIL 2000). UCI Machine Learning Repository. https://doi.org/10.24432/C5630S


Based on the data dictionary provided, the Insurance Company Benchmark (COIL 2000) dataset contains the following information:

It has 86 variables describing various characteristics of customers of an insurance company.
The first set of variables (1-43) contain socio-demographic information about the customers, such as customer subtype, household size, age, religion, marital status, education level, occupation, social class, housing situation, income level, and purchasing power class.
The next set of variables (44-64) represent the contributions (premiums) paid by the customers for different types of insurance policies, such as third-party insurance, car insurance, motorcycle insurance, life insurance, accident insurance, disability insurance, fire insurance, boat insurance, and property insurance.
The last set of variables (65-85) indicate the number of different types of insurance policies held by each customer, corresponding to the contribution variables.
The target variable (86) is "CARAVAN," which represents the number of mobile home policies held by the customer (0 or 1).
The dataset has 9,000 instances (customer records), with no missing values.
The data was provided in a tab-delimited format, with one instance per line.
The dataset was divided into a training set (TICDATA2000.txt) with 5,822 customer records and a test set (TICEVAL2000.txt) with 4,000 customer records.
The dataset was donated by the Dutch data mining company Sentient Machine Research and based on a real-world business problem.
The dataset is suitable for tasks such as regression, classification, and descriptive analysis, particularly for predicting whether a customer has a caravan insurance policy based on their socio-demographic and insurance product ownership characteristics.
