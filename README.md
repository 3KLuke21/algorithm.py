Employee Access Management for Restricted Content

This repository contains a Python script designed to automate the management of IP address access to restricted content in a healthcare setting. As part of regulatory compliance, healthcare companies need to ensure that only authorized employees can access personal patient records. Access is restricted based on IP addresses, with an allow list of authorized IPs and a remove list that specifies employees who must be removed from the allow list.

Features:

	•	Allow List Validation: The script checks the allow list to ensure it contains only the IP addresses of employees currently authorized to access the restricted subnetwork.
	•	IP Removal: The script scans through the remove list and removes any IP addresses that match entries in the allow list, ensuring that unauthorized employees are promptly denied access.
	•	Data Integrity: Ensures that the allow list is updated accurately and without errors, protecting sensitive patient information.

Use Case:

This script is specifically designed for IT and security professionals in healthcare companies who need to ensure that only authorized personnel can access sensitive patient data. It automates the tedious process of updating and maintaining access controls based on employee changes or security requirements.

Instructions:

	1.	Load the allow list and remove list from their respective files.
	2.	Run the Python script to cross-check and remove any IP addresses found in both lists.
	3.	Save the updated allow list to maintain proper access controls.
