* ESMS’S REQUIREMENTS

<br/>
ID | Requirement | Description|
|-------|------|-------------|
|R01 | Register | Create new account (for staff, by admin) |
|R02 | Authentication |	Verify authorize user |
|R03 | Manage Staff |	CRUD staff |
|R04 | Edit permission |	Edit rights to access features of the system |
|R05 | Manage product |	CRUD product |
|R06 | Import goods |	Import a large quantity of products when supplier supply goods |
|R07 | Manage customer |	CRUD customer |
|R08 | Export invoice |	Export invoice of past purchases made by customers and the staff who processed it |
|R09 | Issue warranty |	Every product has a warranty, staff is usually in charge of managing these |
|R10 | Check warranty |	Check the warranty validation of a purchased item |
|R11 | Manage supplier |	CRUD supplier |
|R12 | View supplier's product |	View all products that were supplied by a supplier |
|R13 | View change history of supplier |	Since staff can edit supplier’s information, the system needs to keep track of who made the changes |

<br/>
** Requirements Traceability Linkage Matrix
<br/>
| ID | R01 | R02 |	R03	| R04 |	R05 | R06 |	R07 | R08 |	R09 | R10 |	R11 | R12 | R13 |
|--|--|--|--|--|--|--|--|--|--|--|--|--|--|
| R01 |  |  | U | U |  |  |  |  |  |  |  |  |  |
| R02 |  |  | U |  |  |  |  |  |  |  |  |  |  |
| R03 | R |  |  | U |  |  |  |  |  |  |  |  |  |
| R04 |  |  | R |  |  |  |  |  |  |  |  |  |  |
| R05 |  |  |  |  |  | U |  | U |  |  |  |  |  |
| R06 |  |  |  |  | R |  |  |  |  |  |  |  |  |
| R07 |  |  |  |  |  |  |  |  |  |  |  |  |  |
| R08 |  |  | U |  |  |  | U |  |  |  |  |  |  |
| R09 |  |  |  |  | U |  | U |  |  |  |  |  |  |
| R10 |  |  | U |  | U |  |  |  | R |  |  |  |  |
| R11 |  |  |  |  |  |  |  |  |  |  |  |  |  |
| R12 |  |  |  |  | U |  |  |  |  |  | U |  |  |
| R13 |  |  | U |  |  |  |  |  |  |  | U | U |  |

<br/>
** Requirements Source Linkage Matrix
<br/>
| Requirement ID |	[Customer requirement](https://github.com/thanhLoc1087/SE357-Pratice-class/blob/Lab_1_3/Lab1.3/Customer_Requirements.docx)	| [Use case Specification](https://github.com/thanhLoc1087/SE357-Pratice-class/blob/Lab_1_3/Lab1.3/Use_case_Specification.docx) |	[Luật Thương Mại 2005](https://thuvienphapluat.vn/van-ban/Thuong-mai/Luat-Thuong-mai-2005-36-2005-QH11-2633.aspx)|
|--|--|--|--|
| R01 |	X |	X |	 |
| R02 |	X |	X |	 |
| R03 |	X |	X |	 |
| R04 |	X |	X |	 |
| R05 |	X |	X |	 |
| R06 |	X |	X |	X |
| R07 |	X |	X |	X |
| R08 |	X |	X |	X |
| R09 |	X |	X |	 |
| R10 |	X |	X |	 |
| R11 |	X |	X |	 |
| R12 |	X |	X |	 |
| R13 |	X |	X |	 |


<br/>
** Requirements Stakeholder Linkage Matrix
<br/>
| Requirement ID |	Rank 1 (lowest importance) – 5 (highest importance)	| Stakeholder Source A-Admin, S-Staff |
|--|--|--|
| R01 |	3 |	A |
| R02 |	3 |	A |
| R03 |	5 |	A |
| R04 |	3 |	A |
| R05 |	5 |	A, S |
| R06 |	4 |	A, S |
| R07 |	4 |	A, S |
| R08 |	2 |	A, S |
| R09 |	3 |	A, S |
| R10 |	3 |	A, S |
| R11 |	3 |	A, S |
| R12 |	2 |	A, S |
| R13 |	2 |	A, S |
