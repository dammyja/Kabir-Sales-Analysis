PATIENT ANALYSIS

 Total Number of Patients

54,966 patients in the dataset.

 Key Finding

The dataset is large and statistically robust enough to draw meaningful conclusions across all dimensions — conditions, billing, admissions, and medication usage.

  GENDER DISTRIBUTION

Key Finding

Gender distribution is almost perfectly equal (50/50 split), with males marginally exceeding females by only 26 patients.

Observation

This near-perfect balance is notable and may suggest either a balanced patient catchment area or a deliberately balanced data collection methodology.

Insight

Gender cannot be used as a significant differentiating variable for high-level resource planning — both genders place essentially equal demand on the hospital system.

Recommendation

Analyze further at condition-level by gender (e.g, are women more prone to arthritis admissions, men to hypertension?) to identify gender-specific care pathways and enable targeted health programmes.
![IMAGE](<Screenshot 2026-05-17 143043.png>)

 
  AGE GROUP WITH HIGHEST ADMISSION

 Key Finding

Adults (37.1%) and Elders (36.7%) together account for 73.8% of all admissions. Teens represent only 1.6%.

 Observation

The hospital is predominantly serving middle-aged and elderly patients. Youth (under-adult, above-teen) accounts for nearly a quarter of admissions, which is significant. Teen admissions are remarkably low.

 Insight

The heavy skew toward Adults and Elders indicates the hospital’s patient profile is typical of chronic disease management facilities — conditions like arthritis, diabetes, and hypertension are predominantly adult/elder concerns.

Recommendation
Investigate the low teen admission rate this could indicate under-reporting, a gap in adolescent outreach services, or genuine low incidence
![IMAGE1](<Screenshot of the Pivots chart/MOST COMMON BLOOD GROUP.png>)


 MOST COMMON BLOOD GROUP

Chart Type: Bar Chart

Key Finding

All 8 blood groups are represented with striking uniformity — ranging from 6,804 (O-) to 6,898 (A-), a spread of only 94 patients across all groups.

 Observation

A- and A+ are the most common at 12.55% each, while O- is the least common at 12.38%. However, the difference between the highest and lowest is less than 1.5%.

 Insight

This distribution is statistically unusual compared to general population blood type distributions (where O+ typically dominates). This may reflect the dataset’s nature or patient demographic specificity.

 Recommendation
 Despite the even distribution, O- (universal donor) should be watched carefully as it is the lowest and highest in demand during emergencies.



MEDICAL CONDITION ANALYSIS 
![IMAGE1](<Screenshot of the Pivots chart/MOST MEDICAL CONDITIONS.png>)


 MOST COMMON MEDICAL CONDITIONS

 Key Finding

All 6 conditions are distributed almost equally (16.5–16.8% each), with Arthritis the most common and Asthma the least.

Observation

The spread between the highest (Arthritis: 9,218) and lowest (Asthma: 9,095) condition is only 123 patients — an extremely even distribution. This suggests no single condition overwhelmingly dominates the patient load.

 Insight

The hospital treats a diverse chronic disease burden. The even distribution means no single speciality is uniquely overburdened — but it also means the hospital must maintain equal depth of expertise across 6 major disease areas simultaneously

Recommendation

Prioritize preventable conditions like Obesity, Diabetes, and Hypertension together account for ~50% of cases and are largely manageable with lifestyle intervention and early screening.

CONDITION WITH THE LONGEST AVERAGE HOSPITAL STAY
![IMAGE1](<Screenshot of the Pivots chart/CONDITION WITH LONGEST AVERAGE HOSPITAL STAY.png>)


 Key Finding

Asthma patients stay the longest on average at **15.68 days**, while Diabetes patients have the shortest average stay at **15.43 days**. The overall average is ~15.5 days.

Observation

The variation between the longest (Asthma: 15.677) and shortest (Diabetes: 15.431) stay is only **0.246 days** — approximately 6 hours. This is a remarkably narrow range across all conditions.

Insight

Asthma, while being the least admitted condition by count, demands the most hospital time per patient. This presents a disproportionate resource-consumption pattern worth monitoring. Cancer, despite its severity, has a shorter average stay than Asthma, which may indicate outpatient chemotherapy routing.

Recommendation

 Investigate Asthma discharge protocols  the longest stay may indicate opportunities for improved acute management, patient education, or respiratory therapy to enable earlier safe discharge.
