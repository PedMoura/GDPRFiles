This contains a training set used in an Machine Learning algorithm for scanning files.

Contents:

"pt" folder contains the portuguese version of the training set.

"en" folder contains the translated english version of the same training set
<br />
<br />
<br />
"pt" folder content:

two folders, one with private files and the other one with non private files.


"pt/private" folder content:

two folder, one with real files and another with synthetic files, created with the purpose of adding some kind of pattern to the algorithm.
<br />
<br />
"pt/private/Real" folder content:

This folder contains the private and real files

- Six kinds of Curruculum Vitae (CV), these files are private because they contain a lot of personal information.

- Three Invoices created by the Instituto Superior T�cnico. Invoices that contains private information like the taxpayer number.

- A already written form.

- A proposal of an event, considered private since it has the organization's Tax Identification Number.

- A Pay Slip, which is a private file since it has a Tax Identification Number.

- A request for a sponsorship of an event. With private information being sent, like the Tax Identity Number (TIN/NIF/VAT) of the requesting organization.

- Two receipts which have personal information from the buyer and the seller

- A file with a course evaluation scores.
<br />
<br />
"pt/private/Synthetic" folder content:

This folder contains the private and synthetic files

- pt_p_Synthetic-1, which contains the initials BI followed by 8 digits, which could mean that it was the number of someone's identification card (from Portugal), among another possibly personal data like the phrase "nascido a" (which means "born at" in portuguese).

- pt_p_Synthetic-2, which contains the initials cc, with 8 digits in the cell below, which leads to believing that it is the number of someone's citizen's card (from Portugal).

- pt_p_Synthetic-3, which has a phrase "nascido a" (which means "born at" in portuguese), the other words don't mean anything since they don't have numbers associated with them.

- pt_p_Synthetic-4, which has a phrase that indicates the possibility of the existence of private information and the initials CC with 8 digits ahead, which may indicate that the number of someone's citizen's card (from Portugal) is present.

- pt_p_Synthetic-5, a file that has some factors that may be private, such as bi with 8 digits at the right side, which may mean that a person's identification card number (from Portugal) is present and the phrase "nascido a" (which means "born at" in portuguese).

- pt_p_Synthetic-6, similar to the file pt_p_Synthetic-5 but with the number of 8 digits before the initials bi.

- pt_p_Synthetic-7, which has the phrase "nascido a" that can mean the presence of private information, having also the initials B.I. which by having 8 digits in the line below may mean that it is the number of an identification card (from Portugal).

- pt_p_Synthetic-8, this file is considered private since it has the phrase "nascido a" (which means "born at" in portuguese). It also has the initials NIF (VAT/UTR/NINO in Portugal), but since near the initials there is no number with 9 digits, this is not personal data.

- pt_p_Synthetic-9, is considered private because it has C.C. (Citizen Card in Portugal) with 8 digits behind and NIF (VAT/UTR/NINO in Portugal) with 9 digits across, with also the phrase "nascido a" (which means "born at" in portuguese). Which leads to consider that the file has personal information.

- pt_p_Synthetic-10, is similar to the pt_p_Synthetic-9 file but with 9 digits ahead of the acronym NIF (VAT/UTR/NINO in Portugal).

- pt_p_Synthetic-11, similar to the pt_p_Synthetic-4 file, but with the 8 digits behind the acronym cc (Citizen Card in Portugal).

- pt_p_Synthetic-12, which contains the acronym nif (VAT/UTR/NINO in Portugal) with 9 digits in the line below, which may mean that the Tax Identification Number is present.

- pt_p_Synthetic-13, which has the phrase "nascido a" (which means "born at" in portuguese) which by itself already indicated that the file is probably private, however also has C.C. with 8 digits behind (Citizen Card in Portugal). The word social as it does not have a number of 11 digits (Social Security Number in Portugal) close does not bring concern regarding being private.

- pt_p_Synthetic-14, similar to the pt_p_Synthetic-13 file, however the 8-digit number is ahead of the acronym C.C (Citizen Card in Portugal).

- pt_p_Synthetic-15, which has the social word and the acronym C.C but as there is no number of 11 digits (Social Security Number in Portugal) and no number of 8 digits (Identity Card in Portugal), respectively, they don't pose personal data. In these conditions the file is considered private since it also contains the phrase "nascido a" (which means "born at" in portuguese), which suggests that this file contains someone's date of birth.

