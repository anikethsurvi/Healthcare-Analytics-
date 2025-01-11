OBJECTIVE
As a data analyst for a healthcare organization, provide actionable insights on hospital performance, revenue streams, and patient trends to support strategic decision-making.
-	Revenue
-	Average Total Bill
-	Number of Visits
-	Patient Satisfaction
-	Patient Trends

DOMAIN KNOWLEDGE
In a healthcare business, money comes from several key sources, and the business operates through a combination of services provided and the payments received for those services :
How Money Comes In:
1.	Patient Payments:
o	Insurance: Most revenue comes from insurance companies. Hospitals are paid by private insurers, Medicare, and Medicaid for the treatments and services they provide to insured patients.
o	Out-of-Pocket Payments: Some patients pay directly for services (e.g., co-pays or for treatments not covered by insurance).
2.	Clinical Services:
o	Revenue is generated from patient care, including consultations, surgeries, diagnostics (X-rays, MRIs), and treatments (e.g., medications, therapies).
3.	Ancillary Services:
o	Extra services like lab tests, pharmacy sales, imaging, and rehabilitation contribute to hospital income.
4.	Government Funding & Grants:
o	Hospitals may receive funds from government programs or grants to support public health initiatives or specific care services.
How the Business Operates:
1.	Care Delivery:
o	Hospitals provide medical services, including emergency care, surgeries, diagnostics, and patient treatment in inpatient and outpatient settings.
2.	Cost of Care:
o	Hospitals have operating costs such as staff salaries, equipment, medications, facility maintenance, and utilities. These need to be covered by the revenue they generate.
3.	Payer Systems:
o	Insurance companies and government programs (Medicare/Medicaid) pay hospitals based on the services provided to patients, often using a billing code system for diagnosis and treatments (ICD-10, CPT).
4.	Revenue Cycle Management:
o	Hospitals manage billing, collections, and reimbursements through a process called revenue cycle management, ensuring that they are paid for services provided.
5.	Regulation and Compliance:
o	The healthcare industry is heavily regulated. Hospitals must adhere to legal requirements (like HIPAA for patient privacy) and quality standards to stay operational and receive reimbursements.
Summary - The healthcare business generates money mainly through patient care services (paid by insurance or directly by patients) and other services, while operating costs like staff, equipment, and facility maintenance need to be carefully managed to ensure profitability.

DATA KNOWLEDGE(Dataset)
City Table
•	city id: A unique identifier for each city.
•	city: The name of the city.
•	state: The state or region where the city is located.
Patient Table
•	age: The age of the patient.
•	city id: A reference to the city the patient resides in (linked to the City Table).
•	gender: The gender of the patient.
•	patient id: A unique identifier for each patient.
•	patient name: The name of the patient.
•	race: The race or ethnicity of the patient.
Providers (Doctor) Table
•	age: The age of the provider (doctor).
•	gender: The gender of the provider.
•	image: A picture of the provider.
•	nationality: The nationality of the provider.
•	provider id: A unique identifier for each provider.
•	provider name: The name of the provider (doctor).
Department Table
•	department id: A unique identifier for each department in the hospital.
•	department: The name of the department (e.g., Cardiology, Neurology).
Diagnosis Table
•	Diagnosis: The name or description of the medical diagnosis.
•	Diagnosis id: A unique identifier for each diagnosis.
Insurance Table
•	insurance id: A unique identifier for each insurance policy.
•	insurance provider: The name of the insurance company providing coverage.
Procedures Table
•	procedure: A description of the medical procedure performed.
•	procedure id: A unique identifier for each procedure.
Visits (Main) Table
•	admitted date: The date the patient was admitted to the hospital.
•	date: The date of the visit.
•	dept id: The department where the patient was treated (linked to the Department Table).
•	diagnosis id: The diagnosis given to the patient (linked to the Diagnosis Table).
•	discharge date: The date the patient was discharged from the hospital.
•	emergency visit (Yes/No): Indicates whether the visit was an emergency (Yes or No).
•	insurance coverage: The type of insurance coverage (could include the insurance provider or policy details).
•	insurance id: A reference to the insurance policy covering the patient (linked to the Insurance Table).
•	length of stay: The duration of the patient’s stay in the hospital.
•	medication cost: The cost of medication during the visit.
•	patient id: A reference to the patient visiting (linked to the Patient Table).
•	patient satisfaction score: A rating given by the patient regarding their satisfaction with the visit.
•	payment status: The status of the payment (e.g., Paid, Unpaid).
•	procedure id: A reference to the procedure performed during the visit (linked to the Procedures Table).
•	provider id: A reference to the provider (doctor) who treated the patient (linked to the Providers Table).
•	re-visit date: The date of the patient's next visit, if applicable.
•	referral source: How the patient was referred to the hospital (e.g., self-referred, referred by a doctor).
•	room charge (daily-rate): The daily charge for the patient’s hospital room.
•	room type: The type of room the patient stayed in (e.g., private, shared).
•	service type: The type of service the patient received (e.g., inpatient, outpatient).
•	treatment cost: The total cost of treatment during the visit.
•	visit type: The type of visit (e.g., initial visit, follow-up).

Please do visit the interactive dashboard 
Thanks 😊



