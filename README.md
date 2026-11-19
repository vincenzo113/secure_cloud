# Secure Cloud Computing Project - Group 06

**Track:** Discriminating healthy subjects from Alzheimer's disease patients

**Members:** Vincenzo Ragone (IE22700030), Silvio Ventura (IE22700072)

## Abstract

This project delivers a machine learning classifier that distinguishes healthy subjects from Alzheimer's disease patients, offered as a SaaS web app on a secure cloud infrastructure. The model is trained offline, containerized with Docker, checked and patched with Docker Scout, stress tested with `wrk` and deployed on a Kubernetes cluster secured with NGINX. The service is designed for about 50,000 customers and up to 5,000 requests per minute, with a response time under 1 second and availability of at least 99.5% during working hours (8:00-18:00, Monday to Friday).