#  Azure App Service Web App Deployment & Monitoring Lab

This hands-on lab demonstrates the complete lifecycle of deploying, staging, swapping, and monitoring an Azure App Service Web App using the Azure Portal. The project covers essential real-world practices such as deployment slot management, environment configuration, zip-based deployment, and application diagnostics


 # Key Learning Objectives
 
* Understand how Azure App Service works and the different plan tiers

* Create and configure an App Service Plan (S1 Tier, Windows OS)

* Deploy a production-ready Web App using zip push deployment

* Configure staging and production slots for seamless updates and rollback

* Swap slots with preview and manage slot-specific settings

* Enable application logging and monitor with Azure built-in tools

* Use Kudu for advanced app deployment and diagnostics


---

| Task                | Details                                                 |
| ------------------- | ------------------------------------------------------- |
| ✅ App Service Plan  | `ca-lab-plan` created in **West US**, S1 tier           |
| ✅ Web App           | Windows-based, .NET 8.x Runtime                         |
| ✅ Deployment Slots  | `staging` slot created                                  |
| ✅ Zip Deployment    | Pre-built app deployed using **Kudu**                   |
| ✅ Swap with Preview | Staging → Production with test-setting confirmation     |
| ✅ Logging           | Verbose App + Web Server logging enabled                |
| ✅ Monitoring        | Metrics tracked: Connections, Thread Count, 2xx, Errors |
| ✅ Health Check      | Verified with Azure Resource Health                     |


---

## 🧱 Architecture Diagram
<h3 align="center">Azure App Service Deployment Architecture</h3>

<p align="center">
  <img src="https://github.com/nyashamahara/Azure-App-Service-Web-App-Deployment-Monitoring-Lab/blob/main/screenshots/architecture%20diagram.png?raw=true" 
       alt="Azure Architecture Diagram" 
       width="600"/>
</p>

<p align="center">
  <em>Figure: Visual overview of the deployment and monitoring architecture.</em><br>
  📸 <a href="https://github.com/nyashamahara/Azure-App-Service-Web-App-Deployment-Monitoring-Lab/tree/main/screenshots" target="_blank">
  View all 18 step-by-step screenshots in the <code>/screenshots</code> folder</a>
</p>


![Azure App Service Flow Diagram](./screenshots/azure-app-service-flow.png)

---

## 📁 Folder Structure

