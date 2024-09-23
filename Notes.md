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













