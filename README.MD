This contains a training set used in an Machine Learning algorithm for scanning files.

Contents:

"pt" folder contains the portuguese version of the training set.

"en" folder contains the translated english version of the same training set
<br />
<br />

"pt" folder content:

two folders, one with private files and the other one with non private files.


"pt/private" folder content:

two folder, one with real files and another with synthetic files, created with the purpose of adding some kind of pattern to the algorithm.


"pt/private/Real" folder content:

This folder contains the private and real files

- Six kinds of Curruculum Vitae (CV), these files are private because they contain a lot of personal information.

- Three Invoices created by the Instituto Superior Técnico. Invoices that contains private information like the taxpayer number.

- A already written form. 

- A proposal of an event, considered private since it has the organization's Tax Identification Number.

- A Pay Slip, which is a private file since it has a Tax Identification Number.

- A request of sponsorship of an event. With private information being sent, like the Tax Identity Number (TIN/NIF/VAT) of the requesting organization.

- Two receipts which have personal information from the buyer and the seller 


"pt/private/Synthetic" folder content: 

This folder contains the private and synthetic files

- pt_p_Synthetic-1, which contains the initials BI followed by 8 digits, which could mean that it was the number of someone's identification card (from Portugal).

- pt_p_Synthetic-2, which contains the initials cc, with 8 digits in the cell below, which leads to believing that it is the number of someone's citizen's card (from Portugal).

- pt_p_Synthetic-3, which has certain words that may mean that there is private information in this file, such as the phrase "nascido a" (which means "born at" in portuguese).

- pt_p_Synthetic-4, which has phrases that indicate the possibility of the existence of private information, for example CC with 8 digits ahead, which may indicate that the number of someone's citizen's card (from Portugal) is present.

- pt_p_Synthetic-5, a file that has some factors that may be private, such as bi with 8 digits at the right side, which may mean that a person's identification card number (from Portugal) is present.

- pt_p_Synthetic-6, similar to the file pt_p_Synthetic-5 but with the number of 8 digits before the initials bi.

- pt_p_Synthetic-7, which has several words / phrases that can mean the presence of private information, having also the initials B.I. which by having 8 digits in the line below may mean that it is a number of an identification card (from Portugal).

- pt_p_Synthetic-8, this file is considered private since it has the phrase "nascido a" (which means "born at" in portuguese). It also has the initials NIF (TIN in Portugal), but since near the initials there is no number with 9 digits, it is not private information.

- pt_p_Synthetic-9, is considered private because it has C.C. (Citizen Card in Portugal) with 8 digits behind and NIF (TIN in Portugal) with 9 digits across, with also the phrase "nascido a" (which means "born at" in portuguese). Which leads to consider that the file has personal information.

- pt_p_Synthetic-10, is similar to the pt_p_Synthetic-9 file but with 9 digits ahead of the acronym NIF (TIN in Portugal).

- pt_p_Synthetic-11, similar to the pt_p_Synthetic-4 file, but with the 8 digits behind the acronym cc (Citizen Card in Portugal).

- pt_p_Synthetic-12, which contains the acronym nif (tin in Portugal) with 9 digits in the line below, which may mean that the Tax Identification Number is present.

- pt_p_Synthetic-13, which has the phrase "nascido a" (which means "born at" in portuguese) which by itself already indicated that the file is probably private, however also has C.C. with 8 digits behind (Citizen Card in Portugal). The word social as it does not have a number of 11 digits (Social Security Number in Portugal) close does not bring concern regarding being private.

- pt_p_Synthetic-14, similar to the pt_p_Synthetic-13 file, however the 8-digit number is ahead of the acronym C.C (Citizen Card in Portugal).

- pt_p_Synthetic-15, which has the social word and the acronym C.C but as there is no number of 11 (Social Security Number in Portugal) and 8 digits (Identity Card in Portugal), respectively. In these conditions the file is considered private since it also contains the phrase "nascido a" (which means "born at" in portuguese), which suggests that this file contains someone's date of birth.

- pt_p_Synthetic-16, which is similar to the file pt_p_Synthetic-13, but with the difference that the number of 8 digits is above the acronym C.C ..

- pt_p_Synthetic-17, similar to pt_p_Synthetic-15 file but with the acronym CC instead of C.C ..

- pt_p_Synthetic-18, similar to the file pt_p_Synthetic-13 but with the number of 8 digits under the acronym.

- pt_p_Synthetic-19, with several potentially private elements, such as social, having a number of 11 digits ahead.


"pt/non_private" folder content:

two folders, one with real files, another with synthetic ones, created in order to add some kinda of pattern. 


"pt/non_private/Real" folder content:

This folder contains the real files considered non private.

- The front cover of an assignment but without any means of identifying the authors.

- A contract from the company Vodafone, available online.

- A document with Logic and Arithmetic Reasoning exercises.

- Two lab statement created in the university Instituto Superior Técnico

- Four manuals of packages from an open-source software

- Three receipts with the private information hidden.

- Four tests created in the university Instituto Superior Técnico


"pt/non_private/Synthetic" folder content: 

This folder contains the non private and synthetic files.

Content: 

- A file with a number of 8 digits too far from the initials cc. Which leads one to believe that they are not connected, that way the file cannot be considered private.



"en" folder content:

two folder, one with private files and the other one with non private files.


"en/private" folder content:

two folder, one with real files and another with synthetic files, created with the purpose of adding some kind of pattern to the algorithm


"en/private/real" folder content:

This folder contains the private and real files

- Six kinds of Curruculum Vitae (CV), these files are private because they contain a lot of personal information.

- Three Invoices created by the Instituto Superior Técnico. Invoices that contains private information like the taxpayer number.

- A already written form. 

- A proposal of an event, considered private since it has the organization's Tax Identification Number.

- A Pay Slip, which is a private file since it has a Tax Identification Number.

- A request of sponsorship of an event. With private information being sent, like the Tax Identity Number (TIN/NIF/VAT) of the requesting organization.

- Two receipts which have personal information from the buyer and the seller.


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


"en/non_private" folder content:

two folders, one with real files, another with synthetic ones, created in order to add some kinda of pattern. 


"en/non_private/Real" folder content:

This folder contains the private and real files

- Six kinds of Curruculum Vitae (CV), these files are private because they contain a lot of personal information.

- Three Invoices created by the Instituto Superior Técnico. Invoices that contains private information like the taxpayer number.

- A already written form. 

- A proposal of an event, considered private since it has the organization's Tax Identification Number.

- A Pay Slip, which is a private file since it has a Tax Identification Number.

- A request of sponsorship of an event. With private information being sent, like the Tax Identity Number (TIN/NIF/VAT) of the requesting organization.

- Two receipts which have personal information from the buyer and the seller.


"en/non_private/Synthetic/" folder content:

This folder contains the non private and synthetic files.

Content: 

- A file with a number of 8 digits too far from the initials id. Which leads one to believe that they are not connected, that way the file cannot be considered private.