- pt_p_Synthetic-16, which is similar to the file pt_p_Synthetic-13, but with the difference that the number of 8 digits is above the acronym C.C..

- pt_p_Synthetic-17, similar to pt_p_Synthetic-15 file but with the acronym CC instead of C.C ..

- pt_p_Synthetic-18, similar to the file pt_p_Synthetic-13 but with the number of 8 digits under the acronym.

- pt_p_Synthetic-19, with several potentially private elements, such as social, having a number of 11 digits ahead (social security number in Portugal).

- pt_p_Synthetic-20, the initials B.I. by themselves already mean that the file could be private, since it could mean that the number of an identification card (from Portugal) is present.

- pt_p_Synthetic-21, that represents the information of a student, where it is present his name and student id number.

- pt_p_Synthetic-22, that represents information of a student, having more information about him than in the file pt_p_Synthetic-21.

- pt_p_Synthetic-23, file that has the number of a student, thing that happens on course evaluation scores.

- pt_p_Synthetic-24, which has the beginning of the word identification followed by 8 digits (that way it works for both portuguese and english documents).

- pt_p_Synthetic-25, similar to file pt_p_Synthetic-25 but with a different wording on the student id number

- pt_p_Synthetic-26, which has the word "contribuinte" followed by 9 digits, indicating that the taxpayer number of someone is present.

- pt_p_Synthetic-27, which has the word "aluno" (student in Portuguese) followed by 5 digits (student id number in Instituto Superior Técnico), also present in some course evaluation course.
<br />
<br />
"pt/non_private" folder content:

two folders, one with real files, another with synthetic ones, created in order to add some kinda of pattern.
<br />
<br />
"pt/non_private/Real" folder content:

This folder contains the real files considered non private.

- The front cover of an assignment but without any means of identifying the authors.

- A contract from the company Vodafone, available online.

- A document with Logic and Arithmetic Reasoning exercises.

- Two lab statement created in the university Instituto Superior Técnico

- Four manuals of packages from an open-source software

- Three receipts with the private information hidden.

- Four tests created in the university Instituto Superior Técnico

- Two front covers from two thesis
<br />
<br />
"pt/non_private/Synthetic" folder content:

This folder contains the non private and synthetic files.

Content:

- pt_np_Synthetic-1, which is a file with a number of 8 digits too far from the initials cc. Which leads one to believe that they are not connected, that way the file cannot be considered private.

- pt_np_Synthetic-2, which has the phrase "Diário da República" (the official gazette from Portugal) which usually has a lot of personal information, but since those articles are publicly available, the files that contain this phrase probably aren't private.

- pt_np_Synthetic-3, which contains the word "curriculum", to show that the word by itself doesn't mean that personal information is present on the file.
<br />
<br />
<br />
"en" folder content:

two folder, one with private files and the other one with non private files.
<br />
<br />
"en/private" folder content:

two folder, one with real files and another with synthetic files, created with the purpose of adding some kind of pattern to the algorithm
<br />
<br />
"en/private/real" folder content:

This folder contains the private and real files

- Six kinds of Curruculum Vitae (CV), these files are private because they contain a lot of personal information.

- Three Invoices created by the Instituto Superior T�cnico. Invoices that contains private information like the taxpayer number.

- A already written form.

- A proposal of an event, considered private since it has the organization's Tax Identification Number.

- A Pay Slip, which is a private file since it has a Tax Identification Number.

- A request of sponsorship of an event. With private information being sent, like the Tax Identity Number (TIN/NIF/VAT) of the requesting organization.

- Two receipts which have personal information from the buyer and the seller.

- A file with a course evaluation scores.
<br />
<br />
"en/private/Synthetic" folder content:

This folder contains the private and synthetic files.

- en_p_Synthetic-1, which contains the initials ID followed by 8 digits, which could mean that it was the number of someone's identification card.

- en_p_Synthetic-2, which contains the initials ID, with 8 digits in the cell below, which leads to believing that it is the number of someone's citizen's card.

- en_p_Synthetic-3, which has certain words that may mean that there is private information in this file, such as the phrase "born". Since social security doesnt have a number near it, it is not considered personal information

