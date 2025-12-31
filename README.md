# ShopSphere | ASP.NET Core Full-Stack Reference Application

ShopSphere is a **modern ASP.NET Core full-stack web application** that demonstrates enterprise web application patterns using a **single-process (monolithic) architecture**. The project focuses on clean architecture, maintainability, and cloud-ready deployment practices.

## Project Context

ShopSphere is conceptually related to the **eShopOnContainers** project, which focuses on a microservices and container-based architecture.

In contrast, **ShopSphere emphasizes traditional web application development** using a single deployment model. This makes it easier to understand core architectural principles without the additional complexity of distributed microservices.

The purpose of this project is to demonstrate architectural and design principles described in the referenced ebook. It is **not intended to be a complete eCommerce solution**, and some production-level features are intentionally omitted.

---

## Versions

- The `main` branch runs on **ASP.NET Core 8.0**
- Older versions are available via tagged releases

---

## Topics Covered

- Introduction to modern web applications
- Characteristics of scalable and maintainable web apps
- Traditional web apps vs SPAs
- Architectural principles and patterns
- Common web application architectures
- Client-side technologies
- ASP.NET Core MVC development
- Data access with Entity Framework Core
- Testing ASP.NET Core applications
- Azure-hosted application workflows
- Hosting and deployment recommendations

---

## Running the Application Using Azure Developer CLI

The application home page appears as follows:

![ShopSphere home page]
<img width="800" height="533" alt="image" src="https://github.com/user-attachments/assets/1b7a0cc3-7e09-4626-8df4-b17406f36d1b" />


The Azure Developer CLI (`azd`) is used to provision and deploy the application to Azure.

### Install Azure Developer CLI

#### Windows
```powershell
powershell -ex AllSigned -c "Invoke-RestMethod 'https://aka.ms/install-azd.ps1' | Invoke-Expression"
