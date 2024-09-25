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

## Routing
Create a folder in the app folder, the name will serve as the route.  
Let's say we want to create /user route. Go to app folder, create a new folder called user. Inside this folder, create a page.js file.  
<img width="196" alt="{278BE553-D1C3-428E-9FBB-B2A0DCB17E86}" src="https://github.com/user-attachments/assets/f5f6f095-65bd-4ee4-aef6-7bbb27db1428">  

In the file, you can create a react functional component.  
![image](https://github.com/user-attachments/assets/b20fe96f-983e-4431-97b5-6eac9dc9e9d6)  

### Example
We want to create a blog app. We have below routing for this in react.  
<img width="475" alt="{7D67359E-276F-40CB-B263-8BC5658BCB14}" src="https://github.com/user-attachments/assets/5fed3dc2-f592-4a3f-9437-784fa11134df">  


Achiving the same in next js:  
<img width="178" alt="{74144379-3CCB-44CD-99C9-4ADB3297CB3C}" src="https://github.com/user-attachments/assets/e4e1b131-6389-4095-b9f2-775a5f7b6e5d">  


### Dynamic Routing
Creating website pages based on different variables or data. For example, in our blog website example, we might have a route like `posts/:posId` we want to show a blog post with dynamic id.  
In react, we do this:  
<img width="432" alt="{17757F55-77D5-44AD-9DC7-5CDC0FBA0701}" src="https://github.com/user-attachments/assets/3b5bdecd-a3ec-4527-8164-c0a82e8792c6">  

We have `path = :postId`, This will render the dyanmic route.  
In next js, we will create a new folder but this time we will wrap it inside square brackets. See below:  
<img width="181" alt="{01997713-B13E-4079-A966-CA525B3BCE29}" src="https://github.com/user-attachments/assets/aaebaac0-b26f-4b8d-b027-ed09f0ff3e79">  

Inside this folder, we have a page.js file. This file will have access to the postId dynamic variable.  
![image](https://github.com/user-attachments/assets/dfa7090f-2e8f-44a6-b9b1-aa51223daa38)  

In the app folder, we have the route folder. The route folder contains a file page.js which will be rendered on that route. Inside this folder we can have folders with squares [], which will be for the dynamic routes.  
On top of this, we can have below files inside the route folder as well.  
1. **layout.js**: You can share UI components between routes with the help of this. For example, we can create a component navigate to top and use in any of the dynamic routes in that route folder.
   <img width="183" alt="{13B00CB1-DCBF-48D8-9339-577437C170A3}" src="https://github.com/user-attachments/assets/f14d8d07-82c6-40e2-8a47-ca8cead9d67f">

Now, the layout will show in dynamic routes of posts ie postId routes. New posts and all the posts.  
2. **loading.js**: This will be a loader component which will be shown whenever any of the route loads.  
<img width="466" alt="{DA7213E7-5982-4A98-B675-253940DFA23C}" src="https://github.com/user-attachments/assets/d368b138-7e5b-4725-8755-efd077b4a60e">  

3. **error.js**: This will automatically run when an error happens and it will show the error gracefully to the user. Error components must be client components. So, you must use `use client` in the error component.
Final Structure:
<img width="184" alt="{2950CF74-0E20-407E-815A-8B96B9C0080B}" src="https://github.com/user-attachments/assets/4cbc8717-dcc0-4dc6-a586-548852d45f8d">

## Data Fetching
<img width="474" alt="{4392F1E7-F8D5-4DC6-A570-B083354896CC}" src="https://github.com/user-attachments/assets/a5a7c100-2634-402d-b4d8-a317d2048b8c">  

### Server Side Rendering (SSR) 
Each request to the server triggers a new rendering cycle and data fetch. This makes sure that the content is always up to date.  
Eg.  
<img width="445" alt="{F98EAFBF-B437-48EB-8024-C2C479E6DA9B}" src="https://github.com/user-attachments/assets/9d4db01f-0cf6-4e14-8833-1c58e045b012">  

### Static Site Generation (SSG)
Data is fetched and cached. Once cached, data is not fetched on every request. This can be used for the content that does not change frequently such as blog posts, documents etc.  
<img width="445" alt="{F7000AD9-6D8E-4B29-92A6-5AF76E237865}" src="https://github.com/user-attachments/assets/269560b6-bb4c-4aa3-afc2-7c4e2d95ee54">  

We just removed the cache line.  
### Incremental Static Generation (ISG)
Combines the benefit of both. We specify certain data to be statically fetched at build time while also defining a revalidation time interval. The data will be fetched and cached but after the interval time the data will be refreshed.  
<img width="446" alt="{07699752-6302-4D2D-BEEA-98BD8D60F3B3}" src="https://github.com/user-attachments/assets/2a5fc676-b2e2-4aad-ad25-0d6cb580e6ab">  

## Next JS API Endpoints
Creating endpoints using express js:  
<img width="466" alt="{137DF6B0-1163-4F37-97E9-E907C5446679}" src="https://github.com/user-attachments/assets/da15c1b1-ce9f-46bd-8957-aa042a9d10e4">  

Next Js has all of the features that a tradition backend server will have. Those are middleware, parsing, auth checks etc.  
There are two ways to do it:  
1. File based routing: Create api folder inside the app folder. Then create route folders inside this folder.
   <img width="106" alt="{50EF51E3-2A5E-46AB-BB52-CB9CC1E3D6B4}" src="https://github.com/user-attachments/assets/ba65d5a3-ef19-4c19-a0f7-0c87ab4104b9">

2. Route handler in app directory: Create a route.js folder. This will be the backend api route.
Because all of this is happening inside the app folder, next js will get confused as which one is an API route and which was is a page.
<img width="464" alt="{7D78F668-484A-4591-A723-C52CF13BDA62}" src="https://github.com/user-attachments/assets/4c1bbe2f-33a3-430c-b5d7-ce8489cdf691">

First method is better. We will create a api folder and create routes inside that folder.  
<img width="100" alt="{41544308-E76C-4305-91C1-9F5A972AE305}" src="https://github.com/user-attachments/assets/ac1b977e-aadf-4eca-a9e0-980dffcfcf8f">  

<img width="446" alt="{E25F4E0A-6969-456D-911B-5732D733CBF6}" src="https://github.com/user-attachments/assets/e202199e-d3f0-453b-a71a-fb8cd2f3e23c">  

<img width="443" alt="{9739D37B-F79E-452F-A96F-8AF75263D52E}" src="https://github.com/user-attachments/assets/cb97c8ef-d7ee-4d45-b777-3fc3af5cc9d0">  

Get api route in next js:  
<img width="441" alt="{8F2AAD2F-8B1E-4987-9B68-BBAAE428683F}" src="https://github.com/user-attachments/assets/56b48577-e1bf-4d0c-b7b9-d29debdb79db">  


How to call the api:  
<img width="441" alt="{004688C5-4E3A-485D-ADF3-1CC979A53D61}" src="https://github.com/user-attachments/assets/407ec8d4-2365-46cd-9e16-9ba8831e1a0f">

















 





















































