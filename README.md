<p align="center">
  <img src="https://www.multisafepay.com/img/multisafepaylogo.svg" width="400px" position="center">
</p>

# MultiSafepay plugin Odoo 13 eCommerce 

Easily integrate MultiSafepay payment solutions into your Odoo 13 eCommerce webshop with our free plugin.

## About MultiSafepay 

MultiSafepay is a collecting payment service provider, which means we take care of electronic contracts, technical details, and payment collection for each payment method. You can start selling online today and manage all your transactions in one place.

## About Odoo 13 eCommerce

Odoo is open-source software founded in 2004 by a student. First known as OpenERP, the brand changed its focus from an ERP solution to a suite of business applications. More than 360 apps are available, some officially validated by Odoo and others are developed by the community.

Odoo is available in three editions: 

- Community: Download for free from Odoo's website. 
- Enterprise: Offers more features for an annual subscription. 
- Online: The equivalent of the Enterprise version, but hosted in the cloud for a monthly subscription. 

## Supported payment methods

See MultiSafepay Docs – [Odoo](https://docs.multisafepay.com/docs/odoo) > Payment methods.

## Prerequisites

- You will need a [MultiSafepay account](https://testmerchant.multisafepay.com/signup). Consider a test account first.
- Odoo 13.0
- Tested on Python 3.6
- [MIT license](https://github.com/MultiSafepay/odoo/blob/develop/LICENSE)

##  Installation

1. Download ZIP archive with module.
2. Unpack the content of the .ZIP file.
3. In your Odoo server (`/mnt/extra-addons/`), under **Custom apps**, add the **payment_multisafepay_official** folder.
4. Install the required Python dependencies:
   ```shell
   pip3 install -r requirements.txt
   ```
   Alternatively, you can install them manually:
   ```shell
   pip3 install multisafepay==0.2.0
   ```
   For more information about dependencies, see Python – [MultiSafepay](https://pypi.org/project/multisafepay/).
5. Restart your Odoo server.
6. In your Odoo backend, activate developer mode.
7. Go to the **Apps menu** > **Update apps list**.
8. Search for and open the MultiSafepay payments module: `payment_multisafepay_official`.
9. Click **Install**.

For more information and configuration instructions, see MultiSafepay Docs – [Odoo](https://docs.multisafepay.com/docs/odoo).
  
## Contributors

If you see an opportunity to make an improvement, we invite you to create a pull request, create an issue, or email <integration@multisafepay.com> 

As a thank you for your contribution, we'll send you a MultiSafepay t-shirt, making you part of the team!

## Testing

To try out a working version of a Odoo 13 webshop, email <integration@multisafepay.com> 
We'll help you create a test account, where you can install our latest Odoo 13 plugin and test its current functionality.

## Want to be part of the team?

Are you a developer interested in working at MultiSafepay? Check out our [job openings](https://www.multisafepay.com/careers/#jobopenings) and feel free to get in touch!
