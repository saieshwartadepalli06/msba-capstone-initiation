# Capstone-Initiation HomeCredit 

## Business Problem and Objective

Home Credit Group, established in 1997, has a mission to provide financial solutions to individuals who have limited or no credit history. A key business challenge they face is accurately evaluating credit risk. They must prevent loan defaults while ensuring that deserving clients can access loans. Home Credit uses various data sources, including telecom and historical transactional data, to enhance the overall borrowing experience. The project's focus is on identifying creditworthy individuals without a credit history, reduce the number of loan rejections for eligible applicants and ensuring loans are not extended to those unable to meet their payment commitments. This enhancement is achieved by evaluating whether a client is likely to meet their loan obligations, effectively utilizing the target variable.

The solution to this problem would include the development of supervised predictive classification models since we have historical labelled data and as the outcome of the target variable is binary with values of 0 and 1, indicating that the potential customer will repay the loan on time or will have difficulty repaying loan respectively. This involves Logistic Regression and use of ensemble methods for extracting a list of customers with higher probabilities of loan repayment. The client’s repayment prediction will be based on alternate data to loan history such as telco and transactional information.

Before we delved into building models, EDA has been performed. EDA generally involves the following:

a. Import & inspect dataset along with the target variable
b. Explore the relationship between target and predictors
c. Scope of missing values; imputing
d. One hot encoding of the categorical variables
e. Univariate analysis
f. Bivariate analysis
g. Testing for Hypothesis
h. Joining the Bureau and previous application tables and inspecting again

## Business Takeaway - Solution

To address the challenges and capitalize on the opportunities in the lending landscape, I propose a comprehensive solution for Home Credit:

**Advanced Predictive Models:** Implement predictive models that leverage machine learning algorithms to assess creditworthiness. These models should analyze a diverse set of data points, including transaction history, behavioral patterns, and alternative data sources to provide a more accurate risk assessment.

**Transparent Decision-Making with Tree Explainer:** Integrate Tree Explainer algorithms to enhance the transparency of model predictions. This not only ensures a clear understanding of the factors influencing decisions but also allows for more effective communication with customers, fostering trust and transparency in the loan approval process.

**Tailored Credit Limits and Interest Rates:** Develop a dynamic system for determining credit limits and interest rates based on individual risk profiles. This personalized approach will not only attract a diverse customer base but also mitigate risks by aligning financial terms with each customer's unique financial situation.

**Proactive Default Prevention Measures:** Implement proactive measures to identify potential defaults before they occur. Early warning systems, customer communication strategies, and personalized financial counseling can be integrated to mitigate the risk of defaults and promote responsible lending practices.

## Individual Contribution 

-- Conducted in-depth exploratory data analysis to gain insights into the dataset.
-- Conducted research and implemented innovative feature engineering techniques to enhance model performance.
-- Applied Under and Synthetic Minority Over-sampling Technique (SMOTE) to address class imbalances in the dataset.
-- Implemented baseline Random Forest and XG Boost models as a foundational step in the modeling phase.
-- Led documentation, structured the notebook with a clear Table of Contents (TOC) and headers for improved readability and accessibility.
-- Implemented outlier analysis to identify and handle outliers in the data.
-- Incorporated a Lightgbm model into the ensemble, contributing to the diversity of the modeling approach.
-- Conducted an extensive grid search to fine-tune the parameters of the Lightgbm model, optimizing its performance.
-- Explored the realm of explainable AI (XAI) and generated SHAP plots to provide interpretability to model predictions.

## Business Value 

The overarching impact of my contributions lies in significantly reducing the number of borrowers who face challenges in repaying their loans. Through data preparation, advanced feature engineering, and model optimization, the project is focused to enhance the precision of identifying borrowers with a higher likelihood of successful loan repayment. By implementing robust sampling techniques, baseline models, and advanced model tuning, our project aims to minimize the financial repercussions associated with borrower defaults. 

One of the significant outcomes of my work is the empowerment of the company to identify and implement effective risk mitigation strategies. Through the exploration of explainable AI (XAI) and SHAP plots, the project provides insights into the factors influencing predictions, enabling the company to devise targeted measures to mitigate risks associated with loan approvals.

## Difficulties Encountered

**Initial Collaboration Hurdles:** At the project's onset, our team grappled with the challenge of establishing a shared workspace, as Google Colab presented limitations for simultaneous collaboration on the same file. This initial difficulty led to considerable time delays as team members had to wait for others to finish their respective tasks, impacting the overall efficiency of our collaborative efforts.

**Computational Resource Constraints:** Notably, during the execution of the Lightgbm and XGBoost models, we encountered substantial challenges related to computational memory. The resource-intensive nature of these models resulted in prolonged runtimes, spanning hours. This posed a significant hurdle, requiring us to strategize and optimize our approach to efficiently manage computational resources and enhance overall model performance.

To overcome the collaboration constraints, we implemented a more structured approach to task allocation, ensuring that team members could work on distinct components simultaneously. This reorganization helped minimize wait times and streamlined our workflow, allowing for a more efficient and synchronized project development process. In response to the extended runtimes for Lightgbm and XGBoost models, we proactively sought ways to optimize computational efficiency. This involved fine-tuning parameters, exploring parallel processing options, and leveraging distributed computing resources to expedite model training. Through these efforts, we successfully mitigated the challenges posed by resource-intensive computations, enhancing the overall effectiveness of our modeling approach.

## Learning

One of the key takeaways from this project was gaining valuable experience in collaborative teamwork. Overcoming initial challenges in finding a common workspace, I learned to allocate tasks efficiently, ensuring a seamless workflow. This experience enhanced my ability to collaborate effectively within a team, demonstrating adaptability and coordination in a dynamic project environment. Working within a defined time frame highlighted the importance of time management in project delivery. 

Through careful planning and prioritization, I developed skills in meeting deadlines and delivering project milestones on schedule. This experience reinforced the significance of efficient time utilization in achieving successful outcomes. The project provided an opportunity for extensive research into various machine learning models. By evaluating their suitability for specific project requirements, I expanded my knowledge of different model architectures, enhancing my understanding of when to apply each model to achieve optimal results. 

This learning has equipped me with a more nuanced approach to model selection in future projects. Crafting and delivering a presentation proved to be a valuable learning experience. Through the process of creating a PowerPoint presentation, I honed my ability to convey complex findings and insights to stakeholders in a clear and impactful manner. This newfound skill in effective communication ensures that project outcomes are not only robust but also comprehensible to diverse audiences, including stakeholders and decision-makers.
