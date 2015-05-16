[Salesforce® Federated Single Sign-on solution(s) with IBM WebSphere® DataPower®][9]
----------------------------------------

> ***[Dipak K. Pal][14]***


----------

Introduction
------------

As more institutions and organizations offer services and collaborations online, employees need to access both on-premises as well as cloud-based applications to do their day-to-day work. This demands implementing a single sign-on (**SSO**) infrastructure enabling users to sign in once to access all authorized internal and external resources and applications. Organizations with a large Salesforce user base can leverage their existing **SSO** infrastructure to implement **SSO** to the **Force.com** platform, which supports Federated Identity Management powered by an external **SSO** identity provider. The **Force.com** platform supports both delegated and federated authentication for **SSO**.

This **[IBM developerWorks® tutorial series][9]** focuses on federated authentication only, which has several advantages over delegated authentication and is widely accepted in the IT industry. Federated authentication does not validate the user's actual password on the Force.com platform. Instead, the platform receives a Security Assertion Markup Language (**SAML**) assertion in an HTTP POST request. The **SAML** assertion has a limited validity period, contains a unique identifier, is digitally signed, and is optionally encrypted. If the assertion is still valid within its validity period, has an identifier that has not been used before, and has a valid signature from a trusted identity provider, the user is granted access to the requested resource or page. Using **IBM® WebSphere DataPower** (hereafter called **DataPower**) as the **SSO** identity provider, enterprises can implement a single registry of user identities with a centralized management interface for all of their internal applications as well as external applications (for example, **Force.com**) that support federated single sign-on.

**This [IBM developerWorks® tutorial series][9] consists of the following four tutorials:**


 - **[Part 1: Identity provider initiated
   SSO using a signed SAML assertion][1]**

![image alt][2]

 - **[Part 2: Identity provider initiated
   SSO using an encrypted and signed
   SAML assertion][3]**

![image alt][4]

 - **[Part 3: Service provider initiated
   SSO using a signed SAML assertion][5]**

![image alt][6]

 - **[Part 4: Service provider initiated
   SSO using an encrypted and signed
   SAML assertion][7]**

![image alt][8]

[Resources @IBM developerWorks®][9]
---------

**Salesforce® Federated Single Sign-on solution(s) with IBM WebSphere® DataPower®**

 - **[Part 1: Identity provider initiated
   SSO using a signed SAML assertion][10]**

 - **[Part 2: Identity provider initiated
   SSO using an encrypted and signed
   SAML assertion][11]**

 - **[Part 3: Service provider initiated
   SSO using a signed SAML assertion][12]**

 - **[Part 4: Service provider initiated
   SSO using an encrypted and signed
   SAML assertion][13]**

Feedback
--------

Please feel free to put your questions/comments/suggestions/feedback at ***Comments*** section of the corresponding [IBM developerWorks® article][9]. I will try my best to address your questions/comments/suggestions as soon as possible.


  [1]: http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal1/1505_pal1.html
  [2]: 
http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal1/images/figure2.png
  [3]:  http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal2/1505_pal2.html
  [4]: 
http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal2/images/figure1.png
  [5]: http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal3/1505_pal3.html
  [6]: 
http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal3/images/figure2.png
  [7]: http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal4/1505_pal4.html
  [8]: 
http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal4/images/figure1.png
  [9]: http://www.ibm.com/developerworks/views/websphere/libraryview.jsp?search_by=Implementing+Salesforce+federated+single
  [10]: http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal1/1505_pal1.html
  [11]:  http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal2/1505_pal2.html
  [12]: http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal3/1505_pal3.html
  [13]: http://www.ibm.com/developerworks/websphere/library/techarticles/1505_pal4/1505_pal4.html
  [14]: https://www.linkedin.com/in/dipakpal/
