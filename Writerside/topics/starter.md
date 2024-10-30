# Getting started :books:

A friendly guide to help our retail partners get started with introducing <b><a href="https://pendoo.io">Pendoo</a></b> to their brick-and-mortar stores.
The <b>real</b> new era of retail awaits, so let's get going :rocket:


## What's Pendoo? :bulb:
><b>Ad valorem</b> :tophat:<br/>
>In Latin? Well, <i>pendo</i> relates to the concept of <i>value</i>. And Pendoo? Think 
>of it as <i>value added</i>, or <i>value+</i>, if you will. We have added an extra O, you see...

On the face of it, Pendoo is a <b>scan-and-go</b> technology. It allows retail consumers to use their mobile device to scan 
product barcodes, add them to their digital basket and ultimately check-out. All on their device.


><b>Plug-and-Play</b> :circus_tent: <br/>
>Pendoo integrates seamlessly with <a href="https://shopify.com"><b>Shopify</b></a> in the form of a <a href="https://help.shopify.com/en/manual/apps/app-types/custom-apps">custom app</a>.
>As a true <i>plug-and-play</i> solution, integrating Pendoo takes less than 5 minutes and requires <b>no</b> additional work.
>We are currently working on introducing stable integrations with other popular platforms such as <a href="https://lightspeedhq.com">Lightspeed</a> and <a href="https://squarespace.com">Squarespace</a>.
{style="note"}

![Create new topic options](scan.svg){ width=240 }

## Installation :package:

>   <b>Prerequisite</b> :construction:<br/>
    To install the app, a Shopify account with an active Shopify shop is required. You must either be the shop owner or have 
    the appropriate permissions to carry out the installation.

### Create a merchant account :female_farmer: {id="create-merchant-account"}
First things first - go ahead and <a href="https://pendoo.io/merchant-signup" target="_blank"><b>create your merchant account</b></a>.

### Connect your Shopify shop :electric_plug: {id="connect-your-shop"}

