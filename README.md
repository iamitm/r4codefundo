# Microsoft Codefundo 

### Team bits_R4

##### Team Member 1: Amit Mishra
##### Team Member 2: Yaduraj Gupta

## Idea on secure voting system using Azure Blockchain

###### A. Who will be a suitable user for this system?
i. Person must be above 18 years old.
ii. He/she should hold an Aadhaar Card.
iii. He/she should have a phone with a working camera. 

###### A. Registering on the voting system
i. Use OTP based authentication on mobile number linked with aadhar number.
ii.Check who is eligible for voting and authenticate accordingly. 

###### B. Voting
i. Vote can be given only once. Multiple confirmation dialog boxes so that the user doesn't make a mistake.
ii. Allot different slots such that server is never overloaded with requests.
iii. While voting, to confirm a legible vote the user must click a video of himself saying a random phrase.
iv. Use speech to text api to check if the voter said the correct phrase and also confirm identity of the voter via face recognition and cross check with Aadhar Card photo.
v. Use Azure Blockchain to register vote. 

