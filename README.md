# Hypothesis-Testing-For-Pharmaceutical-Drug
Drug Safety Analysis This project evaluates the safety of a drug by comparing adverse effects between treatment and placebo groups using hypothesis testing.

**Overview**
This project analyzes clinical trial data to evaluate the safety of a drug by comparing the occurrence of adverse effects between participants treated with the drug versus those given a placebo. Using hypothesis testing, it assesses whether there is a significant difference in the number of adverse effects between the two groups and examines if these effects are independent of the treatment type.

**Project Overview**
Data: The dataset includes participant details such as age, sex, treatment group (Drug/Placebo), number of adverse effects, and vital signs (WBC, RBC).
Methods: The project applies hypothesis testing to compare the proportion of adverse effects between treatment groups and examine their independence.
_The dataset was obtained from Hbiostat courtesy of the Vanderbilt University Department of Biostatistics._

**Key Findings**
Proportion of Adverse Effects:
A two-sample z-test was conducted to compare adverse effects between the Drug and Placebo groups. The result showed no significant difference (p-value = 0.96).
Independence of Adverse Effects:
A Chi-squared test was performed to determine if the occurrence of adverse effects is independent of the treatment group. The result showed no significant association.

**Conclusion**
The analysis did not find a statistically significant difference in the number of adverse effects between the Drug and Placebo groups.

**Getting Started**
Clone this repository:
Copy code
git clone https://github.com/yourusername/drug-safety-analysis.git

This project is licensed under the MIT License.

