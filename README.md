# 1. Possible Types of Fraud
**By the Customer:**
- False Pickup Requests: Customers might request pickups for packages they never intend to send, leading to wasted resources.
- Package Misrepresentation: Customers could misrepresent the contents of packages to avoid higher shipping fees or to commit fraud (e.g., shipping illegal items).
- Chargeback Fraud: If customers were to make payments online, they might claim they did not receive a package to initiate a chargeback.


**By the Truck Driver:**
- Theft of Packages: Drivers could steal packages during transit or delivery.
- Falsifying Delivery Records: Drivers might mark packages as delivered when they were not, potentially keeping the items for personal gain.
- Collusion with Customers: Drivers could collaborate with customers to falsely report deliveries or pickups for shared profits.


**By Collaboration Between System Users:**
- Collusion Between Drivers and Customers: Drivers and customers could work together to create false pickup requests or delivery confirmations, splitting the profits from stolen or misrepresented packages.
- Manipulation of Tracking Information: Users could manipulate the system to alter tracking information, making it appear as though packages were delivered or picked up when they were not.


**Steps to Minimize Fraud Opportunities:**
- Verification Processes: Implement verification for pickup requests, such as requiring customers to confirm their identity through a secure method (e.g., email or SMS verification).
- Tracking and Auditing: Use GPS tracking for drivers and maintain logs of all package statuses and updates. Regular audits of these logs can help identify discrepancies.
- Training and Awareness: Train drivers and staff on recognizing fraudulent behavior and the importance of reporting suspicious activities.
- Secure Payment Systems: If payments are introduced, use secure payment gateways with fraud detection mechanisms.


# 2. Access Controls
**For the Customer:**
- Current Access Control: Since customers currently do not engage in financial transactions, basic access controls (e.g., userID and password) may suffice.
- If Payments Are Introduced: If customers can make payments online, implement multi-factor authentication (MFA) to enhance security. This could include SMS verification or email confirmation for transactions.


**For the Truck Drivers:**
- Access Control: Drivers should have access to their schedules and package statuses. Implement MFA for drivers as well, especially since they handle sensitive information and packages. This could include biometric authentication (e.g., fingerprint or facial recognition) on their devices.


**For Bill (Management):**
- Access Control: Bill should have administrative access to all system features, including accounting and scheduling. Implement MFA for Bill as well, given the sensitive nature of the information he handles. Consider role-based access controls to limit what each user can see and do based on their role.


**UserID and Password Sufficiency:**
- Basic Users (Customers): For non-financial transactions, userID and password may be sufficient, but MFA is recommended if payments are involved.
- Drivers and Management: For both drivers and Bill, typical userID and password are not sufficient due to the sensitive nature of their roles. MFA should be required to enhance security and reduce the risk of unauthorized access.


**Conclusion**
By understanding the potential fraud risks and implementing robust access controls, Bill can create a secure and reliable system for his courier services. This proactive approach will help protect the business from fraud while ensuring a smooth operation for customers and drivers alike.


## References
Bank, S. (n.d.). Beware: Courier scams are on the rise | Articles | Insights. https://contenthub.sasfin.com. https://contenthub.sasfin.com/insights/articles/beware-courier-scams-are-on-the-rise/ 

Blog, I., & Blog, I. (2024, July 15). What are the most common types of food delivery scams and courier fraud? Incognia. https://www.incognia.com/the-authentication-reference/food-delivery-scams 

Damaini, A. A., Nugroho, G. S., & Suyoto, S. (2018). Fraud Crime Mitigation of Mobile Application Users for Online Transportation. International Journal of Interactive Mobile Technologies (iJIM), 12(3), 153. https://doi.org/10.3991/ijim.v12i3.8070 

Package Delivery Scams. (2023). American Bankers Association. https://www.aba.com/advocacy/community-programs/consumer-resources/protect-your-money/package-delivery-scams
