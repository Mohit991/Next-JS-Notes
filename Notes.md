# Next JS
## Introduction
<img width="460" alt="{CE863207-0512-4A42-BEF7-2DC79CF3E230}" src="https://github.com/user-attachments/assets/22a59e4e-7640-416c-97a3-544ce57f6dd7">  

Next JS optimizes your web app through its primary features, which are explain below.  
### Rendering
The primary difference between react and next is how they handle rendering.  
React JS renders the app on the client side.  
<img width="448" alt="{841AB7C3-8B90-4DB7-B6C1-7AC34FE04113}" src="https://github.com/user-attachments/assets/ff753ed7-ed07-4c6c-a502-53a849e861ab">  

On the other hand next js performs server side rendering.  
<img width="439" alt="{213AB3DC-66D3-4FEA-9608-BACC45039951}" src="https://github.com/user-attachments/assets/1887d3bf-30e1-48e0-a1a4-7aa03b5cae8c">  

Next js offers flexibility in rendering options. You can choose to render the UI on client side or the server side according to your needs.  
### Client-side rendering
It happens on the client side ie the browser.  
<img width="432" alt="{EB13927E-568B-44D7-B43A-409DC65C6609}" src="https://github.com/user-attachments/assets/122b114d-988d-40c3-af21-7c045b416a34">  

When the user request a web page, the server sends html file and js code. This JS code is executed on the browser and then the page is shown on the browser.  
### Server-side rendering
This means rendering the web page on the server and then transmitting it to the client.  
<img width="450" alt="{74DB142C-C9E1-4A01-8CA5-0129532D8E49}" src="https://github.com/user-attachments/assets/36308c80-e9ea-4490-a92e-1bcb9b255a84">  

When the user requests the page, the code is executed on the server side and fully rendered HTML is sent to the client. The fully rendered HTML is immediately rendered on the web browser.  
This leads us to **SEO (Search Engine Optimization)**

### SEO (Search Engine Optimization)
Search engine web crawlers face difficulties indexing pages dynamically renderd on the client side. As a result, the SEO or the ranking of such pages may suffer. Because search engines are not able to fully comprehand their content. This is resolved by using Next JS because it sends pre-rendered pages to the client.  
<img width="458" alt="{C5828325-299A-4D9E-A1C9-9DB8487ADE44}" src="https://github.com/user-attachments/assets/6384bc89-920f-48a4-a392-e63e9d33b24b">  

**Why SEO?**  
<img width="457" alt="{25CC5DF2-0B35-4523-BDF1-0CDA44DE40A0}" src="https://github.com/user-attachments/assets/1ca46872-b258-4514-91a6-b45bf82cbfe9">  

Benifits:  
<img width="458" alt="image" src="https://github.com/user-attachments/assets/76bc4290-e187-49ff-a748-e1cbda3d2e0c">  

### Routing
In react we have to use react router DOM (additional package) to do routing.  
<img width="467" alt="{874D3C1E-6B57-43D8-B3F4-A50E7FB143C0}" src="https://github.com/user-attachments/assets/02fcc7a0-66ab-4332-a535-dc306dd17974">  

In Next JS we do file based routing:  
<img width="443" alt="{369775D7-4B8F-4AC0-B6F8-E3D6B2BEDE57}" src="https://github.com/user-attachments/assets/597a7de6-db31-481f-9adc-81f53230b219">  

<img width="412" alt="{8EC33318-1994-4121-91DC-09AFAC9594F7}" src="https://github.com/user-attachments/assets/8e254a00-c7e1-499b-a336-850cd698b95e">  

<img width="422" alt="{1D291530-9A92-4136-A69C-2B5CB3EE9395}" src="https://github.com/user-attachments/assets/d54b905f-42fb-4f40-939f-aaf6717ae1f3">  

Each folder in app directory becomes a route:  
<img width="386" alt="{4F19977C-A68A-40FA-8CA4-92A27C99D0B5}" src="https://github.com/user-attachments/assets/af4110c6-1b37-4cfd-9c34-c4e63a452a42">  

For example, about folder will become /about route and so on.  
<img width="449" alt="{A9476858-1A45-4D09-9D82-5FF618864541}" src="https://github.com/user-attachments/assets/932193e6-73e0-46ad-bd54-ce522492ea4f">  

No external packages are needed.  
### Full Stack Applications 

<img width="633" alt="{DEC9A4E1-9E7B-490F-BFF1-8390CFE6562F}" src="https://github.com/user-attachments/assets/5693f63f-4231-44d3-a603-74f21d1a0958">  


