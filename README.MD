The General Data Protection Regulation [1] (GDPR) is a new European Regulation that was created and implemented to protect users’ personal data and ensure their privacy rights. 
According to chapter 2, article 5 of the GDPR controllers are accountable for all the life cycle of the personal collected data. This cycle includes the storage and processing of data, but its transfer to processors or other recipients. 
This accounting requires the development of tools that track document exchanged inside an organization verifying if documents includes data that is considered personal, and if the transmission is authorized.
These tools can use machine learning techniques but need to be trained (if using supervised machine learning techniques) and tested. To perform the training and testing steps, it is necessary to use a dataset with documents that may contain personal data.
The presented dataset is composed of 127 files, (85 files of which have personal data and 42 do not), of multiple type (e.g. receipts, CVs, …), in distinct formats (text, pdf, word and excel) and in two languages (Portuguese and English). This dataset was created resorting to real documents and synthetic ones.
These files were used to test various supervised machine learning classification algorithms implemented using WEKA [2].
The documents are publicly available in a Git Hub repository in [3].
<br />
<br />
This dataset is organized in the following hierarchy of folders:<br />
•  Pt <br />
&nbsp; -  non_personal <br />	
&nbsp; &nbsp; *  real – 18 documents <br />
&nbsp; &nbsp; *  Synthetic – 3 documents <br />
&nbsp; -  Personal <br />
&nbsp; &nbsp; *  Real – 16 files <br />
&nbsp; &nbsp; *  Synthetic – 26 files <br />
•  En <br />
&nbsp; -  non_ personal <br />	
&nbsp; &nbsp; *  real – 18 files <br />
&nbsp; &nbsp; *  Synthetic – 3 files <br />
&nbsp; -  Personal <br />
&nbsp; &nbsp; *  Real – 16 files <br />
&nbsp; &nbsp; *  Synthetic – 26 files <br />
<br />
The */personal/Real folder contains real documents that have personal information:<br />
•	Six different Curruculum Vitae (CV)<br />
•	Invoices/ receips/ pay slips - contain personal information such as the taxpayer number.<br />
•	One fulfilled form – contains personal information<br />
•	A proposal of an event - contains the organization's Tax Identification Number.<br />
•	A request for a sponsorship of an event - contains the Tax Identity Number (TIN/NIF/VAT) of the requesting organization.<br />
•	A file with a course evaluation grades.<br />
<br />
The */personal/Synthetic folder contains synthetic documents that have personal information:<br />
•	*_p_Synthetic-1 - contains the initials BI followed by 8 digits, which could mean that it was the number of someone's identification card (from Portugal), among another possibly personal data like the phrase "nascido a" (which means "born at" in portuguese).<br />
•	*_p_Synthetic-2 -  contains the initials cc, with 8 digits in the cell below, which leads to believing that it is the number of someone's citizen's card (from Portugal).<br />
•	*_p_Synthetic-3 - has a phrase "nascido a" (which means "born at" in portuguese), the other words don't mean anything since they don't have numbers associated with them.<br />
•	*_p_Synthetic-4 - has a phrase that indicates the possibility of the existence of personal information and the initials CC with 8 digits ahead, which may indicate that the number of someone's citizen's card (from Portugal) is present.<br />
•	*_p_Synthetic-5 - has some factors that may be considered personal, such as the word BI with 8 digits at the right side, which may mean that a person's identification card number (from Portugal) is present and the phrase "nascido a" (which means "born at" in portuguese).<br />
•	*_p_Synthetic-6 - similar to the file pt_p_Synthetic-5 but with the number of 8 digits before the initials bi.<br />
•	*_p_Synthetic-7 - has the sentence "nascido a" that can mean the presence of personal information, having also the initials B.I. which by having 8 digits in the line below may mean that it is the number of an identification card (from Portugal).<br />
•	*_p_Synthetic-8 - has the phrase "nascido a" (which means "born at" in portuguese). It also has the initials NIF (VAT/UTR/NINO in Portugal), but since near the initials there is no number with 9 digits, this is not personal data.<br />
•	*_p_Synthetic-9 - has C.C. (Citizen Card in Portugal) with 8 digits behind and NIF (VAT/UTR/NINO in Portugal) with 9 digits across, with also the phrase "nascido a" (which means "born at" in portuguese). Which leads to consider that the file has personal information.<br />
•	*_p_Synthetic-10 - similar to the pt_p_Synthetic-9 file but with 9 digits ahead of the acronym NIF (VAT/UTR/NINO in Portugal).<br />
•	*_p_Synthetic-11 - similar to the pt_p_Synthetic-4 file, but with the 8 digits behind the acronym cc (Citizen Card in Portugal).<br />
•	*_p_Synthetic-12 - contains the acronym nif (VAT/UTR/NINO in Portugal) with 9 digits in the line below, which may mean that the Tax Identification Number is present.<br />
•	*_p_Synthetic-13 - has the phrase "nascido a" (which means "born at" in portuguese) which by itself already indicated that the file contains personal information, however also has C.C. with 8 digits behind (Citizen Card in Portugal). The word social as it does not have a number of 11 digits (Social Security Number in Portugal) close does not bring concern regarding being personal.<br />
•	*_p_Synthetic-14 - similar to the pt_p_Synthetic-13 file, however the 8-digit number is ahead of the acronym C.C (Citizen Card in Portugal).<br />
•	*_p_Synthetic-15 - has the social word and the acronym C.C but as there is no number of 11 digits (Social Security Number in Portugal) and no number of 8 digits (Identity Card in Portugal), respectively, they don't pose personal data. In these conditions the file is considered personal since it also contains the phrase "nascido a" (which means "born at" in portuguese), which suggests that this file contains someone's date of birth.<br />
•	*_p_Synthetic-16 - similar to the file pt_p_Synthetic-13, but with the difference that the number of 8 digits is above the acronym C.C..<br />
•	*_p_Synthetic-17 - similar to pt_p_Synthetic-15 file but with the acronym CC instead of C.C ..<br />
•	*_p_Synthetic-18 - similar to the file pt_p_Synthetic-13 but with the number of 8 digits under the acronym.<br />
•	*_p_Synthetic-19 – contains several potentially personal elements, such as social, having a number of 11 digits ahead (social security number in Portugal).<br />
•	*_p_Synthetic-20 – contains the initials B.I., meaning that the number of an identification card (from Portugal) is present.<br />
•	*_p_Synthetic-21 - represents the information of a student, where it is present his name and student id number.<br />
•	*_p_Synthetic-22 - represents information of a student, having more information about him than in the file pt_p_Synthetic-21.<br />
•	*_p_Synthetic-23 - that has the number of a student, thing that happens on course evaluation scores.<br />
•	*_p_Synthetic-24 - has the beginning of the word identification followed by 8 digits (that way it works for both portuguese and english documents).<br />
•	*_p_Synthetic-25 - similar to file pt_p_Synthetic-25 but with a different wording on the student id number<br />
•	*_p_Synthetic-26 - has the word "contribuinte" followed by 9 digits, indicating that the taxpayer number of someone is present.<br />
•	*_p_Synthetic-27 - has the word "aluno" (student in Portuguese) followed by 5 digits (student id number in Instituto Superior Técnico), also present in some course evaluation course.<br />
<br />
The */non_personal/Real" folder contains the real files considered non personal.<br />
•	The front cover of an assignment but without any means of identifying the authors.<br />
•	A contract from the company Vodafone, available online.<br />
•	A document with Logic and Arithmetic Reasoning exercises.<br />
•	Two lab statement created in the university Instituto Superior Técnico<br />
•	Four manuals of packages from an open-source software.<br />
•	Three receipts with the personal information hidden.<br />
•	Four tests created in the university Instituto Superior Técnico.<br />
•	Two front covers from two thesis.<br />
<br />
The */non_personal/Synthetic folders contain the non personal and synthetic file:<br />
•	*_np_Synthetic-1 - , a number of 8 digits too far from the initials cc. Which leads one to believe that they are not connected, that way the file cannot be considered personal.<br />
•	*_np_Synthetic-2 – contains the sentence "Diário da República" (the official gazette from Portugal) which usually has of personal details that have to be made public by the law (for-instance public nominations, or work contracts).<br />
•	*_np_Synthetic-3 - contains the word "curriculum", to show that the word by itself doesn't mean that personal information is present on the file.<br />
The English versions of these documents contain the corresponding translations of the personal data patterns.<br />
