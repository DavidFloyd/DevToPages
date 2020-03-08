+++
title = "In Short"
id = "79"
period = "Nov 2019 - Mar 2020"
image = "/images/main.png"
date = "2020-03-03T06:56:45"
+++

{{% img-responsive"/images/inShortLogo.png"%}}

## Live link: https://app.inshrt.com/

In Short is a service that aims to provide a clean and convenient solution to the hustle of dealing with multiple online profiles and sharing these with other people by having a centralized collection available by sharing a simple QR code.  

## What I learnt from this project

This project was initially an excuse to play around with the newer features of NgRx given that at work I work daily with an older version of this state management tech for Angular and we may consider upgrading soon.

The requirements of deploying this service publicly gave me an understanding of AWS, specifically Elastic Beanstalk, DNS setup, Domain management, Beanstalk deployment files and certificate configuration that I didn't have before.

# Tech stack

Frontend:

    Framework: Angular 8, upgrading to 9 recently

    State management: NgRx 8.4.0 (which was the main reason to pick up this project, as an excuse to play with the newest features of this version)

    Other: RxJs, Material

Backend:

    Framework: NodeJS, Express

    JWT to handle token encryption and authentication

    Other: express-validator, bcryptjs, gravatar

Database: 

    MongoDB: For all the DB setup and management I used MongoDB Atlas, I found it quite convenient since I had enough new elements on this project to tackle and this service allows to do away with a local database (just pointing to a mongoURI is enough).  

Infrastructure / Deployment

    Hosting: AWS, Elastic Beanstalk

    Certicate provider: LetsEncrypt

## Some screenshots

{{% img-responsive"/images/features01.png"%}}

{{% img-responsive"/images/features04.png"%}}

{{% img-responsive"/images/features05.png"%}}

{{% img-responsive"/images/features02.png"%}}

{{% img-responsive"/images/features03.png"%}}