> <b>Prerequisite</b> :construction: <br/>A Pendoo [merchant account](#create-merchant-account) is required prior to connecting your shop.

Log into your brand-new account and head over to your dashboard.
<img src="Group 54.svg" alt="initial dashboard"/>

<note>
    The initial connection allows us to prepare the stage by creating the necessary foundation upon
    which the installation will be carried out. Most importantly, we set up a 2-way communication channel that is used exclusively
    between you, the retailer, and us, the sales channel. This channel is created on a per-retailer basis to ensure data security and integrity.
</note>


<tip>
    Currently, the default platform integration is with Shopify. This may change in the future as we will be releasing more 
    integrations.
    <img src="platform-integrations.png" alt="platform integrations"/>
</tip>

Enter your domain, the email address associated with your Shopify account and click <b>Connect</b>. 
<u>Establishing a connection can take up to 3 minutes to complete</u>.

<note>
    The domain can either be the custom domain you use for your Shopify shop, e.g. <b>my-store.com</b>, or it could be
    your permanent Shopify address, e.g. <b>my-store.myshopify.com</b>.
</note>

### Install the Shopify app :crane:

> <b>Prerequisite</b> :construction:<br/>An [initial connection](#connect-your-shop) is required prior to installing the app.

If the connection has been made successfully, your dashboard's <b>Connected shop</b> card should have been updated.

<img src="install_dashboard.svg" alt="install dashboard"/>

This is where the magic starts - you can now install the app. Go ahead, click on <b>Install now</b>! <br/><br/>
> <b>Access scopes</b> - <i><a href="https://shopify.dev/docs/api/usage/access-scopes#authenticated-access-scopes">what are Shopify access scopes?</a></i><br/><br/>
To facilitate the creation and processing of orders and in order for Pendoo to route them appropriately to your shop and/or specific location,
certain access scopes are required. These include scopes around <i>products</i>, <i>customers</i>, <i>orders</i>, <i>locations</i> and <i>fulfillments</i>.
They will be explicitly requested upon installation. <br/><br/>If you have questions or concerns, please get in touch with us at
[info@pendoo.io](mailto:info@pendoo.io).



## Features :pushpin:
We have been working with retailers in various markets with a range of different requirements. This exposure offers us a 
prime opportunity to recognise patterns in some of our retailers' most pressing issues when it comes to their customers' shopping experiences.

<note>Introducing new software tools to your team almost always comes with overhead. So much so, that it can even feel 
counter-productive at times. Let's <b>not</b> do that this time! Let us take care of the admin while your customers shop away. 
</note>

### Payment methods :credit_card: {id="payment-methods"}
Every market has different methods of payment that are popular among its retail shoppers. We
strive to be flexible regardless of geography. Beyond <b><a href="https://www.apple.com/apple-pay/">Apple Pay</a></b> and
<b><a href="https://pay.google.com/intl/en/about/">Google Pay</a></b>, maybe you are considering 
accepting payments in installments from your customers? Let them pay with <b><a href="https://www.klarna.com/">Klarna</a></b>. 
Or maybe you have presence in Denmark and/or Finland - why not use <b><a href="https://mobilepaygroup.com/">MobilePay</a></b>? 

Default payment methods include **Apple Pay** and **Google Pay**. <br/><br/>Are you missing a payment method you were hoping to
offer to your customers? Let us know at [info@pendoo.io](mailto:info@pendoo.io).

### Localisation :earth_africa: {id="localisation"}
Regardless of how prominent the English language is, **localisation has been proven to increase customer satisfaction
and, ultimately, revenue.** As Pendoo enters new markets around the world, we work closely with our retail partners on
localising our service so your customers can feel comfortable using your new mobile self-checkout service.

After all, Pendoo <tooltip term="so-cool">er så sejt</tooltip>!

### Customer record creation :woman_superhero: {id="customer-record-creation"}
Upon a user's successful transaction, <b>a customer record is created or updated in your Shopify admin</b>. <br/><br/>During checkout, the user's
email address is used to perform a look-up. If a customer record is found, the order will be created against their existing record and will
be appended to their order history. <br/><br/>
Otherwise, a new customer record will be created along with their first order.
<warning>To enable this feature, a premium plan may be required.</warning>

### Location sale attribution :vertical_traffic_light: {id="location-sale-attribution"}
Running a Shopify shop with **multiple locations**? Reporting can be a nightmare when it shouldn't be!<br/><br/> As an omnipresent sales-channel, 
we don't just blindly fulfill orders. **We route the order to the location where the sale took place**, update the fulfillment order's
assigned location and ultimately fulfill the order.

Your reports have never looked neater :broom:
<warning>To enable this feature, a premium plan may be required.</warning>

### Branding and customisation :genie: {id="branding-and-customisation"}
Set your brand elements, starting with your logo, to determine how the Pendoo checkout appears to your customers.
You can even use your domain as a Pendoo subdomain, making it clear to your customers that mobile self-checkout is an 
extension of your company's shopping experience. <br/>

As we continue to develop our product, more customisation options will become available.
<warning>To enable this feature, a premium plan may be required.</warning>

### Anti-theft :lock: {id="anti-theft"}
Pendoo collaborates with leading anti-theft solutions providers, such as <a href="https://nedap.com/">Nedap</a>, 
to enhance our security offerings and ensure robust protection for our retail partners. Are you using RFID? Or magnetic tags?
We are interested to hear your approach and are ready to devise a secure plan for you.
<warning>To enable this feature, a premium plan may be required.</warning>

## Feedback and support :incoming_envelope:
Please report any issues, usability improvements, or feature requests to our
<a href="https://pendoo.io/contact">sales and development teams</a>.

You can also always email us at [info@pendoo.io](mailto:info@pendoo.io).

<seealso>
    <category ref="pendoo">
        <a href="https://pendoo.io">Pendoo</a>
        <a href="https://shopify.com">Shopify</a>
    </category>
</seealso>