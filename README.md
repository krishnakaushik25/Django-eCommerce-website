# Django eCommerce website using RDS Postgres and deployed on Amazon AWS


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/krishnakaushik25/Django-eCommerce-website">
    <img src="img/logo_pro.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">Real World eCommerce app using Python and Django Framework</h3>

  <p align="center">
    A Full stack, fully-featured ecommerce application!
    <br />
    <a href="http://simplekart-env.eba-eweha2je.eu-west-2.elasticbeanstalk.com/">View Demo</a>
    ·
    <a href="https://github.com/krishnakaushik25/Django-eCommerce-website/issues">Report Bug</a>
    ·
    <a href="https://github.com/krishnakaushik25/Django-eCommerce-website/issues">Request Feature</a>
  </p>
</p>



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#Features">Features</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot1]](https://www.linkpicture.com/q/homepage.png)
[![Product Name Screen Shot][product-screenshot2]](https://www.linkpicture.com/q/homepage.png)

Star⭐ the repo if you like what you see😉.



#### For deployment ,we will be using AWS Elastic Beanstalk (EB) and AWS S3 Bucket for Static & Media Files Storage

The list of resources that I used for building this project are listed in the acknowledgements.

### Built With

Major frameworks and tools that are used in the project.
* [Django](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django)
* [Python](https://www.python.org/)
* [PostgreSQL](https://aws.amazon.com/rds/postgresql/)
* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/)
* [Amazon S3](https://aws.amazon.com/s3/)



## Installation


1. Firstly Create a virtual environment(virtual environment can be really useful to maintain dependencies of both the projects.)
 ```sh
  py -m venv env
   ```
2.activate your virtualenv.(if working in git, the command is below)
 ```sh
 source env/Scripts/activate
   ```
3.Clone the repo
   ```sh
   git clone https://github.com/krishnakaushik25/Django-eCommerce-website.git
   ```
4.Install all packages ( all dependencies are mentioned in requirements.txt)
   ```sh
 pip install -r requirements.txt
   ```
5. Create a .env file and fill all the fields mentioned in the .env-sample(secure enough for saving secret values)

6.Run the development server
   ```sh
  python manage.py runserver
   ```

<!-- USAGE EXAMPLES -->
## Features

- Registration, Login with Token Based Verification & Message Alerts
- Forgot Password with Secure Validation Links
- Orders & Order Number Generation
- Add to Cart using Session Keys, Increment/decrement/remove Cart Items
- Paginator & Search
- Adding the Variation in Cart, Grouping Cart Item Variations
- User Account Activation & Activation Link Expiry
- Payment Gateway Integration & Place Order
- Orders & Order Number Generation
- Review and Rating System
- Product Gallery with Unlimited Images
- Context Processors & Product Details



<!-- CONTRIBUTING -->
## Contributing
Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* [A Complete Beginner's Guide to Django](https://simpleisbetterthancomplex.com/series/beginners-guide/1.11/)
* [Build an E-commerce Website with Django and Python](https://www.youtube.com/watch?v=YZvRrldjf1Y)
* [Deploying a Django application to Elastic Beanstalk](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create-deploy-python-django.html)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[product-screenshot1]: img/esite.png
[product-screenshot2]: img/esite2.png
