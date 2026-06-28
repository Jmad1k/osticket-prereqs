<img src=images/osticketLogoHeader.png width="450">

# osTicket: Prerequisites and Installation

This project demonstrates the deployment of **osTicket**, an open-source helpdesk ticketing system, within a virtualized Azure environment. This lab focuses on the infrastructure setup, web server configuration, and database integration required to host a functional helpdesk platform.

## Infrastructure Overview
*   **Virtualization:** Azure Virtual Machines
*   **Operating System:** Windows Server 2025 DataCenter
*   **Web Server:** IIS
*   **Database:** MySQLi
*   **PHP Version:** v7.3.8

## Deployment Steps
1.  **Environment Provisioning:** Configured and deployed a virtual machine in Azure.
2.  **Server Stack Installation:** Installed and configured the required web server, database management system, and PHP runtime environment.
3.  **Application Setup:** Downloaded, extracted, and placed the osTicket source files in the web root directory.
4.  **Database Configuration:** Created a dedicated database and user, granting the necessary privileges for osTicket.
5.  **Final Installation:** Completed the web-based installer and verified the application's functionality.

## Project Evidence

<!-- Image 1 -->
<a href="images/your-first-file.png">
  <img src="images/your-first-file.png" alt="Installation Wizard" width="600">
</a>
<p>Figure 1: Successful completion of the osTicket web-based installation wizard.</p>

<!-- Image 2 -->
<a href="images/your-second-file.png">
  <img src="images/your-second-file.png" alt="Server Dashboard" width="600">
</a>
<p>Figure 2: Verifying the web server and PHP environment settings required by osTicket.</p>

## Lessons Learned
*   **Permission Management:** Learned how to correctly set file/folder permissions to ensure the web server could read/write necessary configuration files.
*   **Dependency Resolution:** Gained experience in troubleshooting missing PHP extensions required by osTicket during the pre-check phase.
*   **IIS Configuration:** Gained hands-on experience in managing server roles using Windows Server Manager.

---
*Created by Gerardo M.*