Since all stays cluster around 15.5 days, evaluate whether the hospital has a policy or insurance-driven length-of-stay target that is artificially compressing variation.

 REVENUE AND BILLING ANALYSIS

 ![IMAGE1](<Screenshot of the Pivots chart/MONTHLY REVENUE TREND.png>)
 Monthly Revenue Trend


 Key Finding

August is the highest revenue month ($121.6M) and February the lowest ($106.7M) — a gap of **~$14.9M (14%)**.

 Observation

Revenue shows a dip in February, recovers through spring, peaks in mid-summer (Jul–Aug), dips again in September, then stabilises Oct–Dec. The second half of the year (Jul–Dec) performs slightly better than the first.

Insight

The February dip likely reflects a shorter calendar month combined with post-holiday reduced elective admissions. The Jul–Aug peak may be driven by seasonal conditions (heat-related illness, summer injuries) or planned elective procedures.

Recommendation

 Investigate the February revenue gap implement targeted elective procedure scheduling campaigns or health promotion events to reduce seasonality impact.
 Leverage the Jul–Aug peak by ensuring maximum staffing and bed availability to handle higher-volume, higher-revenue periods. 
 Aim to smooth monthly revenue variance to improve financial forecasting and operational planning


 Total Hospital Revenue

Key Finding

The hospital generated over $1.4 billion in total billing across the full period.

Recommendation

Cross-reference this against operational costs to establish the hospital’s actual margin and benchmark it against comparable-size healthcare institutions.


Insurance Provider with Highest Billing Amount
!![IMAGE1](<Screenshot of the Pivots chart/INSURANCE PROVIDER WITH HIGHEST BILLING AMOUNT.png>)


Key Finding

Cigna leads in billing at $284.3M (20.3%), but all five providers are extremely close — the range between highest (Cigna) and lowest (Aetna) is only $7.8M (2.8%).

Observation

Revenue is almost perfectly distributed across insurance providers, with no single payer dominating. This represents ideal **payer diversification**.

Insight

The hospital is not over-dependent on any single insurer, which significantly reduces financial risk. However, the near-equal distribution may also reflect a cap or policy in how billing is coded across providers.

Recommendation

Aetna appears to generate the lowest revenue contribution, management should evaluate whether low reimbursement rates, claim processing issues, or patient coverage limitations are affecting revenue collection from Aetna patients

![IMAGE1](<Screenshot of the Pivots chart/ADMISSION GENERATING HIGHEST REVENUE.png>)
Admission Type Generating Highest Revenue
![]()

 Key Finding

Elective admissions generate the highest total revenue ($473.1M) despite the admission type count being almost even across all three types.

Observation

Revenue per patient is nearly identical across all three types (~$25,500–25,600), but Elective admissions lead due to slightly higher patient volume. Emergency admissions have the lowest revenue per patient, which is common in healthcare settings where billing recovery for emergency cases can be lower.

Insight

The hospital’s revenue is robustly balanced across admission types. Elective procedures, being plannable, allow for better resource utilisation and higher billing recovery.

Recommendation

Improve emergency billing capture rates emergency admissions often see billing leakage due to incomplete documentation; investing in emergency coding staff could recover significant revenue.
Assess whether the low Emergency revenue-per-patient reflects pricing, insurance mix, or bad debt write-offs.

 ADMISSION ANALYSIS

 Most Common Admission Type

!![IMAGE1](<Screenshot of the Pivots chart/MOST COMMON ADMISSION TYPE.png>)


Key Finding

Admissions are almost perfectly split across three types (33–34% each), with Elective slightly leading.

 Observation

The balance between Elective, Urgent, and Emergency admissions is unusual — most hospitals see Emergency as the largest category. This even distribution suggests either a specialist-focused hospital or a dataset that has been structured to reflect system-wide activity.

Insight

The near-equal split gives the hospital a predictable and manageable mix of planned vs unplanned care — a financially and operationally favourable position.

Recommendation

 Protect and grow Elective capacity as it drives the highest revenue.
 Track trends over time if Emergency admissions begin growing, it may signal a deteriorating community health landscape requiring preventive intervention.


 Emergency Admissions by Gender

 Key Finding

Female patients account for a slightly higher proportion of Emergency admissions (50.6%) vs. Males (49.4%).

 Recommendation

