# Magento 2 Auto Invoice Extension

## Introduction
The **Magento 2 Auto Invoice** extension by CodeDecorator automates the invoicing process, ensuring smooth transactions without manual intervention. This extension generates invoices automatically after a successful order placement, reducing administrative workload and improving order management efficiency.

## How It Works
The **Magento 2 Auto Invoice** extension automatically creates invoices once an order is successfully placed and paid. By streamlining this process, store owners can focus on business growth instead of handling invoices manually. Additionally, the extension supports auto-shipment generation, making order fulfillment seamless.

## Key Features
- Automates invoice generation upon order placement.
- Supports automatic shipment creation.
- Compatible with multiple payment methods.
- Reduces manual effort in order processing.

## Auto Invoice Generation
Once an order is placed and the payment is confirmed, the extension automatically generates an invoice without requiring manual approval. This reduces the processing time and ensures a seamless order-to-invoice workflow.

## Auto Shipment Processing
The extension allows automatic shipment generation along with the invoice, streamlining the order fulfillment process and ensuring timely deliveries.

## Compatibility with Payment Methods
Magento 2 Auto Invoice is compatible with various payment gateways, including PayPal, Stripe, and offline payment methods, ensuring smooth invoice creation across different payment options.

## Easy Configuration
The extension provides an easy-to-use admin interface where store owners can configure auto-invoicing settings based on their business requirements.

## Extension Installation
To install the **Magento 2 Auto Invoice** extension, follow these steps:

### Step 1: Install the extension using Composer
```bash
composer require codedecorator/magento2-auto-invoice
```
For a specific version:
```bash
composer require codedecorator/magento2-auto-invoice:1.0.0
```
*Note: You may need authentication keys from the vendor or Magento Marketplace.*

### Step 2: Run the following Magento commands
```bash
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:flush
```

## How to Configure Magento 2 Auto Invoice Extension

### Step 1 - Navigate to Admin Panel
Go to **Stores > Configuration > Sales > Auto Invoice Settings**.

### Step 2 - Enable the Extension
Set **Enable Auto Invoice** to **Yes**.

### Step 3 - Select Payment Methods
Choose the payment methods for which auto-invoicing should be enabled.

### Step 4 - Save Configuration
Click **Save Config** and refresh the cache to apply changes.

## Download Our [Magento 2 Auto Invoice](https://codedecorator.com/magento-2-auto-invoice.html) Extension
