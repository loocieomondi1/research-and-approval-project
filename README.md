# ALL FARMERS AND MARKET STORE E-COMMERCE
USING MODERN, NEXT.JS, PAYPAL, PAYSTACK INTEGRATION

### Home Page And Landing page

![ farmers and market](https://user-images.githubusercontent.com/106968663/229288997-26ca966a-cfee-424b-b959-a8a6bcf5ba7b.png)

![aaa](https://user-images.githubusercontent.com/106968663/229373503-061e68e0-df26-4b83-a464-0496cd675cda.png)

![ farmers and market 2](https://user-images.githubusercontent.com/106968663/229289046-03ba3a41-fdd5-43ce-a411-6814a22b99a8.png)

## Significant of this project

> Farmers and their productive  Food items are one of the best lucrative businesses around the world. They get patronage on a daily basis without being much affected by the country's economy because people depend on food for survival.

> This hence results to the whole idea behind farmers and food products to be soled online, to solve a problem of helping seller get market online and buyers buy online.

In this reserch project, you will learn how to build a modern e-commerce storefront, using Paypal and Paystack integration. 

## Inspiration behind the application

> My inspiration came from a life experience, where people of the world are faced with virtual challenges that distracts their daily lives actives such as the issues of easy accessibility to food and food products.  such challenges can be so overwhelming ofcause, let's take an example; imagine coming back from work,8-5 maybe  and realizing that you have no groceries,no food at home yet you are hungry and not to mention exhausted at the same time. Frustrating. right??

> To solve such a problem, an inspired and innovative thought kicked in booom...., hoping this will highly be  part of those solving world problem by incooperating  an application where people can at the comfort of their home or offices or any place at a particular time and make orders online and get there food and groceries delivered to them faster and comfortably.

## Overview

This project is composed of three different components: the headless backend, the storefront, and the admin dashboard.

It also provides bespoke commerce infrastructure for developers. Its composable commerce engine addresses the challenges of existing ecommerce platforms which APIs offer bad developer experiences, extension capabilities are insufficient, and results are hacky and hard to maintain.

[ext.js](https://extjs.org/) is a JavaScript open source framework for building superfast and extremely user-friendly frontend websites using React. It is a server-rendered, lightweight, and flexible React framework that requires little or no configuration during usage.

Using this project to build your online stores gives you the opportunity to work with this project, which can be easily installed through CLI commands.

ext.js storefront is a 100% ready-to-use  storefront template. It comes with all ecommerce storefront features such as product display, featured products, shopping cart, checking out, multiple payment processing, and more.

[PayPal](https://www.paypal.com/ng/home/) is a payment provider used by millions around the world. It allows customers to purchase orders from your website using their PayPal account rather than the need to enter their card details.

As a developer, you can use PayPal’s SDKs and APIs to integrate PayPal as a payment method into your ecommerce store. You can test out the payment method in sandbox mode before going live with it as a payment method.

[Paystack](https://paystack.com/) is the #1 African payment gateway that helps businesses to accept online payments through their ecommerce stores, websites, and applications. Paystack provides other services such as point-of-sale (PoS), payment through an invoice, and more.

[Algolia](https://www.algolia.com/) is a search engine service that allows developers to integrate advanced search functionalities into their websites including typo tolerance, recommended results, and quick responses.

Algolia can be used for a wide range of use cases, including ecommerce websites. By integrating Algolia into your ecommerce website, you can provide your customers with a better user experience and help them find what they’re looking for swifltly.

Through project's flexible plugin system, it is possible to add a search engine to your  backend and storefront using Algolia with just a few steps.

[S3](https://ws.amazon.com/s3/) To manage images in this project, you need a file service plugin responsible for hosting the images. Without a file service plugin, you will face issues while working with the project, such as when uploading images
The project provides three different options to handle your file storage.

# Prerequisites

To follow through this tutorial, make sure to have:

* Node.js and NPM installed on your local machine. You can follow the instructions [in this link](https://phoenixnap.com/kb/install-node-js-npm-on-windows/) to fully install Node.js and npm on your local computer.

* Git installed locally with a GitHub account. Follow the instructions [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git/) to install git, and create a GitHub account [here](https://github.com/).

* PayPal Account with API Secret and Public Key, on the developer dashboard [here](https://developer.paypal.com/)

* Paystack Account with API Secret and Public Key, on the developer dashboard [here](https://paystack.com/)

* S3 Account with API Secret and Public Key [here](https://aws.amazon.com/s3/)

 
# Set up Your Food Restaurant and Market Store E-commerce with us

* **Backend installation and setup using  CLI*

CLI tool can be installed either using `npm` or `yarn`, but this tutorial is based on `npm`. Use the command below to install Medusa CLI:

```
```

**Then create a new project with the installed CLI**

```

```

`my-farmer-and-market-store` will be your project name, but you can change this to your preferred choice of name.

Change to the preferred name of your project directory.

```
cd my-farmer-and-market-store
```

Finally, start up the created server.

```

```
 **Create an Algolia App**
 
The first step is to create an Algolia app for your  backend. To create one, open your dashboard, go to Settings then choose Applications.

On the Applications page, click on the New application button at the top right.

![image](https://user-images.githubusercontent.com/106968663/229312418-82999b08-e7de-4437-ab50-1b606eb5680a.png)

In the new page that opens, optionally enter a name for the application and choose a subscription plan. You can choose the Free plan for now, but it's recommended to switch to the Pay-as-you-go plan as your business grows.

![image](https://user-images.githubusercontent.com/106968663/229312440-8760c271-7739-4a76-b7bd-152c0949a697.png)

Once done, click on the Next Step button. If you picked Pay as you go service, you'll need to enter billing details before you proceed.

Then, you'll be asked to pick a region for your application. Once you're done, click on Review Application Details.

![image](https://user-images.githubusercontent.com/106968663/229312482-6bfce1d4-15f0-4a86-a868-c15b62acc6ed.png)

In the last step, you'll see a summary of your order. If all looks good, check the checkboxes at the end of the form to indicate that you agree to the terms and conditions. Then, click on the Create Application button.

![image](https://user-images.githubusercontent.com/106968663/229312521-20b46a05-9167-4e32-9f78-e221b91df344.png)

**Retrieve API Keys**

To retrieve the API keys that you'll use in the next sections, go to Settings, then choose API Keys in the Team and Access section.

![image](https://user-images.githubusercontent.com/106968663/229312551-82271cad-6612-42c9-ab84-db714f92db11.png)

On this page, you'll find the Application ID, Search-Only API Key, and Admin API Key. You'll need the Application ID and Admin API Key for the backend. As for the storefront, you'll need the Application ID and Search-Only API Key.

![image](https://user-images.githubusercontent.com/106968663/229312580-f6f1743f-f695-4205-b43e-42aac9bbb32e.png)

**install the Algolia Plugin**

In the directory of your backend, run the following command to install the Algolia plugin:

```

```

