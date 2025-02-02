---
description: 'Here, you will know the two Ritchie''s versions for download.'
---

# Choosing a version

## Intro

Before you begin to use Ritchie, it is necessary to choose one of available versions :

* **Single version**: suitable for freelance professionals; 
* **Team version**: suitable for teams or professionals of a corporation. 

Both versions were created to meet the different needs of infrastructure analysts, SREs, architects or software engineers. 

In practice, the main difference between the versions is in the use \(or not\) of a server for storing the **formulas**, mandatory for those who use the Team Version, since, in the case of those who use Ritchie for corporate projects, it is necessary to ensure security information to protect sensitive data.

![Versions single and team architecture ](../.gitbook/assets/team-and-single%20%282%29%20%281%29.png)

## **Comparing versions**

![](../.gitbook/assets/captura_de_tela_2020-06-09_as_09.55.22.png)

## **Single version**

The main characteristics of this version are:

* Access to community formulas.
* The possibility to test new formulas on a local repository.
* Encrypted information on the local machine.

### Repositories

If you choose the **Single Version,** you are able to access ****two repositories:

1. [**ritchie-cli**](https://github.com/ZupIT/ritchie-cli): this repository contains the core of the tool.  
2. [**ritchie-formulas**](https://github.com/ZupIT/ritchie-formulas): ****this repository contains the formulas shared with the community that every Ritchie user can access, update and execute through the terminal.



![](../.gitbook/assets/single-ritchie.png)

## Team version

The main characteristics of this version are: 

* Access to community formulas as well as team formulas;
* The possibility to test new formulas on a local repository; 
* Encrypted information on the server session.

### Repositories 

With the **Team Version** is possible to access more repositories: 

1. [**ritchie-cli**](https://github.com/ZupIT/ritchie-cli): this repository contains the core of the tool.  
2. \*\*\*\*[**ritchie-formulas**](https://github.com/ZupIT/ritchie-formulas): this repository contains the formulas shared with the community that every Ritchie user can access, update and execute through the terminal. 
3. \*\*\*\*[**ritchie-server**](https://github.com/ZupIT/ritchie-server): This repository contains the integrations with the platforms [Keycloak](https://www.keycloak.org/) & [Vault](https://www.vaultproject.io/), used to create the session and store datas securely.

{% hint style="warning" %}
It is also possible to store your team specific formulas in **other repositories**, and access them through [the login command](https://docs.ritchiecli.io/software-architecture-1/security#login-command).
{% endhint %}

![](../.gitbook/assets/team-ritchie-white.png)