Investigate which conditions are driving the female Emergency admission lead — this could guide targeted women’s health emergency prevention programmes.


 ![IMAGE1](<Screenshot of the Pivots chart/MONTH WITH HIGHEST ADMISSION TRENDS.png>)
 Month with Highest Admission Trend
![]()

 Key Finding

August peaks at **4,785 admissions** and February has the lowest at **4,210** — a difference of 575 patients (13.7% higher in August).

Observation

The admission trend mirrors the revenue trend almost perfectly — peak in August, trough in February. The H2 months (Jun–Dec) are consistently stronger than H1 (Jan–May, excluding Jan peak).

Insight

Seasonal patterns are clear and actionable. Summer months drive more admissions, which may reflect heat-related illness, increased physical activity, accidents, or post-school-year health checks.

Recommendation
- Analyse admissions by condition per month to understand which specific diseases drive the August peak.

TEST RESULT ANALYSIS

 Abnormal Results Only

Key Finding

33.5% of all patients (1 in 3) have abnormal test results — 18,437 patients out of 54,966.

Observation

This pivot was filtered to show only “Abnormal” results. The proportion is high and clinically significant if it represents a point-in-time test result rather than a cumulative flag.

 Insight

A one-in-three abnormal test rate is elevated and warrants clinical investigation. This could indicate the hospital serves a high-acuity patient base, or that certain routine screening panels are generating abnormal flags at high rates.

 Recommendation

Break down abnormal results by condition and test type to identify which diagnoses carry the highest abnormal test burden.
Develop abnormal result follow-up protocols ensure all 18,437 cases have documented clinical responses and care plan adjustments.

 MEDICATION ANALYSIS

 Medication Usage by Prescription Count

 Key Finding

Lipitor leads prescription volume at 11,038 (20.1%), but all 5 medications have remarkably equal usage the range between highest and lowest is only 82 prescriptions.

 Observation

Every patient appears to receive exactly one prescription. The five medications span pain relief (Aspirin, Ibuprofen, Paracetamol), cholesterol management (Lipitor), and antibiotics (Penicillin) — a diverse formulary aligned with the six chronic conditions being treated.

Insight

The near-identical prescription volumes suggest these medications are being systematically assigned, possibly one per admission. Lipitor’s slight lead aligns with the high prevalence of cardiovascular-linked conditions (Diabetes, Hypertension, Obesity).

 Recommendation

 Evaluate Lipitor prescribing trends given its dominance  are patients with multiple cardiovascular risk factors being appropriately prescribed statins
 Consider Penicillin stewardship prescribing patterns must be reviewed in the context of antimicrobial resistance guidelines.


 ![IMAGE1](<Screenshot of the Pivots chart/MEDICATION WITH HIGHEST BILLING AMOUNT.png>)
 
 Medication with Highest Billing Amount


 Key Finding

Ibuprofen generates the highest billing at **$283.8M** despite being 2nd in prescription count (11,023), suggesting slightly higher per-prescription billing than Lipitor.

Observation

The billing is almost equally distributed across all 5 medications (~20% each), with a total range of only $4.6M between the top (Ibuprofen) and bottom (Penicillin) biller.

Insight

The billing pattern mirrors prescription volume closely, confirming approximately uniform per-prescription costs. Ibuprofen’s billing lead over Lipitor, despite lower script count, suggests marginally higher average cost per Ibuprofen prescription — possibly due to dosage variations or brand vs generic formulations.

Recommendation

- Review formulary pricing for all five medications — given the even billing split, there may be opportunities to negotiate bulk purchasing discounts or shift to generics to reduce costs.
- Investigate Penicillin billing efficiency lowest billing and lowest prescription count may indicate under-utilization or appropriate stewardship.
- Compare medication costs against treatment outcome data when available to assess cost-effectiveness.


OVERALL  RECOMMENDATIONS

Address Seasonal Demand e.g The Feb dip and Aug peak are consistent across both revenue and admissions build staffing and elective scheduling plans around this pattern.
Prioritize Preventable Conditions like Obesity, Diabetes and Hypertension account for nearly 50% of admissions and are preventable. A strong community health and wellness outreach programme could meaningfully reduce inpatient burden.
Improve Emergency Billing Recovery Emergency admissions generate the lowest revenue per patient. Dedicated emergency coding and billing support could recover millions in currently under-billed revenue.
Investigate Abnormal Test Rate One-in-three patients with abnormal results is a clinical red flag that demands structured follow-up protocols and potentially earlier community screening.