<img width="618" alt="{EBD27FD0-D24B-4BC2-AF10-06092529E594}" src="https://github.com/user-attachments/assets/34808fee-347b-4cdd-a18e-fbe08b06315f">  


<img width="619" alt="{8B5C7CB2-A2B9-402F-8099-361D82026879}" src="https://github.com/user-attachments/assets/6005650a-c85e-40be-9d4e-f56de8b6a853">  

With this feature, we can create an API route by simply creating a file route.js in a specific folder within the app directory. This file in any route segment of the app directly corresponds to that API endpoint.  
### Automatic Code Splitting  

<img width="587" alt="{14B349E9-F74A-4EE8-A042-D03CF51CCFBA}" src="https://github.com/user-attachments/assets/376fb75d-6e6c-4dba-bce3-e43c222bdd18">  

Only load when needed.  
**In React**:  

<img width="572" alt="{2524C25E-D72B-4CBE-A072-55B4BC9C254F}" src="https://github.com/user-attachments/assets/22e65dcf-81b6-4f61-b9eb-95153279d0f5">  


<img width="616" alt="{20712611-B6E3-4C20-850F-280C30DD3A0C}" src="https://github.com/user-attachments/assets/58bbc8f7-8f6e-4407-b71e-f95ed9dc9c7e">  

**In Next, this process is automatic**:  
<img width="632" alt="{5DC5A7AE-6A58-4875-9BEF-FA105F1C0974}" src="https://github.com/user-attachments/assets/41d07856-eaa4-4a4f-b65e-c4978ce68226">  

### Final
<img width="570" alt="{E34A3499-51CF-45BB-B42A-1BAC8EBD7CEA}" src="https://github.com/user-attachments/assets/a799c642-9fd9-4656-8d83-a8e2e0f29b40">  


<img width="560" alt="{60572D43-D0E9-4197-A0B9-DE25AC3F6048}" src="https://github.com/user-attachments/assets/441988e6-ebcd-4ca5-ad48-a78a375dc63c">  


<img width="626" alt="{38B09587-A874-4DCA-BB56-827774FE3ABE}" src="https://github.com/user-attachments/assets/f7a68b27-c317-4e28-a26d-33e21056447a">  


<img width="628" alt="{82FA386C-9079-44EA-97A6-6CCC3A3EEDC6}" src="https://github.com/user-attachments/assets/06b58c3a-0bf2-47c1-b870-561683c59d8e">  

## Folder Structure

<img width="182" alt="{C06F317B-7FCA-45CB-ABA7-C77CF2D80C0F}" src="https://github.com/user-attachments/assets/e5a857d0-5d73-4801-8b86-3446ae3dfea4">  

### app folder

<img width="196" alt="{82F46966-4DA9-40BF-9E3A-E3503115324A}" src="https://github.com/user-attachments/assets/7fb93862-cf43-4b23-9e12-f9a8c07984ee">  

**layout.js**  
This is the entry point of our application. All of the components are wrapped within it as its children. Whatever components you put here will be shown in all the components. You can put navbar or footer or anything you want shown on all routes here. Also, when you use redux, you need to put provider here.  

![image](https://github.com/user-attachments/assets/131081b6-de0f-4a08-8f82-1c4be0b48b4a)  

**page.js**  
This is just the home page for your new application. It is shown on:  
`http://localhost:3000/`  
**globals.css**  
It is imported in layout.js hence every component will inherit styles from this file.  

## Server and Client Components
page.js seems to be a simple react component but it is being rendered as a server side component.  
If you want to run a component on the client side, you must use `"use client"` on top of the component.  
By default components are loaded on the server side.  
**A typical server side component looks like this**.

<img width="472" alt="{2E68473D-3884-4FA5-9E1B-458885D90532}" src="https://github.com/user-attachments/assets/b347fa48-8aa6-47df-b431-defdc7d9d6da">  


**A typical client side component looks like this**.  
<img width="468" alt="{58E36AA8-F4A8-4310-BDA8-48047C2E0F14}" src="https://github.com/user-attachments/assets/cef02dca-e525-49c9-9f39-27260f06cd31">  

**Whenever you are using a state or react hooks (useState or useEffect etc.) or any client side solutions, you have to render them on client side. State management in react is primarily handled on the client side**.  

<img width="464" alt="{C055611B-A90B-49D3-8F70-6DC489614A11}" src="https://github.com/user-attachments/assets/929033a7-d9d5-4a3c-bcdd-cd8eb7d757a1"><img width="464" alt="{21D7F2C4-F705-48CF-961D-40FC50E4F16E}" src="https://github.com/user-attachments/assets/9c19911a-91e1-47fc-8628-c2643ee94887">











































