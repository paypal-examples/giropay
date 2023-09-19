# Paying with Giropay or PayPal on the web

<p>
<img src="https://www.paypalobjects.com/images/checkout/latinum/Altpay_logo_giropay.svg" alt="Giropay Logo">
<img src="https://upload.wikimedia.org/wikipedia/commons/b/b5/PayPal.svg" width="90px" alt="Paypal Logo">
</p>


This integration uses the JavaScript SDK to accept Giropay payments on the web


See a [hosted version](https://giropay-js-sdk.herokuapp.com) of the sample


### How to run locally

Copy the .env.example file into a file named .env

```
cp .env.example .env
```

and configuring your .env config file with your Paypal ClientId and ClientSecret

1. Clone the repo  `git clone git@github.com:paypal-examples/giropay-payment.git`
2. Run `npm install`
3. Run `npm run dev`
4. Navigate to `http://localhost:8080/`

## PayPal Codespaces

PayPal codespaces require a client ID and client secret for your app. 

### Link to codespaces 

[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/paypal-examples/giropay)

### Learn more 

You can read more about codespaces in the [PayPal Developer Docs](https://developer.paypal.com/api/rest/sandbox/codespaces).

### Submit Feedback 

* To report a bug or suggest a new feature, create an [issue in GitHub](https://github.com/paypal-examples/paypaldevsupport/issues/new/choose). 
* To submit feedback, go to [GitHub Codespaces](https://developer.paypal.com/api/rest/sandbox/codespaces) and select the "Feedback" tab.