- en_p_Synthetic-4, which has phrases/initials that indicate the possibility of the existence of private information, for example ID with 8 digits ahead, which may indicate that the number of someone's identity card is present.

- en_p_Synthetic-5, a file that has some factors that may be private, such as id with 8 digits at the right side, which may mean that a person's identification card number is present.

- en_p_Synthetic-6, similar to en_p_Synthetic-5 file but with the number of 8 digits before the initials id.

- en_p_Synthetic-7, which has several words / phrases that can mean the presence of private information, having also the initials I.D. which by having 8 digits in the line below may mean that it is a number of an identification card.

- en_p_Synthetic-8, this file is considered private since it has the phrase "born". It also has the initials VAT/NIF/UTR/NINO, but since near the initials there is no number, it is not personal information.

- en_p_Synthetic-9, is considered private because it has ID with 8 digits behind and VAT, NIF, UTR and NINO nearby a number with 9,9,10 digits and a combination of letters/digits, respectively, with also the phrase "born". Which leads to consider that the file has personal information.

- en_p_Synthetic-10, is similar to the en_p_Synthetic-9 file but with 9,9,10 digits and a combination of letters/digits ahead of the acronyms VAT, NIF, UTR and NINO, respectively.

- en_p_Synthetic-11, similar to the en_p_Synthetic-4 file, but with the 8 digits behind the acronym id.

- en_p_Synthetic-12, which contains the acronyms VAT, NIF, UTR and NINO with 9,9,10 digits and a combination of letters/digits, respectively in the line below, which may mean that the Tax Identification Number is present.

- en_p_Synthetic-13, which has the phrase "born" which by itself already indicated that the file is probably private, however also has I.D. with 8 digits behind. The word social security as it does not have a number nearby, it does not bring concern regarding privacy.

- en_p_Synthetic-14, similar to the en_p_Synthetic-13 file, however the 8-digit number is ahead of the acronym ID.

- en_p_Synthetic-15, which has the social word and the acronym I.D. but as there is no number nearby neither, that means that the acronym and the word do not mean personal information. In these conditions the file wouldn't be considered private but the file also contains the word "born", which suggests that this file contains someone's date of birth, therefore it is considered private.

- en_p_Synthetic-16, which is similar to the file en_p_Synthetic-13, but with the difference that the number of 8 digits is above the acronym ID ..

- en_p_Synthetic-17, similar to en_p_Synthetic-15 file but with the acronym ID instead of I.D..

- en_p_Synthetic-18, similar to the file en_p_Synthetic-13 but with the number of 8 digits under the acronym.

- en_p_Synthetic-19, with several potentially private elements, such as social, having a number of 11 digits ahead.

- en_p_Synthetic-20, for I.D. by itself to be considered private.

- en_p_Synthetic-21, containing the name and student id number of a student.

- en_p_Synthetic-22, which contains the personal information from a student.

- en_p_Synthetic-23, which has the the word "number" followed by 5 digits, which appears on some course evaluation scores.

- en_p_Synthetic-24, which has the beginning of the word identification followed by 8 digits (that way it works for both portuguese and english documents).

- en_p_Synthetic-25, for documents with a taxpayer identification number to be considered private, thing that happens if there is a 9 digits number near the word.

- en_p_Synthetic-26, which has the number of a student id number near the word student, which happens in some course evaluation scores.
<br />
<br />
"en/non_private" folder content:

two folders, one with real files, another with synthetic ones, created in order to add some kinda of pattern.
<br />
<br />
"en/non_private/Real" folder content:

This folder contains the private and real files

- Six kinds of Curruculum Vitae (CV), these files are private because they contain a lot of personal information.

- Three Invoices created by the Instituto Superior T�cnico. Invoices that contains private information like the taxpayer number.

- A already written form.

- A proposal of an event, considered private since it has the organization's Tax Identification Number.

- A Pay Slip, which is a private file since it has a Tax Identification Number.

- A request of sponsorship of an event. With private information being sent, like the Tax Identity Number (TIN/NIF/VAT) of the requesting organization.

- Two receipts which have personal information from the buyer and the seller.

- Two front covers from two thesis
<br />
<br />
"en/non_private/Synthetic/" folder content:

This folder contains the non private and synthetic files.

Content:

- A file with a number of 8 digits too far from the initials id. Which leads one to believe that they are not connected, that way the file cannot be considered private.
